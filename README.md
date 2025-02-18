# Selenium Multi-Site Login Automation

## Overview

This project automates login testing for multiple popular websites using Selenium WebDriver. The script navigates to each login page, inputs dummy credentials, and attempts to interact with the login button. It then logs success or failure for each website.

### Features

✅ Automates login form interactions for 10+ websites.

✅ Implements explicit waits to handle dynamic page elements.

✅ Handles multi-step logins (e.g., Gmail & YouTube require a "Next" button before the password field).

✅ Logs results to a file (login_tests.log) for debugging and analysis.

✅ Uses headless mode compatibility (can be toggled for silent execution).

### Technologies Used

🐍 Python

🌍 Selenium WebDriver

🖥 Google Chrome & ChromeDriver

📝 Logging module for structured test results

### Limitations

❌ Some websites use CAPTCHAs or bot detection, which may prevent interaction.

❌ Websites change frequently, requiring updates to element locators.

❌ Not all pop-ups and cookies are handled dynamically.

### License

This project is released under the MIT License.



