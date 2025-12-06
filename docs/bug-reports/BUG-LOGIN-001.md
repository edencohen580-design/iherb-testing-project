**Bug ID:** BUG-LOGIN-001  
**Title:** Login error message displays raw HTML and non-clickable support link  
**Module:** Login / Authentication  
**Severity:** Major  
**Priority:** High  
**Status:** Fail  

---

**Environment:**  
- OS: Windows 11  
- Browser: Chrome 126 (Desktop)  
- URL: https://il.iherb.com  
- Language: Hebrew  

---

**Preconditions:**  
1. User has an active iHerb account  
2. The login page is accessible  
3. Browser is set to Hebrew display  

---

**Steps to Reproduce:**  
1. Navigate to the iHerb homepage.  
2. Click **“My Account”** in the top navigation bar.  
3. Enter a valid registered email address.  
4. Enter an **incorrect password** (repeat 4–5 times).  
5. Click the **“Sign In”** button.  

---

**Expected Result:**  
- A clear, readable error message should be displayed.  
- No raw HTML or broken markup should appear.  
- The support link should be clickable and correctly formatted.  
- User should remain logged out and be able to retry login.  

---

**Actual Result:**  
- Error message contains **raw HTML fragments**.  
- Customer support link appears as **plain text** and is **not clickable**.  
- The message appears unformatted and inconsistent with UI standards.  

---

**Impact:**  
This issue affects usability and trust.  
Users cannot access support easily, and the broken markup makes the system appear unstable or insecure.

---

**Attachments:**  
- Screenshot of the broken error message (HTML + non-clickable link):  
   `../screenshots/login-error/login-error.png`
