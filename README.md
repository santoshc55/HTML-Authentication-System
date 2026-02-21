# HTML Authentication System
The HTML Authentication System is a basic front-end project that simulates a user authentication workflow including login, registration, password recovery, and dashboard access using HTML forms and page navigation.


---

## 🔐 Pages Included

The project contains the following HTML pages:

1. **login.html**  
   - Username and Password fields  
   - Login button (redirects to dashboard)  
   - Links to Register and Forgot Password pages

2. **register.html**  
   - Name, Email, Phone, Password, Confirm Password inputs  
   - Register button (redirects to login)  
   - Link back to Login

3. **forgot-password.html**  
   - Enter Email field  
   - Button to send reset link (redirects to Reset Password page)

4. **reset-password.html**  
   - New Password and Confirm Password inputs  
   - Update Password button (redirects to Login)

5. **dashboard.html**  
   - Simple welcome message  
   - Logout button (redirects back to Login)

---

## 🧩 How It Works

This is a static HTML project — there is **no backend or database**.  
Navigation between pages is done using hyperlinks and form actions to simulate page redirections.

---

## 📁 File Structure

```text
HTML-Authentication-System/
│
├── login.html
├── register.html
├── forgot-password.html
├── reset-password.html
├── dashboard.html
└── README.md