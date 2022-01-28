# **CKKS Homomorphic Encryption Polynomial Calculator**

## What is CKKS and Homomorphic Encryption?

* **Homomorphic encryption** is the conversion of data into ciphertext that can be analyzed and worked with as if it were still in its original form. Homomorphic encryptions allow complex mathematical operations to be performed on encrypted data without compromising the encryption.

![homomorphic-enc](https://user-images.githubusercontent.com/51766689/151620612-a1cbf298-f635-4f47-86c3-086d372b148f.png)


* **CKKS (Cheon-Kim-Kim-Song)** is a public key encryption scheme, where a secret key and a public key are generated. While the public key is used for encryption and can be shared, the private key is used for decryption and must be kept secret.

![ckks](https://user-images.githubusercontent.com/51766689/151620611-bdc9a709-3985-4f64-844b-e71f0a7b3fe1.svg)


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

![Results](https://user-images.githubusercontent.com/51766689/151003708-e115d9d3-5319-4cbf-a737-cc37bf6a3981.png)
