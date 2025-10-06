# Qr-Code-Phishing

Medusa Phisher is a phishing tool script designed to create phishing pages for various online services. It allows users to set up phishing pages for services like Instagram, Facebook, Twitter, and more. The script facilitates hosting these phishing pages using localhost.run for tunnelling, making it easy to capture user credentials.

---

# Features
1. Create phishing pages for multiple online services.

2. Host phishing pages using localhost.run for easy access.

3. Customizable phishing page creation for a tailored approach.

4. Catch credentials entered into phishing pages for analysis.

5. Add option to choose either to use default port or custom.

6. The generated phishing link will be displayed, along with its QR code for easy access.

---

# Dependencies
• PHP: Required for hosting the phishing pages locally.

• SSH: Necessary for creating SSH tunnels using localhost.run.

• XTERM: Necessary to generate link and QR code.

• Note: `setup.sh` installs those dependencies for you

---

# Installation & Setup

### Clone the github:
```
git clone https://github.com/Adrilaw/MedusaPhisher.git
cd MedusaPhisher
chmod +x setup.sh
./setup.sh
```

### SSH keygen
```
ssh-keygen -t rsa -b 4096 -C "user@example.com"
```
Generates a new RSA SSH key pair (private + public) using a 4096-bit key length and attaches the comment user@example.com to the public key (useful for identifying the key later).

  `ssh-keygen` — OpenSSH tool for creating and managing SSH keys.
  `-t rsa` — choose the RSA algorithm.
  `-b 4096` — set the key size to 4096 bits (stronger than 2048).  
  `-C "user@example.com"` — attach a comment to the public key (commonly an email or identifier).

### Start the tool
```
./medusaphisher
```
* Select the platform.
* Select the tunneling method.
* The QR will generate.
* Scan the qr to access the phishing sites.

---

# Disclaimer
This script is intended for educational purposes only. The misuse of this tool for illegal activities is strictly prohibited. The author assumes no responsibility for any misuse of this script.
