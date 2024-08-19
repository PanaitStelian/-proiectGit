<h1>Testing Project for **Temu**</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

**Application under test:** Temu

**Tools used:** Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below story was created in Jira and describes the functional specifications of the "*Create Account**" module, on which the final project is performed upon.

![image](https://github.com/user-attachments/assets/2f4f905c-e886-4690-a986-12934e2a97fd)

The full document with stories can be found [here](https://github.com/PanaitStelian/manual_testing_jira/blob/master/Jira%20Stories.pdf).

Here you can find the release that was created for this project:

![image](https://github.com/user-attachments/assets/2d4e5dec-253c-47f9-983f-7f550fbeac26)


<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. 

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>


<ul>
  <li>Gabriela Radulescu-Project manager</li> 
 
  <li>Panait Stelian-tester</li>
  <li>Panait Stelian-QA Engineer</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

- All functional and non-functional requirements are clearly defined and approved by all parties involved.
I chose the online sales platform <https://www.temu.com/ro> and more precisely the important functionalities that involve creating an account as a user.
- The chosen test environment is jira -Zephyr Squad and we used the online version of the application
- As a search engine, to navigate the web platform I used Google Chrome.
- The software version of the application used for testing is the public one available on the internet in the web version
- The deployed source code is stable, with no known critical bugs that could hinder testing.
- Ten test cases have been implemented, defined and approved.
- All test cases are written, reviewed and approved, ensuring that they cover all relevant scenarios.
- The available test data was as needed to execute the test cases and available in the test environment.<br>
* The specifications for the account creation functionality in the Temu platform are complete and approved.
* The test environment is configured and includes relevant test data.
* The web version of the platform containing the functionality is stable and delivered to the testing team.
* Test cases for the account creation functionality have been written and reviewed.
* The necessary testing tools are installed and functional.

<h4> 1.1.3 Exit criteria defined </h4>
a. All test cases for the create an account as a user functionality have been executed.<br>
b. The critical and major defects identified were corrected and validated.<br>
c. A test coverage report has been generated, indicating more than 95% coverage.<br>
d. Regression tests have been successfully performed.is. The documentation for the functionality of creating an account as a user, has been updated and revised.<br>
f. The test results have been approved by the customer and the management team.


<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

Ten tests have been implemented, which target the main functionalities related to: 
-positive test such as logging into your account with valid data.<br>
-negative testing such as logging into the account with invalid data.<br>
-logging into an existing account when we have certain security breaches enabled, such as logging into the account when the 2FA option is enabled. <br>

Functionalities aimed at the user's interaction with the platform for the purpose of placing orders, such as adding a payment method, but also adding the delivery address.<br>
For the purpose of testing we used the web version of the temu platform available for windows. <br>
I mention that the web version of the platform used is responsive in terms of: performance, design but also user interactions. <br>

<h5>Tests not in scope: </h5>

The functionality of logging out of the account, has not been implemented because it is not subject to testing in this case.

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>
 1. The lack of experience of the testing team can lead to important defects being missed during testing.<br>
 2. The short testing time may result in the inability to cover all the important functionalities of this product.<br>
 3. The lack of business requirements that are not defined can lead to an incomplete understanding of the product's functionalities.<br>



<h5> Product risks: </h5>
1. Due to the short testing time, we were not able to cover a large enough percentage of the application, which can lead to a high density of defects reproduced in production in uncovered areas.<br>
2. Due to a small investment in usability, it is possible that the user experience with the web version of the platform will not be as good as we would like, which is why users will have to use the native version of the platform (this is where problems related to the server, the resolution of the device used or a poor internet connection come in).<br>
3. The platform's login functionality is not very intuitive in terms of the graphical user interface, having an unsatisfactory design, which can lead to inconvenience caused to users and their migration to other sites or online sales platforms.<br>



<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control</h3>

  
  Test status report was generated in order to provide information about the progress of the testing process.
  One example of test status report can be found below:<br>
![image](https://github.com/user-attachments/assets/79cc8b48-fa43-42b0-8069-823f5cfd4d91)


<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <br>

The following test conditions were found: <br>
![image](https://github.com/user-attachments/assets/dcfee260-47b0-438e-9eb9-3e91fe060872)


<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://github.com/user-attachments/files/16663957/ZFJ-Cycles-08-19-2024.-.ZFJ-Cycles-08-19-2024.pdf)

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:
- test environment must be configured and validated.
- test data must be created.
- test cases must be prioritized.
- access must be provided.

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: Test cases for creating an account.

Bugs have been created based on the failed tests. The complete bug reports can be found here: 
![image](https://github.com/user-attachments/assets/64c4cf0b-4168-4794-9916-0d535c4c3788)


![image](https://github.com/user-attachments/assets/e60c9481-962f-4135-b81c-397ad9834b98)



The following is a summary of the bugs that have been found
1. <The application does not accept the payment method I used> is the first bug, and its priority is Medium.
2. <When creating a new account with valid data, if you do not enter a valid email address in the "Email address" field, the platform does not display an error message> is the second bug, and its priority is High.


Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 
![image](https://github.com/user-attachments/assets/76fdc269-8bf2-40b7-b0d9-1932e53a4978)


Test execution chart was generated and can be found below. 
- The attached diagram gives us an overview and the progress made in meeting the requirements, testing and the overall condition of the project. The main important functionality of this project is the creation of an account in the sales platform that has been successfully implemented and tested.<br>
- All the tests associated with this functionality have passed successfully, this indicates that the account creation functionality is complete and works as expected (green area).<br>
- During the testing process, two bugs were detected, one of which was assigned, fixed and retested successfully (PST-19) and the other bug (PST-31) that was not assigned, unfixed and untested again (red area).<br>
- As a general conclusion, this does not affect the creation of an account within the application and does not generate negative effects on it, not having a negative effect that impacts the state of the application or its performance.


![image](https://github.com/user-attachments/assets/1f1851ad-abc7-4543-a335-8d52c52acb4c)


The final report shows that a number zero tests have failed of a total of ten.

A number of two bogs total bugs were found, from which the priority is: one bug are high and one bug are medium.<br>
In this project we tested the online sales platform <https://www.temu.com/ro> and more precisely one of its most important functionalities, the account creation functionality as a customer, but also other functionalities such as: adding a payment method, adding a delivery address, logging in when the user uses credentials or not or has the 2FA option activated.<br>
   The testing process went as expected and without problems.<br>
  Within the project, the following were carried out:
- Three Stories
- Ten tests carried out and fully executed
- Two bugs that do not have a major significant impact on the functionality and performance of the product, including:

I mention that the two bugs do not have a significant negative impact on the product.

