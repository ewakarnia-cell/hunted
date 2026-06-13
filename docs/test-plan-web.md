# Test Plan - Hunted Web Application

## Introduction
The Hunted Web Application is a browser‑based platform that enables users to search for jobs, manage applications, and track their progress. This Test Plan prescribes the scope, approach, resources, and schedule for all testing activities of the "Hunted" website.

---

## 1. Test Strategy

### 1.1 Testing Scope
#### 1.1.1 Features to be tested
| Module | Scope description |
| :--- | :--- |
| **Main page (Recruiters)** | Product info, comparison, CEO quotes, partner logos, CTA buttons. |
| **Main page (Engineers)** | Registration, links to Jobs/Web3, mobile app banner, feedback. |
| **Candidates list** | Display, pagination, filters, sign-in prompts. |
| **Filters** | Role, Technologies, Salary, Level, Location (authorization required). |
| **Candidate profile** | Profile details, contact visibility, experience sorting/expansion. |
| **Sign Up** | Multi-step forms, social login (Google/LinkedIn/GitHub), validation. |
| **Sign In** | Login form, validation, error messages, Forgot Password. |
| **Chats** | Initiation, visibility rules, approval/rejection, offers. |
| **Profile** | Editing, role switching, social accounts, activation/deactivation. |
| **Footer** | Web3 companies, vacancies, social & documentation links. |
| **Web3 & Jobs** | Company listings, ATS import, 1-click apply, vacancy filters. |

#### 1.1.2 Out of test scope
* Admin functionality.
* Question/feedback forms.

### 1.2 Test types
* System & Integration Testing
* Functional, UI, & Usability Testing
* Form & Navigation Testing
* Regression & Exploratory Testing
* Permission / Role-Based & End-to-End Testing

### 1.3 Risks and Issues
| Risk | Mitigation |
| :--- | :--- |
| Lack of specific web testing skills | Internal training, pair testing, access to best practices. |
| Limited time for multi-browser testing | Priority-based matrix (Top 3 browsers). |
| Limited time for test scenarios | Prioritize Critical/High scenarios first. |
| Team member unavailability | Reassign critical tasks, adjust priorities. |

### 1.4 Test Logistics
* **Who will test?** QA Engineer (Ewa).
* **When?** Currently available production version and future updates.

---

## 2. Test Objective
To verify that core functionalities (authentication, browsing, filtering, profile interactions) meet requirements and provide a stable user experience.

---

## 3. Test Criteria
### 3.1 Suspension Criteria
* 10% of P0/P1 tests failed.
* 30% of P2/P3 tests failed.

### 3.2 Exit Criteria
* Execution rate: 95%.
* Pass rate: 100% for P0/P1, 80% for P2/P3.
* No Critical/Major bugs or High Priority defects remaining.

---

## 4. Resource Planning
### 4.1 System Resources
* **Browsers:** Google Chrome, Opera, Mozilla Firefox.
* **Network:** Stable Wi-Fi (min 10Mbps).
* **Hardware:** Laptop.

### 4.2 Human Resources
* **QA Engineer:** Documentation, execution, reporting.
* **Mentors:** Test case review.

---

## 5. Test Environment
Publicly available production version. No local environment setup required.

---

## 6. Schedule & Estimation
### 6.1 Effort Estimation
| Task | Effort |
| :--- | :--- |
| Test Plan | 3 man-hours |
| Decomposition, Decision Table, State Diagram | 20 man-hours |
| Test Case Creation | 80 man-hours |
| Test Case Review | 16 man-hours |
| Execution | 40 man-hours |
| Bug Reporting | 16 man-hours |
| Test Summary Report | 8 man-hours |

---

## 7. Test Deliverables
* **Before:** Plan, Decomposition, Test Cases, State Diagram, RTM.
* **During:** Test Data, Execution logs, Bug Reports.
* **After:** Test Summary Report, Defect Report, Release Notes.
