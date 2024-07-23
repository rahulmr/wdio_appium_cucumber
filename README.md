# MobileUI Automation Test Project Example with Appium & WebdriverIO

## Description:

An example project about Mobile automation (Android & iOS) testing using WebdriverIO. The test examples are created in Cucumber framework

## Requirements
  
- NodeJS
- Appium Server
- Appium Inspector (to find selector)
- Android Studio (for device emulator)
- Xcode (for iOS Simulator)
- Demo App (for testing sample) by Sauce Labs

### Inside the project:

- #### WebdriverIO Packages
    - Mocha and Cucumber as Test Framework
    - Allure as Test Reporter
    - Appium Server as a service to run the test
    - Appium Driver (`uiautomator2` & `xcuitest`)

### How to setup:

- Clone the project  
  Run `npm install`

### How to run the test:
        
#### Android:

- all the test
    - `npm run test-android-bdd`
- specific feature / test file
    - `npm run test-android-bdd --spec ./to/file/location.feature`
- specific test case or suite using tags
    - `npm run test-android-bdd --cucumberOpts.tagExpression='@sanity and @stage'`

#### iOS

- all the test
    - `npm run test-ios-bdd`
- specific feature / test file
    - `npm run test-ios-bdd --spec ./to/file/location.feature`
- specific test case or suite using tags
    - `npm run test-ios-bdd --cucumberOpts.tagExpression='@sanity and @stage'`


### Common issue might happen:

- Appium doesn't start automatically during the test (in local)
    
    - to solve the issue, just run the Appium server manually and re-run your test.

### How the report look like?

#### Allure Report

use `npm run report` to open the test report

Execution Video:

[![Watch the video](https://raw.githubusercontent.com/rahulmr/wdio_appium_cucumber/main/executionVideo/thumbnail.jpg)](https://www.youtube.com/watch?v=iMUN7eu8sZU)

Check YouTube

<video src="https://raw.githubusercontent.com/rahulmr/wdio_appium_cucumber/main/executionVideo/execution_recording.mp4" > Video </video>

[<img src="https://raw.githubusercontent.com/rahulmr/wdio_appium_cucumber/main/executionVideo/thumbnail.jpg" width="50%">](https://www.youtube.com/watch?v=iMUN7eu8sZU "Now in Android: 55")

