**Bug ID:** BUG-PHONE-006  
**Title:** Phone number displays with incorrect formatting and extra symbols  
**Module:** User Profile / UI  
**Severity:** Low  
**Priority:** Low  
**Status:** Fail  

---

**Environment:**  
- OS: Windows 11  
- Browser: Chrome  
- Language: Hebrew  
- URL: https://il.iherb.com  

---

**Preconditions:**  
1. User has a saved phone number in their account  
2. User is logged into the website  

---

**Steps to Reproduce:**  
1. Log in to the iHerb website  
2. Navigate to **My Account**  
3. Locate the phone number shown in the header or profile section  
4. Edit user details (optional)  
5. Save changes and observe formatting again  

---

**Expected Result:**  
- Phone number should be displayed in a consistent, readable format  
- No extra characters (such as "!") should appear  
- RTL/LTR alignment should be correct for Hebrew users  
- Format examples:  
  - `+972-50-712-5465`  
  - `050-712-5465`  

---

**Actual Result:**  
- Phone number contains extra symbols such as "!"  
- Spacing is incorrect  
- Mixed RTL/LTR direction makes it appear broken  
- Formatting changes inconsistently after editing profile  

---

**Impact / Risk:**  
- Minor UI defect  
- Reduces professionalism of the profile page  
- Could confuse users reading their contact information  

---

**Attachments:**  
👉 [phone-format-problem.png](../screenshots/phone-format/phone-format-problem.png)
