# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: [Notino](https://www.notino.ro/)

API Documentation: 

**The final project contains the [Testing section](https://github.com/PaveM/Proiect-Practic-Testare-Manuala/blob/main/README.md#11-test-planning)

Tools used: JIRA and plug-in Zephyr

# Functional specifications TBD

-> enter here the functional specifications created in JIRA


# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing Sign-up and Promotii section for Notino website. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

#### 1.1.1 Roles assigned to the project and persons allocated
* Project manager - Diana Pop 
* Product owner - Martin Smith 
* Software developer - Ștefan Gavrilă 
* QA Engineer - Pavelina Mutu 

#### 1.1.2 Entry criteria defined
* Roles needed for the project are allocated;
* Initial project risks were detected;
* Functional specifications are defined.

#### 1.1.3 Exit criteria defined
* All tests have been executed.
* All resolved bugs have been re-tested and approved by the QA team.
* Technical requirements have been met.
* All development activities have been completed.
* All risks have been mitigated.

#### 1.1.4 Test scope

* __Tests in scope:_functional testing of the features included in Sign-up and Promotii sections. 
* __Tests not in scope:__performance testing, compatibility testing with multiple browsers, integration testing.

#### 1.1.5 Risks detected

* Project risks:
   * lack of experience of the QA team
   * short deadline of Zephyr Squad trial
   *  unavailability of test environment
   *  bussiness requirements not clear etc.
* Product risks:
   * the website is not intuitive enough when a Screen Reader is used
   * the extension is not compatible with the website
   * the clients might switch to a better website when it comes to price sorting
   * clients that have disabilities cannot use the website properly etc.
* The risc analysis can be seen below:
![risc](https://github.com/PaveM/Proiect-Practic-Testare-Manuala/assets/130222538/33971b9a-6721-48b7-9b86-b951cce8a60d)

#### 1.1.6 Evaluating entry criteria

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue. 

## 1.2 Test Monitoring and Control

It will be done by generating periodic reports that reflect the current status of the test.

## 1.3 Test Analysis

The testing process will be executed based on the above requirements. The following test conditions were found:
 ![Test Conditions](https://github.com/PaveM/Proiect-Practic-Testare-Manuala/assets/130222538/03040d1b-4057-4043-8070-969a894f242a)

## 1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases 
are: boundary value analysis, exploratory testing.

**Test cases:** 
![Test Cases_1](https://github.com/PaveM/Proiect-Practic-Testare-Manuala/assets/130222538/f54d32a1-aab8-4bc5-b9c0-d289878a33b6)
![Test Cases_2](https://github.com/PaveM/Proiect-Practic-Testare-Manuala/assets/130222538/a93e881a-4b94-4ae0-8595-c85f8668865e)

The test cases with steps can be viewed here: [test_cases.pdf](https://github.com/PaveM/Proiect-Practic-Testare-Manuala/blob/main/PM-10%20(4)_merged.pdf)

## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* Testing environment is up and running: https://www.notino.ro/
* Access to the testing environment is given using credentials: Username : pexepa1211@soombo.com | Password : Tokyo311
* Using Zephyr Squad, Cycle Summary was created
* Test cases were added to the Cycle Summary


## 1.6 Test Execution

* Test cases are executed on the created test Cycle summary: [cycle_summary_execution.csv](https://github.com/PaveM/Proiect-Practic-Testare-Manuala/blob/main/ZFJ-Cycles-09-24-2023.csv)
* From 15 test cases, 4 have failled.
* Bugs have been created based on the failed tests. The complete bug reports can be found here: [created_bugs.pdf](https://github.com/PaveM/Proiect-Practic-Testare-Manuala/blob/main/PM-16%20(2)_merged.pdf)
![Bugs](https://github.com/PaveM/Proiect-Practic-Testare-Manuala/assets/130222538/78a1b747-2b5c-41d0-ad56-b7e51a63a26a)



## 1.7 Test Completion

* The traceability matrix was generated and can be found here: [Traceability_matrix.csv](https://github.com/PaveM/Proiect-Practic-Testare-Manuala/blob/main/Forward%20Traceability_23_9_2023%20(1).xlsx)
* A number of 15 test cases were planned for execution and all of them were executed
* Test execution chart was generated, the final report shows a number of 4 tests have failed from a total of 15
* A number of 4 total bugs were found, 3 with high priority, 1 with medium priority

![Report Dashboard](https://github.com/PaveM/Proiect-Practic-Testare-Manuala/assets/130222538/4a3ac970-3c9a-4dae-90e4-fec938108f06)
