# Test Plan

## LeafGrow Web Application

**Format:** IEEE 829

**Version:** 1.0

**Status:** Draft

**Date:** 15/05/2024

**Prepared by:** Evgeniya Turtschina

### References:

1. Project Plan
[Project and Design Workflow](https://leafgrowproject.atlassian.net/wiki/spaces/~712020339fb673d2c94eb7bc5cee2b56307e22/pages/2719784/Project+and+Design+Workflow)

2. User Stories
[User Stories (Confluence)](https://leafgrowproject.atlassian.net/wiki/spaces/~712020339fb673d2c94eb7bc5cee2b56307e22/pages/12288086/User+Stories+En)

3. User Flow & Feature Flow
[Navigation diagrams for key features](https://leafgrowproject.atlassian.net/wiki/spaces/~712020339fb673d2c94eb7bc5cee2b56307e22/pages/10649621/User+Flow+Feature+Flows)

4. Detailed Design Document
[Figma: LeafGrow Project](https://www.figma.com/design/jlyto9BuYwaqMMt3N0t1BE/LeafGrow?node-id=0%3A1&t=XQKjBHlxfTd4MSUY-1)

5. Mind Map
[LeafGrow Project Mind Map](https://drive.mindmup.com/map/1PilpuCS8YL3AMDbli1e8uHp4GvWO0c_o)

## 1. Introduction

This Test Plan defines the overall strategy and structure for testing the LeafGrow web application.
The objectives of this document are:

- Define the tools, environments, and methods used during testing.

- Communicate scope, responsibilities, and scheduling requirements.

- Describe how functional, UI, and integration tests will be executed.

- Verify that core user flows operate correctly in a realistic usage scenario.

- Validate UI behavior, layout consistency, and usability.

- Ensure that the application meets basic expectations of accessibility and user interaction.

## 2. Test Approach
### 2.1 Functional Testing

Functional testing verifies that the application behaves according to specified requirements.

Areas include:

- User registration

- Login/logout

- Navigation between pages

- Pot creation, deletion, and growth-start functionality

- Email notifications

### 2.2 UI Testing

UI testing focuses on layout correctness, element behavior, and visual consistency.

Activities include:

- Verifying correct rendering on different resolutions

- Checking interactive elements (buttons, inputs, links)

- Testing navigation flow and page accessibility

- Basic usability checks

### 2.3 API Testing

API testing validates communication between the frontend and backend.

Core checks:

- Correct responses for GET, POST, PUT, DELETE

- Validation of returned data structure

- Error handling

- Compliance with API specifications

### 2.4 Test Design Techniques

- The following techniques will be used:

- Black Box Testing

- Exploratory Testing

## 3. Software Risk Issues

- Insufficient or unclear product requirements  
- Lack of technical resources  
- Communication gaps between testers and developers  
- New functionality added during the sprint  

## 4. Features to Be Tested

### 4.1 Functionality (Unauthenticated User)

- Register a new user  
- Navigate the website  
- Receive alert-invitation to register  
- Restricted access to preparation guide and Pot creation  

### 4.2 Functionality (Registered User)

- Log in and log out  
- Change password  
- Delete account  
- Navigate all available pages  
- Open Preparation Guide  
- Add Pots (first, second, third)  
- Start Pot growth process  
- Receive confirmation and notification emails  
- Delete Pots (first, second, third)

### 4.3 User Interface

- Visual analysis of screens  
- Interaction with UI elements  
- Cross-browser compatibility  
  - Chrome  
  - Firefox  
  - Safari  

### 4.4 Integration Testing

- Identifying input data and expected output  
- Verifying data exchange across components  

### 4.5 Accessibility & Usability

- Basic accessibility checks  
- User-centered interaction evaluation 

## 5. Features Not to Be Tested

- Mobile and tablet versions of the application  
- Any out-of-scope third-party integrations  

## 6. Testing Tools and Software

### 6.1 Development Environment
- IntelliJ IDEA

### 6.2 Build System
- Maven

### 6.3 Testing Framework
- TestNG

### 6.4 UI Automation
- Selenium WebDriver

### 6.5 Version Control
- GitHub

### 6.6 API Testing
- Postman

### 6.7 Continuous Integration
- Jenkins

### 6.8 Documentation Tools
- Google Docs  
- Google Spreadsheets

### 6.9 Test Management
- Confluence  
- Trello

## 7. Entry and Exit Criteria

### 7.1 Entry Criteria

- Approved and finalized requirements  
- Test cases prepared and reviewed  
- Access to required test data  
- Test environment fully configured  
- Spot checks confirm readiness for execution  

### 7.2 Item Pass/Fail Criteria

**Fail**  
- A defect is identified and assigned severity  

**Pass**  
- All requirements for a test case are satisfied  

### 7.3 Exit Criteria

- 100% of critical test cases passed  
- Full functional coverage achieved  
- All high-priority defects resolved  
- No open blockers or Severity 1 issues 

## 8. Suspension and Resumption Criteria

### 8.1 Suspension

Testing may be suspended when:

- External dependent systems are unavailable  
- A blocking defect prevents further execution  

### 8.2 Resumption

Testing may resume when:

- Dependent systems become available  
- A fix for the blocking defect is delivered and confirmed  

## 9. Test Deliverables

- Completed test cases  
- Test execution results  
- Logged defects (with links to the bug tracking system)  
- Retest results  
- Final test summary report  

## 10. Remaining Test Tasks

- Final review of regression results  
- Updating documentation after fixes  
- Preparing acceptance testing notes 

## 11. Environmental Needs

### 11.1 Operating Systems
- Windows 10

### 11.2 Devices
- Lenovo Laptop, Intel Core i5 vPro, 8 GB RAM  
- HP ProBook 440 G4, 16 GB RAM  

### 11.3 Web Browsers
- Chrome  
- Firefox  
- Safari  
- Microsoft Edge  

## 12. Additional Staffing and Training Needs

No additional resources or training required.

## 13. Responsibilities and Schedule

### 13.1 Responsibilities

| Name               | Position | Responsibilities                                   |
|--------------------|----------|---------------------------------------------------|
| Evgeniya Turtschina | QA       | Test plan drafting, test design, test execution, user stories |

### 13.2 Schedule

| Stage                  | Date |
|------------------------|------|
| Requirements Analysis   |      |
| Test Design             |      |
| First Test Session      |      |
| Regression Testing      |      |
| Acceptance Testing      |      |

## 14. Risks and Contingencies

- Insufficient coverage of critical scenarios  
- Missing or unclear requirements  
- Environment instability  
- New features added mid-sprint  

**Mitigation:**  
- Use detailed checklists for coverage  
- Log and track defects in the bug tracking system  

## 15. Approvals

| Name        | Position     | Approval Comments |
|-------------|--------------|-------------------|
| Irina Baker | Head of QA   |                   |

