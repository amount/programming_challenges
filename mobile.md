# Mobile Challenge
This challenge may be completed using any native mobile environment of your choice. Building the app for iOS (Objective-C/Swift) or Android (Java) is preferred, but please use whatever you are most comfortable with. For the web service, you may use any tool you are comfortable with. We suggest something simple, such as Parse. This challenge is designed to be open-ended.

At Avant Credit, we provide unsecured personal loans, backed by proof that a customer has a steady income stream.  To verify that income stream or other vital customer information, our customers send us documents, proving that income (like W2 forms, 1099s, voided checks, utility bills, etc.).  To make the process of getting those documents to us faster and easier for our customers, we would like to build a mobile document uploader. The app will allow a customer to log in, take a picture of their documents using their phone, and then an Avant Credit verifications specialist will review the documents.

Create an implementation of a **Document Uploader** app that meets the following requirements:

* Allow a user to input/set their `Customer ID`
	* No true login system is required, but bonus points if you want to make one.
* Allow a user to take a photo of a physical document using the mobile device's camera
	* Ensure the document's orientation/rotation is correct
	* Allow the user to preview the photo before submitting
* Upload the document to a web service, attaching the customer information
* When the document has been uploaded, show the user a confirmation message specifying that Avant will review their submission within 24hrs.
* Allow the user to upload multiple documents and view the documents they have uploaded for verification. 
* Ensure a user understands where they are in the process flow throughout
* Ensure any network errors are handled properly and the user never gets "stuck" in the app
