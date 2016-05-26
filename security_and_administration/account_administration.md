# Account administration

##Navigate to Users Tab

Admin can administer all user accounts through the Users Tab on the Home Screen.

**There should only be one dataset storing a list of accounts and roles within the Users dataset. Please do not 'Save as' a second dataset - this creates duplicate users.**

##Open the Users Dataset
In the users dataset you can see a list of all of the accounts that have access to this Tenant

##Add a new account

Add a New Account through the ‘Add Node’ option on the Property Pane.

##Edit properties of the account node

Edit the Properties of the Account Node in the same way you would for any other nodes. There are only three editable properties for an account node:

1.
Login: in principle, email address can be edited, but If there is a mistake in an email address, you cannot amend it using this property – you will need to delete the node or change the ‘Enabled’ value to “false” and re-add the correct login

2.
Enabled: you can select between ‘true’ and ‘false’. To de-activate an account set the Enabled Property to ‘false’ as opposed to deleting the Node itself

3.
Role: most accounts should be set up as a ‘User’ Role, which limits the datasets they can view and edit in the tenant. You can then assign single or multiple permission groups to an individual user.
