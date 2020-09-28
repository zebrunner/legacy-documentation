# Dashboards

Dashboard in Zebrunner is a special page that displays widgets with main analytical info on your test results.

A system **General** dashboard is displayed when you open Zebrunner (or press ![Zebrunner](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/zebrunner_icon.png?raw=true) in the upper-left corner of the window). General is not editable – you cannot change its name, make it hidden, delete it or add widgets.

In addition to General, you can create other dashboards to systemize widgets according to your needs.

**What can you do with dashboards?**

* Create Dashboards
* Edit Dashboards
* Make Dashboards Hidden
* Delete Dashboards
* Send Dashboards via email
* Search for Dashboards by name
* Change order of dashboards

## Create dashboard
To create a new dashboard, perform the following steps:

1. Navigate to the side menu and click the **“Dashboards”** icon ![Dashboards](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/dashboards_icon.png?raw=true). Then press the **“+Add dashboard"** button. 
2. The **“New Dashboard”** popup will appear.
3. Enter a name of a new dashboard.
4. Click **"Create"**.

Now you can add widgets to the new dashboard.

![Create Dashboard](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/create_dashboard.gif?raw=true)

## Edit dashboard
To edit a dashboard, perform the following steps:

1. Navigate to the side menu and click the **“Dashboards”** icon ![Dashboards](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/dashboards_icon.png?raw=true). Choose the necessary dashboard.
2. Click ![Edit Dashboard](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/edit_dashboard_icon.png?raw=true) in the upper-right corner of the window.
3. The **“Edit Dashboard”** popup will appear.
4. Make the necessary changes to the dashboard (except for General): edit the name of the dashboard; make the dashboard visible or hidden by clicking the **“Hidden”** switch (only if you have the **“View hidden dashboards”** permission)(read more [here](https://zebrunner.github.io/documentation/guide/dashboards/#hidden-dashboards)).
5. Click **“Save”**.

The dashboard will be displayed with updates.

![Edit Dashboard](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/edit_dashboard.png?raw=true) 

**Optional:** If you have **“Modify widgets”** and **“Modify dashboards”** permissions, you can edit a dashboard by applying a certain parameter to all the widgets on a dashboard (instead of setting it for each widget manually).

For example, you want to see your test results on a dashboard for the Chrome API only.

For this, perform the following steps:

1. After the **“Edit Dashboard”** popup appears, enter the parameter **“PLATFORM”** (in uppercase) to the **“Key”** field and **“api”** (in lowercase) to the **“Value”** field.
2. Click **“Add”** and **“Save”**.
3. Refresh the page.

The dashboard will be displayed with updates.

**Note:** You can apply several parameters (keys) to a dashboard. But you can add only 1 value to a parameter.

![Key and Value](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/key_and_value.png?raw=true)

## Hidden dashboards
Dashboards in Zebrunner can be visible or hidden.

Hidden dashboards are useful when:

* You need to test and adjust experimental widgets to a dashboard;
* You want to track your automation team performance on a special dashboard;
* You’d like to hide a dashboard from other users.

**Note:** You need the **“View hidden dashboards”** permission to make a dashboard hidden. Otherwise, you will not see this option.

To make a dashboard hidden, open **“New dashboard”** or **“Edit dashboard”** popup and click the  on the ![Hidden Dashboard Icon](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/hidden_dashboard_icon.png?raw=true) icon.

![Hidden Dashboards](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/hidden_dashboard.gif?raw=true)

## Delete dashboard
To delete a dashboard, perform the following steps:

1. Navigate to the side menu and click the **“Dashboards”** icon ![Dashboards](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/dashboards_icon.png?raw=true). Choose the necessary dashboard.
2. Click ![Delete Dashboard](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/edit_dashboard_icon.png?raw=true) in the upper-right corner of the window.
3. The **“Edit Dashboard”** popup will appear.
4. Press **“Delete”.**
5. Submit the action.

The dashboard and attached widgets will be removed.

**Note:** You cannot delete the General dashboard.

![Delete Dashboard](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/delete_dashboard.png?raw=true)

## Send dashboard via email
To send a dashboard via email, perform the following steps:

1. Navigate to the side menu and click the **“Dashboards”** icon ![Dashboards](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/dashboards_icon.png?raw=true). Choose the necessary dashboard.
2. Click ![Send by Email](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/send_dashboard_by_email_icon.png?raw=true) in the upper-right corner of the window.
3. The **“Email”** popup will appear.
4. The **“Name”** and **“Text”** fields are filled by default, still you can change them.
5. Fill in the **“Recipients”** field (unlimited number of emails per time).
6. Press the **“Send”** button.

A popup message **“Email was successfully sent”** will appear in the lower-right corner of the window.

![Send Dashboard via Email](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/send_dashboard_via_email.png?raw=true)

## Search for dashboard
To search for a dashboard, perform the following steps:

1. Navigate to the side menu and click the **“Dashboards”** icon ![Dashboards](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/dashboards_icon.png?raw=true).
2. Go to the **“Search”** field and enter the name/part of the name of a dashboard.
3. Choose the necessary dashboard.

![Search for Dashboard](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/search_for_dashboard.gif?raw=true)

## Change the order of dashboards
To change the order of dashboards, perform the following steps:

1. Navigate to the side menu and click the **“Dashboards”** icon ![Dashboards](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/dashboards_icon.png?raw=true).
2. Grab a dashboard with a hand cursor by clicking ![Change the order](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/icon_six_dot.png?raw=true).
3. Drag and drop the chosen dashboard to the necessary place.

Dashboards will be displayed in a new order.

![Change the Order of Dashboards](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/change_order_of_dashboards.gif?raw=true)
