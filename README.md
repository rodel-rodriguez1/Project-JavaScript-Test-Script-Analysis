# Project-JavaScript-Test-Script-Analysis
Project: JavaScript Test Script Analysis
Assignment Debugging Report
Overview

This project involved debugging and improving three JavaScript testing scripts. Each script originally contained logical errors, missing test cases, or inefficiencies. The goal was to identify issues, fix them, add missing tests, and ensure functionality was clear and reliable.

Script 1: Math Functions Test
Issues Found

Some math operations (like division by zero) were not handled.

No input validation (non-numeric input caused errors).

Limited test coverage (only basic operations were tested).

Fixes Applied

Added handling for division by zero (returning Infinity).

Ensured inputs were validated as numbers before performing operations.

Expanded test cases to include negative numbers and edge cases.

Challenges

Balancing simplicity with robustness: ensuring the script didn’t become too complex while still covering edge cases.

Script 2: Login Validation Test
Issues Found

Login function accepted invalid credentials due to incorrect logical checks.

Missing tests for common scenarios like empty input or incorrect password.

Poor separation of concerns (validation mixed with test logic).

Fixes Applied

Rewrote the login validation function to properly check username/password.

Added comprehensive test cases: valid login, invalid login, empty credentials, wrong password.

Cleaned up test outputs for clarity.

Challenges

Ensuring clarity between what was being tested (function logic) vs. what was producing test results (test cases).

Script 3: Shopping Cart Functions
Issues Found

Case sensitivity caused removeItem("apple") to fail when Apple was in the cart.

Invalid quantities (e.g., 0) still added items.

Missing tests for:

Adding duplicate items.

Removing items not in the cart.

Handling empty cart scenarios.

Fixes Applied

Fixed case sensitivity by normalizing item names (converted to lowercase).

Prevented invalid quantities from being added.

Added missing test cases for duplicates, non-existent removals, and empty carts.

Challenges

Maintaining simplicity in logic while still covering all the edge cases.

Avoiding over-complicating the cart (e.g., no price or advanced features) while making it function correctly.

Conclusion

Through this debugging process, each script was improved by:

Fixing logical and functional errors.

Adding missing test cases for broader coverage.

Improving reliability without over-engineering.

This assignment highlighted the importance of clear test coverage, edge-case handling, and maintaining simple but correct code.
