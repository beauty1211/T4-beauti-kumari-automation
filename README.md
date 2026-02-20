Octopus SaaS – End to End Automation

Project Description

This project contains an End-to-End automation script for the Octopus SaaS application.
The automation covers the complete workflow from Login to Logout, including Generator creation, Billing details, Service setup, Route assignment, and Price Book updates.

The automation is implemented using Python with Selenium WebDriver.

Tools & Technologies Used
1.Python
2.Selenium WebDriver
3.PyCharm IDE
4.Google Chrome Browser

Test Flow Covered

The automation script performs the following steps:
Login to the application
Add a new Generator
Enter Generator details (Name, Internal Account Number)
Fill Billing Information
Industry
Street Address
City, State, ZIP
Email and Phone
Verify Latitude and Longitude
Configure Service Hours
Assign Route
Add a Service
Select Route
Select Service Type
Select Frequency
Select Weekdays
Select Scope of Work
Select Anchor Date
Open Price Book
Toggle View Mode
Update container prices
Logout from application

Setup Requirements:- 
Before running the automation, make sure you have:
Python installed (Python 3.x recommended)
Google Chrome browser installed
ChromeDriver compatible with your Chrome version
PyCharm or any Python IDE installed
How to Run the Automation
Clone the GitHub repository:
git clone https://github.com/beauty1211/T4-beauti-kumari-singh-automation
Open the project in PyCharm.
Create a virtual environment.

Install required dependencies:
pip install selenium
Make sure ChromeDriver is properly configured.
Open the main automation script file (example: octopus_.py).

Run the script:
python octopus_.py
The browser will open automatically and execute the full workflow.

Notes
The script uses implicit wait and time delays for synchronization.
XPath locators are used to identify web elements.
The script runs on Chrome browser.
Test credentials are currently hardcoded inside the script.


