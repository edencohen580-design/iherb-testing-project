**Bug ID:** BUG-SEARCH-003  
**Title:** Search returns irrelevant results in Hebrew and English queries  
**Module:** Search Engine  
**Severity:** Medium  
**Priority:** Medium  
**Status:** Fail  

---

**Environment:**  
- OS: Windows 11  
- Browser: Chrome  
- Language: Hebrew & English  
- URL: https://il.iherb.com  

---

**Preconditions:**  
1. User can access the search bar  
2. Website is functional in Hebrew and English  

---

**Steps to Reproduce:**  
1. Set the website language to **Hebrew**  
2. Enter the search term **“כדורים לתזונה”**  
3. Observe the results  
4. Switch the website language to **English**  
5. Enter the search term **“nutrition pill”**  
6. Compare both sets of results  

---

**Expected Result:**  
- The search engine should display relevant dietary supplement products  
- Keywords should match user intent (vitamins, capsules, probiotics, etc.)  
- Results should be consistent between languages  

---

**Actual Result:**  
- Hebrew search displays unrelated food items (baking mixes, powders, etc.)  
- English search displays pill organizers and accessories instead of supplements  
- No relevant nutrition-related products appear in top results  

---

**Impact / Risk:**  
- Users cannot find the products they need  
- Reduces confidence in the search system  
- Causes friction in product discovery  

---

**Attachments:**  
👉 [search-issue-hebrew.png](../screenshots/search-issue/search-issue-hebrew.png)  
👉 [search-issue-english.png](../screenshots/search-issue/search-issue-english.png)
