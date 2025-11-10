## Vacation Tracking System

### Vision:
Replacing manual process of vacation requests by an automated rules-based validation system, for achieving the following goals:
1. Enabling employees to manage thier vacation requests using easy-use system.
2. Saving time and money mostly in HR department.
3. Speed up the process by minimize manual approval of immdediate manager to at most one (if needed).
### Domain (Problem defined)
In the past, all vacation time had to be approved by an immediate manager and then checked by a clerk in the HR department before it was authorized.
Sometimes this manual process could take days. 
### Functional Requirements:
1. Implements a flexible rules-based system for validating and verifying leave time requests.
2. Enables manager approval (if needed).
3. Dispalying employee's requests for previous year.
4. Allowing Requests to be made up to a year and a half in the future
5. Uses e-mail notification to request manager approval and notify employees of request status changes.
6. Keeps activity logs for all transactions.
7. Enables the HR and system administration personnel to override all actions restricted by rules, with logging of those overrides.
8. Allows managers to directly award personal leave time (with system-set limits)
9. Interfaces with the HR department legacy systems to retrieve required employee information and changes.
10. Provides a Web service interface for other internal systems to query any given employee’s vacation request summary.
### Non-Functional Requirements:
1. Uses existing hardware and middleware.
2. Implemented as an extension to the existing intranet portal system.
3. uses the portal’s single-sign-on mechanisms for all authentication.
### Constraints:
1. Uses existing hardware and middleware may evoke unexpected problems related to legacy technology or servers, leading to difficulty in integration.
### Assumptions:
 The rules and employees data are avaliabe and well-documented
### Actors and thier activites
1. Employee: is the main user of the system. He uses the system to manage his/her vacation time.
2. Manager: approves employee's request or rejects. Award time to subordinates.
3. HR ClerK: views employees time, entering or updating employee vacation data in the system. override leave records, manage locations
4. System Admin: back up system logs.
### ERD Model
<img width="1366" height="751" alt="VTS-Entities" src="https://github.com/user-attachments/assets/1c41b1a8-4d68-4b1a-b314-dc5c5bdc692b" />

### Entities Relations Model
<img width="1071" height="531" alt="task1-ERD-Entities Relations drawio" src="https://github.com/user-attachments/assets/3e69ccc6-8a89-4004-8c4b-1ff00f345626" />


## Use Cases
### 1- Manage Time
### 1-1 Submit Request
<img width="1961" height="771" alt="VTS-submit request" src="https://github.com/user-attachments/assets/7f73e407-fdb9-4e6d-9734-a93599976ed6" />


### 1-2 Approve/Reject Request
<img width="1412" height="872" alt="VTS-approve request" src="https://github.com/user-attachments/assets/40662951-f53d-4ed3-8673-8fe343e70288" />


### 1-3 Cancel Approved Request
<img width="1412" height="872" alt="VTS-approve request" src="https://github.com/user-attachments/assets/089a17e2-70db-4159-8de1-8e3e0f0e23da" />

### 1-4 Withdraw Pending Request
<img width="1826" height="792" alt="VTS-withdraw request" src="https://github.com/user-attachments/assets/3ea36bb2-0564-4fda-a11e-4c52c95c37b1" />

### 1-5 Edit Pending Request
<img width="1941" height="1101" alt="VTS-edit request" src="https://github.com/user-attachments/assets/6e1f3817-aeca-4403-b260-19ccd4a23c29" />

## UI of Requests
### Employee Page
<img width="1893" height="504" alt="employee-requests" src="https://github.com/user-attachments/assets/9f2c463b-5e20-47e4-a11f-a8bc7ef7c153" />

### Manager Page
<img width="1894" height="678" alt="manager-requests" src="https://github.com/user-attachments/assets/ef8a0ba3-9bc3-45f3-aa28-18861b6cd5e0" />





