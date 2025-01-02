# UserInterFaceSpecs

## Requirements
There will be 3 main components.

1. A row at top with 3 functional components: 
  - New User
  - Hide Disabled User 
  - Save User

2. A list of users with attributes:
  - ID
  - User Name
  - E-mail
  - Enabled

3. Form for saving a new user with attiributes:
   - UserName
   - DisplayName
   - Phone
   - Email
   - User Roles
   - Enables

## General Layout and Flow
Generally, white and blue tones will be used.
Component 1 will always shown at top of the screen. Below it, shown component 2,
covering rest of the screen at the beginning. This component looks like a database table.
It will show names of the attributes at top and below it shows users informations row by row.
Initially all users can be shown in any order.
Some buttons will change this list or order of the list. These are declared bottom at Details Section

When user click '+New User' button, which is part of a Component 1 and located at top right,
There will be shown Component 3, covering rest of the screen like Component 1. It is a form.
After user enters his informations, 'Save User' button, which is partf of a Component 1,
will be looked brighter and user can click on it. User can not click 'Save User' button until
filling all informations. After User click 'Save User' button, Component 1 will be shown again.


## Details

### Details of Component 1
- It will cover the entire screen from left to right, and from top to bottom, 
it will cover an area slightly larger than a normal text size. 
From top to bottom, it can be as much as a row of the 2nd Component in terms of ratio.
Background color, whic is color of this row will be light grey.

- 'New User' component will be a blue button. Inside this button, written "+New User" colored white.
This component will be located at left side of the row

- 'Hide Disabled User' component will be a checkBox. It will be located just to the right of the 'New User' component.
CheckBox located at left, the text 'Hide Disabled User' will be at right.
When user clicked this button, only users shown, whose Enabled attribute 'true' is.

- 'Save User' component will be a button and same color with the 'New User' component.
Inside the button, Written "Save User" colored white.
This component will be located at far right of the row.
This button will be pale blue until the user opens a new form and fills in all the information,
then it will turn bright blue.

### Details of Component 2
- It will look like a database table. First row show attribute names.
- Rows will be in color white and pale one after another.

- Next to 'User Name', 'Email', 'Enabled' attributes, there will be a figur and rows.
When User hit up row in 'UserName' and 'Email', users shown in dictionary order.
When User hit up row in Enabled, users whose Enabled attribute 'true' is, displayed first
For 3 of them, if down row hit, rows will be displayed in reverse order.

- For ID attribute, there will be only up row,
which causes the users displayed in ascending order by ID.


### Details of Component 3

It is a form. There will be gray bar at top and insede 
there will Title with text "New User". 
Under of it there will be attributes, which listed above, and components which get informations from users.

Next to 'UserName', 'Display Name', 'Phone', 'Email' there will be textBoxes.
User enters informations by them.

For UserRoles there will be a bar. When user click on it, a list shown with values:
'Guest', 'Admin', 'SuperAdmin'. User choose one of them.

At the bottom there will be 'Enabled' checkBox.

  




  
