# Test runs

The **Test runs page** allows you to launch tests from your GitHub repository, see detailed test results in real time and on a test run finish.

To access the Test runs page, go to the side menu and click on the **Test runs** icon. All the actions with test runs are performed on this page.

## Test launches

To start running tests, you need to add your GitHub repository. Or choose our Carina demo repository to try out the Zebrunner testing process (the option is available while you are creating your company).

### Add repository

To add a new repository, perform the following steps:

1. On the Test runs page, click the **“Test launcher”** button.
2. The **Launcher wizard** will be opened.
3. Click the **“+Add repo”** button.
4. Provide valid credentials for your GitHub account (select the organization of your user and the repository that contains automation tests).
5. Press **“Add”.**
6. Select the automation server and the branch.
7. Press **“Scan”.** The scanner will pick up all the test XML files and create a launcher template for every XML. It may take a few minutes to complete this task.
8. When you see the **“Done”** message, click **“Back to list”.**

Multiple launchers will be created for API, web, and mobile tests.

### Remove repository

To remove a repository, perform the following steps: 

1. On the Test runs page, click the **“Test launcher”** button.
2. The **Launcher wizard** will be opened.
3. Click the gear button beside the repository name.
4. Press **“Delete repo”** at the bottom of the wizard.

The repository will be removed from the list.

### Provide branch for automatic scanner

To provide a branch for automatic scanner, perform the following steps: 

1. On the Test runs page, click the **“Test launcher”** button.
2. The **Launcher wizard** will be opened.
3. Click the gear button beside the repository name.
4. Choose the branch.
5. Press **“Scan”.**

### Create launcher manually

To create a test launcher manually, perform the following steps:

1. On the Test runs page, click the **“Test launcher”** button.
2. The **Launcher wizard** will be opened.
3. Click the **“+”** button beside the repository name.
4. Create a new template specifying the template name, choosing the platform and the template, adding or removing arguments.
5. Press **“Add”.**

The new launcher template will be added with a tag **“Manual creation” (“M”).**

### Launch test run

To launch a test run, perform the following steps:

1. On the Test runs page, click the **“Test launcher”** button.
2. The **Launcher wizard** will be opened.
3. Choose the necessary test launch from the list.
4. Select the test automation server (you will see this option the first time you open a new repository).
5. Select the type of a test run, browser name and its version. 
6. The section below is dedicated to parameterization of your automation code. Select a branch, environment, thread count, emails and other parameters.
7. Add additional parameters by clicking the **“Edit”** button (pencil icon at the top of the wizard).
8. Press **“Launch”.**

The test run will be in the compilation state.
After it switches to **“In-progress”** (marked blue), you can track the automation results in real time.

### Remove launcher

To remove a launcher, perform the following steps:

1. On the Test runs page, click the **“Test launcher”** button.
2. The **Launcher wizard** will be opened.
3. Select the launcher you would like to remove.
4. Click the **“Edit”** button (pencil icon) at the top of the wizard.
5. Press **“Delete”.**

The launcher will be removed from the list.

## Test run results

On the Test runs page, you can see all the test runs that have been executed recently. Moreover, view test run details, logs and video recordings, share test results with your colleagues.

On the Test Runs page, for every test launch you can see:

* Test suite name and type
* Environment
* Platform/browser
* The number of passed, skipped, failed, etc. tests
* Execution time.

### Filter test runs

At the top of the Test Runs page, you can filter the results by different criteria:

* Test status (passed, failed, skipped, aborted, in_progress, queued, unknown)
* Environment
* Platform name 
* Browser name
* Time range
* Name of a test suite.

### Add stored filter

You can create a custom filter that will be used on a daily basis by you and your teammates.

For this, click **“+Add stored filter”** in the upper-left corner of the page. Tap the name, choose necessary parameters from the list, press **“Add”.**

You can create up to 30 new parameter sets at once.

After you are done, press **“Create”.**

### View test run results

To analyze test run results, click on any item in the list. Or go to the **Test run menu** (3-dot button on the left) and click **“Open”** (the **Test results page** will be opened in a new window).

Passed tests are marked green, and failed ones are red.

For every test, you can see the following details:

* Execution time
* Test owner
* Tags
* Reference to a Jira ticket

Stack trace is provided for failed tests.

#### Filter/group tests

You can filter test results by statuses (passed, failed, skipped, aborted, in_progress) by clicking on coloured dots in the upper-right area of the page.

Or group tests by different criteria in the upper-left area of the page:
* Class name
* Package name
* Tags

View all tests by returning to the **“Plain”** category.

##### Mark test as passed/failed

To mark a test as passed/failed, on the **Test results page**, click on the **Test menu** (3-dot button) and press **“Mark test as passed/failed”.**

##### Link known issue to test

This option is available only for failed tests.

On the **Test results page**, click on the **Test menu** (3-dot button) and press **“Link issue”.**

The red label will appear, the same one will be displayed in test statistics.

After you link a known issue from Jira to a failed test, next time you get the same stack trace, the test run will be automatically identified and displayed with the same label.

#### Analyze test flow

To analyze the test flow and see additional information about it, click the **“Details”** button (eye icon).

In the test log area, all the test steps are tracked.

Turn on the video to view the test flow with comments of what is going on right now in the text script. You can maximize the video to get a better view.

Under the video player, get the idea of test platform/browser, actual test status, its date and duration.

### Share test run results

#### Copy link

To copy the link to test run results, perform the following steps.

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Copy link”.**

#### Send as email

To send test results via email, perform the following steps:

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Send as email”.**
3. The **“Email”** popup will appear.
4. Fill in the **“Recipients”** field (unlimited number of emails per time).
6. Press the **“Send”** button.

A popup message **“Email was successfully sent”** will appear in the lower-right corner of the window.

#### Export to HTML

You can export test results to an HTML file and send it to your colleagues.

For this, perform the following steps:
1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Export to HTML”.**
3. Save the document on your computer.

### Mark test run as reviewed

To mark a test run as reviewed, perform the following steps:

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Mark as reviewed”.**
3. The **“Comments”** popup will appear.
4. Provide a comment if necessary.
5. Press **“Mark as reviewed”.**

A mark **“R”** will appear beside the test run name.

### Rerun/build test

To rerun tests with the same parameters, perform the following steps:

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Rerun”.**
3. The **“Rebuild testrun”** popup will appear.
4. Choose what tests you want to rerun: **Only failures** or **All tests.**
5. Press **“Rerun”.**

To run tests with additional parameters, perform the following steps:

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Build now”.**
3. The **“Build now”** popup will appear.
4. Change the proposed parameters.
5. Press **“Build now”.**

### Delete test run

To delete a test run, perform the following steps:

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Delete”.**
3. Submit the action.

The test run will be removed.
