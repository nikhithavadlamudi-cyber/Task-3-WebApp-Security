# Web Application Security Assessment - Task 3

## 🔍 Target Website:
https://testphp.vulnweb.com

use an alternative XSS Demo Site

https://xss-game.appspot.com/level1

This is a legal, intentionally vulnerable web application provided by Acunetix for learning and testing purposes.

---

## 🛠️ Tools Used:
- Web Browser (Google Chrome)
- Optional: OWASP ZAP (for automated scanning)

---

## 🚨 Vulnerability 1: Cross-Site Scripting (XSS)

- **Location:** Search bar
- **Payload Used:** `<script>alert('XSS')</script>`
- **Result:** The alert box popped up in the browser
- **Impact:** If exploited, attackers can run malicious scripts in the user’s browser, steal session cookies, or deface the site.

---

## ✅ Suggested Mitigation:

- Sanitize input on the server side.
- Escape special characters in HTML.
- Implement Content Security Policy (CSP) headers.

---

## 🎯 Outcome:

The vulnerability was successfully identified using manual input testing in the search field. This shows how important input validation and output encoding are for protecting web applications.

---

## 📚 Learning:

- How to test basic web app vulnerabilities
- How to write a professional vulnerability report
- Understanding the importance of safe input handling
