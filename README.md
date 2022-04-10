Build an application that requires login and registration <br>
Practice connecting a Flask application to a MySQL database <br>
Become familiar with the logic that is required to validate a user's registration to a website <br>
Become familiar with the logic that is required to validate a user logging in to a website <br>
Process a user logging out of an application <br> 
Practice using session



![image](https://user-images.githubusercontent.com/89495764/162641632-f86de3bc-7642-4017-bfc4-77b5b5a8c1f5.png)



[ ] BONUS:
Add more fields to your registration form with different form elements. For example, include a drop down menu, radio buttons, checkboxes, and a date picker. Include validations for each field. Have users provide their birthday, and require that they must be at least ten years old in order to register. Level up your password validations by requiring at least one capital letter and one number. Provide the user with several programming languages, and require that they check at least one as an interest of theirs. Customize this assignment and get creative!

[ ] Create a new Flask project

[ ] Create a new MySQL database with a table and the appropriate fields

[ ] The root route should display a template with the login and registrations forms

[ ] Validate the registration input

[ ] If registration is invalid errors messages should be displayed on the index page

[ ] If registrations is valid, hash the password and save the user in the database, store the user in session and then redirect to the success page

[ ] Validate the login input

[ ] If the login is invalid, display an error message on the index page

[ ] If login is valid, store the user in session and then redirect to the success page

[ ] Add a functioning logout button to the success page that clears session

[ ] After logging out, ensure you cannot reach the success page

[ ] NINJA Bonus: Add an additional validation on passwords to have a least 1 number and 1 uppercase letter

[ ] SENSEI Bonus: Add additional input types on the form. Get creative with you validations! (Consider including a date picker, radio buttons and/or checkboxes)
