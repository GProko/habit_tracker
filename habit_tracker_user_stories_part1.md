
# Habit Tracker User Stories

## User Story Template
**Title:**  
_As a [user role], I want [feature/goal], so that [reason]._  
**Acceptance Criteria:**  
1. [Criteria 1]  
2. [Criteria 2]  
3. [Criteria 3]  
**Priority:** [High/Medium/Low]  
**Story Points:** [Estimated Effort in Points]  
**Notes:**  
- [Additional information or edge cases]

---

## Exercise 2: Login/Registration Page

### Account Registration
**Title:**  
_As a user, I want to register with my name, username, age, and country, so that I can create an account and access the habit tracking features._  
**Acceptance Criteria:**  
1. The registration form captures name, username, age, and country.  
2. Registration is successful upon entering valid details.  
3. The user is directed to the homepage after registration.  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- Registration credentials are not stored in browser cache for security.  

### Account Login
**Title:**  
_As a user, I want to log in using my username and password, so that I can access my account and track my habits._  
**Acceptance Criteria:**  
1. Login form includes username and password fields.  
2. Login is successful when valid credentials are entered.  
3. Redirects to homepage upon successful login.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Only default credentials work due to credential clearance after logout.  

### Error Feedback on Login
**Title:**  
_As a user, I want to receive a message if I enter the wrong username or password, so that I know my login attempt was unsuccessful._  
**Acceptance Criteria:**  
1. User is shown an error message for incorrect credentials.  
2. Error message does not expose valid usernames or passwords.  
3. Login remains disabled until valid credentials are entered.  
**Priority:** High  
**Story Points:** 1  
**Notes:**  
- Important for user experience and security feedback.  

---

## Exercise 3: Homepage

### View Welcome Message
**Title:**  
_As a user, I want to see a personalized welcome message with my name on the homepage, so that I feel recognized and can confirm I am logged into the correct account._  
**Acceptance Criteria:**  
1. User’s name appears in the welcome message.  
2. Message loads immediately upon login.  
3. Message updates if profile name is changed.  
**Priority:** Medium  
**Story Points:** 1  
**Notes:**  
- Depends on profile data retrieval.

### Display Weekly Progress
**Title:**  
_As a user, I want to see my daily progress for each habit on the homepage, so that I can easily monitor my progress._  
**Acceptance Criteria:**  
1. Habits are displayed with daily completion status.  
2. Progress resets weekly.  
3. Interface shows a clear visual (e.g., bar or dot) per habit.  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- Requires tracking completion data by day.

### View Completed Habits
**Title:**  
_As a user, I want to see a section for completed habits on the homepage, so that I can track what I have already achieved._  
**Acceptance Criteria:**  
1. Completed habits are separated or marked clearly.  
2. Users can toggle between completed and pending.  
3. Data updates in real time after completion.  
**Priority:** Medium  
**Story Points:** 2  
**Notes:**  
- Helpful for habit review and motivation.

---

## Exercise 4: Menu

### Access Menu Options
**Title:**  
_As a user, I want to access a menu with options for configuring my habits, viewing reports, editing my profile, and signing out, so that I can easily navigate to different parts of the app._  
**Acceptance Criteria:**  
1. Menu is accessible from all major screens.  
2. Menu contains all listed options.  
3. Menu design is responsive and intuitive.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Accessible via a persistent icon (hamburger or tab).

### Navigate to Habits Page
**Title:**  
_As a user, I want to access the habits page from the menu, so that I can configure and manage my habits._  
**Acceptance Criteria:**  
1. Menu link leads to habits page.  
2. Page loads user’s existing habits.  
3. Provides options to add/edit/delete habits.  
**Priority:** High  
**Story Points:** 1  
**Notes:**  
- Essential for daily functionality.

### Sign Out from Menu
**Title:**  
_As a user, I want to sign out of my account using an option in the menu, so that I can securely log out when I'm finished using the app._  
**Acceptance Criteria:**  
1. "Sign Out" button is clearly visible.  
2. Logs out user and redirects to login page.  
3. Clears session data securely.  
**Priority:** High  
**Story Points:** 1  
**Notes:**  
- Must be confirmed to prevent accidental logout.

(Continued in next cell...)
