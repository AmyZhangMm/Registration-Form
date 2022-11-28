# form.github.io


Challenges I faced while completing this page and waht I found a solution. I spent some time on self learning and iterating my codes on the following areas while programmin this web page:

1. How to edit the relevant code of mobile.
![image](https://user-images.githubusercontent.com/102950347/204204849-25a41851-3861-4f1b-adf5-17504e425de4.png)


The knowledge of input-group class.
![image](https://user-images.githubusercontent.com/102950347/204206813-11c59068-b48f-4b7e-bba4-8317ac093954.png)

                    
https://www.w3schools.com/bootstrap4/bootstrap_forms_input_group.asp 
Bootstrap 4 Input Groups
The .input-group class is a container to enhance an input by adding an icon, text or a button in front or behind the input field as a "help text".
Use .input-group-prepend to add the help text in front of the input, and .input-group-append to add it behind the input.
At last, add the .input-group-text class to style the specified help text.



2.	<form> tag – bootstrap - https://www.w3schools.com/bootstrap/bootstrap_forms.asp 
-	form action="/action_page.php" – this tag will help me to collect all my input data and send to another path/location to be shown.

Standard rules for all three form layouts:
  
 - Wrap labels and form controls in <div class="form-group"> (needed for optimum spacing) – if I remove the attribute, the space between 2 input text will become smaller. 
 - Add class .form-control to all textual <input>, <textarea>, and <select> elements – this will make the input box 100% width of the screen. Once remove, the width   will change to the default width. So this depends on how you want my input box look like.
 - Vertical form (this is default)
 - Horizontal form (Add class .form-horizontal to the <form> element)

  
  

  
 3. <textarea> tag – bootstrap
  
https://www.w3schools.com/tags/tag_textarea.asp 
  
The <textarea> element is often used in a form, to collect user inputs like comments or reviews.
A text area can hold an unlimited number of characters, and the text renders in a fixed-width font (usually Courier). The size of a text area is specified by the cols and rows attributes (or with CSS).The name attribute is needed to reference the form data after the form is submitted (if you omit the name attribute, no data from the text area will be submitted). The id attribute is needed to associate the text area with a label. 

  
  
  
 4. Mobile responsive. In order to make this table change smoothly in different screen sizes, I realized its responsive function through bootstrap row and column, but when I was designing a small screen style, I found that the original codes had been allocated in a fixed <div> tages, they cannot be re-group in different media queries. After searching a lot of information on the Internet, I couldn't find the easiest way. Finally, I decided to edit another set of codes in HTML for small size of screen to realize the vertical distribution of table.


  
  
  
