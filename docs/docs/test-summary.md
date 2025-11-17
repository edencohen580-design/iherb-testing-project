# **🧪 Test Summary Report – iHerb Website (Manual Testing)**

## **1. Overview**
This Test Summary Report provides a high-level overview of all test activities performed on the iHerb website (il.iherb.com).  
The purpose of this testing cycle was to identify functional, UI, localization, and responsiveness issues across desktop and mobile environments.

Testing focused on *Bug-Oriented Testing*, meaning the primary goal was to discover defects rather than validate fully-working areas.

---

## **2. Test Execution Status**

| Status | Count |
|--------|--------|
| **Passed** | 0 |
| **Failed** | 5 |
| **Blocked** | 0 |
| **Not Executed** | 0 |
| **Total Test Cases** | **5** |

---

## **3. Summary of Test Cases**

Below is a summary of all the test cases executed during this cycle:

| Test Case ID | Module | Title | Result |
|--------------|---------|--------|---------|
| **TC-LOGIN-001** | Login | Error message shows broken HTML | ❌ Fail |
| **TC-CART-002** | Cart | Adding more items than allowed limit | ❌ Fail |
| **TC-SEARCH-003** | Search | Irrelevant results in Hebrew/English | ❌ Fail |
| **TC-MOBILE-004** | Mobile UI | Safari mobile layout issues | ❌ Fail |
| **TC-AZ-005** | Localization | A–Z brands list in English on Hebrew mode | ❌ Fail |

---

## **4. Severity Distribution of Failed Tests**

| Severity | Count |
|----------|--------|
| **Critical** | 1 |
| **Major** | 2 |
| **Medium** | 1 |
| **Minor** | 1 |

---

## **5. Key Findings**

- The **Checkout Flow** is impacted by a major defect (cart allows more than 15 items).
- **Login UI behavior** displays raw HTML, reducing reliability and user trust.
- **Search Engine Relevancy** is weak in both Hebrew and English, indicating NLP issues.
- **Mobile Safari** layout is broken and requires responsive design fixes.
- **Localization** lacks completeness — brand list remains in English even in Hebrew mode.
- **Phone number formatting** shows RTL/LTR alignment issues.

---

## **6. Positive Observations (Outside Project Scope)**
Although not part of the official test cases, several basic flows were found working correctly:

- PayPal redirect opens successfully and securely.
- Invalid credit card entry does not proceed to billing (validation working).
- Basic navigation across categories is functional.

These tests were not included in the formal Test Cases section but support the conclusion that some core flows do operate correctly.

---

## **7. Test Environment**

- **Devices tested:** Desktop (Windows), Mobile (iPhone)
- **Browsers:** Chrome, Firefox, Safari Mobile
- **Languages:** Hebrew, English

---

## **8. Conclusion**
The system has multiple defects that impact usability, localization, and checkout functionality.  
Given the number of failed test cases (5/5), the website is **not ready for release** without addressing the identified issues.

However, basic critical paths (such as PayPal redirect and invalid credit card validation) were functional.

---

## **9. Related Documentation**

- **📄 Bug Reports:** `/docs/bug-reports/`
- **📄 Test Cases:** `/docs/test-cases/`
- **📷 Screenshots:** `/docs/screenshots/`
- **🐞 Bug Summary:** `/docs/bug-summary.md`

