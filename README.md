# React homework template

This project was created with
[Create React App](https://github.com/facebook/create-react-app). To get
acquainted and configure additional features
[refer to documentation](https://facebook.github.io/create-react-app/docs/getting-started).

## Contact Book

Write an application to store your phonebook contacts.

### Step 1

The application should consist of a form and a list of contacts. In the current
step, implement adding a contact name and displaying a list of contacts. The
application should not save contacts between different sessions (page
refresh).<br> Each contact must be an object with properties name and id. To
generate identifiers, use any suitable package, e.g. nanoid. After completing
this step, the application should look something like this.

### Step 2

Expand the functionality of the app by allowing users to add numbers phone
numbers.

### Step 3

Add a search field that you can use to filter your contact list by name.

The search field is a formless intuplet whose value is written to the state
(controlled item). The filtering logic should be case insensitive.

### Step 4

If your application is implemented in a single component App, perform
refactoring by separating the appropriate parts into separate components. In the
state of the root component App will leave only the contacts and filter
properties. <br> Four components are enough: add contact form, contact list
contact list, contact list item, and search filter.

### Step 5

Deny the user the ability to add contacts whose names are already in the
phonebook. If you try to do so, print alert with a warning.

### Step 6

Extend the functionality of the app by allowing the user to delete previously
saved contacts.
