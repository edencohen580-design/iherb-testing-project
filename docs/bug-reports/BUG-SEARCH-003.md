**Bug ID:** BUG-SEARCH-003

**Module:** Search

**Title:** Nutrition-related search terms return irrelevant products in Hebrew and English

**Severity:** Medium

**Status:** Fail

**Environment:**
1) Website: iHerb (il.iherb.com)
2) Browsers: Chrome / Safari / Firefox
3) Languages tested: Hebrew & English

**Preconditions:**
1) User is logged in (optional).
2) Search bar is visible and active.
3) Website fully loaded in both Hebrew and English modes.

**Steps to Reproduce:**
1) Navigate to the iHerb homepage.
2) Switch the website language to Hebrew.
3) Enter the term “כדורים לתזונה” in the search bar and press Enter.
4) Observe the search results.
5) Switch the website language to English.
6) Enter the term “nutrition pill” and press Enter.
7) Observe the search results again.
8) Compare both results to expected supplement-related products.

**Expected Result:**
1) Search should return nutrition-related pills such as:
   - vitamins
   - minerals
   - supplements
   - capsules
   - probiotics
2) Both Hebrew and English queries should return consistent and relevant results.
3) Search engine should interpret the user intent correctly.

**Actual Result:**
1) Hebrew search returns unrelated food products (baking mixes, chocolate drink mixes, etc.).
2) English search returns pill organizers and accessories instead of dietary supplements.
3) No relevant supplement pills appear in top results for both languages.
4) Search relevancy does not match user intent or query meaning.

**Attachments:**
1) Screenshot: search-nutrition-issue.png

