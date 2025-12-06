**Bug ID:** BUG-CART-002  
**Title:** Cart allows adding more than 15 items without proper warning  
**Module:** Cart / Checkout  
**Severity:** Critical  
**Priority:** High  
**Status:** Fail  

---

**Environment:**  
- OS: Windows 11  
- Browser: Chrome  
- URL: https://il.iherb.com  

---

**Preconditions:**  
1. User is logged in  
2. Cart is initially empty  

---

**Steps to Reproduce:**  
1. Search for any product  
2. Add products to the cart  
3. Continue adding beyond 15 items  
4. Navigate to the cart  
5. Click **“Proceed to Checkout”**  

---

**Expected Result:**  
- System should prevent adding more items OR show immediate warning  

---

**Actual Result:**  
- User can add up to 22 items without warning  
- Only during checkout the system blocks the order  

---

**Impact:**  
- High frustration  
- Checkout failure at late stage  

---

**Attachments:**  
👉 [cart-limit-issue.png](../screenshots/cart-limit/cart-limit-issue.png)  
👉 [cart-limit-02.png](../screenshots/cart-limit/cart-limit-02.png)
