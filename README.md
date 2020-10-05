# SpringBootFormHandling
As you can see, this form contains almost standard HTML input fields like textbox, radiobutton, select box (dropdown list), checkbox and text area – along with labels and submit button. We will be using Spring Boot with Spring MVC, Spring Form tags and JSP. You can use any Java IDE like Eclipse or Spring Tool Suite. If you are new to Spring Boot, I recommend you to follow this tutorial first. Then come back to this one.



Note that the @ModelAttribute annotation is used for the method parameter User user – so Spring will know to read values of fields on the form and set them to the model object’s fields. We don’t have to write a single line of code to get form data – just use the model object!
The submitForm() method simply prints the user object’s details to the console, and return the view named register_success which resolves to the JSP page described below.

