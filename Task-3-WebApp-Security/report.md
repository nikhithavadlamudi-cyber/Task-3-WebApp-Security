## 🔍 Target Website:
https://xss-game.appspot.com/level1

This is a legal XSS training site by Google used to test and learn about Cross-Site Scripting.

---

## 🚨 Vulnerability: Cross-Site Scripting (XSS)

- **Input Field Used:** "What's your name?"
- **Payload:** `<script>alert('XSS')</script>`
- **Result:** An alert popup appeared, confirming that the script executed successfully.
- **Confirmation:** The site showed a message to proceed to the next level — proving the test was successful.

---

## ✅ Suggested Fix (if this were a real app):

- Sanitize all user inputs
- Encode HTML output properly
- Use a strict Content-Security-Policy (CSP) header
