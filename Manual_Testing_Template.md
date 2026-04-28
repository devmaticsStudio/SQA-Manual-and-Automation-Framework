# Devmatics Studio - Manual Testing Template
**Project:** E-Commerce User Authentication  
**Author:** SQA Team @DevmaticsStudio  
**Standard:** ISTQB Guidelines

## 1. Introduction
This document outlines the manual test cases for verifying the Login and Registration functionality of a standard web application.

## 2. Test Case Table

| Test Case ID | Test Scenario | Steps to Reproduce | Expected Result | Priority |
| :--- | :--- | :--- | :--- | :--- |
| **TC-001** | Valid Login | 1. Enter registered email <br> 2. Enter correct password <br> 3. Click Login | User should be redirected to the Dashboard. | High |
| **TC-002** | Invalid Password | 1. Enter registered email <br> 2. Enter WRONG password <br> 3. Click Login | System should show "Invalid Credentials" error. | High |
| **TC-003** | Empty Fields | 1. Leave email/password blank <br> 2. Click Login | System should prompt "Field is required". | Medium |
| **TC-004** | Forgot Password | 1. Click 'Forgot Password' <br> 2. Enter registered email | A reset link should be sent to the user's email. | Medium |

## 3. Bug Reporting Format
If any test case fails, we follow this structure for reporting:
- **ID:** BUG-001
- **Severity:** Critical / Major / Minor
- **Environment:** Chrome v120 / Windows 11
- **Steps:** (Detailed steps to reproduce)
- **Status:** Open / Fixed / Retest
