# 1. What are HTML forms
Hello there, today we are going to learn about HTML forms, how to create them, the different elements that are used when creating the forms.
What is an HTML form? It is an area with input elements where users enter data based on the questions asked and the data is often sent to a sever for processing.
Forms are defined with the &lt;form&gt; tag
Pages that make use of HTML forms include login, registration, search, payments etc.
# 2. HTML form structure
As we have said the HTML forms are defined by the &lt;form&gt; tag which has an opening and closing tag.
All the elements in the form are going th be enclosed by this tag, it acts as a container for the different types of input elements such as textfields,checkboxes,radio buttons,submit buttons etc.
## **&lt;fieldset&gt;** 
This tag which is used to group related elements in a form, it draws a box around the related elements for example my form has the first &lt;fieldset&gt; **personal infomation** then followed by **contact and address information**.
This tag has both opening and closing tags where those group of related elements are contained.
## **&lt;legend&gt;**
This tag is used is used to define a caption or a title for the &lt;fieldset&gt; element, in my form the first &lt;legend&gt; is the tittle **personal information**
this tag encloses the title of the different &lt;fieldset&gt; that you will have on your form.
## **&lt;label&gt;**
This tag adds a small description to an input field. It renders text that provide a brief description about an input field.
As you can observe my first &lt;label&gt; was **First Name** where the user inputs their name. 
# HTML input Elements
This are elements  that are designed for users to enter data they include;
### **checkboxes**
The syntax for checkboxes is &lt;input type="checkboxes"&gt;
This tag creates a checkbox, and each checkbox is paired with a &lt;label&gt; to display the associated text.
it is important to include *for* attribute on the &lt;label&gt; or else the text will not be clickable.
This element was applied when I asked about the education level of the user list came up for the user to choose.
this element was used when I wanted the user to select his/her interests, he/she could pick more than one option.
### **&lt;select&gt;**
This element has an opening and a closing tag. It is used to create a drop-down list.
The *name* attribute is needed to refference the form data after the form is submitted, if left out no data from the the drop-down list will be submitted.
The *id* attribute is needed to associate the drop down-list with a &lt;label&gt;
The *&lt;option&gt;* tag is enclosed inside the &lt;select&gt; tag and it defines the available options in the drop-down list.
This element was applied when I asked about the education level of the user list came up for the user to choose 
### **Radio Button**
This button creates two input types, a good example is when you want the user to mention their gender. You only want to create two options, this is where we use the radio    button.
We use the syntax &lt;input type="radio"&gt;
You always have to add a name of the topic to be selected and a value and to group radio input elements they must have name value.
This button was used in the form to create where the user can choose their gender
### **submit button**
&lt;input type="submit"&gt;
This button  allows the forms' input data to be submitted  to a form handler, usually code on the sever
The text on the submit button is set by default *submit* but can be manipulated by modifying the *value* attribute.
### **Reset a form Button**
&lt;input type="reset"&gt;
When a user enters data and decides to start all over again we use this button.
The text on the reset button is set by default *reset* but can be manipulated by modifying the *value* attribute.
### **&lt;textarea&gt;**
This tag defines a multi-line text input control, it is used to collect user inputs like comments or reviews.
The sixe of the &lt;textarea&gt; is specified by the *col* and *rows* attributes
The *name* attribute is needed to efference the form data after the form is submitted, the *id* attribute is needed to associate the &lt;textarea&gt; with the                &lt;label&gt;.
   






