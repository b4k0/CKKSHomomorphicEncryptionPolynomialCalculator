# **CKKS Homomorphic Encryption Polynomial Calculator**

## What is CKKS and Homomorphic Encryption?

* **CKKS (Cheon-Kim-Kim-Song)** is a public key encryption scheme, where a secret key and a public key are generated. While the public key is used for encryption and can be shared, the private key is used for decryption and must be kept secret.

* **Homomorphic encryption** is the conversion of data into ciphertext that can be analyzed and worked with as if it were still in its original form. Homomorphic encryptions allow complex mathematical operations to be performed on encrypted data without compromising the encryption.

## Problem

* Calculation of a polynomial using **homomorphic encryption** and **CKKS** scheme.

![polynomial](https://user-images.githubusercontent.com/51766689/150867255-e948a92c-b943-49fd-a2a7-3158c533b14e.PNG)


## Tools and Programming Language

*  [Microsoft SEAL library](https://github.com/microsoft/SEAL) for CKKS scheme.
*  Visual Studio 2019 with C++ CMake Tools for Windows
*   **C++**

## Implementation

* Based on [4_ckks_basics.cpp](https://github.com/microsoft/SEAL/blob/main/native/examples/4_ckks_basics.cpp) of [Microsoft SEAL library](https://github.com/microsoft/SEAL)

## Results
