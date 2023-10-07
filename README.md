# PRODIGY_SD_03
Created a basic web interface that displays contact information using HTML and simple javascript. 


Description of how this simple contact management system works:

HTML Structure:
The code starts with the <!DOCTYPE html> declaration, which defines the document type.
Inside the <html> tag, there is a <head> section that contains the page's title.The main content is in the <body> section.


Page Title and Heading:
<h1>Contact Management</h1> displays a heading at the top of the page, indicating that this is a contact management application.


Contact Form:
The <form> element with the id="contact-form" defines a form for adding new contacts.It includes input fields for the contact's name, phone number, and email address.
The "Add Contact" button (<button>) is used to submit the form.


Contact List:
Below the form, there is an <h2> heading indicating "Contact List."
An unordered list (<ul>) with the id="contact-list" is used to display the list of contacts.


JavaScript for Adding Contacts:
The <script> section contains JavaScript code to add contacts.The addContact() function is defined.
When the "Add Contact" button is clicked, this function is called.
Inside addContact(), the values entered in the form fields (name, phone, email) are retrieved.A new list item (<li>) is created dynamically to display the contact details.
The contact details are inserted into the list item's HTML.The new list item is appended to the contact list (<ul>).
Finally, the form fields are cleared for the next input.


Output Display:
The output is displayed directly on the web page.After clicking "Add Contact," the contact's details are added to the list below the form.
You can continue to add more contacts by filling out the form and clicking the button again.


