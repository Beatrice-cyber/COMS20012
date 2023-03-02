# Exercises sheet 2

## Intro to Cryptography 

1. What are the two basic functions used in encryption algorithms?
*substitution and transposition. Substitution replace plaintext bit patterns with cipher text bit patterns 
Transposition shifts the position of plain text accordingly*
2. How many keys are required for two people to communicate via a cipher?
*to communicate using a cipher only one confidential secret key neede*
**For symmetric encryption, you need n(n-1)/2 keys**
3. What is the difference between a block cipher and a stream cipher?
*Block Cipher is the type of encryption where the conversion of plaintext is performed by taking its block at a time. Stream Cipher is the type of encryption where the conversion of plaintext is performed by taking one byte of the plaintext at a time*
4. What are the two general approaches to attacking a cipher?
*cryptanalysis, based on properties of the encryption algorithm, and brute-force, which involves trying all possible keys.*
5. What is a trap-door one-way function?
*a trap-door function is a function that is easy to compute in on way but very difficult to compute the other way.*
6. What requirements must a public-key cryptosystems fulfill to be a secure algorithm?
*Their are 2 pair of keys and the secret key is never shared between anyone, but the public key can be shared.
7. What is the difference between a message authentication code and a one-way hash function?
[diff](https://stackoverflow.com/questions/2836100/what-is-the-difference-between-a-hash-and-mac-message-authentication-code)
*The difference mainly lies on that a MAC can guarantee integrity and authentication, while hash can only guarantee integrity. This is because MAC function is based on private key and the plain text.*
## Intro to Networking 

1. What is the difference between ISO/OSI model and TCP/IP model? Elaborate!
[diff chart](https://www.tutorialspoint.com/difference-between-osi-and-tcp-ip-reference-model)
TCP/IP only have 4 layer, Application layer, transport layer, Internet layer and Network access layer.
2. Explain difference between Physical Links, Data Links, and Routes!
Phsical links means cables/signal. 
Data link means there is a route from a node in the network to another node.
3. Which is a security attack at layer 1 of the OSI model?
Cut the signal.
4. What is a replay attack?
Typically a man-in-the-middle attck, the attacker can gain the information in the session.
5. Suppose that the current replay window spans from 120 to 530.
a. If the next incoming authenticated packet has sequence number 105, what will the receiver do with the packet, and what will be the parameters of the window after that?
b. If instead the next incoming authenticated packet has sequence number 440, what will the receiver do with the packet, and what will be the parameters of the window after that?
c. If instead the next incoming authenticated packet has sequence number 540, what will the receiver do with the packet, and what will be the parameters of the window after that?

