# Check-List
Log In, Sign Up, Forgot Password functions of facebook.com
_____
## Log In
1. Enter a valid email/phone number and password.
2. Enter a valid email/phone number and wrong password.
3. Enter wrong email/phone number and correct password.
4. Leave the fields blank and press the enter or click the login button.
5. The login field is empty, the password field is correct data.
6. Login field with correct data, password field - empty.
7. Enter wrong email/phone number and password.
8. Is there a warning that the character limit has been exceeded in the login field or in the password field?
9. Make sure there is a limit on the total number of failed attempts.
10. Are login and password fields case sensitivity?
11. The password field masks characters? (usually asterisks).
12. Is there a minimum length for the password field?
13. Check the copy-paste for the login field and for the password field.
14. Check the Log In button.
15. Does pressing the log out button take you to the login form?
## Sign Up
1. Fill in all fields with correct information and press the button ‘Create an account’.
2. In the notification of successful registration, received to the mailbox, go to provided link for confirmation of registration.
3. Make sure that there are required fields to fill out.
4. Do not fill in required fields and press the button ‘Create an account’.
5. Enter spaces in all fields marked with as required and press the button ‘Create an account’.
6. Insert spaces before and after the main text in all text boxes.
7. Fill in all fields with correct or incorrect information and click Cancel button.
8. Enter html tags / wildcards / special characters in the text boxes and click the button ‘Create an account’.
9. Register a new user with the login new @ user.
10. Register a new user with login 'newuser' and password 'newuser' (full match).
11. Registration of a user with a login containing XSS or SQL injections.
12. Is it possible to register the user "admin" and the user "admin"?
13. Register putting in the field ‘Date of birth’ the date in the future. 
14. In the field ‘Date of birth’ enter the text manually.
15. Check radiobuttons it the field ‘Sex.
## Forgot Password
1. Enter valid phone number and click button ‘Search’.
2. Wait for code sent on your mobile and put it in the field.
3. Put incorrect code/set the code field empty.
4. Put new password (containing one or more numbers, both upper and lower case letters, at least six characters long)
5. Put empty value in 'new password' field and click button ‘Skip’.
