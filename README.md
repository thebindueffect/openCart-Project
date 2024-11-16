# OpenCart Manual Testing Project - Frontend

This project demonstrates the manual testing process for the frontend of OpenCart, a popular eCommerce platform. The goal was to test various features of the OpenCart frontend to ensure that the functionality and user experience align with the provided functional requirements. Below is a breakdown of the testing activities, test scenarios, and test cases executed, along with additional insights and outcomes from the project.

## Table of Contents
- [Project Overview](#project-overview)
- [Test Plan & Methodology](#test-plan--methodology)
- [Test Scenarios & Test Cases](#test-scenarios--test-cases)
- [Test Execution & Results](#test-execution--results)
- [Requirement Traceability Matrix (RTM)](#requirement-traceability-matrix-rtm)
- [Bug Report](#bug-report)
- [Learnings & Insights](#learnings--insights)

## Project Overview

In this project, I performed manual testing on the frontend of the OpenCart website to validate its functionalities, ensuring they meet the expectations outlined in the functional requirement document. The test plan was created after a thorough analysis of the requirements, followed by the creation of detailed test scenarios and test cases. The testing covered all major aspects of the site, from user registration to checkout and account management.

## Test Plan & Methodology

1. **Analysis of Functional Requirement Document**  
   A detailed analysis of the functional requirements document was performed to understand the features and user flows that needed to be tested.

2. **Test Plan Preparation**  
   Based on the requirements, a comprehensive test plan was developed, which included the scope of testing, testing objectives, test scenarios, resource allocation, testing schedule, and risk mitigation strategies.

3. **Test Scenarios & Test Case Development**  
   Test scenarios were derived from the functional requirements, and for each scenario, specific test cases were designed with the following information:
   - Test case ID
   - Test case description
   - Test steps
   - Expected results
   - Actual results

4. **Test Environment Setup**  
   The OpenCart build was deployed on a local system using the XAMPP server, providing a suitable environment for testing.

## Test Scenarios & Test Cases

The following functionalities were tested based on the functional requirements:

1. **User Authentication**
   - Register a new user
   - Login
   - Logout
   - Forgot password

2. **Product Search and Comparison**
   - Search for products
   - Compare products

3. **Product Display Page**
   - View product details

4. **Shopping Features**
   - Add to cart
   - Add to wish list
   - Manage shopping cart
   - Checkout process

5. **User Account Management**
   - My Account
   - My Account Information (profile update)
   - Change password
   - Address book management
   - View order history and order information

6. **Returns and Transactions**
   - Product returns
   - Order history and transactions
   - Recurring payments

7. **Additional Features**
   - Reward points
   - Affiliate system
   - Newsletter subscription
   - Contact Us form
   - Gift certificate system
   - Special offers
   - Header, menu, and footer options
   - Currency selection

## Test Execution & Results

Once the test cases were developed, the build was deployed locally using XAMPP, and the following steps were carried out:

1. **Test Case Execution**  
   Each test case was executed manually by interacting with the OpenCart frontend. For each scenario, the actual results were compared with the expected outcomes.

2. **Bug Identification**  
   Any discrepancies or failures were logged as bugs and further investigated. Screenshots and detailed steps were provided to reproduce the issues.

3. **Defect Tracking**  
   Defects were tracked and categorized based on their severity (e.g., critical, major, minor). Issues were prioritized for resolution.

## Requirement Traceability Matrix (RTM)

A Requirement Traceability Matrix (RTM) was generated to ensure that all test cases correspond to a functional requirement. The RTM served as a reference to verify that the implemented features were tested thoroughly.

- **RTM Contents:**
  - Requirement ID
  - Test Case ID
  - Status (Pass/Fail)
  - Comments (if any)

The RTM helped ensure full coverage of the requirements and allowed for tracking the status of each requirement against the test execution.

## Bug Report

After executing the test cases, a detailed bug report was prepared, which included:

- Bug ID
- Summary of the issue
- Steps to reproduce
- Severity (Critical, Major, Minor)
- Expected vs. Actual results
- Screenshots (if applicable)
- Status (Open, In Progress, Resolved, Closed)

### Common Issues Found:
- UI inconsistencies across pages (e.g., font size, button alignment).
- Functional issues in product search (incorrect results, slow response times).
- Missing validation for certain form fields (e.g., email format, password strength).
- Issues with currency selection on checkout.
- Minor bugs in the "Order History" page (incorrect date formats, missing data).

## Learnings & Insights

This manual testing project provided me with valuable insights and experience in the following areas:

1. **Test Planning & Execution:**  
   - Developing a structured test plan and breaking down requirements into test scenarios and test cases improved my understanding of systematic testing.
   - Executing tests manually helped me focus on real-world user behavior and interface interactions.

2. **Bug Reporting:**  
   - Reporting and categorizing bugs efficiently helped improve communication with developers and provided clear guidance for resolving issues.
   - Understanding the importance of capturing detailed reproduction steps and adding supporting visuals (screenshots/videos) improved the bug resolution process.

3. **Test Environment Setup:**  
   - Setting up a local testing environment using XAMPP was a valuable learning experience, especially in configuring databases and connecting the build to the local server.

4. **Requirement Traceability:**  
   - Generating an RTM helped me understand the importance of mapping test cases to requirements, ensuring that all features are tested, and tracking the progress of each requirement.

5. **UI/UX Testing:**  
   - Observing and testing UI elements for usability (e.g., buttons, navigation, form layouts) deepened my appreciation for user experience and responsive design.

6. **Communication & Collaboration:**  
   - The project enhanced my ability to collaborate with developers and stakeholders by providing clear and concise bug reports and test case documentation.

## Conclusion

This manual testing project for OpenCart's frontend was a comprehensive exercise that allowed me to apply my testing skills to a real-world application. Through detailed planning, systematic execution, and effective communication, I was able to thoroughly assess the platform’s frontend functionality and provide valuable feedback to improve its quality.

Feel free to explore the test cases, bug reports, and other materials in the repository.

--- 🚀
