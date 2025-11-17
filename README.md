# 🧪 iHerb Website – Manual QA Testing Project

![Status](https://img.shields.io/badge/Project%20Status-Completed-brightgreen)  
![Tests](https://img.shields.io/badge/Test%20Cases-Completed-blue)  
![Bugs](https://img.shields.io/badge/Bugs%20Found-6-red)

This repository contains a complete manual QA testing project performed on the **iHerb (il.iherb.com)** website.  
It includes test cases, bug reports, screenshots, a bug summary, and a test summary — all documented and organized professionally.

---

# 📌 Project Overview

The objective of this project was to test the Hebrew version of the iHerb website and identify issues related to:

- Functional behavior  
- Localization (Hebrew/English)  
- UI/UX  
- Mobile responsiveness  
- Input validation  
- Search engine behavior  

Testing was performed manually on desktop and mobile devices.

---

# 🗂️ Repository Structure

```
iherb-testing-project/
│
├── docs/
│   ├── bug-reports/        # Detailed bug reports
│   ├── test-cases/         # All written test cases
│   ├── screenshots/        # Organized screenshots (per bug)
│   ├── bug-summary.md      # High-level summary of all bugs
│   └── test-summary.md     # Summary of executed tests
│
└── README.md               # Project overview
```

---

# 🧩 What Was Tested?

### ✔ Functional Testing  
- Login  
- Cart behavior  
- Search engine  
- Error handling  
- Checkout flow  

### ✔ Localization Testing  
- Translated UI text  
- RTL vs LTR  
- Brand list translation  

### ✔ UI/UX Testing  
- Layout  
- Spacing  
- Visibility  
- Alignment and responsiveness  

### ✔ Mobile Testing (Safari on iPhone)  
- Mobile layout  
- Overlapping elements  
- Correct rendering of Hebrew  

---

# 🐞 Bugs Summary

A total of **6 bugs** were identified:

| Bug ID | Module | Severity | Status |
|--------|---------|-----------|---------|
| BUG-LOGIN-001 | Login | Major | Fail |
| BUG-CART-002 | Cart | Critical | Fail |
| BUG-SEARCH-003 | Search | Medium | Fail |
| BUG-MOBILE-004 | Mobile UI | Major | Fail |
| BUG-AZ-005 | Localization | Minor | Fail |
| BUG-PHONE-006 | Phone Format | Low | Fail |

👉 **Full bug details:**  
[📄 Bug Summary](docs/bug-summary.md)

👉 **Screenshots folder:**  
[📸 View Screenshots](docs/screenshots)

---

# 📑 Test Cases

All test cases, including login, cart behavior, search testing, localization, and UI tests:

👉 [`/docs/test-cases`](docs/test-cases)

---

# 🧪 Test Summary

A summary of all executed tests, including pass/fail status, severity breakdown, and observations:

👉 [📄 Test Summary](docs/test-summary.md)

---

# 📷 Screenshots

Screenshots are organized per bug:

```
docs/screenshots/
   ├── login-error/
   ├── cart-limit/
   ├── search-issue/
   ├── mobile-ui/
   ├── az-brands/
   └── phone-format/
```

Each bug report links directly to the relevant screenshot folder.

---

# 🚀 Tools Used

- Manual exploratory testing  
- Chrome / Firefox / Safari  
- iPhone (Mobile Safari)  
- GitHub for documentation  
- Markdown for structured reporting  

---

# ✔ Conclusion

This project demonstrates strong knowledge in:

- Functional testing  
- Localization issues  
- Bug reporting  
- Writing detailed test cases  
- Documenting defects professionally  
- Managing a clean QA project on GitHub  

Multiple issues were found in search behavior, mobile UI rendering, and Hebrew localization — highlighting critical user-facing defects.

---

# 🙌 Author

**Eden Cohen**  
Manual QA Tester  
Web Testing · Bug Reporting · GitHub Documentation

