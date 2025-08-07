# 🔐 Encrypted Chat Application using OpenSSL + Netcat

This project simulates a secure encrypted chat session between two Kali Linux virtual machines using OpenSSL and Netcat. It's designed to demonstrate how SSL/TLS can be used to secure simple terminal-based communications.

## 🧰 Tools Used

- Kali Linux
- OpenSSL
- Netcat
- VirtualBox (2 VMs)
- Shared network adapter (Internal network)

## 🛠️ What I Did

- Created self-signed SSL certificates using OpenSSL.
- Set up encrypted listener using Netcat on one VM.
- Connected to the encrypted listener from another VM.
- Verified secure communication using SSL.
- Captured screenshots as proof of implementation.


## 📂 Commands Used

```bash
# Generate private key and certificate
openssl req -x509 -newkey rsa:4096 -keyout key.pem -out cert.pem -days 365 -nodes

# Start encrypted server
openssl s_server -quiet -key key.pem -cert cert.pem -port 8080

# Connect from client
openssl s_client -connect [SERVER_IP]:8080

