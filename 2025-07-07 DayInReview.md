Hash - integrity (compare). algorithm: MD5, SHA family

- wifi single key SSID is a pre-shared key it's ok depending on use-case

Symmetric key - single key, secret. algorithm: RC4, AES, DES, 3DES fishes "confidentiality"
There's a issue with the symmetic key system. However symmetric keys are used for Bulk encryption. Starts with receiver.

Asymmetric - 2 keys public and privat. Algorithms: Diffie and Hellman (D-H), RSA/DSA, ECC, ECDSA. D-H algorithm is used for key exchange. Confidentiality. Starts with the receiver generating keys.

Authentication starts with sender.

Digital signature starts with the sender as well. Authentication, non-repudiation, and integrity.

Not man in the middle anymore it's on path.

Certificate Authority - Comodo, DigiCert, GeoTrust, IdenTrust, Let's Encrypt, GoDaddy, Amazon, Microsoft, and etc. 

Video "What is Public Key Infrastructure (PKI)" by Securemetric talks about CA

Sunny Classroom Videos "PKI - trust & chain of trust - why, who and how?" and "Revocation of digital cetificates: CRL, OCSP, OCSP stapling"
1. Distributed Trust model establishes a chain of trust (on test).
   





