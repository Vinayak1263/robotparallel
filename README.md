# Browserstack Robot Framework 

![BrowserStack Logo](https://d98b8t1nnulk5.cloudfront.net/production/images/layout/logo-header.png?1469004780) 


## Set BrowserStack Credentials 
* You can export the environment variables for the Username and Access Key of your BrowserStack account. 

  ```
  export BROWSERSTACK_USERNAME=<browserstack-username> &&
  export BROWSERSTACK_ACCESS_KEY=<browserstack-access-key>
  ```

## Running tests

### App Automate
* Navigate to `cd app/test`
* To run parallel tests, navigate to 'parallel' folder, run `cd parallel`
* In each Suite.robot file replace app_url with url you get by uploading app on browserstack.
  1. Test Suite level
    - `pabot --processes 2 Suite1_App.robot  Suite2_App.robot`

    
