# XOR Cypher

XOR encryption is a simple method of encrypting data by applying the XOR (exclusive OR) operation between the data and a key. This technique is reversible, meaning that the same operation can be used to decrypt the data by applying the XOR operation again with the same key.

How XOR Encryption Works

- Encryption Process: Each bit of the plaintext is combined with a corresponding bit from a key using the XOR operation. The result is the ciphertext.
- Decryption Process: To retrieve the original plaintext, the same XOR operation is applied again using the same key.

What it does

- Reads a hard-coded shellcode byte array in memory.
- Uses a simple repeating XOR cipher (XorByInputKey) to encrypt the shellcode with a small key.
- Prints the original shellcode bytes, the XOR-encrypted bytes, then decrypts back and prints the resulting original bytes to verify correctness.

Usage notes

- The program prints hex-escaped bytes (e.g. \x90\x90...) for each stage.
- To change the input, replace the shellcode byte array.
- To change the key, modify the bKey array and sKeySize.

<img width="1218" height="434" alt="image" src="https://github.com/user-attachments/assets/e0d016d7-c5e6-4679-9f6c-b8ed93e90cd6" />

