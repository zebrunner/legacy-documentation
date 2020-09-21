# Integrations[Draft].

### CI / Automation Server:
CI (continuous integration) server is used for running Maven and Gradle jobs.
If you need other CI tools, please ask for [support](https://t.me/zebrunner).

There is a possibility to add integrations for more than one Jenkins:
 * Click the **"+ New Integration"** button and add Jenkins
 * Populate the valid values for each field:
   * NAME - Enter the name of your Jenkins
   * URL - Enter the URL of your running Jenkins, e.g. http://xx.xxx.xxx.xxx:80/jenkins
   * USER - Enter the username of your Jenkins
   * API_TOKEN_OR_PASSWORD - Enter the value of the API token or password to Jenkins
   * FOLDER - Enter the name of your organization 
   * JOB_URL_VISIBILITY: TRUE - If you need a Jenkins URL of a test run in the reporting;  FALSE - If you don't need an URL of a test run in the reporting
   
      Example of a Test run with JOB_URL_VISIBILITY: TRUE:
     ![Integration](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/job_url_visibility.png?raw=true)
    
 * Save changes.

### Notification Service
In addition to the default email notification, it is possible to send test result reports via Slack and/or Microsoft Team.
For this, configure an integration with Slack or Microsoft Team:
   * Webhook URL is required to configure an integration with Slack. You can ask for assistance from your Slack administrator or generate a Webhook URL by yourself.
   * Webhook is required to configure an integration with Microsoft Teams. You can ask for assistance from your Microsoft Team administrator or generate a Webhook by yourself.

### Test Case Management
Integration with Test Case Management systems helps to get real-time insights of your testing progress to optimize the test plans.

 * Configure Testrail:
   * URL - Enter the URL of your Testrail project
  
 * Configure Qtest:
   * URL - Enter the URL of your Qtest project
   
 * Configure Jira:
   * URL- Enter the URL of your Jira instance, e.g. https://mycompany.atlassian.net
   * USER - Enter your Jira user account
   * PASSWORD - Enter the password to your Jira account
   * CLOSED_STATUS - Comma-separated list of closed Jira ticket states, for example, done, closed.  
   
### Test Environment Provider:
The main purpose of Test Environment Provider is to execute tests on different Selenium/Appium hubs using the Test Launcher feature.

![Launcher](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/launcher.png?raw=true)

What do you need to use it?
   * Get the URL and credentials from your hub provider, activate and save the appropriate provider settings. 

![Selenium Hub](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/selenium.png?raw=true)

