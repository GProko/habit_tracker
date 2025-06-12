
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

---

## Exercise 5: Profile Page

### View Personal Information
**Title:**  
_As a user, I want to view my saved name, username, age, and country on my profile page, so that I can see the details I provided during registration._  
**Acceptance Criteria:**  
1. User's name, username, age, and country are displayed.  
2. Information is fetched from the user profile.  
3. Fields are read-only by default.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Allows the user to verify their information.

### Edit Personal Information
**Title:**  
_As a user, I want to update my name, username, age, and country on my profile page, so that I can keep my information up to date._  
**Acceptance Criteria:**  
1. User can edit the displayed information.  
2. Changes are saved upon submission.  
3. Validation occurs for required fields (e.g., username length).  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- Important for profile customization.

### Save Updated Information
**Title:**  
_As a user, I want the changes I make to my profile to be saved, so that my updated details are stored and reflected throughout the app._  
**Acceptance Criteria:**  
1. Changes are saved to the backend.  
2. Confirmation is shown after saving.  
3. Information is updated immediately in the app.  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- Requires data synchronization.

### Update Name in Header
**Title:**  
_As a user, I want my updated name to be displayed in the app's header after I change it in the profile, so that my changes are immediately visible._  
**Acceptance Criteria:**  
1. Header updates after profile change.  
2. Change is reflected across all pages.  
3. Header is re-rendered after user saves changes.  
**Priority:** Medium  
**Story Points:** 2  
**Notes:**  
- Visual consistency is important for user satisfaction.

---

## Exercise 6: Habits Page

### Add a New Habit
**Title:**  
_As a user, I want to add new habits on the details configuration page, so that I can manage and update my habits as needed._  
**Acceptance Criteria:**  
1. User can enter a new habit’s name and details.  
2. Habit is saved to the user's profile.  
3. Habit appears in the list of active habits.  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- Users should be able to add as many habits as they like.

### Delete a Habit
**Title:**  
_As a user, I want to delete existing habits, so that I can keep my habits up to date._  
**Acceptance Criteria:**  
1. User can delete any habit from the habit list.  
2. Deleted habit is removed from the user's profile.  
3. Deletion is confirmed via a dialog box.  
**Priority:** Medium  
**Story Points:** 2  
**Notes:**  
- Deleting a habit should be a permanent action.

### Personalize a Habit with Color
**Title:**  
_As a user, I want to assign a specific color to each habit to make it personal to me._  
**Acceptance Criteria:**  
1. User can select a color for each habit.  
2. The color is saved and displayed in the habit list.  
3. Color selection is visually clear and easy to change.  
**Priority:** Low  
**Story Points:** 2  
**Notes:**  
- Color can help with habit differentiation.

---

## Exercise 7: Reports Page

### View Weekly Reports
**Title:**  
_As a user, I want to see a report of my weekly habit progress, so that I can understand how well I am maintaining my habits._  
**Acceptance Criteria:**  
1. Weekly report shows completed and pending habits.  
2. Report covers all 7 days of the week.  
3. Report can be downloaded or shared.  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- This feature is key to habit tracking.

### Visualize Completed Habits
**Title:**  
_As a user, I want to see a chart of my completed habits for each day of the week, so that I can quickly identify trends in my progress._  
**Acceptance Criteria:**  
1. Completed habits are represented on a chart.  
2. User can click on each day to view detailed progress.  
3. Chart is updated in real time.  
**Priority:** Medium  
**Story Points:** 3  
**Notes:**  
- Helps in tracking consistency visually.

### View All Habits
**Title:**  
_As a user, I want to see both completed and incomplete habits in my report, so that I have a comprehensive view of my habit tracking performance._  
**Acceptance Criteria:**  
1. Report shows a breakdown of all habits (completed/incomplete).  
2. Habits can be filtered by status.  
3. The report updates in real time as habits are tracked.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Provides insight into both successes and areas for improvement.

---

## Exercise 8: Notifications Page

### Enable/Disable Notifications
**Title:**  
_As a user, I want to be able to enable or disable notifications for the app, so that I can choose whether or not to receive reminders for my habits._  
**Acceptance Criteria:**  
1. User can toggle notifications on/off.  
2. Changes take effect immediately.  
3. User can enable/disable notifications per habit.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Critical for user control over reminders.

### Add Habits for Notifications
**Title:**  
_As a user, I want to select specific habits to receive notifications for, so that I only get reminders for the habits I am actively working on._  
**Acceptance Criteria:**  
1. User can select habits to receive notifications for.  
2. Only selected habits trigger notifications.  
3. User can update selections anytime.  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- Allows for personalized reminder settings.

### Set Notification Times
**Title:**  
_As a user, I want to have the option to receive notifications three times a day (morning, afternoon, evening) for all selected habits, so that I get timely reminders throughout the day to complete my habits._  
**Acceptance Criteria:**  
1. User can select specific times for notifications (morning, afternoon, evening).  
2. Notifications are sent at selected times.  
3. Times can be edited or removed.  
**Priority:** Medium  
**Story Points:** 2  
**Notes:**  
- Customizable reminder times improve user engagement.

