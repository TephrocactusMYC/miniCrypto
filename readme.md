# Encrypted Voice Communication System

This project implements a **secure communication mechanism** in **C++**, featuring both a **client** and a **server** component.
It enables encrypted voice (or message) transmission between two parties using modern cryptographic techniques.

## 🔐 Cryptographic Design

* **RSA** — used for **key exchange and authentication**, ensuring that the AES session key is securely distributed.
* **AES** — used for **message encryption**, providing efficient and secure symmetric encryption for real-time communication.

## 🧩 Project Structure

```
client/    # Client-side source code and executable
server/    # Server-side source code and executable
keys/      # Automatically generated RSA key pairs
```

> ⚠️ Note: The program uses **relative paths**, so please keep the folder structure unchanged to ensure proper operation.

## ⚙️ Compilation & Execution

Both the client and server executables are **statically linked**, allowing them to run **directly on Windows 11** without additional dependencies.

To start:

1. Launch the server executable.
2. Run the client executable and connect to the server.
3. Exchange encrypted messages or data securely.

---

Would you like me to include a short example command-line usage section (e.g., how to run `server.exe` and `client.exe`)?
