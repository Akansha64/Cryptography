# Cryptography
Encryption and Decryption of files and strings using Hill Cipher

Cryptography is the study and practice of secure communication through
unique methods and techniques that prevents third parties or organizations
from accessing sensitive information.
● We have used the Hill Cipher technique for encryption and decryption of
files and strings.
● Alphabets are converted to reference numeric values for eg. A
corresponds to 1, B to 2,...Y to 25 and Z to 0. They are then grouped into
pairs and converted to column matrices. A symmetric key is used to
encrypt them and decrypt them
● During encryption, the key is multiplied with the matrix thus created, and its
modulo 26 is taken in order to retrieve the corresponding encrypted
alphabets.
● During decryption, the inverse of the key is multiplied with the encrypted
alphabet matrix, and its modulo 26 is taken to retrieve the corresponding
decrypted alphabets.

Module-wise description

1. NumPy library: We have used the NumPy python library for matrix
operations. Numpy stands for ‘Numerical Python’. NumPy aims to provide
an array object that is up to 50x faster than traditional Python lists.
We use the following modules from NumPy.
● Multiplication : We are required to multiply the key matrix with the
column matrix created by grouping alphabets and converting them to
their reference numbers in the process of encryption. In decryption,
we multiply the encrypted alphabet matrix with the inverse of the key
matrix in order to decrypt it.
● Modulo 26 : We take modulo 26 upon multiplication of matrices in
both processes in order to be able to convert them back to
alphabets.

2. Tkinter : We have used the Tkinter library for our GUI.
● Buttons: We created buttons to create a choice between various
methods like encryption/ decryption and/or strings and files.
● Shifting frame: Upon choosing, we used the inbuilt Tkinter function to
shift the main frame to the frame of choice. Also we have provided
the option of returning to the previous frame.
● Filedialogue: We have used this Tkinter function for creating
file/directory selection windows.
● We have customized the background color of buttons as well as the
frame and used various fonts and text styles available in the Tkinter
library to enhance the user experience.
