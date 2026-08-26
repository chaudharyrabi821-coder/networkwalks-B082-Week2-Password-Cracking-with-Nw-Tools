         
**- [Back to README](README.md)**                     **- [Methodology](Methodology.md)**
# 🔐 Password Cracking with Networkwalks Tools — Lab Result

<p align="center">
  <img width="1024" height="1536" alt="01-Lab-Page" src="https://github.com/user-attachments/assets/718a67de-b7a6-4253-8e66-bcddb37e8acc" />

</p>

<h1 align="center">🛡️ Password Cracking — Practical Lab Result</h1>

<p align="center">
  <strong>Cybersecurity & Ethical Hacking • Week 3 • Module W3-PM2</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Module-W3--PM2-1f6feb?style=for-the-badge">
  <img src="https://img.shields.io/badge/Lab-Completed-2ea043?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Web--Based-8957e5?style=for-the-badge">
  <img src="https://img.shields.io/badge/Purpose-Educational-orange?style=for-the-badge">
</p>

> 🟢 **Lab Status:** Successfully Completed
> 🎯 **Environment:** Authorized Networkwalks training lab
> 🔎 **Focus:** PDF password-hash extraction, controlled dictionary attack, and password validation

---

## 📑 Table of Contents

- [1. Lab Overview](#1--lab-overview)
- [2. Objectives](#2--objectives)
- [3. Tools Used](#3--tools-used)
- [4. Lab Workflow](#4--lab-workflow)
- [5. Practical Evidence](#5--practical-evidence)
- [6. Recovered Password](#6--recovered-password)
- [7. Final Validation](#7--final-validation)
- [8. Technical Findings](#8--technical-findings)
- [9. Security Recommendations](#9--security-recommendations)
- [10. Evidence Summary](#10--evidence-summary)
- [11. Learning Outcomes](#11--learning-outcomes)
- [12. Repository Structure](#12--repository-structure)
- [13. Related Documentation](#13--related-documentation)
- [14. Ethical Disclaimer](#14--ethical-disclaimer)

---

## 1. 🔎 Lab Overview

This lab demonstrates a controlled password-recovery workflow against a **training PDF supplied for an authorized cybersecurity exercise**.

The practical process consisted of:

```text
📄 Protected PDF
      ↓
🔐 Hash Calculator
      ↓
🧬 PDF Password Hash
      ↓
🧪 Password Cracker
      ↓
📚 Dictionary Attack
      ↓
🔑 Password Recovered
      ↓
📖 PDF Password Validation
      ↓
🏆 Lab Completed
```

The exercise provides practical understanding of how weak or predictable passwords can be vulnerable to offline dictionary-based password testing when a crackable password hash is available.

> ⚠️ **Authorization:** This documentation is for educational and authorized security-testing purposes only.

---

## 2. 🎯 Objectives

| # | Objective | Status |
|---|---|---|
| 01 | Understand how a password-protected PDF can be represented as a crackable hash | ✅ Completed |
| 02 | Extract the PDF hash using the Networkwalks Hash Calculator | ✅ Completed |
| 03 | Perform a controlled dictionary attack | ✅ Completed |
| 04 | Recover the lab password | ✅ Completed |
| 05 | Validate the recovered password against the original PDF | ✅ Completed |
| 06 | Document the evidence and final result | ✅ Completed |

---

## 3. 🧰 Tools Used

| Tool | Purpose |
|---|---|
| 🔐 **Networkwalks Hash Calculator** | Extract a crackable hash from the protected PDF |
| 🧪 **Networkwalks Password Cracker** | Perform a controlled dictionary-based password test |
| 🌐 **Web Browser** | Access the Networkwalks training tools |
| 📄 **PDF Reader** | Verify the recovered password |
| 📚 **Dictionary Wordlist** | Provide candidate passwords for the authorized attack |

---

## 4. 🔄 Lab Workflow

### Workflow at a Glance

| Step | Activity | Result |
|---:|---|---|
| 1️⃣ | Open the Networkwalks training lab | ✅ |
| 2️⃣ | Upload the protected PDF | ✅ |
| 3️⃣ | Extract the PDF hash | ✅ |
| 4️⃣ | Copy the generated hash | ✅ |
| 5️⃣ | Paste the hash into Password Cracker | ✅ |
| 6️⃣ | Start the dictionary attack | ✅ |
| 7️⃣ | Recover the password | ✅ |
| 8️⃣ | Enter the password into the PDF | ✅ |
| 9️⃣ | Confirm successful PDF access | ✅ |

---

# 5. 📸 Practical Evidence

## Step 1 — 🧑‍💻 Open the Training Lab

The initial Networkwalks lab page introduced the exercise and presented the controlled workflow for PDF password recovery.

<p align="center">
  <img width="1024" height="1536" alt="01-Lab-Page" src="https://github.com/user-attachments/assets/cb93544b-3445-485a-8171-2ef450bf0710" />

</p>

**Observation**

- Authorized training environment identified.
- Password-cracking workflow presented.
- Lab objective was to recover the password of the supplied protected PDF.

---

## Step 2 — 🔐 Upload the Protected PDF to Hash Calculator

The protected PDF was loaded into the **Networkwalks Hash Calculator**.

<p align="center">
 <img width="1076" height="876" alt="02-Hash-Calculator" src="https://github.com/user-attachments/assets/75796445-9c39-4cd4-8cba-b99a07e108fc" />

</p>

The calculator detected that the PDF was encrypted and generated a crackable PDF hash.

### Key Evidence

```text
File: My Locked PDF4.pdf
Status: PDF is encrypted
Output: Crackable $pdf$... hash
Format: pdf2john / Hashcat-compatible
```

> 💡 **Security Concept:** A password-protected file may expose enough cryptographic information for authorized offline password-strength testing.

---

## Step 3 — 🧬 Hash Successfully Extracted

The generated PDF hash was displayed and made available for copying.

<p align="center">
<img width="871" height="230" alt="03-Hash-extracted" src="https://github.com/user-attachments/assets/3b44b7b0-75a7-409e-9c78-ff2e8c011de3" />

</p>

### Evidence

- 🔒 PDF encryption detected
- 🧬 `$pdf$...` hash generated
- 📋 Hash ready for the next stage
- 🔗 Hash compatible with the training password-cracking workflow

---

## Step 4 — 🧪 Configure Password Cracker

The extracted hash was supplied to the **Networkwalks Password Cracker**.

<p align="center">
 <img width="1072" height="633" alt="05-Password-Cracker" src="https://github.com/user-attachments/assets/1b7f959c-3941-43b7-a343-7121662243de" />

</p>

### Attack Configuration

| Parameter | Configuration |
|---|---|
| Attack Type | 📚 Dictionary Attack |
| Target | Authorized training PDF |
| Hash Input | `$pdf$...` |
| Wordlist | Built-in list |
| Wordlist Size | 100 passwords |
| Objective | Recover the PDF password |

---

## Step 5 — ▶️ Start the Dictionary Attack

The configured password-recovery process was started.

<p align="center">
 <img width="1042" height="851" alt="06-Attack-Started" src="https://github.com/user-attachments/assets/3e88205b-f771-46ca-981d-08d51c1f42c0" />

</p>

The interface displayed candidate passwords being tested against the PDF hash.

### Attack Progress Observed

```text
[*] Loaded wordlist: built-in list
[*] Target: PDF R4 / 128-bit dictionary attack
[*] Deriving keys with MD5 + RC4
[-] Trying: 123456
[-] Trying: password
[-] Trying: 123456789
```

> 🧠 **Concept:** A dictionary attack tests candidate passwords from a predefined list instead of exhaustively trying every possible combination.

---

## Step 6 — 🎉 Password Recovered

The password cracker completed the controlled attack and displayed the recovered training password.

<p align="center">
  <img width="837" height="232" alt="07-Password" src="https://github.com/user-attachments/assets/92b85913-3029-4b22-87c5-bfa6b979108d" />

</p>

### 🔑 Recovered Lab Password

<p align="center">
  <code>1qaz2wsx</code>
</p>

> ⚠️ **Training Credential:** This password is documented only as part of the supplied lab evidence. It should never be reused for real accounts, systems, or sensitive files.

---

## Step 7 — 🔓 Enter Recovered Password

The recovered password was entered into the PDF reader to validate the result.

<p align="center">
<img width="1312" height="997" alt="08-Enter-Password" src="https://github.com/user-attachments/assets/91a99b71-c93f-44e9-a04c-190d30a2a42b" />

</p>

### Validation

The password was submitted to the protected PDF.

**Result:** 🟢 Password accepted.

---

## Step 8 — ✅ PDF Successfully Opened

The protected PDF opened successfully after the recovered password was entered.

<p align="center">
<img width="562" height="720" alt="09-Result" src="https://github.com/user-attachments/assets/2b7976e8-023a-41ca-9dc8-78dfe137126b" />

</p>

### Final Validation

```text
PDF Password Verification
        ↓
Password Accepted
        ↓
Protected PDF Opened
        ↓
Lab Successfully Completed
```

---

# 6. 🔑 Recovered Password

<p align="center">

### `1qaz2wsx`

</p>

| Validation Point | Result |
|---|---|
| Password recovered by cracker | ✅ |
| Password entered into PDF reader | ✅ |
| Password accepted | ✅ |
| PDF opened successfully | ✅ |

---

# 7. 🏆 Final Validation

## Overall Lab Result

| Test / Activity | Status |
|---|:---:|
| Training lab accessed | 🟢 PASS |
| Protected PDF loaded | 🟢 PASS |
| PDF hash extracted | 🟢 PASS |
| Hash transferred to cracker | 🟢 PASS |
| Dictionary attack executed | 🟢 PASS |
| Password recovered | 🟢 PASS |
| Password validated | 🟢 PASS |
| Protected PDF opened | 🟢 PASS |
| Lab flag obtained | 🟢 PASS |

### 🚩 Training Lab Flag

```text
nw{networkwalks_flag_260821_1}
```

> 🏅 **Result:** The authorized lab was successfully completed and the recovered password was validated against the protected PDF.

---

# 8. 🔍 Technical Findings

## Finding 01 — Crackable PDF Hash

The protected PDF produced a `$pdf$...` representation through the Hash Calculator.

**Security impact:**
If an attacker obtains a crackable password hash, password candidates may be tested offline without repeatedly interacting with the original PDF.

**Risk:** 🟠 **Medium** in this controlled context; actual risk depends on password strength, hash protection, access to the hash, and surrounding controls.

---

## Finding 02 — Predictable Password

The lab password was successfully recovered using a dictionary-based attack.

**Security impact:**
Predictable password patterns can reduce the time and effort required for password recovery.

**Risk:** 🔴 **High** when similar password practices are used to protect real sensitive information.

---

## Finding 03 — Dictionary Attacks Can Be Effective

The controlled wordlist successfully identified the lab password.

**Security impact:**
Common, predictable, reused, or previously exposed passwords are more susceptible to dictionary-based password testing.

---

# 9. 🛡️ Security Recommendations

### 🔐 Password Security

- Use long, unique, and unpredictable passwords.
- Avoid common passwords and keyboard patterns.
- Never reuse passwords across systems.
- Use a reputable password manager to generate unique credentials.

### 📄 Document Protection

- Use strong passwords for sensitive documents.
- Protect confidential files with appropriate encryption and access controls.
- Limit access to password-protected documents and their associated credentials.

### 🧪 Security Testing

- Conduct password-security assessments only with explicit authorization.
- Use dedicated test accounts and test files during security assessments.
- Securely handle and delete extracted hashes after authorized testing.

---

# 10. 📊 Evidence Summary

| Evidence | What It Demonstrates |
|---|---|
| `01-Lab-Page.png` | Initial authorized lab environment |
| `02-Hash-Calculator.png` | PDF loaded into Hash Calculator |
| `03-Hash-extracted.png` | Crackable PDF hash generated |
| `05-Password-Cracker.png` | Password Cracker configured |
| `06-Attack-Started.png` | Dictionary attack running |
| `07-Password.png` | Password successfully recovered |
| `08-Enter-Password.png` | Recovered password entered |
| `09-Result.png` | Successful PDF validation |

---

# 11. 🧠 Learning Outcomes

### I learned how to:

- 🔐 Understand password protection on PDF documents.
- 🧬 Extract a crackable password hash from a protected PDF.
- 📚 Understand how dictionary attacks operate.
- 🧪 Perform controlled password-recovery testing.
- 🔓 Validate a recovered password against the original document.
- 📸 Collect and organize technical evidence.
- 🛡️ Understand why strong and unique passwords are important.

### Key Takeaway

> **A strong password is an important layer of defense. Predictable passwords can significantly reduce the resistance of protected data to offline password-guessing attacks.**

---

# 12. 📁 Repository Structure

```text
password-cracking-with-networkwalks-tools/
│
├── README.md
├── methodology.md
├── lab-result.md
│
└── screenshots/
    ├── 01-Lab-Page.png
    ├── 02-Hash-Calculator.png
    ├── 03-Hash-extracted.png
    ├── 05-Password-Cracker.png
    ├── 06-Attack-Started.png
    ├── 07-Password.png
    ├── 08-Enter-Password.png
    └── 09-Result.png
```

> 📌 **Recommended:** Keep all screenshots inside `screenshots/` so the repository remains clean and the Markdown image paths remain organized.

---

# 13. 🔗 Related Documentation

| Document | Description |
|---|---|
| 📘 [`README.md`](README.md) | Project overview, objectives, tools, and general documentation |
| 🧪 [`methodology.md`](Methodology.md) | Methodology and technical testing approach |
| 📊 [`lab-Result.md`](lab-Result.md) | Practical evidence, findings, validation, and final result |

---

# 14. ⚖️ Ethical Disclaimer

> 🚨 **IMPORTANT**
>
> This project is strictly intended for **educational, cybersecurity training, and authorized security-testing purposes**.
>
> Do **not** use password-recovery or password-cracking techniques against files, accounts, systems, or data without explicit authorization.
>
> The techniques documented here should be applied only within controlled environments, training labs, or authorized security assessments.
>
> The author assumes no responsibility for misuse of the information or techniques presented in this repository.

---

## 👤 Author

<p align="center">

**Rabi Chaudhary**
Cybersecurity Student / Junior Penetration Tester
**Cybersecurity & Ethical Hacking Internship — Networkwalks**

</p>

---

<p align="center">

### 🟢 LAB COMPLETED SUCCESSFULLY

**Learn Responsibly • Test Ethically • Secure Continuously 🔐**

</p>
