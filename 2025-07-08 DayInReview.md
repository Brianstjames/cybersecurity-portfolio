| Security+ Lesson 3B

| CA is broken up into many components: RA, CA, VA. pg.11 

pg. 12 Wild card.
pg. 13 Cert. Revocatin List (CRL)

| Digital Certificate
a. PKI
b. CA
c. x.509

pg. 14 OCSP Stapling
pg. 15 Cert. and Key Management

|Videop Tom Olzak "key managemnet 
1. Strength of key depends on randomness and key length
2. Hardware Security module to staore key per video
3. Key rotation

Key Strength |
1. Randomness (entropy)
2. key length

| Mobile Device Management (MDM) on test

Video by Dave Crabbe (script less legible) "Digital Certificates: Chain of Trust" 

Root CA to Intermediate CA  NSCCA.CA

Chain of Trust
TPM - Trusted Platform module resides on the motherboard
HSM - Hardware Security module on pg. 17 Security+ Lesson 3B

Security+ Lesson 3C |

Video Richard Sla Data states three state
1. Data-at-rest = passive state data in a persistent storage media
2. Data-in-transit (data in motion) = data is transmitted over network
3. Data-in-use (data in processing) = data is present in volatile memory

Disk and File Encryption pg. 3
MS BitLocker or Apple's FileVault encrypt large amount
MS Encrypting File System (EFS) is used for file encryption

Transprot Encryption and Key Exchange pg. 6

Cipher Suite - negotiation about which algorithms to use.

Collision = is when they have the same hash MD5 = deprecation

Brute force attack = is an attack on credentials. Takes a lot of time.
Dictionary attack = 
Rainbow attack = 

Salting and Key Stretching; Video by Seytonic "Password Hashing, Salts, Peppers Explained" and Sunny Classroom video "How to salt and pepper passwords" good video

Video ISO Stenography Practical | Stenography examples ... 2:57  
Steganography is concealing information within a differnet message. Steganography != cryptography, but the two can be combined. 

Data masking and Tokenization pg. 14 on test

Data masking 
1. hole or partial redaction of strings; redacting information from fields
2. format-preserving masks;
3. Irreversible - once data masked, no way to unmask; not good when original data is needed

Tokenization
1. replacing field value with a random generated alphanumeric value (token)
2. token stored in a separate data source (vault)
3. reversible with access to the vault (token server



