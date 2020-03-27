# Test sessions

## Integration via agent/Selenium Hub

On the very first login to Zebrunner, you will be asked to select one of the two screen modes: **Integration via agent (Tests)** or **Selenium Hub (Tests).** This view will be displayed by default when you open the **Test runs/Test sessions page.**

If you skip this step, **Integration via agent (Tests)** will be enabled by default. You can switch between the 2 modes by using the control on the **Test runs/Test sessions page.**

### Tests: Integration via agent

If you choose this mode, you will need to integrate Zebrunner Agent into your automation framework. 

The agent allows to track test results in real time, apply detailed configuration and publish artifacts within one tool. It provides:

* Video recordings
* Session logs
* Known issues tracking
* Test artifacts

This mode requires integration via client library that you can find in our regional GitHub repos.

### Sessions: Selenium Hub

This is the easiest way to run tests in Zebrunner infrastructure. You need to generate an access token and configure your tests to use **Zebrunner Selenium URL.**

This mode provides:

* Real-time test sessions tracking
* Video recordings
* Session logs

## Test sessions page

The **Test sessions page** allows you to view the list of test sessions executed recently and see detailed information about the testing process.

To access the **Test sessions page,** go to the side menu and click on the **"Test runs/Test sessions button"** (the play icon on the side menu). If the **Test sessions mode** is not set by default, click on the **“Tests/Sessions”** switch in the upper-right corner of the window.

All the actions with test sessions are performed on this page.

### View test session info

On the **Test sessions page**, for every item you can see:

* Test and build name
* Test session status
* Environment
* Execution time
* Start date

After you click a test session item, the **Test session results page** will be opened. 

See the test logs captured from Selenium or Appium server in the area to the left, watch how the test session was executed in the video recording to the right, find the status of your test and other information (start date, duration, platform) in the area below.

### Generate access token

To generate an access token, perform the following steps:

1. On the **Test sessions page**, click the **“Access key”** button in the top-right corner of the page.
2. The **Access key popup** will appear.
3. At the top of the popup, in the **"Access URL"** field, generate a new access token (click the lifecycle icon) and copy it (click the icon beside).
4. In the area below, generate the capabilities required to run tests in your language (switch between Java, C#, Go, Ruby, Python, PHP, Webdriver.io).
5. Select the platform (Android/Web), application, browser name and version, video resolution.
6. All the changes will be immediately applied in the code area below.
7. Specify the test name and build name, if needed, in the field called **“name”**, separate them with a # sign.
8. Click **“Copy”.** 

The capabilities will be copied into your clipboard, now you can place them in your favourite id and run your tests in our environment.