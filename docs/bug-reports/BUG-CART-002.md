**Bug ID:** BUG-CART-002

**Module:** Cart / Product Adding

**Title:** System allows adding more than 15 items to the cart without warning

**Severity:** Critical

**Status:** Fail

**Environment:**
1) Website: iHerb (il.iherb.com)
2) Browsers: Chrome / Safari / Firefox
3) Languages: Hebrew / English

**Preconditions:**
1) User is logged into an active account.
2) User can browse products normally.
3) User has at least 1 item available to add.
4) Cart limit stated as 15 products max.

**Steps to Reproduce:**
1) Log in to the iHerb website.
2) Search for multiple products.
3) Begin adding products to the cart.
4) Continue adding products until reaching 15 items.
5) Add additional products (16–22 items).
6) Navigate to the cart.
7) Click “Proceed to Checkout.”
8) Observe the system’s response.

**Expected Result:**
1) System should block adding more than 15 items.
2) A clear warning message should appear once the user reaches the limit.
3) Cart should not accept additional products beyond the maximum allowed.

**Actual Result:**
1) User can add more than 15 items (up to 22 tested).
2) No warning message appears during product addition.
3) Limit is shown only during checkout, preventing purchase unexpectedly.

**Attachments:**
1) Screenshot: cart-limit-issue.png

