
CryptoShield Academy 🔐

A modern, interactive cryptographic learning playground built with vanilla JavaScript, Tailwind CSS, and a cyberpunk-inspired UI.

🎯 Purpose

CryptoShield Academy is an educational tool designed to help learners understand symmetric encryption algorithms through hands-on experimentation. It demonstrates foundational cryptographic concepts including Caesar cipher and XOR cipher implementations with real-time visualization.

Status: Built and deployed as part of IIT Kanpur B.Cyber Program application (June 2026)


✨ Features

🔤 Caesar Cipher


Interactive encryption/decryption with adjustable shift values (0-25)
Real-time output generation
Educational visualization of shift-based substitution
Perfect for understanding basic substitution ciphers


⚡ XOR Cipher


Bitwise XOR operations with configurable keys (0-255)
Hexadecimal output encoding
Demonstrates symmetric key cryptography principles
Shows how XOR is reversible: (plaintext ⊕ key) ⊕ key = plaintext


🖥️ Developer Console


Real-time system logging
Operation telemetry tracking
Terminal-style output for authentic hacker aesthetic
Helps visualize cryptographic state transitions


🎨 Cyberpunk UI


Dark mode optimized for long coding sessions
Neon green/cyan color scheme with glow effects
Responsive design (desktop + tablet friendly)
Tailored for cybersecurity developer experience



🚀 Quick Start

Option 1: Use Live Demo

Visit: https://ritabrata940-maker.github.io/cryptoshield

(Live link automatically generated once you enable GitHub Pages)

Option 2: Run Locally


Clone this repository:


bash   git clone https://github.com/ritabrata940-maker/cryptoshield.git
   cd cryptoshield


Open index.html in your browser:


bash   # macOS
   open index.html
   
   # Linux
   xdg-open index.html
   
   # Windows
   start index.html


Or use a local server (recommended):


bash   # Python 3
   python -m http.server 8000
   
   # Node.js (with http-server)
   npx http-server

Then visit http://localhost:8000 or http://localhost:8080


📚 How to Use

Caesar Cipher


Enter plaintext in the "Input Text" field
Adjust the Shift Value slider (0-25)
Click ENCRYPT to scramble the message
Click DECRYPT to recover the original text


Example:


Input: HELLO
Shift: 3
Output: KHOOR (each letter shifted by 3 positions)


XOR Cipher


Enter plaintext in the "Input Text" field
Set the XOR Key (0-255)
Click ENCRYPT to apply bitwise XOR
Output appears in hexadecimal format
Use the same key with DECRYPT to recover plaintext


Example:


Input: A (ASCII 65)
Key: 42
Binary: 01000001 ⊕ 00101010 = 01101011
Hex Output: 6b



🛠️ Technical Stack


Frontend: Vanilla JavaScript (no frameworks)
Styling: Tailwind CSS (via CDN)
Encryption: Client-side, educational implementations
Deployment: GitHub Pages (static site)
Browser Support: Modern browsers (Chrome, Firefox, Safari, Edge)



🔐 Security Note

⚠️ Educational Use Only

This application is built for learning purposes only. The cryptographic implementations are simplified educational models:


Caesar Cipher: Extremely weak (256 possible keys, easily brute-forced)
XOR Cipher: Weak as a standalone cipher (vulnerable to frequency analysis)
Not for Real Data: Do NOT use these implementations for protecting sensitive information


For production security, use industry-standard libraries:


Node.js: crypto module (built-in)
Python: cryptography library
Java: javax.crypto package



📖 Learning Outcomes

After using CryptoShield Academy, you should understand:


Substitution Ciphers: How character position mapping works
XOR Operations: Bitwise logic and symmetric key principles
Encryption Workflow: Plaintext → Cipher → Ciphertext
Decryption Reversibility: Why XOR can be "undone" with the same key
System Design: How to build interactive cryptographic tools



🎓 Next Steps for Learning


Study AES (Advanced Encryption Standard) for modern symmetric encryption
Explore RSA and ECC for asymmetric cryptography
Learn hashing algorithms (SHA-256, bcrypt) for data integrity
Practice on TryHackMe and OverTheWire for hands-on cybersecurity



📁 Project Structure

cryptoshield/
├── index.html          # Complete application (HTML + CSS + JS)
├── README.md           # This file
└── .gitignore          # Git ignore file (if applicable)


🤝 Contributing

This is a personal educational project for IIT Kanpur's B.Cyber program. However, suggestions and improvements are welcome:


Fork the repository
Create a feature branch (git checkout -b feature/improvement)
Commit changes (git commit -m "Add improvement")
Push to branch (git push origin feature/improvement)
Open a Pull Request



📄 License

This project is provided as-is for educational purposes. Feel free to fork, modify, and use for your own learning.


👨‍💻 Author

Ritabrata Santra

JEE 2026 | IIT Kanpur B.Cyber Program Applicant

📧 ritabrata940@gmail.com




📞 Support

If you encounter any issues:


Check browser console for errors (F12 → Console tab)
Verify JavaScript is enabled
Try a different browser
Clear browser cache and reload



⚡ Version History


v1.0 (June 2026) — Initial release with Caesar & XOR ciphers, console logging, dark UI



Built with ❤️ for cybersecurity enthusiasts
