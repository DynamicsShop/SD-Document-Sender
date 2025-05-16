## SD Document Sender Releases

### 14.1.2

#### Enhancements

- AppSource App - A modification was made to the Setup Wizard.

### 14.1.1

#### Enhancements

- AppSource App - A minor enhancement was made to the user experience flow on initial install of SD Document Sender.

### 14.1.0

#### Enhancements

- AppSource App - A new Licence Install and Setup Wizard was created.

- AppSource App - The notification to activate the app, displayed on fresh install of SD Document Sender, was added to the standard Business Central role centres.

- AppSource App - Changes were made to the Manage Subscriptions page.

- AppSource App - The Lead Subscription Link from the Request Subscription action in the Product Activation page was updated.

- AppSource App - A minor change was made to the About page.

### 14.0.0

#### Enhancements

- AppSource App - New functionality to send draft attachments directly to SFTP. A new delivery method of File Transfer was added to the SD Document Sender Jobs.

- AppSource App - Account Salesperson/Purchasers and Document Salesperson/Purchasers were added as a Recipient Source on the SD Document Sender Jobs.

- AppSource App - For Jobs with the option to Group Documents on Draft enabled, a check was added to prevent users from adding Document, Document Contact or Document Salesperson/Purchaser to the recipients.

- AppSource App - A number of UI Changes were made to the SD Document Sender Setup Card.

- AppSource App - Various UI changes were made to the Job Card. ToolTips were also updated. 

- AppSource App - ToolTips were updated on SD Document Sender pages.

- AppSource App - A change was made to display the contents of the HTML control when the Draft is in view mode.

- AppSource App - A new action was added to the Setup Card called View Our Apps. This action opens a page on AppSource pointing to all our Simply Dynamics Ltd apps. 

- AppSource App - Changes were made to Role Centre and the Attention Activities Card Part to reflect the new File Transfer functionality.

### 13.0.2

#### Enhancements

- AppSource App - A change was made to the licence expiry notification. The logic for checking for expiry dates was reworked.

- AppSource App - Enhancements were made to the App Request Subscription page.

- AppSource App - Additional phrases were added as search phrases for the SD Document Sender pages.

- AppSource App - ToolTips were updated in the About, Product Activation, and Tenant Subscription pages.

- AppSource App - The status detail displayed on the Drafts in Error is updated to display a meaningful message if Graph API is used to send emails and the Graph API token has expired.

### 13.0.1

#### Bug Fixes

- AppSource App - Text Flowfields were not calculating in the templates when set as placeholder fields. 

### 13.0.0

#### Enhancements

- AppSource App - An option was added to the Job Cards to aggregate drafts per account code. Existing draft generation and draft issuing code was reworked to allow for this option. For Job Types of Sales Quote, Sales Order, Reminder, Purchase Order, Service Order, and Service Quote a draft is generated per document but the documents are grouped together into a single email per account when issued. The rest of the drafts are posted to history but not issued. For Job Types of Sales Shipment, Sales Invoice, Sales Credit Memo, and Purchase Invoice a single draft with multiple attachments is generated per account.

### 12.0.0

#### Enhancements

- AppSource App - A new App called SD Document Sender, based on the 11.1.1 version SD Bulk Mailer App was created. 

- AppSource App - Jobs can be generated in XML as Electronic Documents where an electronic document format exists for the Job.

- AppSource App - Functionality to integrate to Azure Blob Storage was added to SD Document Sender.

- AppSource App - A new and improved HTML Editor was created for use in creating the Email Body in the Templates. 

- AppSource App - Codeunits were updated to allow for more efficient draft creation and issue. 

- AppSource App - The logic was changed to create drafts first and then create the draft attachments. 

- AppSource App - The draft generation Codeunit was reworked to remove draft generation from running in a background session. 

- AppSource App - A change was made to the Job Card to update the Job Type from an option field to an enum. 

- AppSource App - A migration path from SD Bulk Mailer to SD Document Sender was created. An action was surfaced on the SD Document Sender Setup card to import data from SD Bulk Mailer. 

- AppSource App - The App was reviewed from a user interface perspective. 

- AppSource App - New data for the Assisted Setup was created. 

- AppSource App - A change was made to the import of Assisted Data Setup.  

- AppSource App - The SD Document Sender App was prepared for AppSource submission. 

- AppSource App - A change was made so that Draft Mails are no longer issued if they do not have a To recipient. Previously the Draft Mails were sent if they had a CC recipient but not a To recipient. 

- AppSource App - An action was surfaced in the SD Document Sender Drafts List page to open the transaction associated with the draft. 

