Security+ Lesson 3A |

Lesson 3 Explaining Appropriate Cryptographic Solutions
Cryptography Defined: |
-Plaintext: Information anyone can read
-Ciphertext: Unreadable information
-Encryption: Translating information to ciphertext
-Decryption: Translating ciphertext to plaintext
-Cryptanalysis: Science of cracking crytography solution

Hash function or algorithm used for comparison and creates a password digest not reversible and size is fixed.

- Hash process - The message is hashed creating a digest sent to recipient with message. Recipient puts message through alorithm creating a digest which must match (integrity) original digest alorithm used must be same (e.g., SHA-256).
- 
- The downside with Hash(ing) is collision(s). |

Symmetric Key |

- Two methods: Stream Cipher (deprecated) and Block Cipher pg. 10.

Sunny Classroom Video Private Key encryption called symmetric key encryption

Sunny Classroom Video "Public Key Encryption" Aysmmetric key Algorithm
- Two keys: Public and Private
Types of Cypher Algorithms: Diffy-Hellman (D-H), RSA, ECC, DSA

Pg. 13 list of algorithms

Sunny Classroom Video "What is Digital Signiture?"

Digital Signature servers three purposes:
1. Authentication: Confirms for the reciever the message was created and sent by the claimed sender.
2. Non-repudiation: the sender cannot deny having sent the message.
3. Integrity: ensures that the message was not altered in transit.

There is a problem with Digital Signatures which is Authentication because during the transfer of message a hacker (man in the middle attack) can intercept and present their own message and digital signature. The solution to this problem is Digital Certificate.
Digital certificates are electronic credentials issued by a trusted third party. It not only verifies the identity of the owner, but also verifies that the owner owns the public key.
 


 
  
