# Integrations[Draft]

### Access Management:
TBD
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

### Test Case Management

### Test Environment Provider:
The main perpouse of Test Environment Provider to execute tests on different selenium/appium hubs using Test Launcher feature.

Image will be added

What you need to use it?:
 * Get URL and credentials from your hub provider,activate and save appropriate provider settings. 

Image will be added

