## Requirements

### Functional Requirements
#### Interface
 - System should display all users that are saved.
 - System should display a user.
 - System shall allow to hide users that are not enabled.
 - System should allow adding new users.
 - System should allow updating/editing users.
 - System should have a panel for adding new users.
 - When there is an error system should display it to the user. 
 

#### User
- User should have a username.
- User should have a display name.
- User should have a phone number.
- User should have an email address.
- User should have one of theese three roles: Guest/Admin/SuperAdmin.
- User should have boolean enabled value 
###

### UI Requirements
 #### New User Interface
This indicates the requirements of new user form.
- System should have a header writing new user that indicates the purpose of the menu.
- System should have a textfield requesting user name.
- System should have a textfield requesting display name.
- System should have a textfield requesting phone number.
- System should have a textfield requesting email address.
- System should have a select menu with possible selections being: Guest/Admin/SuperAdmin.
- System should have a checkmark to state whether the user is enabled or not.
- All inputs should have labels indicating what they are.

#### Navbar Interface
- System should have a new user button on click it should open the new user menu .
- System should have a save user button on click it should add user to the table according to the inputs of new user form.
- System should have a checkmark with label "Hide Disabled User" that hides the users with enabled:false value.

 #### New User Interface
This indicates the requirements of new user form.
- System should have a header writing new user that indicates the purpose of the menu.
- System should have a textfield requesting user name.
- System should have a textfield requesting display name.
- System should have a textfield requesting phone number.
- System should have a textfield requesting email address.
- System should have a select menu with possible selections being: Guest/Admin/SuperAdmin.
- System should have a checkmark to state whether the user is enabled or not.
- All inputs should have labels indicating what they are.

#### User Display Interface
This indicates the requirements of users list.
- System should display users as a table where id, user name, e-mail and enabled value are the columns and users are rows.
- System should have filtering symbol on click it should open filtering menu.
- System should open a update/edit user menu with values loaded when a row containing user is clicked.
- System should indicate the last added/edited or clicked row by changing it's background.
