# flask-user-authentication
A Flask based user authentication system with secure registration ,login, password hashing, session management, and SQLite integration using python ,HTML and CSS.
## 🔄 Authentication Flow

1. The user opens the **Register** page.
2. The user enters a username and password.
3. The password is securely hashed using **Werkzeug** before being stored in the **SQLite** database.
4. After successful registration, the user is redirected to the **Login** page.
5. The user enters their login credentials.
6. The application verifies the username and compares the entered password with the stored hashed password.
7. If authentication is successful, a user session is created and the user is redirected to the **Dashboard**.
8. The Dashboard is protected and can only be accessed by logged-in users.
9. Clicking **Logout** clears the session and redirects the user back to the Login page.
