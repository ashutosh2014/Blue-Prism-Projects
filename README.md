# Blue-Prism-Projects

<b> BP Travel (Web Automation, Web Scrapping) </b>
  
  Tasks that are automated in this project :- \
 		- Open http://bptravel.blueprism.com/login.html \
    - User Name - bp, Password - bp \
    - Left side menu (Search, Create Quote, View Quote, View Booking…) need to be modelled with Dynamic attributes \
    - Save the Quote Numbers and Quote Prices in Quotes.xls \
    - Click on Create Quote and take inputs from Quotes.xls and get the Quotes created \
  
  Use Case Type :-\
    - Web Automation \
    - Excel Handling \
    - Dynamic Elements \
    - App Navigator

<B>ACME UIPATH TEST (Web Automation, Web Scrapping) </B>

Tasks that are automated in this project :- \
- Open the ACME System 1 Web Application. 
- Log in to System 1. Required input data: email and password.
-  Access the Dashboard - the central location, where the user can pick a specific menu item
- Access the Work Items listing to view all the available tasks to be performed (Output data: Work Items).
- For each activity of the WI5 type, perform the following steps:
  - Open the Details page of the selected activity to retrieve the Client Details.
  - Open the SHA1 Online webpage - http://www.sha1-online.com/, and provide the following input: ClientIDClientName-ClientCountry. Replace all the variables with the corresponding values. Use dashes between each item and the next one, as shown above
  - Retrieve the Client Security Hash value from the webpage.
  - Go back to Work Item Details and open Update Work Item.
  - Set the status to “Completed”. Add a comment with the obtained SecurityHash.
- Continue with the next WI5 Activity
