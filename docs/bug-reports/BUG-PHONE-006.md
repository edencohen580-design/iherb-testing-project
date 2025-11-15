**Bug ID:** BUG-ACCOUNT-004

**Module:** Account / User Profile

**Title:** Phone number displayed with incorrect formatting in account header

**Severity:** Low

**Status:** Fail

**Environment:**
1) Website: iHerb (il.iherb.com)
2) Browsers: Chrome / Safari / Firefox
3) Languages: Hebrew / English

**Preconditions:**
1) User has an active account with a saved phone number.
2) User is logged into the website.

**Steps to Reproduce:**
1) Log in to the iHerb website.
2) Click on “My Account” from the top navigation bar.
3) Observe the phone number displayed in the account section.
4) Edit the profile name (optional).
5) Save changes and re-check phone number formatting.

**Expected Result:**
1) Phone number should display in a clean and consistent format:
   - +972-50-712-5465
   - or 050-712-5465
2) No extra characters, broken symbols, or incorrect spacing.
3) Proper RTL/LTR alignment.

**Actual Result:**
1) Phone number includes extra characters (e.g., “!”).
2) Formatting is inconsistent and misaligned.
3) Country code and number appear in mixed RTL/LTR order.
4) Formatting sometimes changes after editing account info.

**Attachments:**
1) Screenshot: phone-format-issue.png

