# Integrations[Draft].

### CI / Automation Server:
CI(continuous integration) server for run maven, gradle job.
If you want another CI tools, please ask [asistance](https://t.me/zebrunner)

There is possibility to add integration for more than one Jenkins:
 * Click **"+ New Integration"** button and add Jenkins.
 * Populate valid values for each field
   * NAME - Enter name of your Jenkins
   * URL - Enter url of your runing jenkins e.g. http://xx.xxx.xxx.xxx:80/jenkins
   * USER - Enter user name for your jenkins
   * API_TOKEN_OR_PASSWORD - Enter value of api token or password for jenkins
   * FOLDER - Name of your organization 
   * JOB_URL_VISIBILITY: TRUE - If you want to have jenkins url for test run in reporting ;  FALSE - If you don't need url for test run in reporting
   
      Example of Test run with JOB_URL_VISIBILITY: TRUE:
     ![Integration](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/job_url_visibility.png?raw=true)
    
 * Save changes

### Notification Service
There is possibility to send test result reports via email, slack or microsoft team.
Need to configure integration with Slack or Microsoft Teams:
   * Webhook Url is required to configure integration with Slack. You can ask assist of your slack administrator or generate Webhook Url by yourself.
   * Webhook is required to configure integration with Microsoft Teams. You can ask assist of your Microsoft Team administrator or generate Webhook by yourself.

### Test Case Management
Integration with Test Case Management systems help to get real-time insights into your testing progress to optimize test plans.

 * Configure Jira:
   * URL- Enter url to your Jira instance, e.g. https://mycompany.atlassian.net
   * USER - Enter your Jira user account
   * PASSWORD - Enter password for your Jira account
   * CLOSED_STATUS - Comma separated list of closed Jira ticket states, for example: done, closed. 
  
 * Configure Testrail:
   * URL - Enter url to your Testrail project
  
 * Configure Qtest:
   * URL - Enter url to your Qtest project
   
### Test Environment Provider:
The main perpouse of Test Environment Provider to execute tests on different selenium/appium hubs using Test Launcher feature.

![Launcher](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/launcher.png?raw=true)

What you need to use it?
   * Get URL and credentials from your hub provider,activate and save appropriate provider settings. 

![Selenium Hub](https://github.com/zebrunner/documentation/blob/master/docs/assets/images/selenium.png?raw=true)

