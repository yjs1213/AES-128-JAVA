# AES-128-JAVA
### AES 128bit for JAVA

### Example

1. Encrypt
   ```java
   AES aes = new AES();
   String plaintext = "6546a6b64b08c8d52b31059e42c06180"; // hex, 128bit
   String key = "6546a6b64b08c8d52b31059e42c06180"; // hex, 128bit
   aes.encryptAES(plaintext, key);
   ```
2. Decrypt
   ```java
   AES aes = new AES();
   String ciphertext = "6546a6b64b08c8d52b31059e42c06180"; // hex, 128bit
   String key = "6546a6b64b08c8d52b31059e42c06180"; // hex, 128bit
   aes.decryptAES(ciphertext, key);
   ```
