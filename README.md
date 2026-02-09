# Manual QA Portfolio: Web Application Validation
[cite_start]**Tester:** Elvin Aghayev [cite: 25, 29]
[cite_start]**Environment:** Google Chrome v.130 on Windows 10 [cite: 27, 28]

## 📋 Overview
This project demonstrates end-to-end manual testing for core web functionalities. [cite_start]It covers requirement analysis, test case design (Positive/Negative), and bug reporting[cite: 2, 167].

### 🛠 Testing Methodologies Used
* [cite_start]**Equivalence Partitioning & Boundary Value Analysis (BVA):** Applied to password lengths and message fields to find edge-case failures[cite: 169].
* [cite_start]**Requirement-Driven Testing:** Every test case is mapped directly to project rules[cite: 168].
* [cite_start]**Security-Focused Testing:** Identifying information disclosure risks in reset flows[cite: 170].

---

## 📂 Project Tasks

### [cite_start]1. Login Page Validation [cite: 3]
[cite_start]Validated a login system requiring mandatory fields, specific email formats (@ and .), and a minimum 6-character password[cite: 5, 6].
* [cite_start]**Test Cases:** 10 total (5 Positive, 5 Negative)[cite: 172].
* [cite_start]**Key Bug Found:** User is not redirected to the Dashboard after valid login (Critical/Blocker).

### [cite_start]2. Contact Form Validation [cite: 11]
[cite_start]Tested a form with Name, Email, and Message fields, focusing on character limits (10-200 chars)[cite: 13, 14].
* [cite_start]**Test Cases:** 9 total[cite: 172].
* [cite_start]**Key Bug Found:** System throws an error at exactly 200 characters (Off-by-one error)[cite: 111, 115].

### [cite_start]3. Password Reset Flow [cite: 18]
[cite_start]Verified the UI and logic for "Forgot Password" requests and email link behavior[cite: 19, 20].
* [cite_start]**Test Cases:** 7 total[cite: 172].
* [cite_start]**Key Bug Found:** System shows a success message for non-existent emails (Security Information Disclosure)[cite: 149, 153].

---

## [cite_start]📊 Testing Statistics [cite: 172]
| Task | Total Cases | Positive | Negative | Bugs Found |
| :--- | :---: | :---: | :---: | :---: |
| Login Page | 10 | 5 | 5 | 3 |
| Contact Form | 9 | 4 | 5 | 3 |
| Password Reset | 7 | 2 | 5 | 3 |
| **TOTAL** | **26** | **11** | **15** | **9** |

---
## 🏁 Conclusion
[cite_start]The testing process identified several high-priority issues, specifically in navigation and security validation[cite: 166]. [cite_start]All identified bugs were documented with severity, priority, and clear reproduction steps[cite: 70, 106, 149].