- AppSource App - The Job Card was updated to prevent users selecting Document or Document Contact as a recipients for Jobs of Type Statement, Vendor and Customer as these recipients are not valid for these Job Types. 

- AppSource App - A change was made to the draft generation to allow users attach linked files that have the same filename on different transactions to the drafts. 

- AppSource App - A  change was made to hide the Email Body Layout field on the Job Card if a Delivery Method of Print or Azure Blob Storage is selected.  

- AppSource App - The Zip file name created when a Delivery Method of print is selected was updated. 

- AppSource App - Functionality was added to allow for implementation of custom Job Type additions to SD Document Sender. 

- AppSource App - Permission Sets were created for SD Document Sender. 

- AppSource App - An upgrade from User Groups in SD Bulk Mailer to Security Groups in SD Document Sender was implemented. User Group Security is marked as obsolete and will be replaced by Security Groups.  

- AppSource App - A new function call was added to the SD Document Sender FactBox to send an individual email manually.  

- AppSource App - New functionality was added to allow users to edit the email body after the draft has been created. 

- AppSource App - The Recreate from History action in the SD Document Sender History list was recaptioned as Regenerate from History and is a full regeneration/recreation of the document and it's recipients. 

- AppSource App - An action was added to the Document Sender Jobs List to show/hide disabled Jobs. 

- AppSource App - The Document Sender Jobs List was changed to order by Job Type. 

- AppSource App - A change was made to allow Job Types of Vendor to have a blank Report ID in the Job Card. This will allow users to attach Additional Attachments such as a circular or promotional material and create drafts for all or a filtered list of Vendors. 

- AppSource App - A change was made to allow Job Types of Customer to have a blank Report ID in the Job Card. This will allow users to attach Additional Attachments such as a circular or promotional material and create drafts for all or a filtered list of Customers.  

- AppSource App - The Job Types in the Job Card were reordered. 

- AppSource App - The File Name format for Attachments was changed.  

- AppSource App - The From Name was removed from the Job Card. 

- AppSource App - The SD Document Send KPI FactBox was surfaced on the document list pages that have an associated Job Type in SD Document Sender. 

- AppSource App - A flowfield count of documents send for a Job was added to the Job Card.  

- AppSource App - An action was added to the Job Card to create a Template for the Job with the same code and Description as the Job. 

- AppSource App - A FactBox was added to the Customer and Vendor Card so users can drill into the documents that have been sent in SD Document Sender. 

- AppSource App - The placeholder delimiters in the templates were changed. 

- AppSource App - A change was made to clear the Email Body Layout if selected on a Job and the Delivery Method is then subsequently changed to Print or Azure Blob Storage.  

- AppSource App - If the Delivery Method of a draft is Azure Blob Storage or Print the Email Content is no longer shown if an Email Body Layout has been specified. 

- AppSource App - A a Posted Document Range field to search from was surfaced in the Job Card for Jobs of Type Vendor Remittance. 

- AppSource App - The Additional Attachments FastTab for Jobs of Delivery Method of Print or Azure Blob Storage is now hidden and additional attachments are no longer being printed or sent to Azure Blob Storage. 

- AppSource App - The Draft list was changed to allow users open the Purchase Order list when the Document No. of a Job of Type Purchase Order is selected. 

- AppSource App - A change was made to the Job Card in the Additional Attachments FastTab not to check for the File Name When choosing the Import New File action as the file won't yet exist. 

- AppSource App - A change was made to populate the Job Description in the SD Document Sender History list. 

- AppSource App - Functionality was created to allow sending of Vendor, Vendor Remittance and Statement Job Types directly from the Document Sender FactBox on the Vendor Card and List. 

- AppSource App - Functionality was created to allow sending of Customer, Customer Remittance and Statement Job Types directly from the Document Sender FactBox on the Customer Card and List. 

- AppSource App - Functionality was added to allow users email Issued Reminders from the SD Document Sender FactBox. 

- AppSource App - UI changes were made to the Job Card for a Job Type of Customer Remittance. 

- AppSource App - UI changes were made to the Job Card for Job Types of Customer and Vendor. 

- AppSource App - A number of UI changes were made to the Job Card for a Job of Type Sales Invoice - Open. 

- AppSource App - UI changes were made to the SD Document Sender Drafts list. 

- AppSource App - A number of UI changes were made to the Job Card including updating tooltips on the card. 

- AppSource App - Various UI changes were made to the SD Document Sender Setup card. 

- AppSource App - Functionality was added to prevent deletion of a Job if the Job has undelivered drafts. 

- AppSource App - The message raised when Issuing Drafts from the Draft Card was changed. 

- AppSource App - For a Job of Type Sales Invoice - Review the code that calculates the due date range for including invoices when generating drafts was reviewed and reworked. 





