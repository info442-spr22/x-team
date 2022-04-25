# Testing Plan

## Types of Testing

This application will use manual acceptance testing. It will not use code reviews as there is only one developer. It will make use of automated unit tests with [Github Actions](https://github.com/features/actions) (*stretch goal*).

The unit tests will test logic that shows quasi-random videos on home page (Home Page 5.1) and logic that handles idea generator form submission (Idea Generator 8, 9, 12)(*stretch goal*).

## Test Environments

Developers will do ad-hoc manual testing of their work on their local machines. All other testing will be done on code that has been deployed to our production environment on Netlify.

## Supported OS/Browser Combinations

 - Chrome browser on MacOS (tested on a MacBook Air laptop)
 - Edge browser on Windows (tested on a Surface Pro tablet)
 - Firefox browser on Android (tested on a Samsung Galaxy S22 phone)

## Process

All feature work will be done on feature branches. After development is complete, the developer will open a Pull Request. There will be no code review on this Pull Request as there's only one developer on this team. Merging of a Pull Request will trigger a Github Action for unit tests (*stretch*). If the Action succeeds, a deploy to Netlify will be triggered.

It is the developer's responsibility to ensure all parts of the merging and deployment process complete successfully for their Pull Requests. When process completes, the developer alerts the product designer that the feature has been deployed.

After being alerted, the product designer will manually test the deploy. They will run manual performance testing using [Web Page Test](https://www.webpagetest.org) and manual acceptance testing using the script below on at least one of the supported OS/browser combinations.

Each Friday during development, the project manager will run the acceptance testing script on all supported OS/browser combinations.

## Defect Management

If any defects are found during manual testing process, they will be brought to the project manager's attention by email. The project manager will determine whether to make a new issue to fix the problem or to ask the developer who wrote the original code to do a quick, immediate fix.

### Manual Acceptance Testing Script

This application has no user authentication, so there is no difference in functionality based on users being logged in. Test should be run against code in production environment, on supported OS/browser combinations. There is no custom data for testing purposes.

#### Home Page

Visit the home page of the application. Expect to see a title, text about the problem of textile waste, a call to action for Idea Generator feature, and an embedded YouTube video. (Home Page 1, 2, 3, 4, 5)

Click anywhere on the call to action for Idea Generator, expect to be redirected to the Idea Generator page. (Home Page 4)

Refresh the home page three times. Expect to see a different embedded video on each page load. (Home Page 5.i)

#### Idea Generator Page

[TODO]






