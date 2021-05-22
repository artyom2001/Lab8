# Lab8_Starter


## Teammates
- Artyom
- Victor

## Check your understanding q's (FILL OUT)
1. In your own words: Where would you fit your automated tests in your Bujo project development pipeline? (just write the letter)

    Within a Github action that runs whenever code is pushed.

2. Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.

    A messaging feature within a messaging app seems beyond the levels of a unit test. Testing whether a message is sent and received requires multiple parts of the app to work together.

3. Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters

    Using a unit test for the max message length feature is more specific and a sub-feature of the main goal of a messaging app, which means it will be more useful to test this way.

4. What do you expect to happen if we run our puppeteer tests with the field “headless” set to true?
   
   When using headless set to true, the browser would not open up to run our tests, meaning it is run without a visual interface.

5. What would your beforeAll callback look like if you wanted to start from the settings page before every test case?

    await page.click('header img');

## Screenshots

![Sum](/images/sum.png)

![Router](/images/router.png)

![Part 2](/images/part2.png)
