# burp-suite-practice
Hands-on Burp Suite practice to test XSS, SQLi, and CSRF vulnerabilities using DVWA and Juice Shop in a safe lab setup.

```markdown
# 🛡️ Burp Suite Web Attacks – Hands-On Practice

This repository documents my hands-on practice using **Burp Suite** to discover and exploit common web vulnerabilities in intentionally vulnerable applications.

---

## 📌 What is Burp Suite?

Burp Suite is a powerful web vulnerability scanner and proxy tool used in **penetration testing**, **bug bounty**, and **web application security**. I used it primarily for:
- Intercepting and modifying HTTP requests/responses
- Automating attacks using Intruder
- Testing for vulnerabilities like **XSS**, **SQLi**, and **CSRF**

---

## 🧰 Tools & Setup

- **Burp Suite Community Edition**
- **Kali Linux** / **Windows**
- **Vulnerable apps**:
  - DVWA (Damn Vulnerable Web App)
  - OWASP Juice Shop
  - bWAPP

---

## 🗂️ Repository Structure

```

burp-suite-practice/
├── screenshots/
│   ├── xss\_payload\_example.png
│   ├── sql\_injection\_demo.png
│   └── csrf\_token\_bypass.png
├── vulnerability-notes/
│   ├── xss.md
│   ├── sqli.md
│   ├── csrf.md
├── burp-config/
│   └── custom\_scope.json
├── README.md

```

---

## 🔍 Web Vulnerabilities Practiced

### 1️⃣ Cross-Site Scripting (XSS)
- Reflected & Stored XSS using `<script>alert('XSS')</script>`
- Input validation bypass

### 2️⃣ SQL Injection
- Classic `OR '1'='1` injection
- Automated detection with Burp Intruder

### 3️⃣ CSRF (Cross-Site Request Forgery)
- Captured CSRF tokens
- Attempted token reuse or missing token exploitation

---

## 📸 Sample Screenshots

| XSS Exploit | SQLi Bypass |
|-------------|-------------|
| ![XSS](screenshots/xss_payload_example.png) | ![SQLi](screenshots/sql_injection_demo.png) |

---

## 📚 What I Learned

- How web apps process user input and fail when improperly validated
- How attackers can intercept, modify, and replay traffic
- How to build defenses using WAFs and secure coding practices
- How to responsibly test using **legal, safe** environments

---

## ⚠️ Disclaimer

> This project is intended strictly for **educational and ethical** purposes. All tests were conducted on **legal, self-hosted vulnerable apps** in isolated lab environments.

---

## ✅ Next Steps

- Add SSRF and IDOR testing
- Automate form fuzzing with Burp extensions
- Explore Burp Pro features

```

---

## 🧾 Description for GitHub (short version):

```
Hands-on practice using Burp Suite to discover and test web application vulnerabilities like XSS, SQLi, and CSRF in safe lab environments.
```
