Overview

This document explains the tools, technologies, and structure used to automate the Octopus SaaS application.
The automation is developed to perform the complete End-to-End workflow from Login to Logout using Selenium with Python.

Software Used
1. Selenium WebDriver
Selenium WebDriver is used to automate browser actions such as:
Clicking buttons
Entering text
Selecting dropdown values
Handling checkboxes
Navigating between pages
It helps in performing real-time user actions on the web application.

2. PyCharm IDE

PyCharm is used as the development environment to:
Write the automation script
Run the script
Debug errors
Manage project files

3. Google Chrome Browser

Automation is executed on the Google Chrome browser.

4. ChromeDriver

ChromeDriver is used to connect Selenium with the Chrome browser.
Programming Language Used
Python
Python is used to write the automation script because it is simple, readable, and easy to maintain.
Project Structure
The automation is written in a single Python script file.
The script is divided into sections using comments for better readability, such as:
Login Section
Add Generator Section
Billing Information Section
Service Hours Section
Route Assignment Section
Price Book Section
Logout Section
This makes the code easy to understand and follow step by step.
Automation Flow

The script follows this workflow:

Login to application
Add new Generator
Fill Generator and Billing details
Verify Latitude and Longitude
Set Service Hours
Assign Route
Add Service
Update Price Book
Logout
Wait Strategy
Implicit Wait is used in the script.
time.sleep() is used for handling page loading and element synchronization.
Locator Strategy

The following locator strategies are used:
ID
XPath
Text-based XPath
Contains-based XPath for dynamic elements
Type of Architecture
This automation follows a simple linear execution structure.
It is suitable for assessment-level automation and small projects.

Conclusion

The automation is built using Selenium with Python in PyCharm IDE.
It successfully covers the complete End-to-End workflow of the application in a structured and step-by-step manner.
