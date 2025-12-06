**Bug ID:** BUG-LOGIN-001  
**Title:** Login error message displays raw HTML and non-clickable support link  
**Module:** Login / Authentication  
**Severity:** Major  
**Priority:** High  

---

**Environment:**  
- OS: Windows 11  
- Browser: Chrome 126 (Desktop)  
- URL: https://il.iherb.com  
- Language: Hebrew  
- Network: Stable home Wi-Fi  

---

**Preconditions:**  
1. User has a valid, registered iHerb account.  
2. User is on the iHerb Hebrew website (https://il.iherb.com).  
3. User is logged out.

---

**Steps to Reproduce:**  
1. Navigate to the iHerb homepage.  
2. Click on **"החשבון שלי" / "My Account"** in the top navigation bar.  
3. In the login form, enter a **valid email address** of an existing account.  
4. In the password field, enter an **incorrect password**.  
5. Click the **"Sign In"** button.  
6. Repeat steps 3–5 **4–5 times** with the wrong password.  
7. Observe the error message displayed below or above the login form.

---

**Expected Result:**  
- A **clear, user-friendly error message** should be displayed, such as:  
  > "The email or password you entered is incorrect. Please try again or contact Customer Support."  
- Any **link to Customer Support** should be **clickable**, visually clear, and properly formatted.  
- The message should **not** contain raw HTML tags or technical text that a non-technical user cannot understand.  
- The layout of the error message should align correctly with the rest of the form.

---

**Actual Result:**  
- The error message contains **raw HTML / code fragments**, which are visible to the user.  
- The **Customer Support link appears as plain text** inside the message and is **not clickable**.  
- The Hebrew sentence is **broken in the middle by the raw link text**, making the message hard to read and confusing, especially for non-technical users.  
- Overall, the error message looks **unprofessional and unclear**, and does not properly guide the user on how to proceed.

---

**Reproducibility:**  
- 100% – the issue occurs on every attempt when entering an incorrect password multiple times.

---

**Impact:**  
- Users who mistype their password may be unable to understand what went wrong or how to get help.  
- Non-technical users are likely to be confused by the visible HTML/code.  
- This reduces trust in the website’s professionalism and can block successful login for some users.

---

### Attachments

🖼 Screenshot:  
[login-error.png](../screenshots/login-error/login-error.png)




---

**Notes:**  
- The issue appears on the Hebrew version of the site.  
- It is recommended to check if the same behavior exists in the English version as well.
