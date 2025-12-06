# 🐞 Bug Summary Report – iHerb Website Testing

This document provides a consolidated overview of all defects identified during manual testing of the iHerb Hebrew website (il.iherb.com).  
It includes severity classification, module impact, and screenshot references.

---

# 🔎 **Overview of All Detected Bugs**

A total of **6 bugs** were discovered:

| Bug ID | Module | Title | Severity | Status |
|--------|---------|--------|-----------|---------|
| **BUG-LOGIN-001** | Login | Error message displays HTML code | **Major** | ❌ Fail |
| **BUG-CART-002** | Cart | User can add >15 items before checkout | **Critical** | ❌ Fail |
| **BUG-SEARCH-003** | Search | Irrelevant results for Hebrew & English nutrition keywords | **Medium** | ❌ Fail |
| **BUG-MOBILE-004** | Mobile UI | Broken Safari layout; overlapping elements | **Major** | ❌ Fail |
| **BUG-AZ-005** | Localization | A–Z brand menu stays in English on Hebrew page | **Minor** | ❌ Fail |
| **BUG-PHONE-006** | User Profile | Incorrect phone number formatting | **Low** | ❌ Fail |

---

# 📊 **Bug Distribution by Severity**

| Severity | Count |
|----------|--------|
| **Critical** | 1 |
| **Major** | 2 |
| **Medium** | 1 |
| **Minor** | 1 |
| **Low** | 1 |

➡️ Most issues impact core functionality, localization, and UI clarity.

---

# 📁 **Bug Categories**

| Category | Description | Count |
|----------|-------------|--------|
| **Functional** | Errors in system behavior (cart limit, login handling) | 3 |
| **Localization** | Hebrew/English mismatch, untranslated labels | 2 |
| **UI / Layout** | Broken or unreadable UI (Safari mobile) | 1 |

---

# 🧭 **Key Observations**

- The search engine returns irrelevant or unrelated results for nutrition-related queries in both languages.  
- Mobile Safari layout is severely broken and harms usability.  
- Cart validation only appears at checkout instead of preventing excess items earlier.  
- Localization is incomplete, especially in A–Z brand lists.  
- Error messages expose HTML code, reducing professionalism.  
- Phone number formatting suffers from RTL/LTR mixing.

---

# 🖼️ **Screenshot Directories**

| Bug ID | Screenshot Folder |
|--------|--------------------|
| BUG-LOGIN-001 | `docs/screenshots/login-error/` |
| BUG-CART-002 | `docs/screenshots/cart-limit/` |
| BUG-SEARCH-003 | `docs/screenshots/search-issue/` |
| BUG-MOBILE-004 | `docs/screenshots/mobile-ui/` |
| BUG-AZ-005 | `docs/screenshots/az-brands/` |
| BUG-PHONE-006 | `docs/screenshots/phone-format/` |

---

# 📌 **Recommendations**

1. Improve search relevancy for Hebrew & English nutrition keywords.  
2. Add real-time validation blocking >15 cart items before checkout.  
3. Rewrite mobile UI responsiveness for Safari.  
4. Fully localize A–Z brand list in Hebrew.  
5. Sanitize all error messages to avoid HTML output.  
6. Fix RTL-safe phone number formatting.

---

# ✔️ **Conclusion**

The iHerb Hebrew website contains multiple functionality and localization issues that impact usability.  
Addressing these defects will significantly improve user experience and overall reliability.