---

## Exercise 5: Profile Page

### View Personal Information
**Title:**  
_As a user, I want to view my saved name, username, age, and country on my profile page, so that I can see the details I provided during registration._  
**Acceptance Criteria:**  
1. Profile displays all stored personal details.  
2. Information is read-only by default.  
3. Accurate reflection of registration data.  
**Priority:** Medium  
**Story Points:** 1  
**Notes:**  
- Data should be securely retrieved.

### Edit Personal Information
**Title:**  
_As a user, I want to update my name, username, age, and country on my profile page, so that I can keep my information up to date._  
**Acceptance Criteria:**  
1. Fields become editable when edit is initiated.  
2. Validation is enforced on update.  
3. Form displays feedback after update.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Consider required vs optional fields.

### Save Updated Information
**Title:**  
_As a user, I want the changes I make to my profile to be saved, so that my updated details are stored and reflected throughout the app._  
**Acceptance Criteria:**  
1. Changes persist after save.  
2. Confirmation message is shown.  
3. Update propagates to all dependent screens.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Avoid overwriting other fields accidentally.

### Update Name in Header
**Title:**  
_As a user, I want my updated name to be displayed in the app's header after I change it in the profile, so that my changes are immediately visible._  
**Acceptance Criteria:**  
1. Header reflects updated name.  
2. Change appears without needing a refresh.  
3. Old name is removed from memory.  
**Priority:** Medium  
**Story Points:** 1  
**Notes:**  
- Test across all screens where header appears.

---

## Exercise 6: Habits Page

### Add a New Habit
**Title:**  
_As a user, I want to add new habits on the details configuration page so that I can manage and update my habits as needed._  
**Acceptance Criteria:**  
1. Add habit button leads to a form.  
2. Form accepts name and optional color.  
3. New habit appears on the homepage.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Default values should be handled properly.

### Delete a Habit
**Title:**  
_As a user, I want to delete existing habits so that I can keep my habits up to date._  
**Acceptance Criteria:**  
1. Delete option is clearly visible.  
2. Confirmation is required before delete.  
3. Deleted habit is removed from all displays.  
**Priority:** High  
**Story Points:** 1  
**Notes:**  
- Must prevent accidental deletion.

### Personalize a Habit with Color
**Title:**  
_As a user, I want to assign a specific color to each habit to make it personal to me._  
**Acceptance Criteria:**  
1. Color picker is available on add/edit.  
2. Habit reflects chosen color in UI.  
3. Color setting persists.  
**Priority:** Medium  
**Story Points:** 1  
**Notes:**  
- Useful for visual differentiation.

---

## Exercise 7: Reports Page

### View Weekly Reports
**Title:**  
_As a user, I want to see a report of my weekly habit progress so that I can understand how well I am maintaining my habits._  
**Acceptance Criteria:**  
1. Reports include all tracked habits.  
2. Time frame is clearly indicated.  
3. Weekly data is summarized in a user-friendly format.  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- Week starts on Monday (or configurable).

### Visualize Completed Habits
**Title:**  
_As a user, I want to see a chart of my completed habits for each day of the week so that I can quickly identify trends in my progress._  
**Acceptance Criteria:**  
1. Each habit shown with daily status.  
2. Visualization is easy to interpret (bar/pie/line).  
3. Updates dynamically as habits are completed.  
**Priority:** Medium  
**Story Points:** 2  
**Notes:**  
- Color-coding should match habit color.

### View All Habits
**Title:**  
_As a user, I want to see both completed and incomplete habits in my report so that I have a comprehensive view of my habit tracking performance._  
**Acceptance Criteria:**  
1. Both states clearly marked.  
2. Incomplete entries highlighted distinctly.  
3. Data is filterable by day or habit.  
**Priority:** Medium  
**Story Points:** 2  
**Notes:**  
- Helps with end-of-week reviews.

---

## Exercise 8: Notifications Page

### Enable/Disable Notifications
**Title:**  
_As a user, I want to be able to enable or disable notifications for the app, so that I can choose whether or not to receive reminders for my habits._  
**Acceptance Criteria:**  
1. Global toggle to enable/disable notifications.  
2. Saves state between sessions.  
3. Affects all notification behavior in the app.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Requires permission management on mobile.

### Add Habits for Notifications
**Title:**  
_As a user, I want to select specific habits to receive notifications for, so that I only get reminders for the habits I am actively working on._  
**Acceptance Criteria:**  
1. List of habits shows toggle for each.  
2. Saves selected notification habits.  
3. Only selected habits trigger reminders.  
**Priority:** Medium  
**Story Points:** 2  
**Notes:**  
- Can be extended to batch select.

### Set Notification Times
**Title:**  
_As a user, I want to have the option to receive notifications three times a day (morning, afternoon, evening) for all selected habits, so that I get timely reminders throughout the day to complete my habits._  
**Acceptance Criteria:**  
1. Three time slots configurable.  
2. Applies to all selected habits.  
3. Notification triggers respect device settings.  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- Support for time zone handling required.

