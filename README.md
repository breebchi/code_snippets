# code_snippets
This is where I throw potentially useful snippets of code.

## RSAKeyGenerator 
I needed to generate and test RSA keys for my project and for so;e reason internet offered very poor answers.
I made this class to serve purpose and eventually thought it would be nice to clean it and share it with people to use.
Many people codes have been used so please inform me if you recognize your code so that I'd add a mention of that.

HOW TO USE IT :
 
 * Make a new Java project and run this code as a Java application
 
 * Notice code is divided into 4 blocks
 * Use them respectively to :
 * -- 	generate new pairs of RSA keys of desired size [It's set to 1024 keys as is]
 * -- 	extract xml files for those key pairs [you might want to change the format. Just reuse theinformation in this file to  suit your need]
 * -- 	test key pairs
 * -- 	test xml key pairs
 * TESTING procedure : 
 * - generate key pair
 * - provide path and file name
 * - copy/past rsaencrypt/rsadecrypt blocks [as shown] to test encryption then decryption or the reverse.
 * comment all non-relevant code [only 1 in 4 up here mentioned blocks should be uncommented]
