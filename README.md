# Python-Sys-Admin
Python Sys Admin

1. Write a python program that reads user information from a file and creates user accounts. The input file will have following format:

FirstName;LastName;Password;UID;GID

The username is created by using the first character of first name followed by the first 7 characters of the lastname - amccormi will be username for Alice McCormick in the sample file belo. If a username already exists, then use the first two characters of the firs name followed by the first 7 characters of last name. Password should be encrypted and stored.

You may use the useradd command.

Here is a sample input file :

Alice;McCormick;ballstate;2000;3000
Bob;Smith;bsu;2001;3000

This is how your program will be run:

python assign6.py NewUser.txt
