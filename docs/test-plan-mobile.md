# Test Plan - Hunted Mobile Application (MVP)

## Introduction
The Hunted Mobile Application is an MVP (Android/iOS) designed to provide users with simplified access to essential features such as chat communication, IAM, and profile settings. This Test Plan prescribes the scope, approach, resources, and schedule for all mobile testing activities.

---

## 1. Test Strategy

### 1.1 Testing Scope
#### 1.1.1 Features to be tested
| Module | Scope description |
| :--- | :--- |
| **IAM** | Login, Logout, Registration flows, validation, session handling. |
| **Chat** | Sending/receiving messages, chat list, unread indicators. |
| **Profile Settings** | Editing info, updating avatar, changing password, saving settings. |
| **Navigation** | Bottom navigation, back transitions, screen flow. |
| **Push Notifications** | Receiving alerts and app launch from notifications. |

#### 1.1.2 Out of test scope
* Features not implemented in the mobile app.
* Web-only functionality.
* API, Performance, Security testing.
* Automation.

### 1.2 Test Types
* Functional & UI/UX Testing.
* Exploratory & Regression Testing.
* Compatibility Testing (OS versions, screen sizes).

### 1.3 Risks and Issues
| Risk | Mitigation |
| :--- | :--- |
| MVP scope limitations | Strictly test only implemented features; avoid feature requests. |
| Limited device coverage | Prioritize testing on most common OS versions/sizes. |
| Unstable builds | Perform smoke tests on each build before full execution. |

### 1.4 Test Logistics
* **Who will test?** QA Engineer (Ewa), Mentor (review).
* **When?** Production build.

---

## 2. Test Objective
To verify that mobile features (IAM, chat, profile) meet requirements and provide a stable UX across supported mobile devices.

---

## 3. Test Criteria
### 3.1 Suspension Criteria
* 10% of P0/P1 tests failed.
* 30% of P2/P3 tests failed.

### 3.2 Exit Criteria
* Execution rate: 95%.
* Pass rate: 100% (P0/P1), 80% (P2/P3).
* No Critical/Major bugs or High Priority defects remaining.

---

## 4. Resource Planning
### 4.1 System Resources
* **Devices:** Android.
* **Network:** Stable Wi-Fi or mobile data.

### 4.2 Human Resources
* **QA Engineer:** Project management, documentation, execution, reporting.
* **Mentors:** Review of test documentation.

---

## 5. Test Environment
Production version of the mobile application. No local environment/database setup required.

---

## 6. Schedule & Estimation
### 6.1 Effort Estimation
| Task | Effort |
| :--- | :--- |
| Test Plan | 3 man-hours |
| Decomposition & RTM | 10 man-hours |
| Test Cases | 20 man-hours |
| Test Case Review | 4 man-hours |
| Execution | 20 man-hours |
| Bug Reports | 6 man-hours |
| Writing Test Report | 4 man-hours |

---

## 7. Test Deliverables
* **Before:** Plan, Decomposition, Test Cases, State Diagram, RTM.
* **During:** Test Data, Execution logs, Bug Reports.
* **After:** Test Summary, Defect Report, Installation Procedures, Release Notes.
