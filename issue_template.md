Exercise 2: Login/Registration Page
Title:
As a user, I want to register with my name, username, age, and country, so that I can create an account and access the habit tracking features.

Acceptance Criteria:

The registration form captures name, username, age, and country.

Registration is successful upon entering valid details.

The user is directed to the homepage after registration.

Priority: High
Story Points: 3
Notes:

Registration credentials are not stored in browser cache for security.

Title:
As a user, I want to log in using my username and password, so that I can access my account and track my habits.

Acceptance Criteria:

Login form includes username and password fields.

Login is successful when valid credentials are entered.

Redirects to homepage upon successful login.

Priority: High
Story Points: 2
Notes:

Only default credentials work due to credential clearance after logout.

Title:
As a user, I want to receive a message if I enter the wrong username or password, so that I know my login attempt was unsuccessful.

Acceptance Criteria:

User is shown an error message for incorrect credentials.

Error message does not expose valid usernames or passwords.

Login remains disabled until valid credentials are entered.

Priority: High
Story Points: 1
Notes:

Important for user experience and security feedback.

Exercise 3: Homepage
Title:
As a user, I want to see a personalized welcome message with my name on the homepage, so that I feel recognized and can confirm I am logged into the correct account.

Acceptance Criteria:

User’s name appears in the welcome message.

Message loads immediately upon login.

Message updates if profile name is changed.

Priority: Medium
Story Points: 1
Notes:

Depends on profile data retrieval.

Title:
As a user, I want to see my daily progress for each habit on the homepage, so that I can easily monitor my progress.

Acceptance Criteria:

Habits are displayed with daily completion status.

Progress resets weekly.

Interface shows a clear visual (e.g., bar or dot) per habit.

Priority: High
Story Points: 3
Notes:

Requires tracking completion data by day.

Title:
As a user, I want to see a section for completed habits on the homepage, so that I can track what I have already achieved.

Acceptance Criteria:

Completed habits are separated or marked clearly.

Users can toggle between completed and pending.

Data updates in real time after completion.

Priority: Medium
Story Points: 2
Notes:

Helpful for habit review and motivation.

Exercise 4: Menu
Title:
As a user, I want to access a menu with options for configuring my habits, viewing reports, editing my profile, and signing out, so that I can easily navigate to different parts of the app.

Acceptance Criteria:

Menu is accessible from all major screens.

Menu contains all listed options.

Menu design is responsive and intuitive.

Priority: High
Story Points: 2
Notes:

Accessible via a persistent icon (hamburger or tab).

Title:
As a user, I want to access the habits page from the menu, so that I can configure and manage my habits.

Acceptance Criteria:

Menu link leads to habits page.

Page loads user’s existing habits.

Provides options to add/edit/delete habits.

Priority: High
Story Points: 1
Notes:

Essential for daily functionality.

Title:
As a user, I want to sign out of my account using an option in the menu, so that I can securely log out when I'm finished using the app.

Acceptance Criteria:

"Sign Out" button is clearly visible.

Logs out user and redirects to login page.

Clears session data securely.

Priority: High
Story Points: 1
Notes:

Must be confirmed to prevent accidental logout.

Exercise 5: Profile Page
Title:
As a user, I want to view my saved name, username, age, and country on my profile page, so that I can see the details I provided during registration.

Acceptance Criteria:

Profile page displays all registration fields.

Information is fetched from user data.

Data is displayed in editable form fields or read-only view.

Priority: Medium
Story Points: 2
Notes:

Data sync with backend or local storage.

Title:
As a user, I want to update my name, username, age, and country on my profile page, so that I can keep my information up to date.

Acceptance Criteria:

Fields are editable.

Input validation is performed.

Confirmation appears on successful save.

Priority: Medium
Story Points: 2
Notes:

May require API or local state update logic.

Title:
As a user, I want the changes I make to my profile to be saved, so that my updated details are stored and reflected throughout the app.

Acceptance Criteria:

Changes persist across sessions.

A success message is displayed.

All relevant screens reflect the updated data.

Priority: High
Story Points: 2
Notes:

Synchronize with state and UI.

Title:
As a user, I want my updated name to be displayed in the app's header after I change it in the profile, so that my changes are immediately visible.

Acceptance Criteria:

Header updates automatically.

No page refresh required.

Change persists on navigation.

Priority: Medium
Story Points: 1
Notes:

Observe name change with state listener or binding.

Exercise 6: Habits Page
Title:
As a user, I want to add new habits on the details configuration page so that I can manage and update my habits as needed.

Acceptance Criteria:

Form to add habit is accessible.

Name and color fields are required.

Habit appears in list after creation.

Priority: High
Story Points: 2
Notes:

Requires validation and update to state.

Title:
As a user, I want to delete existing habits so that I can keep my habits up to date.

Acceptance Criteria:

Each habit has a delete option.

Confirmation is shown before deletion.

Habit is removed from list after deletion.

Priority: Medium
Story Points: 2
Notes:

Undo option can be considered.

Title:
As a user, I want to assign a specific color to each habit to make it personal to me.

Acceptance Criteria:

Color picker available in habit creation.

Color appears with habit in UI.

Color persists across sessions.

Priority: Low
Story Points: 1
Notes:

Enhances visual clarity and personalization.

Exercise 7: Reports Page
Title:
As a user, I want to see a report of my weekly habit progress so that I can understand how well I am maintaining my habits.

Acceptance Criteria:

Report page displays summary for the week.

Data is accurate based on completion.

Highlights trends or completion streaks.

Priority: Medium
Story Points: 2
Notes:

Visual and textual data formats both helpful.

Title:
As a user, I want to see a chart of my completed habits for each day of the week so that I can quickly identify trends in my progress.

Acceptance Criteria:

Chart shows daily completion.

Separate color codes for each habit.

Interactive or scrollable chart preferred.

Priority: High
Story Points: 3
Notes:

Consider bar or line chart with Recharts.

Title:
As a user, I want to see both completed and incomplete habits in my report so that I have a comprehensive view of my habit tracking performance.

Acceptance Criteria:

Report lists all habits.

Each habit shows completion status per day.

Allows filtering or toggling.

Priority: Medium
Story Points: 2
Notes:

Data comes from habit tracking records.

Exercise 8: Notifications Page
Title:
As a user, I want to be able to enable or disable notifications for the app, so that I can choose whether or not to receive reminders for my habits.

Acceptance Criteria:

Toggle to turn notifications on/off.

Saves preference persistently.

Notifications stop or start accordingly.

Priority: High
Story Points: 2
Notes:

Ensure background permission is granted.

Title:
As a user, I want to select specific habits to receive notifications for, so that I only get reminders for the habits I am actively working on.

Acceptance Criteria:

List of habits displayed with checkboxes.

Only selected habits trigger notifications.

Changes persist across sessions.

Priority: Medium
Story Points: 2
Notes:

Improve user control and reduce notification fatigue.

Title:
As a user, I want to have the option to receive notifications three times a day (morning, afternoon, evening) for all selected habits, so that I get timely reminders throughout the day to complete my habits.

Acceptance Criteria:

User can set preferred times.

Notifications are scheduled for all selected habits.

Notifications appear at the configured times.

Priority: High
Story Points: 3
Notes:

Use platform-specific notification scheduling (e.g., flutter_local_notifications in Flutter).
