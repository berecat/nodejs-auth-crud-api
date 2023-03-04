# Node.js Authentication and CRUD API
Node.js Authentication and CRUD API with Email Verification, Image Upload and Password Reset Using JWT, Passport.js and Sendgrid.

**This Branch** <br/>
Email Verification



## Testing
Use <a href="https://www.getpostman.com" target="_blank">Postman</a> to test.<br/>


**Register and Login** <br/>
Create a POST request to /api/auth/register <br/>
Create a POST request to /api/auth/login

**Update User Info and Upload Profile Image** <br/>
Try updating the user information and uploading a profile image using endpoint/api/user/[your_user_id] passing the token.

**Login and Recover Password** <br/>
Create a POST request to /api/auth/recover to recover your password. An email will be sent to you.


**Reset Password and Login with new Password** <br/>
Click the link in the email to reset your password. 
Reset the password then attempt to login with your old password. This should fail. Login with your new password

