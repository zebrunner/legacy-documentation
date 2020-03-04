# Dashboards and widgets

## Work with dashboards
Dashboard in Zebrunner is a special page that displays widgets with main analytical info on your test results.

A system General dashboard is displayed when you open Zebrunner (or press the “Z” button in the upper-left corner of the window). General is not editable – you cannot change its name or make it hidden.

In addition to General, you can create other dashboards to systemize widgets according to your needs.

**What can you do with dashboards?**

* [Create Dashboard](### Create dashboard)
* Create Dashboard 
* Edit Dashboard
* Hidden Dashboards
* Delete Dashboard
* Send Dashboard via email
* Search for Dashboard by its name
* Change order of dashboards

### Create dashboard
To create a new dashboard, perform the following steps:

1. Navigate to the side menu and click the **“Dashboards”** icon. Then press the **“+Add dashboard"** button.
2. The **“New Dashboard”** popup will appear.
3. Enter a name for a new dashboard.
4. Click the **"Create"** button.

Now you can add widgets to the new dashboard.

### Edit dashboard
To edit a dashboard, perform the following steps:

1. Navigate to the side menu and click the **“Dashboards”** icon. Choose the necessary dashboard.
2. Click the pencil icon in the upper-right corner of the window.
3. The **“Edit Dashboard”** popup will appear.
4. Make the necessary changes to the dashboard (except for General):
   * edit the name of the dashboard;
   * make the dashboard visible or hidden by clicking the **“Hidden”** switch (only if you have “View hidden dashboards” permission).
5. Click the **“Save”** button.

The dashboard will be displayed with updates.

**Optional:** If you have **“Modify widgets”** and **“Modify dashboards”** permissions, you can edit a dashboard by applying a certain parameter to all the widgets on a dashboard (instead of setting it for each widget manually).

For example, you want to see your test results on a dashboard for the Chrome browser only.

For this perform the following steps:

1. After the **“Edit Dashboard”** popup appears, enter the parameter **“BROWSER”** (in uppercase) to the **“Key”** field and “chrome” to the **“Value”** field (in lowercase).
2. Click **“Add”** and **“Save”**.
3. Refresh the page.

The dashboard will be displayed with updated results.

**Note:** You can apply several parameters to a dashboard. But you can add only 1 value to a parameter.

### Hidden dashboards
Dashboards in Zebrunner can be visible or hidden.

Hidden dashboards are useful when:

* You need to test and adjust experimental widgets to dashboards;
* You want to track your automation team performance on a special dashboard;
* You’d like to hide a dashboard from other users.

**Note:** You need “View hidden dashboards” permission to make a dashboard hidden. Otherwise, you will not see this option.

To make a dashboard hidden, open **“New dashboard”** or **“Edit dashboard”** popup and turn on the switch **“Hidden”**.

### Delete dashboard
To delete a custom dashboard, perform the following steps:

1. Navigate to the side menu and click the “Dashboards” icon. Choose the necessary dashboard.
2. Click the pencil icon in the upper-right corner of the window.
3. The “Edit Dashboard” popup will appear.
4. Press the “Delete” button.

The dashboard and attached widgets will be deleted.

**Note:** You cannot delete the General dashboard.

### Send dashboard via email
To send a dashboard via email, perform the following steps:

1. Navigate to the side menu and click the “Dashboards” icon. Choose the necessary dashboard.
2. Click the arrow icon in the upper-right corner of the window.
3. The **“Email”** popup will appear.
4. The **“Name”** and **“Text”** fields are filled by default, still you can change them.
5. Fill in the **“Recipients”** field (unlimited number of emails per time).
6. Press the **“Send”** button.

A popup message **“Email was successfully sent”** will appear in the lower-right corner of the window.

### Search for dashboard
To search for a dashboard, perform the following steps:

1. Navigate to the side menu and click the “Dashboards” icon.
2. Go to the “Search” field and enter the name/part of the name of a dashboard.
3. Choose the necessary dashboard.

### Change the order of dashboards
To change the order of dashboards, perform the following steps:

1. Navigate to the side menu and click the **“Dashboards”** icon.
2. Grab a dashboard with a hand cursor by clicking the six-dot button.
3. Drag and drop the chosen dashboard to the necessary place.

Dashboards will be displayed in a new order.


## Work with widgets

Widgets contain special graphical control elements that analyze and display your automation test results overview and other data.

You can perform all actions with widgets listed below on the **"Dashboards"** page.

* Create widget
* Edit widget
* Delete widget
* Change widget placement or resize widget
* Send widget via email

### Create widget
To create a new widget, perform the following steps:

1. Click the **"+ NEW WIDGET"** button in the top-right corner of the **“Dashboards”** page.
2. The **Widget wizard** will be opened.
3. Choose a template for a widget (see them here) or go to the **“Choose from existing widgets”** section with a set of predefined widgets (look through them here). To simplify the process, fill in the search field with a name or part of a widget name.
4. Click on a widget to see its preview.
5. If you’ve chosen a template for a widget:
  * Click the **“Next”** button.
  * Set the necessary parameters. There are two types of them: basic and advanced ones. To see advanced parameters, click **“Show more”**.
  * Click **“Next”** and enter a name and description of the future widget.
6. Click the **“Add”** button.

The created widget will be automatically added to a dashboard.

When you’ve added an existing widget to a dashboard, it will be marked with the word **"Added"** and a checkmark.

### Edit widget
To edit a widget, perform the following steps:

1.	Click the **Widget menu** (3-dot button) in the upper-right corner of a widget.
2.	Press **“Edit widget”.**
3.	The **Widget wizard** will be opened.
4.	Apply the necessary changes in widget settings.
5.	Click the **“Save”** button.

The widget will be displayed with updates.

### Remove widget from dashboard
To remove a widget from a dashboard, perform the following steps:

1.	Click the **Widget menu** (3-dot button) in the upper-right corner of a widget.
2.	Press **“Remove from dashboard”.**

A widget will be removed from a dashboard, but the information will not be lost. You can create a widget with the same settings later, actual data will be displayed.

### Send widget by email
To send a widget via email, perform the following steps:

1.	Click the **Widget menu** (3-dot button) in the upper-right corner of a widget.
2.	Press **“Send by email”.**
3.	The **“Email”** popup will appear.
4.	The **“Name”** and **“Text”** fields will be filled by default, still you can change them.
5.	Fill in the **“Recipients”** field (unlimited number of emails per time).
6.	Press the **“Send”** button.
7.	Pop-up message **“Email was successfully sent”** will appear in the lower-right corner of the window.

### Change widget placement or resize widget
To change a widget placement within a dashboard area, perform the following steps:

1.	Press the **“Widget placement”** button in the upper-right corner of the window.
2.	Drag and drop a widget to the selected position.
3.	When you move the widget to the area with enough space, the system marks this place with a dotted line.
4.	Press the **“Apply”** button.
 
Every widget has a basic size.

To resize a widget, perform the following steps:

1.	Press the **“Widget placement”** button in the upper-right corner of the window.
2.	Hover the mouse cursor over the widget. The system will show resizing arrows.
3.	Grab the arrow with the cursor and drag it to the desired width and height.
4.	Press the **“Apply”** button.
