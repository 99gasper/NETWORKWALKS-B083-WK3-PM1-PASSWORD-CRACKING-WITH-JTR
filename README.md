# NETWORKWALKS-B083-WK3-PM1-PASSWORD-CRACKING-WITH-JTR
# 🔐 Password Cracking Lab Using John the Ripper

## 📌 Project Overview

This project was a practical exercise on **password security and password recovery** using **John the Ripper (JtR)**.

The main goal was to understand how password-protected PDF files can be assessed in an authorized lab environment. I worked with three PDF files, extracted their password hashes, used John the Ripper to perform password cracking, and then used the recovered passwords to open the original PDF files.

> ⚠️ **Ethical Notice:** This practical was performed only on files used for the authorized cybersecurity exercise. Password cracking should only be carried out on systems and files where permission has been given or where you are the owner.

---

# 🎯 Objectives

The main objectives of this practical were to:

- Install and set up John the Ripper on my PC.
- Extract password hashes from three protected PDF files.
- Save the extracted hashes in separate text files.
- Use John the Ripper to recover the passwords.
- Verify the recovered passwords by opening the protected PDF files.
- Understand the basic process of password hash cracking.

---

# 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| **John the Ripper (JtR)** | Used to crack the extracted password hashes |
| **PDF Hash Extractor** | Used to extract password hashes from the PDF files |
| **Text Editor** | Used to save the extracted hashes in text files |
| **Password-Protected PDF Files** | Used as the target files for the practical |

---

# 🔎 Practical Steps

## Step 1: Installing John the Ripper

The first step was to install **John the Ripper (JtR)** on my computer.

After installation, I opened John the Ripper and made sure it was ready to be used for the password-cracking practical.

### Evidence

![John the Ripper Installation](screenshots/1-install-JtR.png)

---

## Step 2: Extracting PDF Hash Values

The second step was to extract the password hash values from the three protected PDF files.

I used a **PDF Hash Extractor** to process each PDF file and obtain the corresponding hash value.

The three PDF files produced three separate hash values.

### Evidence

![PDF Hash Extraction](screenshots/02-pdf-hash-extraction.png)

---

## Step 3: Saving the Extracted Hashes

After extracting the hashes, I copied each hash value and pasted it into a text document.

I saved the extracted hashes as separate files:

- `hash1.txt`
- `hash2.txt`
- `hash3.txt`

These files were then used as input for John the Ripper.

### Evidence

![Hash Files](screenshots/03-hash-files.png)

---

## Step 4: Cracking the Hashes with John the Ripper

The fourth step was to use **John the Ripper** to crack the extracted hashes.

I loaded the saved hash files into John the Ripper and allowed the tool to perform the password-cracking process.

After the cracking process was completed, John the Ripper revealed the recovered passwords for the three PDF files.

### Evidence

![John the Ripper Cracking](screenshots/04-john-cracking.png)

---

## Step 5: Verifying the Recovered Passwords

The final step was to test the recovered passwords.

I entered each recovered password into its corresponding protected PDF file. The passwords successfully opened the PDF files, confirming that the recovered passwords were correct.

### Evidence

![PDF Password Verification](screenshots/05-pdf-password-verification.png)

---

# 📊 Practical Summary

| Step | Activity | Result |
|---:|---|---|
| **1** | Installed John the Ripper | JtR was successfully installed and ready for use |
| **2** | Extracted PDF hashes | Hashes were obtained from three protected PDF files |
| **3** | Saved hashes in text documents | Created `hash1.txt`, `hash2.txt`, and `hash3.txt` |
| **4** | Cracked the hashes using JtR | Passwords were successfully recovered |
| **5** | Tested the recovered passwords | The passwords successfully opened the protected PDF files |

---

# 💡 What I Learned

Through this practical, I learned how password-protected files can be assessed through their extracted password hashes.

I also learned that the password itself is not directly stored in the hash file. Instead, a hash value is extracted and then analyzed by a password-cracking tool such as John the Ripper.

The exercise helped me understand the relationship between:

**PDF File → Password Hash → John the Ripper → Recovered Password → PDF Access**

Most importantly, I learned the importance of using strong passwords. Weak and predictable passwords can be easier to recover during a password-cracking exercise, while stronger passwords are generally more difficult to guess.

---

# 🔐 Security Recommendations

Based on this practical, I recommend:

- Use long and unique passwords for sensitive files.
- Avoid common words and easily guessed information.
- Do not reuse the same password for different files or accounts.
- Use a password manager when managing many passwords.
- Keep password-protected files in secure storage.
- Perform password auditing only with proper authorization.

---

# 📸 Evidence

Screenshots from the practical are stored in the `screenshots` folder.

Suggested structure:

```text
Password-Cracking-JTR/
│
├── README.md
│
├── screenshots/
│   ├── 01-john-installation.png
│   ├── 02-pdf-hash-extraction.png
│   ├── 03-hash-files.png
│   ├── 04-john-cracking.png
│   └── 05-pdf-password-verification.png
│
├── hash1.txt
├── hash2.txt
└── hash3.txt
```

> **Security note:** Do not publish real passwords, sensitive hashes, or confidential documents in a public GitHub repository. Replace sensitive evidence with safe screenshots or redact the sensitive parts before publishing.

---

# ✅ Conclusion

This practical gave me hands-on experience with **John the Ripper** and showed me the basic process involved in recovering passwords from protected PDF files.

I completed the exercise by installing John the Ripper, extracting hashes from three PDF files, saving the hashes in text documents, cracking the hashes, and finally using the recovered passwords to open the protected PDF files.

The exercise improved my understanding of **password security, hash extraction, password auditing, and ethical use of cybersecurity tools**.

---

## 👤 Author

**Gasper Boniphace**  
Cybersecurity Professional — **B083**

---

## 📌 Project Information

| Item | Details |
|---|---|
| **Project** | Password Cracking with John the Ripper |
| **Tool** | John the Ripper (JtR) |
| **Files Tested** | 3 Password-Protected PDF Files |
| **Hash Extraction Tool** | PDF Hash Extractor |
| **Program** | Cybersecurity Program |
| **Batch** | B083 |

---

**End of Report**
