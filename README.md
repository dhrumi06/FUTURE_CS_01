# FUTURE_CS_01

# Web Application Security Testing — DVWA

## 📌 Project Overview

It demonstrates practical web application security testing using Damn Vulnerable Web Application (DVWA). It includes vulnerability assessment and exploitation of common web flaws: SQL Injection, Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF), and Insecure Direct Object References (IDOR).  
All vulnerabilities were tested in a safe, controlled environment for educational purposes only.



## ✅ Objectives

- Identify and exploit common web vulnerabilities.
- Document risk impact and provide mitigation recommendations.
- Build a professional Security Assessment Report.



## 👤 Intern Details
**Name:** Dhrumi Sonani

**Role:** Cybersecurity

**Program:** Future Interns -Cybersecurity Internship

**Task:** Web Application Security Testing — DVWA



## 🛠️ Tools & Technologies

- **DVWA** — Vulnerable web app for hands-on practice.
- **OWASP ZAP** — Open-source web vulnerability scanner.
- **Burp Suite Community Edition** — Manual testing toolkit.
- **Kali Linux** — Penetration testing OS with built-in tools.
- **Browser** — Configured with proxy to intercept traffic.



## 🔍 Vulnerabilities Tested

### 1️⃣ SQL Injection (SQLi)

- **Description:** Inject malicious SQL statements to bypass authentication or extract database data.
- **Tested In DVWA:** `SQL Injection` module.
- **Example:** Entered `' OR '1'='1` to bypass login.
- **Mitigation:** Use prepared statements and parameterized queries.



### 2️⃣ Cross-Site Scripting (XSS)

- **Description:** Inject malicious scripts to run in a victim’s browser.
- **Tested In DVWA:** `XSS (Reflected)` and `XSS (Stored)` modules.
- **Example:** `<script>alert('XSS')</script>` displayed as a pop-up.
- **Mitigation:** Encode output, use Content Security Policy (CSP), validate inputs.



### 3️⃣ Cross-Site Request Forgery (CSRF)

- **Description:** Trick an authenticated user into executing unwanted actions.
- **Tested In DVWA:** `CSRF` module.
- **Example:** Forced user password change via crafted HTML form.
- **Mitigation:** Implement anti-CSRF tokens and validate HTTP headers.

---

### 4️⃣ Insecure Direct Object References (IDOR)

- **Description:** Manipulate object references (IDs) to access unauthorized data.
- **Tested In DVWA:** User ID parameter in the URL.
- **Example:** Changed user ID in the URL to view other user profiles.
- **Mitigation:** Enforce proper access controls and ID validation.




## 📚 Learning Outcomes

- ✅ Practical hands-on experience with vulnerability scanning.
- ✅ Ethical hacking and penetration testing basics.
- ✅Gained practical experience in identifying and exploiting real-world web application vulnerabilities in a safe lab environment.
- ✅Understood how common vulnerabilities such as SQL Injection, Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF), and Insecure Direct Object       References  (IDOR) occur and how attackers exploit them.





