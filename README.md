# 🚀 SauceDemo E2E & QA Testing Suite

A professional QA portfolio project documenting End-to-End (E2E) test execution steps, edge cases, negative flows, and Jira board tracking for the [SauceDemo](https://www.saucedemo.com/) e-commerce web application.

---

## 📋 Test Suite & Case Directory

| Test ID | Category | Description / Scope |
| :--- | :--- | :--- |
| **TC-1** | Positive Purchase | Single-Item Purchase (`standard_user`) |
| **TC-2** | Positive Purchase | Multi-Item Purchase (3 items) |
| **TC-3** | Positive Purchase | Sorted Products Purchase (Price: Low to High) |
| **TC-4** | Positive Purchase | Remove Item from Cart & Complete Checkout |
| **TC-5** | Authentication | Locked-out User Login Attempt |
| **TC-6** | Authentication | Wrong Password Correction Flow |
| **TC-7** | Authentication | Empty Fields Login Validation |
| **TC-8** | Form Validation | Missing First Name Check |
| **TC-9** | Form Validation | Missing Last Name Check |
| **TC-10** | Form Validation | Missing Postal Code Check |
| **TC-11** | Form Validation | All Fields Empty Check |
| **TC-12** | Navigation | Cancel on Information Page & Resume |
| **TC-13** | Navigation | Cancel on Overview Page & Resume |
| **TC-14** | Account Variants | `performance_glitch_user` Full Purchase |
| **TC-15** | Account Variants | `problem_user` Full Purchase |
| **TC-16** | Account Variants | `error_user` Full Purchase Attempt |
| **TC-17** | Account Variants | `visual_user` Full Purchase |
| **TC-18** | Session Check | Full Purchase Followed by Logout & Termination |
| **TC-19** | Negative Case | SQL-Injection Login Attempt |
| **TC-20** | Edge Case | Browser Back Button After Completion |
| **TC-21** | Edge Case | Page Refresh Mid-Flow & Non-Numeric Postal Code |

---

## 🛠️ Tools Used
* **Target Application:** SauceDemo
* **Test Management:** Jira (Agile/Kanban Boards)
* **Documentation & Evidence:** Snpping Tool / Visual Test Logs
