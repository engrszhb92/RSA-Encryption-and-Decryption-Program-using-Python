# RSA-Encryption-and-Decryption-Program-using-Python
To run the RSA key generation, encryption, and decryption program, follow these steps:

1. Save the Python code for RSA key generation, encryption, and decryption in a file named `rsa_program.py`.

2. Make sure you have Python installed on your computer. If you don't have it, download and install Python from the official website (https://www.python.org/downloads/).

3. Prepare a file named `plaintext.txt` with the content you want to encrypt. Ensure the file is in the same directory as the `rsa_program.py` file.

4. Open the `rsa_program.py` file in a text editor or Python IDE.

5. Locate the section for "Key Generation" in the code. If you want to change the key length, modify the `key_length` variable. The value 16 means a key length of 16 binary digits, but you can use a higher value for stronger security (e.g., 32, 64, etc.).

6. After generating the keys using the key generation section, you'll get the public and private keys (n, e) and (n, d). Copy these values.

7. Now, locate the section for "Encryption." Replace `YOUR_N_VALUE` and `YOUR_E_VALUE` in the encryption code with the n and e values obtained from the key generation stage (public key).

8. After the encryption section, locate the "Decryption" section. Replace `YOUR_N_VALUE` and `YOUR_D_VALUE` in the decryption code with the n and d values obtained from the key generation stage (private key).

9. Save the changes made to the `rsa_program.py` file.

10. Open a terminal or command prompt and navigate to the directory where you saved the `rsa_program.py` file and the `plaintext.txt` file.

11. Run the program by typing the following command and pressing Enter:

   ```
   python rsa_program.py
   ```

12. The program will execute the key generation, encryption, and decryption processes sequentially.

13. After running the program, you should see the public and private keys printed on the console during the key generation stage.

14. The encrypted content will be saved as "ciphertext.txt" in the same directory.

15. The decrypted content will be saved as "decoded.txt" in the same directory.

16. Open the "decoded.txt" file to verify that the decrypted content matches the original plaintext from "plaintext.txt".

That's it! You have successfully generated RSA keys, encrypted the content, and decrypted it using the RSA algorithm. You can now use this program to securely encrypt and decrypt data using RSA encryption.
