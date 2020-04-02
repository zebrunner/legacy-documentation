# Test runs

On the very first login to Zebrunner, you will be asked to select one of the two screen modes: **Integration via agent (Tests)** or **Selenium Hub (Tests).** This view will be displayed by default when you open the **Test runs/Test sessions page.**

If you skip this step, **Integration via agent (Test runs view)** will be enabled by default. You can easily switch between the 2 modes by using the control on the **Test runs/Test sessions page.**

![Test Runs and Test Sessions](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/test_runs_and_sessions.png?raw=true)

The **Test runs page** allows you to launch tests from your GitHub repository, see detailed test results in real time and on a test run finish.

To access the Test runs page, go to the side menu and click on the **Test runs** icon. If the **Test runs mode** is not set by default, click on the **“Tests/Sessions”** switch in the upper-right corner of the window.

All the actions with test runs are performed on this page.

![Test Runs Page](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/test_runs_page.gif?raw=true)

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

![Add Repository](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/add_repository.gif?raw=true)

### Remove repository

To remove a repository, perform the following steps: 

1. On the Test runs page, click the **“Test launcher”** button.
2. The **Launcher wizard** will be opened.
3. Click the gear button beside the repository name.
4. Press **“Delete repo”** at the bottom of the wizard.

The repository will be removed from the list.

![Remove Repository](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/remove_repository.gif?raw=true)

### Create launcher manually

To create a test launcher manually, perform the following steps:

1. On the Test runs page, click the **“Test launcher”** button.
2. The **Launcher wizard** will be opened.
3. Click the **“+”** button beside the repository name.
4. Create a new template specifying the template name, choosing the platform and the template, adding or removing arguments.
5. Press **“Add”.**

The new launcher template will be added with a tag **“Manual creation” (“M”).**

![Create Launcher Manually](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/create_launcher_manually.gif?raw=true)

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

![Launch Test Run](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/launch_test_run.gif?raw=true)

### Abort test run

To abort a test run **“In-progress”** (marked blue), perform the following steps:

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Abort”.**

The test run will become aborted (marked grey).

![Abort Test Run](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/abort_test_run.gif?raw=true)

### Remove launcher

To remove a launcher, perform the following steps:

1. On the Test runs page, click the **“Test launcher”** button.
2. The **Launcher wizard** will be opened.
3. Select the launcher you would like to remove.
4. Click the **“Edit”** button (the gear icon) at the top of the wizard.
5. Press **“Delete”.**

The launcher will be removed from the list.

![Remove Launcher](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/remove_launcher.gif?raw=true)

## Test run results

On the Test runs page, you can see all the test runs that have been executed recently. Moreover, view test run details, logs and video recordings, share test results with your colleagues.

On the Test Runs page, for every test launch you can see:

1. Test suite name and type.
2. Environment.
3. Platform/browser.
4. The number of passed, skipped, failed, etc. tests.
5. Execution time and start day.
6. Settings (the 3-dot button).

![Test Runs Page View](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/test_runs_page_view.png?raw=true)

### Filter test runs

At the top of the Test Runs page, you can filter the results by different criteria:

1. Name.
2. Reviewed/not reviewed.
3. Test status (passed, failed, skipped, aborted, in_progress, queued, unknown).
4. Environment.
5. Platform name.
6. Browser name.
7. Start date.

![Filter Test Runs](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/filter_test_runs.png?raw=true)

### Add stored filter

You can create a custom filter that will be used on a daily basis by you and your teammates.

For this, click **“+Add stored filter”** in the upper-left corner of the page. Tap the name, choose necessary parameters from the list, press **“Add”.**

You can create up to 30 new parameter sets at once.

After you are done, press **“Create”.**

![Add Stored Filter](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/add_stored_filter.gif?raw=true)

### Edit/delete stored filter

You can edit a created stored filter by clicking the pencil icon beside its name. Make the necessary changes and press **"Save”.**

To delete a stored filtes, click the pencil icon beside its name and press **"Delete".**

