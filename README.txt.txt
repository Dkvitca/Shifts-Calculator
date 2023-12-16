Shift Earnings Calculator
Overview
The Shift Earnings Calculator is a Python script that processes work shift data received via email and calculates earnings for each shift, as well as monthly totals. The script generates an HTML table summarizing the details of each shift, including hours worked, earnings breakdown, and shift type classification.

Features
Email Integration: The script extracts shift data from emails received from a specified sender.

Shift Classification: Shifts are classified into types such as "morning," "night," or "overnight" based on the start time.

Earnings Calculation: Earnings are calculated for each shift, considering regular hours, overtime at 125%, and overtime at 150%.

Monthly Totals: The script provides a summary of total earnings for the month, categorized by regular hours, overtime at 125%, and overtime at 150%.

HTML Table Generation: The results are presented in a structured HTML table for easy readability.

Prerequisites
Python 3.x
Required Python packages (bs4, imaplib, email, datetime)
Usage
Clone the repository to your local machine.
Install the required Python packages: pip install beautifulsoup4
Configure the email login credentials in the script (username and password variables).
Run the script using a Python interpreter.
Example
To illustrate the usage of the Shift Earnings Calculator, consider the following steps:

Receive an email with shift data from a specified sender.
Run the script, providing the necessary email login credentials.
View the generated HTML table summarizing each shift and monthly totals.
Optionally, send the results back as a reply to the original email.
Notes
Ensure that the sender's email address is correctly specified to filter relevant emails.
The hourly rate for earnings calculation is currently set to 40 Shekels. Modify the hourly_rate variable in the Shift class if needed.