---

## Exercise 5: Profile Page

### View Personal Information
**Title:**  
_As a user, I want to view my saved name, username, age, and country on my profile page, so that I can see the details I provided during registration._  
**Acceptance Criteria:**  
1. Personal details are displayed accurately.  
2. Page loads with data fetched from the user’s record.  
3. Information is read-only until edit is initiated.  
**Priority:** Medium  
**Story Points:** 1  
**Notes:**  
- Ensures transparency of stored data.

### Edit Personal Information
**Title:**  
_As a user, I want to update my name, username, age, and country on my profile page, so that I can keep my information up to date._  
**Acceptance Criteria:**  
1. Fields become editable when edit mode is activated.  
2. Inputs validate correct formats.  
3. Changes are saved only upon confirmation.  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- Includes validation and error feedback.

### Save Updated Information
**Title:**  
_As a user, I want the changes I make to my profile to be saved, so that my updated details are stored and reflected throughout the app._  
**Acceptance Criteria:**  
1. Updated info is stored in the database.  
2. Confirmation message is displayed.  
3. Other parts of the app reflect changes immediately.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Syncs updates across views.

### Update Name in Header
**Title:**  
_As a user, I want my updated name to be displayed in the app's header after I change it in the profile, so that my changes are immediately visible._  
**Acceptance Criteria:**  
1. Header updates in real time after save.  
2. Page refresh is not required.  
3. Name appears consistently across views.  
**Priority:** Medium  
**Story Points:** 1  
**Notes:**  
- Ensures a responsive UX.

---

## Exercise 6: Habits Page

### Add a New Habit
**Title:**  
_As a user, I want to add new habits on the details configuration page so that I can manage and update my habits as needed._  
**Acceptance Criteria:**  
1. Users can enter a habit name and details.  
2. New habit is added to the list and tracked.  
3. Validation ensures no duplicates or blanks.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Could use modal or inline entry.

### Delete a Habit
**Title:**  
_As a user, I want to delete existing habits so that I can keep my habits up to date._  
**Acceptance Criteria:**  
1. Each habit has a delete option.  
2. Confirm delete before removal.  
3. Habit is removed from all tracking.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Includes confirmation dialog.

### Personalize a Habit with Color
**Title:**  
_As a user, I want to assign a specific color to each habit to make it personal to me._  
**Acceptance Criteria:**  
1. Users choose from a color palette.  
2. Color shows on habit card or tracker.  
3. Color is saved and persists.  
**Priority:** Medium  
**Story Points:** 1  
**Notes:**  
- Enhances visual organization.

---

## Exercise 7: Reports Page

### View Weekly Reports
**Title:**  
_As a user, I want to see a report of my weekly habit progress so that I can understand how well I am maintaining my habits._  
**Acceptance Criteria:**  
1. Data is grouped by habit and day.  
2. Displays summaries or trends.  
3. Updates as habits are tracked.  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- Could be in text or visual format.

### Visualize Completed Habits
**Title:**  
_As a user, I want to see a chart of my completed habits for each day of the week so that I can quickly identify trends in my progress._  
**Acceptance Criteria:**  
1. Chart type (bar/pie/line) shows daily counts.  
2. Visually distinct completed/incomplete.  
3. Accessible and clear labeling.  
**Priority:** Medium  
**Story Points:** 2  
**Notes:**  
- Adds insight into consistency.

### View All Habits
**Title:**  
_As a user, I want to see both completed and incomplete habits in my report so that I have a comprehensive view of my habit tracking performance._  
**Acceptance Criteria:**  
1. Report includes all habits.  
2. Clear indicator of status.  
3. Filters or legends for clarity.  
**Priority:** Medium  
**Story Points:** 2  
**Notes:**  
- Useful for self-analysis.

---

## Exercise 8: Notifications Page

### Enable/Disable Notifications
**Title:**  
_As a user, I want to be able to enable or disable notifications for the app, so that I can choose whether or not to receive reminders for my habits._  
**Acceptance Criteria:**  
1. Toggle switch for notifications.  
2. Changes take effect immediately.  
3. App respects user preference consistently.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Must comply with OS-level permissions.

### Add Habits for Notifications
**Title:**  
_As a user, I want to select specific habits to receive notifications for, so that I only get reminders for the habits I am actively working on._  
**Acceptance Criteria:**  
1. Checklist or selection UI available.  
2. Habits are tied to notification schedule.  
3. Selection is saved persistently.  
**Priority:** High  
**Story Points:** 2  
**Notes:**  
- Avoid overwhelming the user.

### Set Notification Times
**Title:**  
_As a user, I want to have the option to receive notifications three times a day (morning, afternoon, evening) for all selected habits, so that I get timely reminders throughout the day to complete my habits._  
**Acceptance Criteria:**  
1. User can set time slots.  
2. Notifications are triggered at set times.  
3. Configurable per habit or globally.  
**Priority:** High  
**Story Points:** 3  
**Notes:**  
- Uses system alarms or background services.
