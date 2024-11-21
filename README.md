### Project Overview
This project aims to build an automation solution that automatically responds to emails. The Project works like a helpdesk assistant. It reads the emails from a specific email id and responds to it using a pre-defined email template. The response template is specified in the ‘KeywordandResponses.xlsx’ file. The emails identified are based upon the keywords mentioned in the email. These keywords are already stored in an excel file which the project refers to while responding. The project will read the email and filter them based upon the ‘subject’. It will then further read the email and look for a phrase/keyword in the email body and will match it with the one mentioned in the ‘KeywordandResponses.xlsx’ file. The project will send an email response to the sender by copying the text from the excel file.


### Steps to build the E-Mail Auto-Responder Project:

- Step 1: The Project opens the email application called Outlook.
- Step 2: It reads the email subject of all the unread emails.  
- Step 3: It then checks if the email subject is “Helpdesk”.
- Step 4: If it is “Helpdesk” then it reads the email body.
- Step 5: Checks if the email body has keywords which are mentioned in the key column of ‘KeywordandResponses.xlsx’ file.
- Step 6: If the key is found in email body, then it replies with the associated value of the “value column” line to the email address from which the email was received.
