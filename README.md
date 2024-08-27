Ransomware Simulator: ransom.py
🔐 Overview
This script demonstrates basic ransomware functionality by encrypting and decrypting files and folders using a password-based key derivation system.

🚀 Features
Encrypt Files/Folders: Securely encrypt individual files or entire directories.
Decrypt Files/Folders: Decrypt encrypted files and directories with the correct password.
Password-Based Key Derivation: Uses Scrypt for deriving cryptographic keys.
⚠️ Warning
Use this script with caution. It is intended for educational and demonstration purposes only. Never use it for malicious purposes. Ensure you understand the implications of encrypting and decrypting files before running the script.

💻 Getting Started
Clone the repository:
bash
Copy code
git clone https://github.com/zigzag43/cybersec.git
Navigate to the project directory:
bash
Copy code
cd cybersec
Install dependencies:
bash
Copy code
pip install cryptography
🛠️ Usage
Run the script with the following commands:

Encrypt a file or folder:

bash
Copy code
python ransom.py path/to/file_or_folder -e
Decrypt a file or folder:

bash
Copy code
python ransom.py path/to/file_or_folder -d
🔧 Suggestions for Improvement
To enhance the script, consider adding a feature to automatically encrypt files upon opening them. This can be achieved by integrating a file system watcher or a command that encrypts files after they are accessed.

📜 License

Copyright (c) [Nabin tharu]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Suggestion 
IF you know python you can make the file location to  c:  drives and make it encrypt all file just  by running it in victim laptop you can converting in exe file  and  send it to victim it will encrypt there data when they run it .


📫 Contact
Reach out via LinkedIn or email.  https://www.linkedin.com/in/nabin-tharu-1a82b4286?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BOUrdIkFuTMSndRY3vdb19w%3D%3D or Nabintharu773@gmail.com
