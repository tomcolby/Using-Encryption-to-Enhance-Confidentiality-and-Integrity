# Using-Encryption-to-Enhance-Confidentiality-and-Integrity

## Objective
In this lab, I will learn how cryptography tools can be used to ensure message and file transfer integrity and how encryption can be used to maximize confidentiality. I will use Kleopatra, the certificate management component of GPG4Win, to generate public and private key pairs for both a sender and a recipient. As the sender, I will encrypt a file using the recipient’s public key, send it to the recipient, and decrypt it using the recipient’s private key.

### Skills Learned
- Understand the differences between symmetric and asymmetric cryptography.
- Apply asymmetric cryptography to provide confidentiality, authentication, integrity, and nonrepudiation.
- Encrypt and decrypt data using public and private key pairs.
- Digitally sign and validate communications using public and private key pairs.
- Encrypt and decrypt data using hybrid cryptography.


### Tools and Software Used
- Kleopatra (GPG4Win)
- OpenSSL

### Topology
- vWorkstation (Windows: Server 2022)
- TargetLinux01 (Linux: Ubuntu 20)

### Lab Overview
STEP 1 of this lab has three parts, which should be completed in the order specified.
 
- I will create key pairs using an asymmetric encryption algorithm.
- I will encrypt a secret message using the recipient’s public key.
- I will decrypt the same secret message as the recipient, using their private key.- 

STEP 2
- I will use the OpenSSL library in a Linux environment to transfer messages using a hybrid cryptographic approach.


<h2>Program walk-through:</h2>

## STEP 1
### Part 1: Create and Exchange Asymmetric Encryption Keys

<p align="center">

</p>

### Part 2: Encrypt a File Using Asymmetric Encryption
<p align="center">

</p>


### Part 3: Decrypt a File Using Asymmetric Encryption
<p align="center">

</p>



## STEP 2
### Part 1: Create an Asymmetric Key Pair

<p align="center">

</p>

### Part 2: Encrypt a File Using Symmetric Encryption
<p align="center">

</p>


### Part 3: Transfer and Decrypt a File Using Hybrid Cryptography
<p align="center">

</p>
