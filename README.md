Here is a Python program for text encryption:

This program defines two functions: encrypt and decrypt. The encrypt function takes a text string and a shift value as input and returns the encrypted text. The decrypt function takes the encrypted text and the shift value as input and returns the decrypted text.

In the encrypt function, each character in the text is shifted forward by the specified number of positions (shift) in the alphabet. The shift is performed using the modulo operator % to wrap around to the beginning of the alphabet if necessary.

In the decrypt function, each character in the encrypted text is shifted backward by the specified number of positions (shift) in the alphabet. The shift is performed using the modulo operator % to wrap around to the end of the alphabet if necessary.

The program also includes an example usage section where it encrypts and decrypts a sample text string using a shift value of 3.

Note: This program is for educational purposes and should not be used for secure communication or storage of sensitive information.
