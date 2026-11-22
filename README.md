
# 🔐 Networkwalks Internship – Week 3
## Password Cracking with John the Ripper (JTR) & Networkwalks Tools

## 📌 Project Overview

This repository documents my Week 3 practical tasks completed as part of the Networkwalks Cybersecurity Internship.

The objective of this lab was to understand and practise password recovery techniques on password-protected PDF files using two different approaches:

1. John the Ripper (JTR) with Johnny GUI.
2. Networkwalks Online Password Recovery Tools.

The exercises helped me understand password hashing, hash extraction, password auditing, and practical password-recovery workflows.

---

## 🎯 Objectives

- Understand password-protected PDF files.
- Learn the basics of password hashing.
- Practise password recovery using John the Ripper.
- Explore Johnny GUI on Kali Linux.
- Extract PDF password hashes using online tools.
- Perform password auditing using Networkwalks tools.
- Document practical results and evidence.

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Kali Linux | Operating System |
| John the Ripper | Password auditing and recovery |
| Johnny GUI | Graphical interface for John the Ripper |
| Networkwalks Hash Calculator | PDF hash extraction |
| Networkwalks Password Cracker | Password recovery testing |

### Official Resources

- [John the Ripper](https://www.openwall.com/john/)
- [Johnny GUI](https://openwall.info/wiki/john/johnny)
- [Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator/)
- [Networkwalks Password Cracker](https://networkwalks.com/password-cracker/)

---

# 🔍 Task 1: Password Cracking with John the Ripper (JTR)

### Description

In this task, I used John the Ripper and its graphical interface, Johnny, on Kali Linux to practise recovering passwords from the provided locked PDF files.

### Practical Workflow

1. Opened Kali Linux.
2. Launched the Johnny GUI application.
3. Selected the provided password-protected PDF file.
4. Prepared the PDF hash using the appropriate extraction workflow.
5. Loaded the hash into John the Ripper.
6. Started the password recovery process.
7. Analysed the results.

### Screenshots / Evidence

Add your actual screenshots below:

**1. Johnny GUI Interface**

![Johnny GUI](screenshots/01-johnny-open.png)

**2. PDF Hash Preparation**

![PDF Hash](screenshots/02-jtr-hash-loaded.png)

**3. Password Recovery Result**

![JTR Result](screenshots/03-jtr-result.png)

### Results

| PDF File | Status |
|---|---|
| My Locked PDF1.pdf | Completed / Update result |
| My Locked PDF2.pdf | Completed / Update result |
| My Locked PDF3.pdf | Completed / Update result |

---

# 🌐 Task 2: Password Cracking with Networkwalks Tools

### Description

In this task, I explored browser-based password recovery using Networkwalks online tools.

The process involved extracting a PDF password hash and submitting it to the Networkwalks Password Cracker.

### Practical Workflow

1. Opened the Networkwalks Hash Calculator.
2. Uploaded the provided locked PDF.
3. Extracted the PDF password hash.
4. Copied the generated hash.
5. Opened the Networkwalks Password Cracker.
6. Submitted the extracted hash.
7. Analysed the password recovery results.

### Screenshots / Evidence

**1. Networkwalks Hash Calculator**

![Hash Calculator](screenshots/04-networkwalks-hash-calculator.png)

**2. Extracted PDF Hash**

![Extracted Hash](screenshots/05-pdf-hash.png)

**3. Networkwalks Password Cracker**

![Password Cracker](screenshots/06-networkwalks-cracker-result.png)

### Results

| PDF File | Hash Extracted | Password Recovered |
|---|---|---|
| My Locked PDF1.pdf | Yes / No | Yes / No |
| My Locked PDF2.pdf | Yes / No | Yes / No |
| My Locked PDF3.pdf | Yes / No | Yes / No |

---

## 📚 Key Learning Outcomes

During this practical assignment, I learned:

- Fundamentals of password hashing.
- How password-protected PDF files can be audited.
- How John the Ripper works.
- How to use Johnny GUI on Kali Linux.
- How to extract password hashes from PDF files.
- How browser-based password recovery tools work.
- Differences between local and online password-auditing workflows.
- Importance of ethical and authorised security testing.

---

## 📂 Project Structure

```text
Networkwalks-Week3-Password-Cracking/
│
├── README.md
│
├── screenshots/
│   ├── 01-johnny-open.png
│   ├── 02-jtr-hash-loaded.png
│   ├── 03-jtr-result.png
│   ├── 04-networkwalks-hash-calculator.png
│   ├── 05-pdf-hash.png
│   └── 06-networkwalks-cracker-result.png
│
└── report/
    └── Week3-Report.pdf
```

---

## 🏁 Conclusion

I successfully completed the Week 3 password-cracking practical tasks as part of my Networkwalks Cybersecurity Internship.

This assignment provided hands-on experience with John the Ripper, Johnny GUI, and Networkwalks online password recovery tools.

It strengthened my understanding of password hashing, hash extraction, and password auditing techniques.

I look forward to developing more practical cybersecurity skills through upcoming internship assignments.

---

## ⚠️ Disclaimer

This project is strictly for educational purposes and authorised security testing.

All password recovery activities should only be performed on files that you own or have explicit permission to test.

---

**Internship:** Networkwalks Cybersecurity Internship  
**Week:** 03  
**Project:** Password Cracking with John the Ripper & Networkwalks Tools

#CyberSecurity #EthicalHacking #JohnTheRipper #KaliLinux #Networkwalks
