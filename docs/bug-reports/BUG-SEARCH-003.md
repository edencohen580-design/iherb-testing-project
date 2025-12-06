**Bug ID:** BUG-SEARCH-003  
**Title:** Nutrition-related search terms return irrelevant products  
**Module:** Search Engine  
**Severity:** Medium  
**Priority:** Medium  
**Status:** Fail   

---

**Environment:**  
- OS: Windows 11  
- Browser: Chrome  
- Language: Hebrew & English  

---

**Preconditions:**  
1. User can access iHerb  
2. Search bar is functional  

---

**Steps to Reproduce:**  
1. Set the site to Hebrew  
2. Search for “כדורים לתזונה”  
3. Observe results  
4. Switch site to English  
5. Search for “nutrition pill”  
6. Compare results  

---

**Expected Result:**  
- Results should include nutritional pills (vitamins, capsules, probiotics)  
- Hebrew/English search should return related items  
- NLP should interpret query meaning  

---

**Actual Result:**  
- Hebrew search shows baking mixes, powders, coffee substitutes  
- English search shows pill organizers instead of supplements  
- No nutrition pills are shown in top results  

---

**Impact / Risk:**  
- User cannot find requested products  
- Lower conversion rate  
- Search engine mistrust  

---

**Attachments:**  
- `docs/screenshots/search-issue/search-issue-hebrew.png`  
- `docs/screenshots/search-issue/search-issue-english.png`
