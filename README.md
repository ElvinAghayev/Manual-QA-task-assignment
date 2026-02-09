# Manual QA Portfolio - Elvin Aghayev

This repository showcases my ability to analyze business requirements, design comprehensive test cases, and report bugs for web applications.

## 🛠️ Project Environment
- **Browser:** Google Chrome v.130
- **OS:** Windows 10
- **Testing Techniques:** Boundary Value Analysis (BVA), Equivalence Partitioning, Functional Testing.

---

## 📂 Project Tasks & Requirements

### 1. Login Page Validation
**Business Rules (Requirements):**
- Both Email and Password fields are mandatory.
- Email must contain '@' and '.' characters.
- Password must be at least 6 characters long.
- Successful login must redirect the user to the Dashboard.
- Invalid credentials must trigger an error: "Incorrect email or password."

**Testing Outcome:**
- **Test Cases:** 10 (5 Positive / 5 Negative)
- **Critical Bug:** Found that the system fails to redirect to the Dashboard after valid login.

### 2. Contact Form Validation
**Business Rules (Requirements):**
- All fields (Name, Email, Message) are required.
- Email must follow a valid format.
- Message length must be between 10 and 200 characters.
- Success message: "Your message has been sent successfully."

**Testing Outcome:**
- **Test Cases:** 9 (Focusing on BVA)
- **Major Bug:** System rejects submissions with exactly 200 characters (Boundary Error).

### 3. Password Reset Flow
**Business Rules (Requirements):**
- System sends a reset link if the email exists in the database.
- Show "Email not found" for unregistered users.
- Show "This field is required" if the email field is empty.

**Testing Outcome:**
- **Test Cases:** 7
- **Security Flaw:** Information Disclosure — system confirms email existence for non-registered users.

---

## 📊 Testing Statistics
| Task | Total Cases | Positive | Negative | Bugs Found |
| :--- | :---: | :---: | :---: | :---: |
| Login Page | 10 | 5 | 5 | 3 |
| Contact Form | 9 | 4 | 5 | 3 |
| Password Reset | 7 | 2 | 5 | 3 |
| **TOTAL** | **26** | **11** | **15** | **9** |

---

## 🐞 Sample Bug Report

**Bug ID:** LGN-001  
**Title:** Redirection failure after successful login.  
**Severity:** Critical  
**Actual Result:** User remains on the login page after clicking 'Login' with valid credentials.  
**Expected Result:** User should be automatically redirected to the Dashboard page.

---

## 📂 Project Files
- [TaskAssignmentReport.pdf](./TaskAssignmentReport.pdf) - Full detailed report including all test cases and bug details.
