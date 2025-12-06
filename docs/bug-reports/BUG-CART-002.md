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
- Language: Hebrew / English  
- URL: https://il.iherb.com  

---

**Preconditions:**  
1. User is logged in  
2. Cart is empty  

---

**Steps to Reproduce:**  
1. Search for any product  
2. Add products to the cart one by one  
3. Continue adding items until exceeding 15  
4. Open the cart  
5. Attempt to proceed to checkout  

---

**Expected Result:**  
- The system should prevent adding more than 15 items  
**OR**  
- Display a clear warning message once the limit is reached  

---

**Actual Result:**  
- User can add up to **22 items** without any warning  
- Only at checkout the user receives an error  
- The limitation is not enforced during product addition  

---

**Impact / Risk:**  
- Users waste time adding items they cannot purchase  
- Causes checkout frustration  
- Reduces trust in the platform's reliability  

---

**Attachments:**  
👉 [cart-limit-issue.png](../screenshots/cart-limit/cart-limit-issue.png)  
👉 [cart-limit-02.png](../screenshots/cart-limit/cart-limit-02.png)
