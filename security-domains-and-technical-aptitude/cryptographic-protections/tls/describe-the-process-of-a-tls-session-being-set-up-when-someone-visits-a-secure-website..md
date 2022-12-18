# Describe the process of a TLS session being set up when someone visits a secure website.

1. The client initiates the TLS handshake by sending a “Client Hello” message that includes the client’s supported cipher suites, random bytes, and other parameters.
2. The server responds with a “Server Hello” message that includes the server’s selected cipher suite and random bytes.
3. The client then verifies the server’s certificate, such as its validity and the server’s public key.
4. The client then generates a pre-master secret and encrypts it with the server’s public key, sending it to the server.
5. The server decrypts the pre-master secret with its private key and both the client and server generate the master secret for the session.
6. The client and server then generate session keys based on the master secret and exchange them.
7. The client sends a “Finished” message to the server, verifying that the handshake is complete.
8. The server responds with its own “Finished” message, and the TLS session is now established.
