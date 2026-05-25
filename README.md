![Static Badge](https://img.shields.io/badge/Visual%20Studio%20Code-%230076B8?style=for-the-badge&logo=Visual%20Studio%20Code&labelColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/git%20-%23F05032?style=for-the-badge&logo=git&labelColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Django-%23092E20?style=for-the-badge&logo=Django)
![Static Badge](https://img.shields.io/badge/Python-%233776AB?style=for-the-badge&logo=Python&logoColor=%234584b6&labelColor=%23ffde57)
![Static Badge](https://img.shields.io/badge/HTML5-%23E34F26?style=for-the-badge&logo=HTML5&labelColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/CSS3-%232965f1?style=for-the-badge&logo=CSS3&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/PostgreSQL-%234169E1?style=for-the-badge&logo=PostgreSQL&logoColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/PGVector-%23123456?style=for-the-badge&logo=PGVector&logoColor=%23FFFFFF)
![Visual Studio 2022 C++](https://img.shields.io/badge/Developed%20with-Visual%20Studio%202022%20C%2B%2B-blueviolet?style=for-the-badge&logo=visual-studio&logoColor=white "Build using Visual Studio 2022 with the Desktop development with C++ workload")
![Static Badge](https://img.shields.io/badge/TensorFlow-%23FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=%23FF6F00&labelColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Pytorch-%23EE4C2C?style=for-the-badge&logo=Pytorch&logoColor=%23FF6F00&labelColor=%23FFFFFF)
![Static Badge](https://img.shields.io/badge/Docker-%230db7ed?style=for-the-badge&logo=Docker&logoColor=%23FFFFFF)


# Truth Table: A Logic Expression Evaluator

A **truth table** is a fundamental tool in logic and mathematics, used to determine the functional values of logical expressions based on the truth values of their component variables. It helps visualize how the truth or falsity of a compound statement is derived from the truth or falsity of its simpler parts.

To generate a truth table, you simply provide a logical expression or statement, such as:

`P AND Q` `P OR NOT Q` `(P IF THEN Q) IF AND ONLY IF (NOT P OR Q)`

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
  * Tool: `Pytest` with `Pytest-Django`
- **API Testing (Postman):**
  - Goal: To ensure that the backend API endpoints function correctly, return expected data formats, handle various HTTP methods, and enforce security policies. This bridges the gap between backend logic and frontend consumption.
  * Tool: `Postman`
- **End-to-End Testing (Frontend & User Flows - Cypress):**
  - Goal: To simulate real user interactions and verify that the entire application, from frontend UI to backend logic and database, functions correctly as a cohesive system. This ensures critical user journeys are unbroken.
  * Tool: `Cypress`

### Key Development Milestones

- **Core Feature Implementation**

  - User Authentication (Sign-up, Login, Password Reset): ✅ **Completed**
  - Data Persistence: ✅ **Completed**
  - Core Business Logic Functionality: 🚧 **In Progress** (Estimated 60% done)
  - User Profile Management: 🚧 **In Progress** (Estimated 35% done)

- **UI/UX Design & Integration**

  - Initial Wireframes & Mockups: 🚧 **In Progress**
  - High-Fidelity UI Design: 🚧 **In Progress** (Feedback currently being integrated)
  - Front-end Component Development: 🚧 **In Progress** (Estimated 55% done)
  - Responsive Design Adaptation: 🚧 **In Progress**

- **Bug Fixing & Performance Optimization**

  - Initial Bug Bash & Reporting: ✅ **Completed**
  - Critical Bug Fixes (Release Blocker): 🚧 **In Progress**
  - Performance Profiling & Optimization: 🚧 **In Progress**

- **Testing Phase**

  - Unit Tests for Core Business Logic: 🚧 **In Progress** (65% coverage)
  - Integration Tests for API Endpoints: 🚧 **In Progress** (Targeting 60% coverage by [9/15/2025])
  - User Acceptance Testing (UAT) Prep: ❌ **Not Started**

- **Refinement & Polishing**
  - Accessibility Review: ❌ **Not Started**
  - Internationalization (i18n) Readiness: 🚧 **In Progress**
  - Animation & Transformation Enhancements: ❌ **Planned**

### Current Sprint/Focus

**Sprint #3: Core Business Logic & Profile Management**

- Strategic Reprioritization: Truth Table App Development Paused: ⏩ **Blocked**

Progress on the Truth Table app is currently on hold as I'm strategically re-directing my efforts toward advanced human-centric AI development. This pivot is aimed at pioneering new frontiers in AI understanding and interaction, ensuring my capabilities remain at the cutting edge of the industry's evolution demands.

I'm establishing a revised timeline for the Truth Table app's resumption and I'll communicate updates as they become available. For more context on this strategic shift, please refer to [this detailed overview](https://github.com/brucethagwana/truthtable/issues/2).

### Latest Updates

- **May 22, 2026:** Completed architectural blueprint for Interface Driven Design: Finalized the technical roadmap to decouple core application domain logic from high-performance compute infrastructure. This lays the groundwork for Phase 1 (functional validation) and Phase 2 scaled-out (vLLM/Triton). See the `Architectural Strategy` specifications below.
- **July 21, 2025:** Homepage integrated: Providing a centralized project overview with robust user authentication capabilities.
- **June 30, 2025:** Work on the Truth Table project has been temporarily suspended.
- **June 17, 2025:** Completed integration for data persistence.
- **June 13, 2025:** Addressed critical login bug affecting certain user accounts.
- **June 9, 2025:** Began work on real-time core business logic functionality.

## 🏷️ Architectural Strategy

This repository adopts an **Interface Driven Design** approach, deliberately separating core application domain logic from the underlying high-performance compute infrastructure.

To reduce integration risk, our deployment roadmap is executed in two distinct phases:

### 1. Phase 1 (Current Target): Functional Domain Validation
The application layer communicates with models via an abstract adapter interface. This allows us to rapidly iterate on business logic, data validation pipelines, and UX flows using a lightweight, standard inference wrapper without managing heavy GPU infrastructure dependencies prematurely.

### 2. Phase 2 (Target Milestone): Infrastructure Scale-Out & Optimization
Once the domain logic stabilizes, we will swap out the basic inference wrapper for a production-grade Inference Layer without altering a single line of application code. This optimization phase will focus strictly on scaling throughput and driving down compute costs via:

* **In-Fight / Continuous Batching & PagedAttention:** Maximizing hardware utilization and memory efficiency.
* **Quantization Pipelines (FP8/INT4):** VRAM footprint reduction to enable larger models on cheaper hardware configurations.
* **Dedicated Serving Engines:** Compiling to fused CUDA kernels via specialized backends like vLLM, SGLang, or Triton Inference Server.

### ⚠️ Phase 2 Integration & Risk Mitigation Notes

To ensure a seamless transition between phases, our abstract adapter interface is explicitly designed to mitigate common leaky abstractions and operational bottlenecks associated with high-performance LLM engines:

* **Streaming & Chunking Semantics:** The interface enforces a strict protocol for Server-Sent Events (SSE), ensuring partial tokens, stop sequences, and token counts normalize identically whether served via a lightweight API wrapper or a self-hosted backend.
* **Metadata Pass-Through:** To preserve long-term optimization capabilities, the adapter accommodates upstream metadata (e.g., Logprobs, prompt token blocks, KV-cache metrics) without breaking application-layer validation.
* **Quantization & Semantic Drift Testing:** Because moving to FP8/INT4 can introduce subtle shifts in formatting compliance and instruction-following, the transition will include automated regression pipelines. These pipelines will verify both structural compliance (e.g., strict JSON schema validation) and semantic alignment (e.g., preserving reasoning capability and adherence to negative constraints).
* **Concurrency & Latency Variance under Continuous Batching:** Unlike the predictable latencies of standard Phase 1 cloud API wrappers, Phase 2's continuous batching engines introduce variable Time-to-First-Token (TTFT) and inter-token latency based on cluster load. The application layer's streaming client and UI/UX flows must be engineered to handle variable network jitter and delayed token delivery without timing out or degrading the user experience.
* **KV-Cache Optimization & Context Hydration:** To fully leverage PagedAttention and prefix caching in Phase 2, the abstract adapter interface must explicitly segregate static system prompts from dynamic user context. This ensures the underlying high-performance engine can efficiently hash and cache prompt blocks, preventing cache thrashing and reducing TTFT at scale.

> **🛑 Design Principle Note:** Always code to the interface (`AbstractLLMAdapter`), never to the implementation. If your application code requires an explicit check for whether it is talking to OpenAI or vLLM, the abstraction has leaked.


`#inference-layer` `#ai-systems-engineering` `#api-design` `#real-time-applications` `#mlops` `#llm-serving` `#vllm` `#gpu-optimization` `#triton-inference-server` `#system-design` `ai` `#software-engineering`

### Legend

- ✅ **Completed:** This task/milestone has been successfully finished.
- 🚧 **In Progress:** Work is actively being done on this task.
- ❌ **Not Started / Planned:** This task is planned for future development.
- ⏩ **Blocked:** This task cannot proceed due to an external dependency or issue.
- 🛑 **Design Principle:** Non-negotiable architectural requirements.

### Looking Ahead

Our next major goal is to achieve a stable beta version by [10/25/2025], followed by extensive user testing.

## License / Credits

Copyright © 2024 Bruce R. Thagwana. All rights reserved.
