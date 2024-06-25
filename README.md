# OutAdd_LLM

Goal: creating a button in Outlook that opens a folder on OneDrive containing all documents, photos, and files referred to in an email conversation. Here's the workflow:

1) Outlook Add-in Development: develop an Outlook add-in using Office Add-ins. Office Add-ins are web-based applications that integrate with Office applications. Use HTML, CSS, and JavaScript to create the UI for the add-in.

2) Email Parsing and NLP: 
    - Use Python for Natural Language Processing (NLP) to extract references to documents, photos, and files from the email conversation. 
    - Implement a service to process the email content and identify referenced files.

3) OneDrive Integration:

    - Use Microsoft Graph API to interact with OneDrive.
    - Retrieve and open the folder on OneDrive where the referenced files are stored.

4) Integration and Deployment:
    - Integrate the Python service with the Outlook add-in.
    - Deploy the add-in to the Office environment.