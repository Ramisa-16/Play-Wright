# DailyFinance Test Automation

## Test Steps

#PlayWright
### 1. **User Registration and Email Verification**
   - **Action**: Visit [https://dailyfinance.roadtocareer.net/](https://dailyfinance.roadtocareer.net/), register a new user.
   - **Assertions**:
     - Verify that a congratulation email is sent.
     - Assert that the toast message shows a successful registration message.

### 2. **Login and Item Addition**
   - **Action**: Log in with the newly registered user and add two random items to the item list.
   - **Assertions**:
     - Assert that the two items appear on the item list.

### 3. **Profile Update and Logout**
   - **Action**: Go to the profile settings and upload a profile photo.
   - **Action**: Log out from the account.
   
### 4. **Password Reset**
   - **Action**: From the login page, click "Reset it here" and reset the password.
   - **Assertions**:
     - Ensure the password reset is successful.

### 5. **Login with New Password**
   - **Action**: Log in with the newly reset password.
   - **Assertions**:
     - Assert that the login is successful.
