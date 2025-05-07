# Postman Automation Test Usage Guide

This guide provides step-by-step instructions for using the Postman automation test, tracking and documenting test results, and integrating them into your QA Management Report.

## Prerequisites

- Access to the GitHub repository for the Postman automation test.
- Permissions to modify the QA Test Cases and Audit Log.
- Knowledge of the affected service or component.
- Familiarity with GitHub Actions and CI/CD pipelines.

## Steps and Guidelines
### 1. QA Test Cases
- Navigate to the `/test/data/QA_Test_Cases.csv` file in the repository.
- Add new intent test cases or update existing ones as needed.

### 2. QA Test Audit Log
- Open the `QA_Test_Audit.md` file located in the repository.
- Add a new entry in the following format, specifying:
    - Date and Time of the test.
    - Name of the QA person conducting the test.
    - Purpose for running the test.
    - Test description.
    - Test results.
    - Affected service or component (e.g., Mobile App, API, Web App).

Example entry:
```markdown
## Test Entry #1
- **Date and Time**: [Enter Date and Time]
- **Tester**: [Enter Tester's Name]
- **Purpose**: [Describe the purpose of running this test]
- **Affected Service**: [Specify the service/component affected]
- **Test Description**: [Provide a brief description of the test]
- **Test Results**: [Summarize the test results]
