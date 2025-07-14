# FUTURE_CS_01

# Web Application Security Testing — DVWA

## 📌 Overview

It demonstrates practical web application security testing using Damn Vulnerable Web Application (DVWA). It includes vulnerability assessment and exploitation of common web flaws: SQL Injection, Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF), and Insecure Direct Object References (IDOR).  



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

- **DVWA** – Target application for vulnerability testing
  
  ![image alt](https://github.com/dhrumi06/FUTURE_CS_01/blob/9a09a8380e72ccc6c3f7d72a288ab0fdcddbf5f1/Screenshots/a1.png)
  
- **Burp Suite Community Edition** — Manual testing toolkit.
- **Kali Linux** — Penetration testing OS with built-in tools.
- **Browser** — Configured with proxy to intercept traffic.
- **Firefox** – Used for testing and interacting with DVWA



## 🔍 Vulnerabilities Tested

### 1️⃣ SQL Injection (SQLi)

- **Description:** Inject malicious SQL statements to bypass authentication or extract database data.
- **Tested In DVWA:** `SQL Injection` module.
- **Example:** Entered `1' OR '1'='1` to bypass login.
- **Mitigation:** Use prepared statements and parameterized queries.

  ![image alt](https://github.com/dhrumi06/FUTURE_CS_01/blob/9a09a8380e72ccc6c3f7d72a288ab0fdcddbf5f1/Screenshots/a3.png)
  ![image alt](https://github.com/dhrumi06/FUTURE_CS_01/blob/9a09a8380e72ccc6c3f7d72a288ab0fdcddbf5f1/Screenshots/a4.png)


### 2️⃣ Cross-Site Scripting (XSS)

- **Description:** Inject malicious scripts to run in a victim’s browser.
- **Tested In DVWA:** `XSS (Reflected)` and `XSS (Stored)` modules.
- **Example:** `<script>alert('XSS')</script>` displayed as a pop-up.
- **Mitigation:** Encode output, use Content Security Policy (CSP), validate inputs.
  ![image alt](https://github.com/dhrumi06/FUTURE_CS_01/blob/9a09a8380e72ccc6c3f7d72a288ab0fdcddbf5f1/Screenshots/a5.png)
  ![image alt](https://github.com/dhrumi06/FUTURE_CS_01/blob/9a09a8380e72ccc6c3f7d72a288ab0fdcddbf5f1/Screenshots/a6.png)



### 3️⃣ Cross-Site Request Forgery (CSRF)

- **Description:** Trick an authenticated user into executing unwanted actions.
- **Tested In DVWA:** `CSRF` module.
- **Example:** Forced user password change via crafted HTML form.
- **Mitigation:** Implement anti-CSRF tokens and validate HTTP headers.
  ![image alt](https://github.com/dhrumi06/FUTURE_CS_01/blob/9a09a8380e72ccc6c3f7d72a288ab0fdcddbf5f1/Screenshots/a8.png)
  ![image alt](https://github.com/dhrumi06/FUTURE_CS_01/blob/9a09a8380e72ccc6c3f7d72a288ab0fdcddbf5f1/Screenshots/a9.png)
  



### 4️⃣ Insecure Direct Object References (IDOR)

- **Description:** Manipulate object references (IDs) to access unauthorized data.
- **Tested In DVWA:** User ID parameter in the URL.
- **Example:** Changed user ID in the URL to view other user profiles.
- **Mitigation:** Enforce proper access controls and ID validation.
  ![image alt](https://github.com/dhrumi06/FUTURE_CS_01/blob/9a09a8380e72ccc6c3f7d72a288ab0fdcddbf5f1/Screenshots/b1.png)
  ![image alt](https://github.com/dhrumi06/FUTURE_CS_01/blob/9a09a8380e72ccc6c3f7d72a288ab0fdcddbf5f1/Screenshots/b2.png)
  ![image alt](https://github.com/dhrumi06/FUTURE_CS_01/blob/9a09a8380e72ccc6c3f7d72a288ab0fdcddbf5f1/Screenshots/b3.png)




## 📚 Learning Outcomes

- ✅ Practical hands-on experience with vulnerability scanning.
- ✅ Ethical hacking and penetration testing basics.
- ✅Gained practical experience in identifying and exploiting real-world web application vulnerabilities in a safe lab environment.
- ✅Understood how common vulnerabilities such as SQL Injection, Cross-Site Scripting (XSS), Cross-Site Request Forgery (CSRF), and Insecure Direct Object       References  (IDOR) occur and how attackers exploit them.





