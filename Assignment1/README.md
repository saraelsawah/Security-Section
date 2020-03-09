# Assignment 1

This project is a Decryption/Encryption program using three ciphers (Caesar cipher-Affine cipher-Vigenere cipher) which enables you  
to read your desired words to be encrypted from an input file and write the encrypted into an output file.

# The arguments are as follow:

◦First argument is the cipher type [“shift”,”affine”,”vigenere”].

◦ Second argument is the operation type [“encrypt”, “decrypt”].

◦ The Third argument is the input file.

◦ The fourth argument is the output file.

◦ The last argument is the the list of encryption keys required for the cipher.(S for Shift - A,B for Affine - Key for Vigenere)

# Examples:
,,,
python solution.py affine encrypt input.txt output.txt 17 20
python solution.py affine decrypt input.txt output.txt 17 20
python solution.py shift encrypt input.txt output.txt 4
python solution.py shift decrypt input.txt output.txt 4
python solution.py vigenere encrypt input.txt output.txt CAT
python solution.py vigenere decrypt input.txt output.txt CAT
,,,
