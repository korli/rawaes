# rawaes


rawaes encrypts a file using the Advandced Encryption Standard (AES).  AES uses the Rijndael Algorithm, a 128-bit block cipher, to encrypt.  Since the encryption requires 16-byte blocks, rawaes will pad any uneven blocks with 0s, possibly increasing the size of the file upto 15 bytes.

to build:

haiku

cd to the rawaes directory

make


BeOS

Doubleclick rawaes.proj and build from BeIDE.

License:

rawaes 1.1 for BeOS (Matthew Badger, (c) 2000)

 Encrypts files using the Advanced Encryption Standard
 Makes use of code written by Dr. B. R. Gladman; this 
  code can be found in the sub directory "aes". 

  This program may be freely compiled and distributed,  
  if and only if the program's source is also  
  distributed. The author assumes no responsibility  
  for damaged caused due to the use of this program.

 Rawaes may  be ported to other platforms or used as a
 basis for another freely available program as long as it
 is not claimed that the author/developer of the new
 software is Matthew Badger.
