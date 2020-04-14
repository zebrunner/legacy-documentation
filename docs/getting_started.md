# Getting started

## Registration

To create a workspace in Zebrunner, press **Free trial** on [Zebrunner](https://zebrunner.com) and perform the following steps.

### Step 1. Provide company details

Enter your email and name of your future company in Zebrunner.

Press **Next.**

### Step 2. Verify email

A verification PIN will be sent to your email. Enter it to the specified field.

Press **Next.**

### Step 3. Connect GitHub account 

This step is optional. 

If you want to get a sample test automation project to your GitHub account, specify your organization and the name of the future sample project (you can enter only characters [a-zA-Z], digits [0-9], underscore, dash and dot (_, -, .)).

Make the repository private, if needed, by putting a check below.

If you skip this step, no repository will be added. You can add a repository later on the **Test runs** page.

Press **Finish.**

### Step 4. Verification and login

In a few minutes you will receive a verification email with details on your new workspace and a link to the generated GitHub repository - it is a sample automation project represented by a general TestNG Java automation structure and a Carina-based framework inside.

In the email, press **Let’s start.**

Provide your username and enter a secure password, press **Sign in**, then **Login.**

## Tests vs Sessions
You will be redirected to the starting page where you will be asked to select one of the two screen modes: **Integration via agent (Tests)** or **Selenium Hub (Sessions).** This view will be displayed by default when you open the **Test runs/Test sessions** page.

If you skip this step, **Integration via agent (Test runs view)** will be enabled by default. You can easily switch between the 2 modes by using the control on the Test runs/Test sessions page.

![Test Runs and Test Sessions](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/test_runs_and_sessions.png?raw=true)

### Tests: Integration via agent

If you choose this mode, you need to integrate Zebrunner Agent into your automation framework. 

The agent allows to track test results in real time, apply detailed configuration and publish artifacts within one tool.

**This mode provides:**

* Video recordings
* Session logs
* Known issues tracking
* Test artifacts

This mode requires integration via the client library that you can find in our regional GitHub repositories.

### Sessions: Selenium Hub

This is the easiest way to run tests in Zebrunner infrastructure. You need to generate an access token and configure your tests to use Zebrunner Selenium URL.

**This mode provides:**

* Real-time test sessions tracking
* Video recordings
* Session logs

For more information on Zebrunner, go to the main part of our [User guide](https://zebrunner.github.io/documentation/guide/user_profile)
