# A5-1-Stream-Cipher
Java implementation of A5/1 Stream Cypher to better understand shift register crypto.

## Example output:
```Beginning default run through with default key
Encrypting "Hello World!"
Hello World! encrypted is: 011001100011001101001010111110001110111110001010100100100001110111011001110101000010111110110011
Decrypting 011001100011001101001010111110001110111110001010100100100001110111011001110101000010111110110011
011001100011001101001010111110001110111110001010100100100001110111011001110101000010111110110011 decrypted is: Hello World!
Ending default run through.

******************************
* To encrypt, enter 1:       *
* To decrypt, enter 2:       *
* To enter new key, enter 3: *
* To quit, enter q:          *
******************************
1
Enter plain text to encrypt: 
Hello Bob, this is Alice.
Hello Bob, this is Alice. encrypted is: 01100110001100110100101011111000111011111000101010000111000111011100100110010100011010111110011010100010001011100001001000111100001010010100010100100010100110011000000101101100101001100001001010010010
******************************
* To encrypt, enter 1:       *
* To decrypt, enter 2:       *
* To enter new key, enter 3: *
* To quit, enter q:          *
******************************
2
Enter cipher text to decrypt: 
01100110001100110100101011111000111011111000101010000111000111011100100110010100011010111110011010100010001011100001001000111100001010010100010100100010100110011000000101101100101001100001001010010010
01100110001100110100101011111000111011111000101010000111000111011100100110010100011010111110011010100010001011100001001000111100001010010100010100100010100110011000000101101100101001100001001010010010 decrypted is: Hello Bob, this is Alice.
******************************
* To encrypt, enter 1:       *
* To decrypt, enter 2:       *
* To enter new key, enter 3: *
* To quit, enter q:          *
******************************
3
Enter new 64 bit key: 
00011000 00111111 10011111 10001101 00011111 11101100 00111010 01011001 
******************************
* To encrypt, enter 1:       *
* To decrypt, enter 2:       *
* To enter new key, enter 3: *
* To quit, enter q:          *
******************************
1
Enter plain text to encrypt: 
Hello Bob, this is Alice.
Hello Bob, this is Alice. encrypted is: 10110011010111000110000001110011001101111000000101010011001011101100000101101110010001010111011001101010001000110100100100110000111101010010010000000000000000011110000011100100100000011001001010011000
******************************
* To encrypt, enter 1:       *
* To decrypt, enter 2:       *
* To enter new key, enter 3: *
* To quit, enter q:          *
******************************
2
Enter cipher text to decrypt: 
10110011010111000110000001110011001101111000000101010011001011101100000101101110010001010111011001101010001000110100100100110000111101010010010000000000000000011110000011100100100000011001001010011000
10110011010111000110000001110011001101111000000101010011001011101100000101101110010001010111011001101010001000110100100100110000111101010010010000000000000000011110000011100100100000011001001010011000 decrypted is: Hello Bob, this is Alice.
******************************
* To encrypt, enter 1:       *
* To decrypt, enter 2:       *
* To enter new key, enter 3: *
* To quit, enter q:          *
******************************
q
Goodbye```