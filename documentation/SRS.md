# Software Requirements Specification (SRS)
## CodeForge – Competitive Programming Practice Platform

### 1. Introduction
#### 1.1 Purpose
This document outlines the specifications for CodeForge, a competitive programming practice platform enabling users to solve coding problems with automated server-side execution and detailed verdict analysis.

#### 1.2 Scope
- Practice coding problems by difficulty and tags
- Secure online code execution using Judge0 API
- Automated verdict system (AC/WA/TLE/MLE/CE)
- Submission tracking and analytics
- Leaderboards and ranking system
- Problem setter and admin dashboards
- Responsive web application

#### 1.3 Intended Audience
- Stakeholders, Developers, Testers, Designers, System Administrators

#### 1.4 Product Features
- User registration & login (JWT-based authentication)
- Role-based access control (Admin, Setter, User)
- Problem creation with visible and hidden test cases
- Problem filtering and search
- Monaco-based online IDE
- Multi-language support (C++, Java, Python, JavaScript)
- Dual execution engine
- Per-test-case verdict breakdown
- Submission history & analytics
- Leaderboard and badge system
- Discussion forum with moderation
- Plagiarism detection
- Dark/Light mode

### 2. Functional Requirements (FR)
- **FR001**: User Registration - Allow user registration with validation (Priority 1, Medium Risk)
- **FR002**: Authentication - JWT based login system (Priority 1, High Risk)
- **FR003**: RBAC - Role based access control (Priority 1, High Risk)
- **FR004**: Problem Creation - Setters create problems with test cases (Priority 1, Medium Risk)
- **FR005**: Dual Execution - Execute user & expected solution (Priority 1, Critical Risk)
- **FR006**: Verdict System - Generate AC/WA/TLE/MLE/CE (Priority 1, High Risk)
- **FR007**: Submission History - Store submission attempts (Priority 2, Low Risk)
- **FR008**: Leaderboard - Rank users (Priority 2, Medium Risk)
- **FR009**: Plagiarism Detection - Detect similar code (Priority 1, Critical Risk)
- **FR010**: Discussion Forum - Threaded comments system (Priority 2, Medium Risk)

### 3. Non-Functional Requirements (NFR)
- **NFR001**: Performance - Response time < 2 seconds
- **NFR002**: Concurrency - Support 500 concurrent users
- **NFR003**: Secure Execution - Sandboxed execution
- **NFR004**: Data Security - Password hashing & HTTPS
- **NFR005**: Availability - 99% uptime
- **NFR006**: Scalability - Cloud horizontal scaling

### 4. Revision History
- 2026-08-15: Initial SRS draft created by Jeet Maheshwari.

- 2026-08-18: Problem management specifications reviewed by Vivek Savaliya.

- 2026-10-12: Community guidelines integrated by Harsh Abhichandani.
