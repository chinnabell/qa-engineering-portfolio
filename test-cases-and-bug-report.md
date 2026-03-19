# QA Test Cases & Bug Report

## Feature: Login Functionality

| Test ID | Scenario | Steps | Expected Result |
|---------|----------|-------|-----------------|
| TC001  | Valid login | Enter valid credentials | User logs in successfully |
| TC002  | Invalid password | Enter wrong password | Error message displayed |
| TC003  | Invalid username | Enter wrong username | Error message displayed |

---

## Bug Report

**Title:** Login succeeds with invalid password

**Severity:** High

**Reproduction Steps:**
1. Navigate to login page
2. Enter valid username
3. Enter invalid password
4. Click login

**Expected Result:**
User should see error message.

**Actual Result:**
User is logged in successfully.
