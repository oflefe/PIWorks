# User Management Screen 
## Header From Left to Right
- New User Button: "+ New User" 
- Checkbox: "Hide Disabled User" will hide disabled users from user table 
- Save User Button = "Save User" 
## User Table 
### Layout
- Hide unless logged in as admin or superadmin
- Left Half of screen under header
- 4 column layout with columns "ID" "User Name" "Email" "Enabled" listing corresponding values at the columns
### Functionality
- Columns have buttons to sort ascending or descending 
- Higlight the clicked user 
- Add saved users to the list 
- Pull values from database
- User ID will be last created user's User ID incremented by 1.
## New User Form 
### Layout
- Right half of screen under header
- Hide until "+ New User" has been clicked and hide after user is saved. 
- Display title "New User" at the top of form, aligned to the left in New User Form area
- Text input fields for Username, Display Name, Phone, Email, User Roles, Enabled. 
- Input field labels have the following form: "(field_name):" 
- Input field labels are aligned with the form title
- Input field boxes are aligned to the right
### Functionality
- Flashing text bar when clicked on the value fields to type in values.
- User Roles is a drop-down menu with possible options "Guest" "Admin" "SuperAdmin"
- Email and phone fields will validate entered values to check if correct format has been entered. 
- Email correct format: (username)@(email provider).(website extension)
- Phone correct format is country code plus 10 digits
- Phone number will display as +XX-XXX-XXX-XX-XX
- Username field will validate only if username is not already in the user list
- Enabled checkbox will be checked and unchecked (toggle) when clicked and will determine whether user has enabled=true on the user list.
