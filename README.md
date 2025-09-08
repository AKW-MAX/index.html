# 1. What are HTML forms
Hello there, today we are going to learn about HTML forms, how to create them, the different elements that are used when creating the forms.
What is a HTML forms? It is an area with input elements where users enter data based on the questions asked and the data is often sent to a sever for processing.
Forms are defined with the &ltform&gt tag
Pages that make use of HTML forms include login, registration, search, paymenent etc.
# 2. HTML form structure
As we have said the HTML forms are defined by the <form> tag which has an opening and closing tag.
All the elements in the form are going th be enclosed by this tag, it acts as a container for the different types of input elements such as textfields,checkboxes,radio buttons,submit buttons etc.
## **&ltfieldset&gt** 
This tag which is used to group related elements in a form, it draws a box around the related elements for example my form has the first &ltfieldset&gt **personal infomation** then followed by **contact and address information**.
This tag has both opening and closing tags where those group of related elements are contained.
## **&ltlegend&gt**
This tag is used is used to define a caption or a title for the &ltfieldset&gt element, in my form the first &ltlegend&gt is the tittle **personal information**
this tag encloses the title of the different &ltfieldset&gt that you will have on your form.
## **&ltlabel&gt**
This tag adds a small description to an input field. It renders text that providde a brief description about an input field.
As you can observe my first &ltlabel&gt was **First Name** where the user inputs their name. 
# HTML input Elements
This are elements  that are designed for users to enter data they include;
1. **checkboxes**
   The syntax for checkboxes is &ltinput type="checkboxes"&gt
   This tag creates a checkbox, and each checkbox is paired with a &ltlabel&gt to display the associated text.
   it is important to include *for* attribute on the &ltlabel&gt or else the text will not be clickable.
   This element was applied when I asked about the education level of the user list came up for the user to choose.
   this element was used when I wanted the user to select his/her interests, he/she could pick more than one option.
3. **&ltselect&gt**
   This element has an opening and a closing tag. It is used to create a drop-down list.
   The *name* attribute is needed to refference the form data after the form is submitted, if left out no data from the the drop-down list will be submitted.
   The *id* attribute is needed to associate the drop down-list with a &ltlabel&gt
   The *&ltoption&gt* tag is enclosed inside the &ltselect&gt tag and it defines the available options in the drop-down list.
   This element was applied when I asked about the education level of the user list came up for the user to choose 
5. **Radio Button**
   This button creates two input types, a good example is when you want the user to mention their gender. You only want to create two options, this is where we use the radio    button.
   we use the syntax &ltinput type="radio"&gt
   You always have to add a name of the topic to be selected and a value and to group radio input elements they must have name value.
   This button was used in the form to create where the user can choose their gender
7. **submit button**
   &ltinput type="submit"&gt
   This button  allows the forms' input data to be submitted  to a form handler, usually code on the sever
   The text on the submit button is set by default *submit* but can be manipulated by modifying the *value* attribute.
8. **Reset a form Button**
   &ltinput type="reset"&gt
   When a user enters data and decides to start all over again we use this button.
   The text on the reset button is set by default *reset* but can be manipulated by modifying the *value* attribute.
9. **&lttextarea&gt**
   This tag defines a multi-line text input control, it is used to collect user inputs like comments or reviews.
   The sixe of the &lttextarea&gt is specified by the *col* and *rows* attributes
   The *name* attribute is needed to efference the form data after the form is submitted, the *id* attribute is needed to associate the <textarea> with the &ltlabel&gt.
   






