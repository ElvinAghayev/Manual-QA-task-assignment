# Manual QA Portfolio - Elvin Aghayev

This repository showcases my manual testing skills, including test case design, boundary value analysis, and bug reporting for web applications.

## 🛠️ Environment & Tools
- **Browser:** Google Chrome v.130
- **Operating System:** Windows 10
- **Testing Type:** Manual Functional Testing, UI/UX Testing, Security Testing

---

## 📂 Project Tasks

### 1. Login Page Validation
Testing a login system with specific rules (mandatory fields, email format, minimum password length).
- **Test Cases:** 10 (5 Positive / 5 Negative)
- **Key Result:** Identified a critical bug where the system fails to redirect the user to the dashboard after a successful login.

### 2. Contact Form Validation
Testing a contact form using **Boundary Value Analysis (BVA)** for the message field (10-200 characters).
- **Test Cases:** 9
- **Key Result:** Found a major bug where the form rejects exactly 200 characters despite the requirement.

### 3. Password Reset Flow
Testing the end-to-end "Forgot Password" process and security feedback.
- **Test Cases:** 7
- **Key Result:** Discovered a security information disclosure flaw where the system confirms email existence for non-registered users.

---

## 📊 Summary Table
| Task | Total Test Cases | Bugs Found |
| :--- | :---: | :---: |
| Login Page | 10 | 3 |
| Contact Form | 9 | 3 |
| Password Reset | 7 | 3 |
| **Total** | **26** | **9** |

---

## 🐞 Sample Bug Reports

### [BUG-001] Redirection Failure
- **Severity:** Critical
- **Actual Result:** User stays on the login page after entering valid credentials.
- **Expected Result:** User should be redirected to the Dashboard.

### [BUG-002] Message Field Boundary Error
- **Severity:** Major
- **Actual Result:** Error message appears when entering exactly 200 characters.
- **Expected Result:** The system should accept up to 200 characters.

---
*For a detailed view of all test cases and results, please check the [TaskAssignmentReport.pdf](./TaskAssignmentReport.pdf) file in this repository.*
