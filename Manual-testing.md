Test Case ID: TC001
Title: Verify successful login with valid username and password 

Precondition: User is on login page 

Test Data:
Username: standard_user
Password: secret_sauce

Steps:
1. Enter valid username in the Username field
2. Enter valid password in the Password field 
3. Click login button

Expected Result: 
User is redirected to inventory page

Actual Result: 
User is redirected to inventory page

Status: Pass


Test Case ID: TC002
Title: Verify login fails when Password is invalid

Precondition: User is on login page 

Test Data:
Username: standard_user
Password: invalid_password

Steps:
1. Enter valid username in the Username field
2. Enter invalid password in the Password field
3. Click login button

Expected Result: 
System should display a clear error message indicating that username and password is invalid, and user should be denied access to login. 
User should remain on the login page 

Actual Result: 
System displays an error message and user remains on the login page.

Status: Pass


Test Case ID: TC003
Title: Verify login fails when Username is invalid

Precondition:  User is on login page

Test Data:
Username: invalid_username
Password: secret_sauce

Steps: 
1. Enter invalid username in the Username field
2. Enter valid password in the Password field
3. Click login button

Expected Result: 
System should display a clear error message indicating that username and password is invalid, and user should be denied access to login. 
User should remain on the login page

Actual Result: 
Syste displays an error message and user remianns on the login page.

Status: Pass


Test Case ID: TC004
Title: Verify login fails when Password field is empty

Precondition: User is on login page

Test Data: 
Username: standard_user
Password: (leave blank)

Steps:
1. Enter valid username in the Username field.
2. Leave the Password rd field empty
3. Click the Login buttom

Expected Result: 
System should display a validation error message indicating that the password field is required
User should remain on the Login page
Login request should not proceed to the inventory page. 

Actual Result: 
System displays an error message that Password is required and user remains on Login page

Status: Pass


Test Case ID: TC005
Title:  Verify login fails when Username field is empty

Precondition: User is on Login page 

Test Data: 
Username: (leave blank)
Password: secret_sauce

Steps:
1. Leave Username field empty 
2. Enter password in the Password field
Click the Login button

Expected Result: 
System should display error validation error indicating that the Username field is required
User should remain on the Login page
Login request should not proceed to the inventory page

Actual Result: 
System displays an error message that Username is required and user remains on Login page.

Status: Pass


Test Case ID: TC006
Title:  Verify system displays validation message when Username and Password fields are empty

Precondition: User is on Login page

Test Data: 
Username: (leave blank)
Password: (leave blank)

Steps:
1. Leave the Username field blank
2. Leave the Password field blank
3. Click the Login button

Expected Result: 
System should display a validating error message indicating that Username and Password field is required
User should remain on Login page 
Login request should not proceed to the inventory page

Actual Result:
System dislpays error message that Username is required, user remain on Login page 

Status: Pass


Test Case ID: TC007
Title:  Verify Login fails for Locked user account

Precondition: User is on Login page

Test Data: 
Username: locked_out_user
Password: secret_sauce

Steps:
1. Enter "locked_out_user" in the Username field
2. Enter "secret_sauce" in the Password field
3. Click the Login button

Expected Result: 
System should display an error message indicating that user account is locked.
User should remain on Login page
User should be denied access to the inventory page

Actual Result: 
System displays error message indicating that user has been locked out.
User remains on Login page

Status: Pass


Test Case ID: TC008
Title:  Verify product images on display correctly when logged in with problem_user

Precondition: User is on Login page

Test Data: 
Username: problem_user
Password: secret_sauce

Steps:
1. Enter "problem_sauce" in the Username field
2. Enter "secret_sauce" in the Password field
3. Click the Login button
4. Observe the product images displayed on the inventory page.


Expected Result: 
All product images should display coeectly and correspond to their respective product descriptions. 

Actual Result: 
Product images are displayed incorrectly and do not correspond to their respective product descriptions.

Status: 
Fail

Test Case ID: TC00
Title:  
Precondition: 
Test Data: 
Username: 
Password: 

Steps:
1. 

Expected Result: 

Actual Result: 


Status: 


Test Case ID: TC00
Title:  
Precondition: 
Test Data: 
Username: 
Password: 

Steps:
1. 

Expected Result: 

Actual Result: 


Status: 
