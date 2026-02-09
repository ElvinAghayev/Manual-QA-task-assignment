# Task 1 – Login Page Validation – Test Cases

## Application Under Test
Login Page

## Rules
1. Both fields are mandatory.
2. Email must contain '@' and '.' characters.
3. Password must contain at least 6 characters.
4. Successful login redirects the user to the Dashboard page.
5. Invalid credentials display the error message 'Incorrect email or password.'

---

## TC-LGN-P-001: Successful Login with Valid Credentials
Category: Positive

Preconditions:
A registered user account exists with valid credentials.

Steps:
1. Navigate to the Login Page.
2. Enter a valid Email containing '@' and '.'.
3. Enter a Password with at least 6 characters.
4. Click the 'Login' button.

Expected Result:
The user is successfully redirected to the Dashboard page.

Status: To Be Run

---

## TC-LGN-P-002: 'Forgot Password?' Link Functionality
Category: Positive

Preconditions:
Login page is loaded and the 'Forgot Password?' link is visible.

Steps:
1. Navigate to the Login Page.
2. Click the 'Forgot Password?' link.

Expected Result:
The user is redirected to the Forgot Password page.

Status: To Be Run

---

## TC-LGN-P-003: Password Minimum Boundary Check (6 Characters)
Category: Positive

Preconditions:
A registered user account exists.

Steps:
1. Navigate to the Login Page.
2. Enter a valid Email.
3. Enter a Password with exactly 6 characters.
4. Click the 'Login' button.

Expected Result:
The user is redirected to the Dashboard page.

Status: To Be Run

---

## TC-LGN-N-006: Missing Mandatory Email Field
Category: Negative

Preconditions:
Login page is loaded.

Steps:
1. Navigate to the Login Page.
2. Leave the Email field empty.
3. Enter a valid Password.
4. Click the 'Login' button.

Expected Result:
An inline validation error message is displayed for the Email field.

Status: To Be Run

---

## TC-LGN-N-010: Invalid Credentials (Incorrect Password)
Category: Negative

Preconditions:
A registered user account exists.

Steps:
1. Navigate to the Login Page.
2. Enter a registered Email.
3. Enter an incorrect Password.
4. Click the 'Login' button.

Expected Result:
The error message 'Incorrect email or password.' is displayed.

Status: To Be Run
