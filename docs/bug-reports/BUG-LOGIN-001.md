**Bug ID:** BUG-LOGIN-001  
**Title:** Login error message displays raw HTML and non-clickable support link  
**Module:** Login / Authentication  
**Severity:** Major  
**Priority:** High  
**Status:** Fail   

---

**Environment:**  
- OS: Windows 11  
- Browser: Chrome 126  
- Site: https://il.iherb.com  
- Language: Hebrew  

---

**Preconditions:**  
1. User has a valid registered iHerb account  
2. User is logged out  
3. Browser language set to Hebrew  

---

**Steps to Reproduce:**  
1. Navigate to the iHerb homepage  
2. Click “My Account”  
3. Enter a valid email address  
4. Enter an incorrect password  
5. Click “Sign In”  
6. Repeat incorrect login 4–5 times  
7. Observe the error message  

---

**Expected Result:**  
- A clear, readable error message should appear  
- Support link should be clickable and properly formatted  
- No raw HTML fragments should be visible  

---

**Actual Result:**  
- Error message displays raw HTML inside the text  
- Support link appears as plain text and is not clickable  
- Hebrew text is broken due to inline code  

---

**Impact / Risk:**  
- Users cannot understand the message  
- Login flow becomes unclear  
- Website appears unprofessional  

---

**Attachments:**  
- `docs/screenshots/login-error/login-error.png`
