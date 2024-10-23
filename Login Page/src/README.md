NAME: MAIBHEKA ANOTIDAISHE B
REG NUMBER: H230702E
SECURE CODING MINI PROJECT


1. User Registration:
   - I can create a new account by providing my username and password.
   - The application stores my credentials in a `HashMap` for simplicity.
   - After successful registration, i am redirected to the login screen.

2. User Login:
   - I can log in to the application by entering my username and password.
   - The application validates my credentials against the stored data in the `HashMap`.
   - Upon successful login, the application displays a welcome message with my registration number(H230702E).


Credential Check:
The code first checks if the userDatabase HashMap contains the username entered by the user. This is done using the containsKey() method. If the username exists, it proceeds to the next step.
Password Validation:
If the username is found, the code retrieves the stored password associated with that username using userDatabase.get(username). It then compares this stored password with the password entered by the user using the equals() method.
Successful Login:
If both the username exists and the entered password matches the stored password, the application calls the showWelcomeFrame(username) method. This method displays a welcome message to the user, acknowledging their successful login. Additionally, the current login frame is closed using frame.dispose().
Failed Login Attempt:
If either the username does not exist in the database or the passwords do not match, the application updates the feedbackLabel to inform me that the login attempt was unsuccessful, prompting me to try again.


How it works
1. When the application starts, the user registration screen will be displayed.
2. Enter a username and password, then click the "Register" button.
3. If the registration is successful, the application will redirect you to the login screen.
4. Enter the same username and password you used for registration, then click the "Sign In" button.
5. If the login is successful, a welcome message with the user's registration number will be displayed.