![Edit and Delete Stored Filter](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/edit_and_delete_stored_filter.png?raw=true)

### View test run results

To analyze test run results, click on any item in the list. Or go to the **Test run menu** (3-dot button on the left) and click **“Open”** (the **Test results page** will be opened in a new window).

Passed tests are marked green, and failed ones are red.

For every test, you can see the following details:

* Execution time
* Test owner
* Tags
* Reference to a Jira ticket

Stack trace is provided for failed tests.

![View Test Run Results](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/test_results_page.png?raw=true)

#### Filter/group tests

You can filter test results by statuses (passed, failed, skipped, aborted, in_progress) by clicking on coloured dots in the upper-right area of the page.

Or group tests by different criteria in the upper-left area of the page:

* Class name
* Package name
* Tags

View all tests by returning to the **“Plain”** category.

![Filter and Group Test Results](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/filter_group_test_results.gif?raw=true)

#### Mark test as passed/failed

To mark a test as passed/failed, on the **Test results page**, click on the **Test menu** (3-dot button) and press **“Mark test as passed/failed”.**

![Mark Test as Passed or Failed](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/mark_test_a_passed_failed.gif?raw=true)

#### Link known issue to test

This option is available only for failed tests.

On the **Test results page**, click on the **Test menu** (3-dot button) and press **“Link issue”.**

The red label will appear, the same one will be displayed in test statistics.

After you link a known issue from Jira to a failed test, next time you get the same stack trace, the test run will be automatically identified and displayed with the same label.

![Link Known Issue to Test](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/link_known_issue.gif?raw=true)

#### Analyze test flow

To analyze the test flow and see additional information about it, click the **“Details”** button (eye icon).

In the test log area, all the test steps are tracked.

Turn on the video to view the test flow with comments of what is going on right now in the text script. You can maximize the video to get a better view.

Under the video player, get the idea of test platform/browser, actual test status, its date and duration.

![Analize Test Flow](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/view_test_flow.gif?raw=true)

### Share test run results

#### Copy link

To copy the link to test run results, perform the following steps.

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Copy link”.**

![Copy link](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/copy_link_to_test_run.png?raw=true)

#### Send as email

To send test results via email, perform the following steps:

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Send as email”.**
3. The **“Email”** popup will appear.
4. Fill in the **“Recipients”** field (unlimited number of emails per time).
6. Press the **“Send”** button.

A popup message **“Email was successfully sent”** will appear in the lower-right corner of the window.

![Send as Email](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/send_test_run_as_email.png?raw=true)

#### Export to HTML

You can export test results to an HTML file and send it to your colleagues.

For this, perform the following steps:
1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Export to HTML”.**
3. Save the document on your computer.

![Export to HTML](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/export_to_html.gif?raw=true)

### Mark test run as reviewed

To mark a test run as reviewed, perform the following steps:

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Mark as reviewed”.**
3. The **“Comments”** popup will appear.
4. Provide a comment if necessary.
5. Press **“Mark as reviewed”.**

A mark **“R”** will appear beside the test run name.

![Mark Test Run as Reviewed](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/mark_test_as_reviewed.gif?raw=true)

### Rerun/build test

To rerun tests with the same parameters, perform the following steps:

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Rerun”.**
3. The **“Rebuild testrun”** popup will appear.
4. Choose what tests you want to rerun: **Only failures** or **All tests.**
5. Press **“Rerun”.**

![Rerun Test](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/rerun_test.gif?raw=true)

To run tests with additional parameters, perform the following steps:

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Build now”.**
3. The **“Build now”** popup will appear.
4. Change the proposed parameters.
5. Press **“Build now”.**

![Build Test Run](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/build_test_run.gif?raw=true)

### Delete test run

To delete a test run, perform the following steps:

1. On the **Test runs page**, go to the **Test run menu** (click the 3-dot button on the left).
2. Press **“Delete”.**
3. Submit the action.

The test run will be removed.

![Delete Test Run](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/delete_test_run.png?raw=true)
