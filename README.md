DataOne Innovation Labs QA Automation Engineer Recruitment Test
==================================

Thank you for taking the time to do our technical test. It consists of two parts:

* [A technical test](#technical-test)
* [A few technical questions](#technical-questions)

In order to avoid bounced emails we would like you to submit your results by uploading the relevant zip file to a shared Google Drive folder. In order to obtain the URL for this folder, please supply your Gmail or Google-based email address to either your agent or the DataOne Innovation Labs team member who assigned you the test.

Please make this a **single** zip file named `{yourname}-{role-applied-for}.zip` containing:

1. a single markdown file with the answers to the technical questions
2. one folder containing the technical test

## Technical Test

We have a demo website setup for our upcoming product ![Shoppr - A Customer Science Platform for E-Commerce](https://shoppr.ai). You'll receive an email with the demo site url and credentials for the same. 
The Technical test consists of 2 tasks:

1. Write the step definitions for the below scenario.

		Feature: Allow user to register on the platform
				As a user of the registration page of the demo website
				When I provide valid unique credentials
				An account is created for me
			Scenario: Invalid credentials
				As a user of the registration page of the demo website
				When I provide an email that has already been used in the system
				I see an appropriate error message

2. Add  two more test cases, with corresponding feature, scenario and step definitions, which you feel would enhance the test coverage of the site.


### Platform Choice

You can create step definitions using any Java based testing framework you are experienced with

### Task requirements

Feel free to spend as much or as little time on the exercise as you like as long as the following requirements have been met.  

- Please complete the two tasks described above.
- You should provide clear instructions on your test setup and how to execute your tests. The clarity and precision of these instructions - and the ease with which the interviewers can execute them - will be a key part of the assessment. Please create a README file detailing said instructions. Please also use this file for listing any additional comments or observations you might want to share about your submission.

# Technical questions

Please answer the following questions in a markdown file called `Answers to technical questions.md`.

1. How long did you spend on the technical test? What would you add to your solution if you had more time? If you didn't spend much time on the technical test then use this as an opportunity to explain what you would add.
2. What do you think is the most interesting trend in test automation?
3. How would you implement test automation in a legacy application? Have you ever had to do this?
4. Please describe yourself using JSON.

## What we review

* **Correctness:** Do your tests compile and run?  Do they actually make calls to the API and verify results?
* **Code Quality:** Is your code maintainable, easy to understand, and conducive for future reuse or expansion?
* **Quality Focused:** Does your choice of test case scenarios provide adequate, given the limits, confidence in the quality of the GitHub API endpoints tested?
* **Communication:** Are you able to defend why you picked your test case scenarios and explain what they do in your README and through other forms of communication?

![Good Luck!](http://i.imgur.com/DHxjAeQ.jpg)

#### Thanks for your time, we look forward to hearing from you!
- The [DataOne Innovation Labs team](https://dataone.io)
