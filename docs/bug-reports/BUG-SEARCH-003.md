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
- URL: https://il.iherb.com  
- Languages tested: Hebrew, English  

---

**Preconditions:**  
1. User can access the iHerb homepage  
2. Search bar is functional  

---

**Steps to Reproduce:**  
1. Set the website language to **Hebrew**  
2. Enter the query **“כדורים לתזונה”**  
3. Press Enter and observe the search results  
4. Switch the website language to **English**  
5. Enter the query **“nutrition pill”**  
6. Press Enter and compare the search results  

---

**Expected Result:**  
- Both Hebrew and English queries should return relevant dietary supplement products  
- Results should include pills, capsules, vitamins, probiotics, or supplement-related items  
- Search engine should correctly interpret user intent  

---

**Actual Result:**  
- Hebrew search returns unrelated items, such as baking mixes, powders, or coffee substitutes  
- English search shows pill organizers instead of supplements  
- No nutrition-related pills appear in top search results  

---

**Impact / Risk:**  
- Users cannot find relevant products  
- Search engine appears unreliable  
- Possible loss of sales due to poor search accuracy  

---

**Attachments:**  
👉 [search-issue-hebrew.png](../screenshots/search-issue/search-issue-hebrew.png)  
👉 [search-issue-english.png](../screenshots/search-issue/search-issue-english.png)
