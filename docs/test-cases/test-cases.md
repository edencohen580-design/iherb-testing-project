**Test Case ID:** TC-LOGIN-001


**Module:** Login

**Title:** Login attempt with incorrect password

**Type:** Functional

**Preconditions:**

1)A registered user account exists.

2)User has access to the iHerb website.

3)Browser: Chrome / Safari / Firefox.

4) Website language is set to Hebrew.

**Test Steps:**

1)Navigate to the iHerb website.

2)Click on “My Account” in the top navigation bar.

3)Enter a valid registered email address.

4)Enter an incorrect password and repeat the attempt 4–5 times.

5)Click the “Sign In” button.

**Expected Result:**

*The system displays a clear and readable error message.*

*The user is not logged in.*

*Input fields remain active for another login attempt.*

*The error message does not contain broken HTML, code fragments, or unclickable links.*

**Actual Result:**

The error message contains raw HTML code.

The customer service link appears as plain text and is not clickable.

Status: Fail
Severity: Major
------------------------------------------------------------------------
**Test Case ID:** TC-CART-002
**Module:** Cart / Adding Items
**Title:** Adding more items to the cart than the allowed limit
**Type:** Functional

**Preconditions:**

1)User is logged in to the website.

2)User can search and add products to the cart.

4)Browser: Chrome / Safari / Firefox.

5)Language: Hebrew or English.

**Test Steps:**

1)Log in to the user account.

2)Search for products on the iHerb website.

3)Add multiple products to the cart.

4)Continue adding items until the cart contains more than 15 products (e.g., 16–22 items).

5)Navigate to the cart.

5)Click “Proceed to Checkout”.

6)Observe the system response.

**Expected Result:**

The system should prevent adding more items once the allowed limit (15 items) is reached,
or display a clear warning message when attempting to exceed the limit.

**Actual Result:**

The website allows adding more than 15 items (up to 22 items) without any warning.

The limit is shown only after entering the cart / checkout screen, preventing completion of the purchase.

Stat1us: Fail
Severity: Critical
--------------------------------------------------------------------------
**Test Case ID:** TC-SEARCH-003
**Module:** Search
**Title:** Search for products using Hebrew and English nutrition-related keywords
**Type:** Functional + Localization

**Preconditions:**

1)User is logged into the website.

2)User can access the search bar.

3)Browser: Chrome / Safari / Firefox.

4)Languages available: Hebrew and English.

**Steps to Reproduce:**

1)Navigate to the iHerb homepage.

2)Set the website language to Hebrew.

3)Enter “כדורים לתזונה” in the search bar and press Enter.

4)Observe the products displayed.

5)Switch the website language to English.

5)Enter “nutrition pill” in the search bar and press Enter.

6)Observe the products displayed.

7)Compare whether the results are relevant to dietary supplement products.

**Expected Result:**

The search engine returns relevant dietary supplement products for both search terms
(“כדורים לתזונה” in Hebrew and “nutrition pill” in English).

Results are consistent and match the user’s intent.

Displayed products include nutrition-related pills such as vitamins, minerals, supplements, capsules, probiotics, etc.

Language selection (Hebrew / English) does not affect the relevancy of search results.

The search system correctly prioritizes the “nutrition” aspect of the query over unrelated keywords.

**Actual Result:**

Hebrew search (“כדורים לתזונה”) returns unrelated food products such as baking mixes, coffee substitutes, chocolate mixes, and other non-pill items.

English search (“nutrition pill”) returns pill organizers, pill splitters, and other pill-related accessories instead of nutritional pills.

No relevant dietary supplement pills appear in the top search results for either language.

Search relevancy is inconsistent and does not match the user intent.

This indicates a failure in the search engine’s natural language processing (NLP) and localization handling.

The search engine does not prioritize nutrition-related items and misinterprets the keywords.

Status: Fail
Severity: Medium
---------------------------------------------------------------------------
**Test Case ID:** TC-UI-001
**Module:** Responsive Layout (Mobile Safari)
**Title:** Verify homepage layout on Safari mobile browser
**Type:** Functional + UI + Cross-Browser (Safari)

**Preconditions:**

1)Tester has access to an iPhone device.

2)Safari browser is installed on the device.

3)“Request Desktop Website” option is disabled.

4)Stable internet connection is available.

5)iHerb website is accessible in both Hebrew and English.

6)User may be logged out or logged in (not mandatory).

**Steps to Reproduce:**

1)Unlock the iPhone device and open the Safari browser.

2)Ensure that “Request Desktop Website” is turned off
(Settings → Safari → Request Desktop Website → Off).

3)Navigate to the iHerb homepage: https://il.iherb.com.

4)Allow the page to fully load.

5)Scroll through the homepage and observe the layout.

7)Open any category or product page.

8)Observe the page structure, text alignment, menus, and overall responsiveness.

9)Compare the screen with the expected mobile layout (clean mobile view, not overlapping elements).

**Expected Result:**

The website should display a clean, responsive mobile layout.

Banners, product cards, and buttons should be properly aligned and not overlap.

Text and UI elements should fit within the screen without being compressed or stacked incorrectly.

**Actual Result:**

When opening the website in Safari on mobile, banners (“stickers”) and other elements appear compressed and overlapping.

The overall site presentation looks crowded and stacked on top of each other.

Status: Fail
Severity: Major
-------------------------------------------------------------------------
**Test Case ID:** TC-UI-002
**Module:** Navigation / Brands A–Z
**Title:** Brand list A–Z displayed in English while site language is Hebrew
**Type:** Functional + Localization

**Preconditions:**

1)User navigates to the iHerb website (can be a guest, login is not required).

2)Website language is set to Hebrew.

3)Top navigation bar is visible.

**Steps to Reproduce:**

1)Search for “iHerb” in Google and open the first result (official website)

2)Make sure the site language is set to Hebrew.

3)In the top navigation bar, hover over or click the “A–Z” brands option.

4)Observe the list of brands displayed in the dropdown.

**Expected Result:**

On a Hebrew version of the website, the user expects the navigation elements to be localized.

Brand names should be displayed in a user-friendly way for Hebrew speakers (e.g., translated or at least partially localized),
or there should be a clear indication that the list is in English.

**Actual Result:**

The toolbar and other navigation items are in Hebrew,
but all brand names in the A–Z list are displayed only in English.

Status: Fail
Severity: Minor
--------------------------------------------------------------------------
**Test Case ID:** TC-ACCOUNT-004
**Module:** Account / User Profile
**Title:** Verify correct phone number formatting in the account header
**Type:** UI / Localization / Formatting

**Preconditions:**

1)User has an active account with a valid phone number saved.

2)User is logged into the iHerb website.

3)Browser: Chrome / Safari / Firefox.

4)Website language: Hebrew or English.

**Steps to Reproduce:**

1)Navigate to the iHerb homepage while logged in.

2)Open the “My Account” page from the top navigation bar.

3)Observe the displayed phone number in the account information section or header.

4)(Optional) Edit the user’s name or profile information and save the changes.

5)Return to the account page and observe whether the phone number formatting changes.

**Expected Result:**

The phone number is displayed in a clean, consistent, and standard format, such as:

+972-50-712-5465, or

050-712-5465

No extra symbols, broken characters, spacing issues, or RTL/LTR misalignment appear.

Formatting remains consistent even after updating profile information.

**Actual Result:**

The phone number is displayed incorrectly, including:

Extra symbols (such as !).

Incorrect spacing.

Mixed RTL/LTR rendering.

Disorganized country code (+972) and local number.

After editing profile details, the formatting sometimes changes unexpectedly.

Status: Fail
Severity: Low
