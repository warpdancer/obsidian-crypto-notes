# Elliptic Curve Cryptography
- ECC is a form of cryptography that basically uses elliptic curves over a field as the method of creating an algorithm for public/private key systems
- Also heavily based on using prime numbers for this type of calculation
- Here is an elliptc curve ![ecc-curve](https://github.com/ethereumbook/ethereumbook/raw/develop/images/simple_elliptic_curve.png)
- Some examples of Elliptic curve libraries
	- OpenSSL
	- libsecp256k1
	- KECCAK-256
### Relation to Cryptocurrency
- This means ANYONE can verify that a transaction is valid
	- This is fine because we can check that the digital signature matches the *TX details* **AND** the *ethereum* address to which access is being requested
- Verification does **NOT** involve the private key!
	- What makes the verification unique is that the TX could **only come from someone with the private key that corresponds to the public key behind the ethereum address.**
-