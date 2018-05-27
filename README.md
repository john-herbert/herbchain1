# herbchain1
This is a simple block chain.
The concept is as follows.

Description
===========
1) It is a simple ArrayList
2) Each member of the list contains 
    a. A string (payment data)
    b. the previous members hash value ('0' for the first value)
    c. timestamp as string
    d. nonce - how many times a hash has to be generated to get a match of the starting string '0' Chars (length depending on 'difficulty'        Variable
3) The Hash is calculated using the SHA 256 algotithm. 
4) Data mining is the term ensuring the degree of difficulty in calculating the hash starting pattern matches the length and type of          characters determined by the difficulty variable.

Build
=====

