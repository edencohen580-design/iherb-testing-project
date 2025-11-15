**Bug ID:** BUG-LOGIN-001

**Module:** Login

**Title:** Error message contains HTML code after repeated incorrect password attempts

**Severity:** Major

**Status:** Fail

**Environment:**
1) Website: iHerb (il.iherb.com)
2) Browsers: Chrome / Safari / Firefox
3) Language: Hebrew

**Preconditions:**
1) A registered user account exists.
2) User can access the login page.
3) Stable internet connection.

**Steps to Reproduce:**
1) Navigate to the iHerb website.
2) Click on “My Account” in the top navigation bar.
3) Enter a valid registered email address.
4) Enter an incorrect password.
5) Click the “Sign In” button.
6) Repeat steps 4–5 four to five times.

**Expected Result:**
1) A clean, readable error message is displayed.
2) The message should not contain any HTML code.
3) The customer service link should be clickable and properly formatted.

**Actual Result:**
1) Error message displays HTML fragments (such as `href=` code).
2) Customer service link appears as plain text and is not clickable.
3) Message appears broken and confusing for non-technical users.

**Attachments:**
1) Screenshot: login-error-message.png
