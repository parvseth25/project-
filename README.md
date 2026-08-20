# 🔐 KeyVault-CLI

A lightweight local credential manager protected with **AES-GCM-256** encryption and **PBKDF2-HMAC-SHA256** key derivation.

## 🚀 Setup & Run
```bash
pip install -r requirements.txt
python main.py init
python main.py add github user@example.com -g
python main.py get github
python main.py list
