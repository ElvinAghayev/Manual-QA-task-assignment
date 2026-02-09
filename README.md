Tester: Elvin Aghayev

Focus: Manual Testing, Test Case Design, Bug Reporting

🛠️ Project Environment
Browser: Google Chrome v.130

OS: Windows 10

Testing Techniques: Boundary Value Analysis (BVA), Equivalence Partitioning, Security Validation

📌 Project Overview
Task 1: Login Page Validation
Testing the login functionality including mandatory fields, email format validation (@ and .), and minimum password length (6 characters).

Total Test Cases: 10 (5 Positive / 5 Negative)

Primary Bug: Redirection failure after successful login (Critical).

Task 2: Contact Form Validation
Testing a contact form with Name, Email, and Message fields. Focused on message length constraints (10 to 200 characters).

Total Test Cases: 9 (Focusing on BVA)

Primary Bug: Off-by-one error where the system rejects exactly 200 characters.

Task 3: Password Reset Flow
Testing the end-to-end flow of password recovery, verifying email existence logic and UI feedback.

Total Test Cases: 7

Primary Bug: Security Flaw (Information Disclosure) - showing success for non-existent emails.
