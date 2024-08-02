# Testing Project for Guru Bank


The scope of the final project for ITF Manual Testing Course is to use all gained knowledge through the course and apply them in practice, using a live application

**Application under test:** Guru Bank<br>
**Tools used:** Jira, Zephyr Squad.

## Functional specifications

The below stories were created in Jira and describes the functional specifications of the GURU BANK module, for which the final project is performed upon.

	      
![all stories](https://github.com/kilegna/IT-Factory-Project/assets/164054690/a304d068-4f12-4515-92bd-a5e12571347d)

Here you can find the release that was created for this project:
![releases Guru Bank](https://github.com/kilegna/IT-Factory-Project/assets/164054690/3f927e8d-1e1a-4bd3-8641-e2e4ea7b966b)

## Testing process

The test process was performed based on the standard test process as described below.

### 1.1 Test planning
The Test Plan is designed to describe all details of testing for all the modules from the Guru Bank application.
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.
### 1.1.1. Roles assigned to the project and persons allocated:
<table>
<tr></tr><td>Project manager</td> <td>John Smith</td> </tr>
<tr><td> Product owner</td> <td>Miguel Fernandez</td></tr>
<tr><td>Software developer</td> <td>Angi Paraschiv</td></tr>
<tr><td>QA Engineer</td> <td>Angelica Paraschiv</td></tr>
</table>

### 1.1.2 Entry criteria defined 
**Product Analysis:**
- Understand the product/application in detail that is going to be tested.
- Identify functionalities, requirements, and associated risks.
 
**Testing Strategy:**
- Define how you will approach testing.
- Determine the types of tests (functional, performance, security, etc.) and priorities.
 
**Testing Objectives:**
- Specify what you want to validate through testing.
- Examples of objectives: correct functionality, performance, security, compatibility, etc.
 
**Testing Criteria:**
- _Suspension criteria:_ conditions under which testing should be stopped (e.g., unresolved critical defects).
- _Exit criteria:_ expected test results (e.g., 95% of critical cases must pass).

**Resource Planning:**
- Determine the human and system resources needed for testing.
 
**Testing Environment:**
- Configure the testing environment to reflect the production environment.
 
Scheduling and Estimation:
- Set the schedule for testing activities and estimate the required effort.
 
### 1.1.3 Exit criteria defined 
**Completion of All Test Cases:**
- All planned test cases should be executed.
	This ensures comprehensive coverage of requirements and functionalities.
- Defect Closure:
	Critical defects should be resolved.
	A bypass strategy should be in place for any remaining medium-priority defects.
	Low-priority defects that do not significantly affect software usage can remain open.
- Meeting Target Dates or Budget Constraints:
	The project should meet its target date or stay within the allocated budget.

### 1.1.4 Test scope
**Tests in scope:**

- Module Manager
- Module Customer
	Usability Testing.
	Integration Testing.
        Unit Testing.

**Tests not in scope:**

- Non-Functional Testing:
	Some non-functional aspects, such as usability, accessibility, and localization, will be out of scope initially.

### 1.1.5 Risks detected
**Project risks:**
- Not enough time
- Not enough People assigned to the project

**Product risks:** 
- Unreliable Software.
- Frequent failures or unreliability in the software’s behavior.
- Users might encounter unexpected errors or crashes during normal usage.

### 1.1.6 Evaluating entry criteria
- The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.
https://itfclasses.atlassian.net/projects/TMTA20AP?selectedItem=com.thed.zephyr.je__test-metric-project-level
![test exec](https://github.com/kilegna/IT-Factory-Project/assets/164054690/131b40fa-5b81-466a-9ce6-627b97b37587)

### 1.2 Test Analysis 
**The following test conditions were found: **
https://itfclasses.atlassian.net/jira/software/c/projects/TMTA20AP/boards/315?issueParent=18638%2C18639&issueType=10005
![Desktop Screenshot 2024 07 03 - 03 59 12 97](https://github.com/kilegna/IT-Factory-Project/assets/164054690/9ac37a18-b4d5-4b54-9c0e-f7f87942919f)

### 1.3 Test Design
- Functional test cases were created in Zephyr Squad based on the analysis of the specifications.
- The test cases can be accessed here: https://itfclasses.atlassian.net/projects/TMTA20AP?selectedItem=com.thed.zephyr.je__test-cases

### 1.4 Test Implementation
- The following elements are needed to be ready before the test execution phase begins:

1.	Test Cases and Test Scripts:
i)	Creation of test cases
ii)	Test script preparation
2.	Test Environment Setup
3.	Test Data Preparation
4.	Test Strategy and Priorities
5.	Test Execution Schedule and Resources

### 1.5. Test Execution 
- Test cases are executed on the created test Cycle summary: https://itfclasses.atlassian.net/projects/TMTA20AP?selectedItem=com.thed.zephyr.je__cycle-summary
![cycle](https://github.com/kilegna/IT-Factory-Project/assets/164054690/d6a8b9f0-500c-48f8-96ab-322e824cce79)

- Bugs have been created based on the failed tests.
The complete bug reports can be found here: https://itfclasses.atlassian.net/projects/TMTA20AP?selectedItem=com.thed.zephyr.je__test-metric-project-level
![image](https://github.com/kilegna/IT-Factory-Project/assets/164054690/1838f0e4-3528-45f4-baa4-f5d30bced46c)

- The following is a summary of the bugs that have been found:
![issue sever](https://github.com/kilegna/IT-Factory-Project/assets/164054690/3ae392c5-55b4-4de8-966c-985fb7af9460)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

### 1.6 Test Completion
- The traceability matrix was generated and can be found here: 
![Matrice](https://github.com/kilegna/IT-Factory-Project/assets/164054690/8676ebdd-5c98-45f4-9c92-3dfd6f7a2c26)

- Test execution chart was generated and can be found below. 
https://itfclasses.atlassian.net/jira/dashboards/10339/edit
![Desktop Screenshot 2024 07 06 - 21 02 55 42](https://github.com/kilegna/IT-Factory-Project/assets/164054690/13024cbc-0b02-4087-9c36-fdec28ae15f9)

- The final report shows a number of 12 tests and have 3 failed, 4  blocked and 2 pass
![testsummary](https://github.com/kilegna/IT-Factory-Project/assets/164054690/da74167a-7a77-47a1-81b8-a9de58d2c089)

![test exec](https://github.com/kilegna/IT-Factory-Project/assets/164054690/1d71cc9a-16ce-4957-90d9-c80ae0b9171f)

### Notes: 
**1. Overview**

- Due to unforeseen circumstances, the initial project was terminated prematurely.
- As a result, we now have limited time remaining to complete the current testing project. 
- This note outlines the key points, tasks, and considerations for ensuring successful completion within the given timeframe.

**2. Project Timeline**

- Start Date of Current Project: 06.15.2024
- End Date: 08.31.2024
- Remaining Time: 23 days

**3. Objectives**

- Complete all testing phases effectively within the remaining time.
- Ensure all critical functionalities are thoroughly tested.
- Address any high-priority bugs or issues promptly.
- Deliver a stable and reliable product.

**4. Key Points**

- Time Constraint: The previous project shutdown has significantly reduced our available time for this project.
- Resource Allocation: Efficient use of available resources (manpower, tools, time).
- Prioritization: Focus on high-impact areas and critical functionalities.

**5. Action Items**

- Review and Update Test Plan: Revise the test plan to fit the shortened timeline, focusing on critical tests.
- Identify Critical Areas: Pinpoint functionalities that are crucial and ensure they are prioritized in testing.
- Allocate Resources: Assign tasks to team members based on expertise and priority areas.
- Daily Stand-ups: Conduct daily meetings to track progress, address issues, and adjust plans as necessary.
- Bug Triage: Implement a robust bug triage process to ensure critical bugs are addressed immediately.
- Automated Testing: Utilize automated testing where possible to save time and increase coverage.

**6. Risks and Mitigations**

- _Risk:_ Insufficient time to complete all planned tests.
- _Mitigation:_ Prioritize critical tests and functionalities.
- _Risk:_ High-priority bugs discovered late in the process.
- _Mitigation:_ Implement a rigorous and rapid bug triage and fix process.
- _Risk:_ Resource constraints (e.g., limited manpower).
- _Mitigation:_ Efficient resource allocation and possible temporary additional support.

**7. Communication Plan**

- Regular Updates: Send out daily progress reports to stakeholders.
- Issue Escalation: Establish a clear escalation path for critical issues.
- Feedback Loop: Ensure there is a mechanism for continuous feedback from testers to developers.

**8. Conclusion**

- Despite the challenges posed by the initial project's termination, we are committed to delivering a high-quality product.
- By focusing on critical functionalities, efficient resource management, and maintaining clear communication, we aim to complete the testing project successfully within the remaining timeframe.



