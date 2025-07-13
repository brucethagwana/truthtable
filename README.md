![Static Badge](https://img.shields.io/badge/Visual%20Studio%20Code-%230076B8?style=for-the-badge&logo=Visual%20Studio%20Code&labelColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/git%20-%23F05032?style=for-the-badge&logo=git&labelColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Python-%233776AB?style=for-the-badge&logo=Python&logoColor=%234584b6&labelColor=%23ffde57)
![Static Badge](https://img.shields.io/badge/HTML5-%23E34F26?style=for-the-badge&logo=HTML5&labelColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Django-%23092E20?style=for-the-badge&logo=Django)
![Static Badge](https://img.shields.io/badge/PostgreSQL-%234169E1?style=for-the-badge&logo=PostgreSQL&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/PGVector-%23123456?style=for-the-badge&logo=PGVector&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Docker-%230db7ed?style=for-the-badge&logo=Docker&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/CSS3-%232965f1?style=for-the-badge&logo=CSS3&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/TensorFlow-%23FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=%23FF6F00&labelColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Pytorch-%23EE4C2C?style=for-the-badge&logo=Pytorch&logoColor=%23FF6F00&labelColor=%23FFFFFF)


# Truth Table: A Logic Expression Evaluator

A **truth table** is a fundamental tool in logic and mathematics, used to determine the functional values of logical expressions based on the truth values of their component variables. It helps visualize how the truth or falsity of a compound statement is derived from the truth or falsity of its simpler parts.

To generate a truth table, you simply provide a logical expression or statement, such as:
> `P AND Q`
> `P OR NOT Q`
> `(P IF THEN Q) IF AND ONLY IF (NOT P OR Q)`

Once you provide the expression, our tool constructs the `truth table` displaying all possible truth values (**TRUE[T] or FALSE[F]**) for the variables and the resulting truth value for the entire expression.

## 🚀 App Development & Refinement Status

This section provides an overview of our progress in the development and refinement phase. We aim for transparency and regular updates.

### Current Tech Stack

This application is being developed using the following core technologies:

- **Backend Framework:** `Django`
- **Primary Language:** `Python`
- **Database:** `PostgreSQL`, `PGVector`
- **Frontend Templating:** `Django Templates`
- **Styling:** `Tailwind CSS`
- **Deployment:** `Docker`, `AWS EC2`

### Testing Stack

Our testing strategy employs a multi-layered approach to ensure the robustness, reliability, and user-friendliness of the 'Truth Table' App. We utilize a combination of **unit**, **integration**, **API**, and **end-to-end tests**, leveraging specific tools for each level:

- **Unit & Integration Testing (Backend - Pytest-Django):**
  - Goal: To verify individual components (units) of the Django backend work as expected in isolation, and that integrated modules function correctly together.
  * Tool: `pytest` with `pytest-django`
- **API Testing (Postman):**
  - Goal: To ensure that the backend API endpoints function correctly, return expected data formats, handle various HTTP methods, and enforce security policies. This bridges the gap between backend logic and frontend consumption.
  * Tool: `Postman`
- **End-to-End Testing (Frontend & User Flows - Cypress):**
  - Goal: To simulate real user interactions and verify that the entire application, from frontend UI to backend logic and database, functions correctly as a cohesive system. This ensures critical user journeys are unbroken.
  * Tool: `Cypress`

### Key Development Milestones

- **Core Feature Implementation:**
  - User Authentication (Sign-up, Login, Password Reset): ✅ **Completed**
  - Data Persistence: ✅ **Completed**
  - Core Business Logic Functionality: 🚧 **In Progress** (Estimated 55% done)
  - User Profile Management: 🚧 **In Progress**

- **UI/UX Design & Integration:**
  - Initial Wireframes & Mockups: 🚧 **In Progress**
  - High-Fidelity UI Design: 🚧 **In Progress** (Feedback currently being integrated)
  - Front-end Component Development: 🚧 **In Progress** (Estimated 40% done)
  - Responsive Design Adaptation: ❌ **Planned**

- **Bug Fixing & Performance Optimization:**
  - Initial Bug Bash & Reporting: ✅ **Completed**
  - Critical Bug Fixes (Release Blocker): 🚧 **In Progress**
  - Performance Profiling & Optimization: ❌ **Planned**

- **Testing Phase:**
  - Unit Tests for Core Business Logic: 🚧 **In Progress** (55% coverage)
  - Integration Tests for API Endpoints: 🚧 **In Progress** (Targeting 60% coverage by [9/15/2025])
  - User Acceptance Testing (UAT) Prep: ❌ **Not Started**

- **Refinement & Polishing**
  - Accessibility Review: ❌ **Not Started**
  - Internationalization (i18n) Readiness: 🚧 **In Progress**
  - Animation & Transformation Enhancements: ❌ **Planned**

### Current Sprint/Focus

**Sprint #3: Core Business Logic & Profile Management (June 23 - July 1, 2025)**

Our primary focus for this sprint is to finalize the core business logic functionality and begin implementing user profile management.

### Latest Updates

- **June 30, 2025:** Work on the Truth Table project has been temporarily suspended.
- **June 17, 2025:** Completed integration for data persistence.
- **June 13, 2025:** Addressed critical login bug affecting certain user accounts.
- **June 9, 2025:** Began work on real-time core business logic functionality.

### Legend

- ✅ **Completed:** This task/milestone has been successfully finished.
- 🚧 **In Progress:** Work is actively being done on this task.
- ❌ **Not Started / Planned:** This task is planned for future development.
- ⏩ **Blocked:** This task cannot proceed due to an external dependency or issue.

### Looking Ahead

Our next major goal is to achieve a stable beta version by [10/25/2025], followed by extensive user testing.

## License / Credits

Copyright © 2025 Bruce R. Thagwana. All rights reserved. 
