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
a. All functional and non-functional requirements are clearly defined and approved by all parties involved.
I chose the online sales platform <https://www.temu.com/ro> and more precisely the important functionalities that involve creating an account as a user.
b.The chosen test environment is jira -Zephyr Squad and we used the online version of the application
c. As a search engine, to navigate the web platform I used Google Chrome.
d. The software version of the application used for testing is the public one available on the internet in the web version
e. The deployed source code is stable, with no known critical bugs that could hinder testing.
f. Ten test cases have been implemented, defined and approved.
g. All test cases are written, reviewed and approved, ensuring that they cover all relevant scenarios.
h.The available test data was as needed to execute the test cases and available in the test environment.
* The specifications for the account creation functionality in the Temu platform are complete and approved.
* The test environment is configured and includes relevant test data.
* The web version of the platform containing the functionality is stable and delivered to the testing team.
* Test cases for the account creation functionality have been written and reviewed.
* The necessary testing tools are installed and functional.

<h4> 1.1.3 Exit criteria defined </h4>
a. All test cases for the create an account as a user functionality have been executed.
b. The critical and major defects identified were corrected and validated.
c. A test coverage report has been generated, indicating more than 95% coverage.
d. Regression tests have been successfully performed.is. The documentation for the functionality of creating an account as a user, has been updated and revised.
f. The test results have been approved by the customer and the management team.


<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

Ten tests have been implemented, which target the main functionalities related to: 
-positive test such as logging into your account with valid data
-negative testing such as logging into the account with invalid data
-logging into an existing account when we have certain security breaches enabled, such as logging into the account when the 2FA option is enabled

Functionalities aimed at the user's interaction with the platform for the purpose of placing orders, such as adding a payment method, but also adding the delivery address
For the purpose of testing we used the web version of the temu platform available for windows
I mention that the web version of the platform used is responsive in terms of: performance, design but also user interactions

<h5>Tests not in scope: </h5>

The functionality of logging out of the account, has not been implemented because it is not subject to testing in this case.

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>
 1. The lack of experience of the testing team can lead to important defects being missed during testing.
 2. The short testing time may result in the inability to cover all the important functionalities of this product.
 3. The lack of business requirements that are not defined can lead to an incomplete understanding of the product's functionalities.



<h5> Product risks: </h5>
1. Due to the short testing time, we were not able to cover a large enough percentage of the application, which can lead to a high density of defects reproduced in production in uncovered areas.
2. Due to a small investment in usability, it is possible that the user experience with the web version of the platform will not be as good as we would like, which is why users will have to use the native version of the platform (this is where problems related to the server, the resolution of the device used or a poor internet connection come in).
3. The platform's login functionality is not very intuitive in terms of the graphical user interface, having an unsatisfactory design, which can lead to inconvenience caused to users and their migration to other sites or online sales platforms.



<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>
Tes status report

![image](https://github.com/user-attachments/assets/79cc8b48-fa43-42b0-8069-823f5cfd4d91)

**(inserati aici motivul pentru care a fost facuta etapa de monitorizare si control si respectiv cum s-a facut aceasta etapa. Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)**

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

The following test conditions were found: <br>
![image](https://github.com/user-attachments/assets/ebc21709-bbae-4d55-a4a5-e7f2182d06ca)


**(aici puteti fie sa puneti o poza din jira cu titlurile tuturor testelor - din issues filtrare dupa type test sau sa scrieti cu bulinuta numele fiecarei conditii de testare pe care ati identificat-o)**

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: Test cases for creating an account.

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**
![image](https://github.com/user-attachments/assets/b0a3b70e-49b0-4824-b500-2ca7fe011f65)

![image](https://github.com/user-attachments/assets/425a6777-454f-4c3e-a7da-2290cf2ba3fd)


The following is a summary of the bugs that have been found
1. <The application does not accept the payment method I used> is the first bug, and its priority is Medium.
2. <When creating a new account with valid data, if you do not enter a valid email address in the "Email address" field, the platform does not display an error message> is the second bug, and its priority is High.


Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**
![image](https://github.com/user-attachments/assets/76fdc269-8bf2-40b7-b0d9-1932e53a4978)


Test execution chart was generated and can be found below. 
**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**
![image](https://github.com/user-attachments/assets/1f1851ad-abc7-4543-a335-8d52c52acb4c)


The final report shows that a number zero tests have failed of a total of ten.

A number of two bogs total bugs were found, from which the priority is: one bug are high and one bug are medium.

In this project we tested the online sales platform <https://www.temu.com/ro> and more precisely one of its most important functionalities, the account creation functionality as a customer, but also other functionalities such as: adding a payment method, adding a delivery address, logging in when the user uses credentials or not or has the 2FA option activated. 
   The testing process went as expected and without problems.
  Within the project, the following were carried out:
Three Stories
Ten tests carried out and fully executed
two bugs that do not have a major significant impact on the functionality and performance of the product, including:
a bug has been assigned, fixed, retested and closed
an unassigned, unfixed and unretested bug.
I mention that the two bugs do not have a significant negative impact on the product.

