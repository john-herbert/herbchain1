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
    d. nonce - The incrementing member of the block and also, how many times a hash has to be generated to get a match of the starting string '0' Chars (length depending on 'difficulty' Variable
3) The Hash is calculated using the SHA 256 algotithm. 
4) Data mining is the term ensuring the degree of difficulty in calculating the hash starting pattern matches the length and type of          characters determined by the difficulty variable.
5) A hash is first of calulated based on the the initial block values. Then it goes through the 'mining' stage with the nonce incrementing each time, until the match is met.

Build
=====
> mvn clean install
Where the resultant .jar is generated.
> java -jar herbchain-0.0.1-SNAPSHOT.jar
