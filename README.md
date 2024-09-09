#Task Summary:

##Implement a password reset feature that verifies the user via email and allows resetting the password in the database after validation.

##Password Reset Flow:

##Forgot Password Page:

Design a page where the user can enter their email address.

Check if the user exists in the database.

If the user is not found, return an error message.

##Email Verification:

If the user is found, generate a random string (token).

Send a password reset link with the token to the user's email.

Store the token in the database for later verification.

##Token Verification:

When the user clicks the link, retrieve the token from the URL.

Validate the token against the database.

If the token matches, display a form to reset the password.

If the token does not match, return an error message.

##Password Reset:

Allow the user to submit a new password.

Update the password in the database and clear the token once the password is updated.

@Render URL:
