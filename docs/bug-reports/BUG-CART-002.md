**Bug ID:** BUG-CART-002  
**Title:** Cart allows adding more than 15 items without warning  
**Module:** Cart / Checkout  
**Severity:** Critical  
**Priority:** High  
**Status:** Fail   

---

**Environment:**  
- OS: Windows 11  
- Browser: Chrome  
- Site: https://il.iherb.com  
- Language: Hebrew/English  

---

**Preconditions:**  
1. User is logged in  
2. Cart is empty  

---

**Steps to Reproduce:**  
1. Log in to the iHerb website  
2. Search for various products  
3. Add products to the cart until reaching 15  
4. Continue adding items (16–22 items)  
5. Open the cart  
6. Click "Proceed to Checkout"  

---

**Expected Result:**  
- System should prevent adding the 16th item  
- OR show a clear warning once the limit is reached  
- Limit should be enforced consistently  

---

**Actual Result:**  
- User can add more than 15 items with no warning  
- Only at checkout the system blocks the order  
- User discovers the issue too late  

---

**Impact / Risk:**  
- High frustration  
- Wasted user time  
- Direct checkout blockage  

---

**Attachments:**  
- `docs/screenshots/cart-limit/cart-limit-issue.png`  
- `docs/screenshots/cart-limit/cart-limit-02.png`
