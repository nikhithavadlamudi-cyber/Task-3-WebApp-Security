# 🔐 Task 3 - Web Application Security Assessment (Challenging Level)

This repository contains the submission for Task 3 of my Cyber Security Internship under **Hunar Intern**.

---

## 🧾 Task Objective

To perform a basic web application security assessment by identifying and reporting vulnerabilities like Cross-Site Scripting (XSS). The goal is to strengthen the application's security posture through testing and documentation.

---

## 🌐 Target Web Application

- **Website:** [https://xss-game.appspot.com/level1](https://xss-game.appspot.com/level1)
- **Purpose:** This is a legal and intentionally vulnerable website developed by Google for learning XSS vulnerabilities.

---

## 🛠️ Tools Used

- Web Browser (Google Chrome)
- GitHub (for documentation)
- VS Code (for writing the report)

---

## 🔍 Vulnerability Identified

### ✴️ Cross-Site Scripting (XSS)

- **Test Input:** `<script>alert('XSS')</script>`
- **Location:** Name input box on the level 1 page
- **Result:** A JavaScript alert was triggered and the site allowed advancement to the next level
- **Impact:** Proves that unfiltered user input can execute scripts, which can lead to session hijacking or page manipulation

---

## ✅ Recommendations

- Sanitize all user inputs
- Encode output before displaying in the browser
- Implement Content Security Policy (CSP) headers

---

## 📁 Files Included

- `report.md` – Detailed explanation of the testing process, vulnerability, impact, and mitigation

---

## 🎯 Outcome

Successfully identified and documented a real XSS vulnerability in a controlled environment, gaining hands-on experience in web application penetration testing.

---

## 📢 LinkedIn Post

Shared a short demo video and this report on LinkedIn as part of my internship task under **#HunarIntern** and **#HunarTech**.
