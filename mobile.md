# Avant Mobile Challenge


### Technical Note

This challenge may be completed using the native mobile environment of your choice. Submissions must be written for iOS (Objective-C and/or Swift) or Android (Java). 

We strongly suggest using Parse, or another similar BaaS provider, for the web backend portion of the challenge. This challenge is designed to be open-ended and to demonstrate your ability to implement native front-end code for mobile apps that interface with a backend service. This challenge is not designed to test your ability to create a web backend service.  

### Background 

At Avant, we provide unsecured personal loans, backed by proof that a customer has a given income. To verify that income, our customers may be required to send us digital scans of physical paper documents. The documents may include: W2 tax forms, a voided check, or a utility bill.  

To make the process of providing those documents faster and easier for our customers, we would like to build a feature in our native mobile app for document uploading. This will allow a customer to log in, take a picture of their documents using their phone, and then an Avant verifications specialist will review the documents so a customer can have their loan application processed. 


### Requirements 

Create an app that implements the features of a **Document Uploader**. You can treat this as if you are building the specific document uploading features that would be added to the Avant mobile app. Therefore, the features/concepts you introduce outside of document uploading are open-ended and at your own discretion. 

The Document Upload features must meet the following requirements:

* Allow a user to input their `Customer ID` for identification
	* No true login system is required, but bonus points if you want to make one or utilize an existing method (such as those that exist in Parse's SDK). 
* Allow a user to take a photo of a physical document using the mobile device's camera
	* Ensure the document's orientation/rotation is correct
	* Allow the user to preview the photo before submitting
	* The user must indicate which type of document they are uploading: W2, voided check, or utility bill
* Upload the document to a web service, attaching the `Customer ID` for identification  
* When the document has been uploaded, show the user a confirmation message or alert indicating that Avant will review their submission within 24hrs.
* Allow the user to upload multiple documents and review the documents they have already uploaded for verification. 

### Additional Criteria: What We're Looking For 

* Use consistent code style and comment style throughout. 
* Attention to detail in areas that are easy wins are nice to see.
* Ensure a user understands where they are in the process flow throughout
	* Ensure any errors (networking, uploading, user input validation) are handled properly and the user never gets "stuck" in the app
	* Make it clear what the user is required to do at all times and use traditional/obvious navigation behaviors 
* While we won't evaluate directly on the quality of visual design or graphic design of the submission, we appreciate taking the extra step to make the submission easily navigable and holistic. This can include simple things such as proper use of an App Icon image asset in an asset catalog.  
