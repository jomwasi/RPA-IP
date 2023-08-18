## Explanation
Three files were created
- Main.xmal
- ReadRequest.xaml
- SaaSAutomation.xmal

# Main.xmal
This is the main workflow which will invoke other workflows and orchestrate the automation.

# ReadRequest.xmal
This picks the Request Excel file from the folder we created, read the ticket data, and incorporate them in variables for the next workflow to process

# SaaSAutomation.xmal
SaaS - Software as a Service Zoho application is used here to obtained/read data from Request file to create support ticket/job card.