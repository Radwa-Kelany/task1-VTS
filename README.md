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
 The rules and employees date are avaliabe and well-documented
### Actors and thier activites
1. Employee: is the main user of the system. He uses the system to manage his/her vacation time.
2. Manager: approves employee's request or rejects. Award time to subordinates.
3. HR ClerK: views employees time, entering or updating employee vacation data in the system. override leave records, manage locations
4. System Admin: back up system logs.
## use Cases
## 1- Manage Time
## ERD Model
