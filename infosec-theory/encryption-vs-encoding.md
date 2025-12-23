# Encryption vs Encoding

## Encoding
Encoding is the process of converting data into another format using a publicly known scheme so that it can be properly stored or transmitted. Encoding is not meant to secure data and can be easily reversed.

### Examples
- Base64 encoding
- URL encoding
- ASCII encoding

Encoding ensures compatibility and readability, not confidentiality.

## Encryption
Encryption is the process of transforming data using a cryptographic algorithm and a secret key to protect confidentiality. Only someone with the correct key can decrypt and access the original data.

### Examples
- AES
- RSA
- ChaCha20

## Key Differences

| Aspect | Encoding | Encryption |
|------|---------|------------|
| Purpose | Data representation | Data security |
| Reversible | Yes (publicly) | Yes (with key) |
| Security | None | Strong |

## Why This Matters in Security
Confusing encoding with encryption is dangerous. Encoded data is often mistaken as being secure, even though anyone can decode it. Proper encryption is essential to protect sensitive information.

