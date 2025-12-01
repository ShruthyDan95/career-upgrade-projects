User Story (LOGIN FEATURE)

As a user
I want to log into the application
So that I can securely access my personal dashboard.

Acceptance Criteria

AC1: Successful login

Given the user is on the login page
When they enter a valid username and password
Then they should be redirected to the dashboard

AC2: Invalid password

Given the user enters a valid username
When they enter an incorrect password
Then an error message should appear

AC3: Empty fields

Given the login page is displayed
When the user clicks “Login” without entering credentials
Then an error should indicate required fields

AC4: Forgot Password

Given the user is on the login page
When they click “Forgot Password”
Then they should be taken to a password reset page

AC5: Password visibility toggle

Given the user is entering their password
When they click the “Show/Hide Password” icon
Then the password text should toggle visibility


Login Workflow (Simple)

User opens login page
        ↓
User enters username + password
        ↓
System validates credentials
        ↓
IF valid → Redirect to dashboard
IF invalid → Show error message
