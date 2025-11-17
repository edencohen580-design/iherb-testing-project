# 🧪 iHerb Website – Manual QA Testing Project

This repository contains a full manual QA testing project performed on the **iHerb (il.iherb.com)** website.  
The project includes test cases, bug reports, screenshots, a bug summary, and a test summary — all organized in a clear and professional structure.

---

# 📌 **Project Overview**

The purpose of this testing project was to examine the Hebrew version of the iHerb website and identify issues related to:

- Functional behavior  
- Localization (Hebrew/English)  
- UI/UX  
- Mobile responsiveness  
- Input validation  
- Search engine behavior  

Testing was performed manually on both desktop and mobile devices.

---

# 🗂️ **Repository Structure**

```
iherb-testing-project/
│
├── docs/
│   ├── bug-reports/          # Detailed bug reports
│   ├── test-cases/           # All written test cases
│   ├── screenshots/          # Screenshots for each bug
│   ├── bug-summary.md        # Summary of all discovered bugs
│   └── test-summary.md       # Summary of test execution results
│
└── README.md                 # Project overview (this file)
```

---

# 🧩 **What Was Tested?**

The following areas were covered during testing:

### ✔ Functional Testing
- Login behavior  
- Cart limits  
- Search functionality  
- Checkout behavior  
- Error messages  

### ✔ Localization Testing
- Hebrew/English UI elements  
- Brand list translation  
- Keyboard direction (RTL/LTR)  

### ✔ UI/UX Testing
- Layout  
- Spacing  
- Formatting  
- Visual consistency  

### ✔ Mobile Testing (Safari on iPhone)
- Responsive layout  
- Element positioning  
- Overlapping components  

---

# 🐞 **Summary of Bugs Found**

A total of **6 bugs** were identified:

| Bug ID | Module | Severity | Status |
|--------|---------|-----------|---------|
| BUG-LOGIN-001 | Login | Major | Fail |
| BUG-CART-002 | Cart | Critical | Fail |
| BUG-SEARCH-003 | Search | Medium | Fail |
| BUG-MOBILE-004 | Mobile UI | Major | Fail |
| BUG-AZ-005 | Localization | Minor | Fail |
| BUG-PHONE-006 | Profile | Low | Fail |

📝 **Full details:**  
👉 [Bug Summary](docs/docs/bug-summary.md)

📂 **Screenshots available at**   **Screenshots folder:**  
👉 [📸 Open Screenshots](docs/screenshots)


---

# 📑 **Test Cases**

All relevant test cases, including login, search, cart behavior, UI testing, and localization, are located here:

👉 [`/docs/test-cases/`](docs/test-cases/)

---

# 🧪 **Test Summary**

All test execution results, including passed/failed statistics and severity breakdown:

👉[Test Summary](docs/docs/test-summary.md)

---

# 📷 **Screenshots**

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

Each folder contains the images referenced in the bug reports.

---

# 🚀 **Tools Used**

- Manual exploratory testing  
- Chrome / Firefox / Safari Mobile  
- Windows Desktop + iPhone (iOS Safari)  
- GitHub for documentation & version control  
- Markdown for professional reporting  

---

# ✔ **Conclusion**

This project demonstrates hands-on experience in:
- Writing structured test cases  
- Performing functional and localization testing  
- Identifying defects  
- Documenting bugs professionally  
- Maintaining a clean GitHub testing repository  

The testing revealed multiple usability and functional issues, especially in search behavior, mobile UI responsiveness, and localization accuracy.

---

# 🙌 **Author**

**Eden Cohen**  
Manual QA | Web Testing | Bug Reporting | GitHub Documentation  

