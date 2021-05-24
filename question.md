# User Management Screen

## Purpose 
The user should be able to: 
- view all users in the system in table format with the following information: 
    - ID
    - Username 
    - Email 
    - Enabled 
- sort all user information with sort buttons via table headers of: 
    - Username 
    - Email 
    - Enabled
- filter records of the users in the table via headers of: 
    - username
    - email 
    - enabled
    - ID
- add new users to the system using the New User button which creates a pop-up dialog field with the following fields to be filled and the Save button which saves the data in the dialog boxes:
    - Username 
    - Display name
    - Phone 
    - Email
    - User roles as a dropdown menu with options Guest, Admin, Superadmin
    - Enabled button

- ID : integer type - unique number to represent each user
- email : varchar type - unique email to represent each user
- username : varchar type - unique username to represent each user
- enabled : boolean type - boolean value used to determine the activity of a user in the system
- phone : varchar type - unique phone number to represent each user
- display name : varchar type - unique display name to represent each user on the system
- user-roles name : varchar type - used to determine the role of each user on the system and their access in the system

- hide disabled users using a checkbox


## Navigation 
Review, sort or filter the data of all the users in the system. Add new users into the sytem.

## Data 
The data available on this page will comprise of integer for ID, varchar for Username and email and lastly, boolean for Enabled.


## Interaction
Press the "New User" button to add new users to the system. After the dialog box will pop-up, add the details to the relevant dialog boxes.

Press the "Save" button to save the new users to the system.

Press the filter icon next to username, email, enabled, ID headers to filter the results. 

Press the ascending or descending buttons to sort data according to desired qualities.



