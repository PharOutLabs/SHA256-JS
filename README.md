# SHA256-JS
Vanilla Javascript implementation of SHA256

The SHA (Secure Hash Algorithm) can be used to encrypt data for secure transfer between applications.
The SHA256() function returns a string with the SHA256 encrypted hash as a 64-character hexadecimal string.
It is fully compatible with UTF-8 encoding.

- Usage:
1. Copy the SHA256() function into your JavaScript script.
2. To get the SHA256 hash of a string, calls the SHA256() function:   SHA256('string'); .

- Example. The string entered into an input text field will be encrypted with SHA256, and added into another input form field.

The SHA-256 algorithm is one iteration of SHA-2, an algorithm created by the National Security Agency in 2001 as a successor to SHA-1. SHA-256 hashing plays a crucial role in cybersecurity, used in some of the most popular authentication and encryption protocols. It is also used for securing password hashing on Unix and Linux software. 

SHA-256 algorithms have some distinct features that stand out amongst other hashing algorithms. 

For starters, the message length of the cleartext should be less than 264 bits, ensuring the size remains in the comparison area to help with the randomization of the digest. As for digest length, as mentioned previously, the hash digest should be 256 bits. 

Also, by design, all hash functions such as the SHA 256 are irreversible. This means that you should never get plaintext when you have the digest beforehand, and the digest should never provide its original value when passing through the hash function again.

The three properties that maintain SHA-256 encryption’s security are: 

The near impossibility of recreating the initial data from the hash value; 

The near-impossible chance of receiving two identical messages with the same hash value

Minor changes to the original data will alter the hash value so significantly that it isn’t apparent the new hash value is derived from similar data.
