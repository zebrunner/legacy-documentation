# User management

There are 2 roles in the application: **Admin** and **User**. Each of them has a set of predefined permissions.

By default, **Admins** have the following permissions:

* **Dashboards:** Modify dashboards, Modify widgets
* **Test runs:** Modify test runs, Test runs CI, Modify tests
* **Users:** View users
* **Projects:** Modify projects
* **Invitations:** Invite Users, Modify invitations
* **Launchers:** Modify launchers, View launchers
* **Billing:** Payment methods, Invoices.

**Users** have the following permissions:

* **Test runs:** Modify test runs, Test runs CI, Modify tests
* **Projects:** Modify projects
* **Launchers:** Modify launchers, View launchers


## Users

**Users page** shows all the users registered in the company.

To access the Users page, navigate to the side menu and click the **“User management”** icon, then press **“Users”.**

**Note:** You need **“View users”** permission to see this page!

On the Users page, for every user you can see:

* ID
* Username 
* Email
* First/Last name
* Status (active, inactive)
* Source (LDAP, internal) integration ldap must be turned on
* Registration date.

Go to the **User settings** (the 3-dot button beside the user name), press **“Performance”**, and you will be redirected to a personal dashboard displaying the performance of a chosen user.

## Invitations

You can invite users to your company on the **Invitations page.**

To access the Invitations page, navigate to the side menu and click the **“User management”** icon, then press **“Invitations”.**

**Note:** You need **“Invite users”** permission to see this page!

On the Invitations page, you can see the list of all invitations sent in your company 
Use the Search field at the top of the page to find the necessary invitation.

### Invite user
To invite a user, perform the following steps:

1. Press the **“+Invite user"** button.
2. The **“Invite users”** popup will appear.
3. Choose a group to add user(s): **Admins** or **Users.**
4. Enter the email(s). You can enter an unlimited number of emails at a time.
5. Press **“Invite”.**

Invitations will be sent to the specified emails. Users need to accept the invitation, after that you will see the **ACCEPTED** status in front of the user name. Otherwise, the **PENDING** status will be displayed.

### Manage invitations
Invitation status **ACCEPTED**: If you click on the invitation’s menu and select “Profile”, you will be redirected to the Users page.

Invitation status **PENDING**: By clicking on the invitation’s menu, you can:

* Copy the link and share it with the user.
* Resend the invitation.
* Revoke the invitation - the invited user will not be able to use this link anymore.

