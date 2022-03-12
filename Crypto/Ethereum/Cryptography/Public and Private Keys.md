# Public and Private Keys
- Public keys are similar to a bank account number, and private key is the pin that only YOU know
- This is all asymmetric key encryption
- Easy to calculate the keys for creating them, but difficult to calculate their inverse
	- Similar to when creating a prime number by multiplying two numbers; much more difficult to figure out their prime numbers if we start in reverse.

### Public Key Cryptography and Cryptocurrency
- Public-private key pairs are considered pairs since they operate together.
	- Together, these represent an ethereum account
	- They represent the address (which makes it publically accessible) and the control (which is the private key)
	- Transactions must be **SIGNED** using this key pair, and must be unique; that's the only way that anything can be spent.
	- Signatures can also be sued to **AUTHENTICATE** the user as well.
		- Users using smart contracts must also authenticate with their signature.
	- [[Elliptic Curve Cryptography (ECC)]] is used in this scenario

### Private Keys
- Private keys are just a number picked at random. 
- These are used to create signatures. EXTREMELY IMPORTANT TO PROTECT