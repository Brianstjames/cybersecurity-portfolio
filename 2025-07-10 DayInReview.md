Security+ Lesson 4A

IAM Identity and Access Management
1. Identify - " make claim"
2. Authentication - "prove claim"
3. Authorization - "rights & permissions"
4. Accounting - "

A program can log in via a script.

Identity and Access Management
   4 A's
   1. ADMIN -  create account and manage it
   2. AUTHN - 
   3. AUTHZ - rights & permissions
   4. AUDIT - 
  
Directory is where user information is stored and Directories are stored in databases.

Schema - Design or structure of a database.  

Video IBM Technology Cybersecurity Architecture: Who Are You? Identity and Access Management. 

Authentication protocols
Databases - 
- LDAP = manages and authenticates to directories. 
- MSAD,
- KERBEROS = mutual authentication for client and service over an untrusted network like the internet. 
- RADIUS/TACACS

Resources - printers, files/folders, IOT, Camera, and etc.

Biometric Control System pg. 11 & 12
1. False Rejection Rate (FRR) = false negative
2. False Acceptance Rate (FAR) = false positive
3. Crossover Error Rate (CER) = point at which FRR = FAR

Video Professor Messer Biometrics - SY0-601 CompTIA Security+ : 2.4

Video IBM Technology Passwordless Authentication: Weighing the Options

One-time password (OTP)
- Fast Identity Online (FIDO - uses device to authenticate)
- Universal Second Factor (U2F)
HMAC-based One-time Password Algorithm (HOTP) pg.16
- Time-based One-time Password Algorithm (*TOTP) - time-based OTP; moving factor in each code based on time OTP = TOTP(shared secret + timestamp) *=preferred

- Video IBM Technology "Password vs. Passkeys - FIDO Bites Back!" & "FIDO Promises a Life Without Passwords"

Passwords should be:
- Complex (length and alphanumeric and unique characters/hexadecimal)
- Unique (don't use the same password for different systems)
- Fresh (change periodically)

- Sender generates keys to authenticate, etc.

Security+ Lesson 4B

Subject - something that can manipulate an object usually a human user or process running in memory. User, group or process. They are active.

Object - something that can be manipulate by a subject: files, folders, devices, and other resources. They are passive.

Authorizing one to have the following:
1.Permissions - are actions pertaining to files/folders.
2.Rights - grant users/groups the ability to perform specific actions on a system, e.g. ability to log in, manage print jobs, run backup applications.

Discretionary Access Control (DAC) pg.5 
1. based on "who owns the resource" -will detetrmine permissions
2. a user or group membership grants access
3. assigns permissions (e.g. r,w,x) to data objects

Issue/con:
1. vulnerable to compromised privileged user accounts

File System Permissions
Access Control List (ACL) pg.6
1. each object in a file system has an associated ACL

Mandatory Access Control (MAC) is non-discretionary; e.g. Windows User Account Control (UAC) system
1. based on "security clearance levels"
2. subjects and objects are granted a clearance level - "label", i.e., security "label" tied to the subject or object

Video by Udacity Mandatory Access Control

Role-Based Access Control (RBAC)

Attribute-Based Access Control (ABAC) 
1. It is based on elements such as User's name, role, organization, ID, and security clearance.
2. Environmental: time of access, location of the data, and current organization threat levels.
3. Resource: creation date, resource owner, file name, and data sensitivity. And it is non-discretionary.

Rule-Based Access Control (on page 11) - any sort of access control model where access control policies and determined by system-enforced rules (to enforce other models), e.g., non-discretionary models such as MAC, RBAC, and ABAC.
Key point: RBAC affects all subjects - no matter their identiy.
Example(s): Microsoft User Account Control (UAC) and Linux sudo command.

Provisioning - user account is a type of asset and must by tracked.

Account Attributes and Access Policies
a. Active Directory Group Policy Objects (GPOs)

Account Restrictions pg. 15

Video IBM Technology Why You Need Privileged Access Management
Privileged access management
1. Zero standing privileges - obtain access as and when needed and for a limited time.
   a. temporary elevation = admin rights for limited period
   b. password vaulting/brokering = account checkout
   c. ephemeral credentials = destroy/disable account after task performed



