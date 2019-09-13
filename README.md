# Beginner Android App for Message Encryption!

Hi! You are here for a beginner Android application that would convert any text to a cypher text based on your input rules. This app is called **SDP Encryption**. If you want to learn more about cypher text encryption, refer to the [Caesar Cipher](https://en.wikipedia.org/wiki/Caesar_cipher) wiki article. 
To learn more about this app and it's implementation, continue reading further!


## SDP Encryption

SDP Encryption is an android app which converts a input message into a cypher text.
#### Inputs:

 1. Message to be encoded
      - Input should be a **non-empty string** and must contain atleast one letter.
      - Should be manually entered by user
2. A Key Number
	 - Input should be an **integer >=1 and <26**. It's initially set to 0.
3. An Increment Number
	 - Input should be an **integer >=1 and <26**. It's initially set to 0.
	 
#### Output:
Cipher text, a string resulting from using specified key letter and skip number to encrypt the input string.
Ex: “Cat & Dog” shifted according to the Key Number 3 and Increment Number 2
would be “Ffa & Mzt” (C+3, a+5, t+7, ‘ ‘, &, ‘ ‘, D+9, o+11, g+13).

	To try this app,download the repository and run it using Android studio.
