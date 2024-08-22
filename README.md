# Displaying-Data-Stored-

Displaying Stored Data on a New Web Page
Objective:
Create a new web page to display the most recent command stored in the database. This page will present the latest robot movement command based on data collected from previous interactions with the control panel.

Steps to Implement:
Update the Control Panel:
Command Confirmation: Ensure that the control panel provides confirmation after pressing any movement button. This feature will help users verify that their command has been successfully processed.

Enhance process.php:
Command Handling: Modify process.php to handle incoming commands from the control panel. This script should insert the command into the database and provide appropriate feedback to the user.

Create the New Web Page:
Design the Page: Develop a new PHP file, display_data.php, which will query the database and display the latest command.

Fetch and Display Data: Use PHP to retrieve the most recent command from the commands table and present it on the display_data.php page.

Conclusion:
You have created a new web page to show the latest command stored in the database. This page provides a clear view of the most recent robot movement command, reflecting data collected from the control panel. Future improvements could include detailed command histories, enhanced user interface design..
