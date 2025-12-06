**Bug ID:** BUG-PHONE-006  
**Title:** Phone number displayed incorrectly with extra symbols and wrong direction  
**Module:** User Profile / UI  
**Severity:** Low  
**Priority:** Low  
**Status:** Fail  

---

**Environment:**  
- OS: Windows 11  
- Browser: Chrome  
- Language: Hebrew  

---

**Preconditions:**  
1. Phone number saved in the account  
2. User logged in  

---

**Steps to Reproduce:**  
1. Log in  
2. Go to "My Account"  
3. Observe phone number formatting  
4. Edit profile (optional)  
5. Check formatting again  

---

**Expected Result:**  
- Clean phone number formatting  
- No extra symbols  
- Correct RTL/LTR rendering  

---

**Actual Result:**  
- Number contains extra symbols (e.g., “!”)  
- Wrong spacing  
- Mixed RTL/LTR  

---

**Impact / Risk:**  
- Minor UI issue  
- Looks unprofessional  
- Confusing for users  

---

**Attachments:**  
- `docs/screenshots/phone-format/phone-format-problem.png`
