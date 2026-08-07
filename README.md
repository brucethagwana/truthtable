# Truth Table: Logic Expression Evaluator & AI Reasoning Platform

> **Research & Applied AGI Scope**: An Applied Sciences framework investigating the functional values of logical expressions to drive multi-agent orchestration, autonomous LLM decision trees, and deterministic state consensus.

![VS Code](https://img.shields.io/badge/Visual%20Studio%20Code-%230076B8?style=for-the-badge&logo=Visual%20Studio%20Code&labelColor=%23FFFFFF)
![Git](https://img.shields.io/badge/git%20-%23F05032?style=for-the-badge&logo=git&labelColor=%23FFFFFF)
![Django](https://img.shields.io/badge/Django-%23092E20?style=for-the-badge&logo=Django)
![Python](https://img.shields.io/badge/Python-%233776AB?style=for-the-badge&logo=Python&logoColor=%234584b6&labelColor=%23ffde57)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=for-the-badge&logo=HTML5&labelColor=%23FFFFFF)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%234169E1?style=for-the-badge&logo=PostgreSQL&logoColor=%23FFFFFF)
![PGVector](https://img.shields.io/badge/PGVector-%23123456?style=for-the-badge&logo=PGVector&logoColor=%23FFFFFF)
![Visual Studio 2022 C++](https://img.shields.io/badge/Developed%20with-Visual%20Studio%202022%20C%2B%2B-blueviolet?style=for-the-badge&logo=visual-studio&logoColor=white)
![PyTorch](https://img.shields.io/badge/Pytorch-%23EE4C2C?style=for-the-badge&logo=Pytorch&logoColor=%23FF6F00&labelColor=%23FFFFFF)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=%23FF6F00&labelColor=%23FFFFFF)
![Docker](https://img.shields.io/badge/Docker-%230db7ed?style=for-the-badge&logo=Docker&logoColor=%23FFFFFF)
![CSS3](https://img.shields.io/badge/CSS3-%232965f1?style=for-the-badge&logo=CSS3&logoColor=%23FFFFFF)

**Truth Table** is a hybrid logic-evaluation engine and multi-agent reasoning framework designed to bridge classical symbolic logic with modern probabilistic AI models. It maps complex multi-agent interactions and LLM decision pathways to formal logical truth values, delivering deterministic state evaluation, automated decision verification, and persistent semantic state memory.

---

## 🚀 Architecture & Key Features

* **Deterministic Logic Parser**: Parses boolean and multi-valued logical expressions into verifiable truth tables and evaluation graphs.
* **Multi-Agent Orchestration**: Directs autonomous agent consensus using formal logical bounds rather than purely probabilistic voting.
* **Semantic Vector Memory**: Integrates **PGVector** with **PostgreSQL** to perform similarity searches over reasoning trees and logical assertions.
* **High-Performance Native Core**: Built with **C++** extensions and modern **Python / Django** backends for computational efficiency.
* **Deep Learning Integration**: Leverages **PyTorch** and **TensorFlow** models to align neural representations with symbolic constraints.

---

## 🛠️ Tech Stack & Infrastructure Architecture

* **Backend Framework**: Django (Python 3.10+)
* **Database & Vector Store**: PostgreSQL with `PGVector` extension
* **Cloud & Infrastructure**: GCP (Google Cloud Platform) leveraging identity management efficiencies
* **Authentication & Identity**: Auth0 integrated with GCP IAM workflows for robust user access control
* **Compute & Machine Learning**: C++ (VS 2022 Workload), PyTorch, TensorFlow
* **Frontend Templating**: Django Templates, Tailwind CSS
* **Testing & Quality Assurance**: Pytest-Django, Postman, Cypress
* **Containerization**: Docker & Docker Compose

---

## 🏷️ Architectural Strategy: Interface Driven Design

This platform adopts an **Interface Driven Design** approach, deliberately separating core application domain logic from high-performance compute infrastructure.

### Phase 1: Functional Domain Validation & Identity Baseline
The application layer communicates with models via an abstract adapter interface (`AbstractLLMAdapter`). This allows rapid iteration on business logic, data validation pipelines, Auth0 authentication integrations, and UX flows using lightweight inference wrappers without managing heavy GPU infrastructure prematurely.

### Phase 2: Infrastructure Scale-Out & Optimization
Once domain logic and authentication pipelines stabilize, the basic inference wrapper is swapped for a production-grade Inference Layer without altering application code. Optimization focuses strictly on scaling throughput and driving down compute costs via:

* **In-Fight / Continuous Batching & PagedAttention**: Maximizing hardware utilization and memory efficiency.
* **Quantization Pipelines (FP8/INT4)**: VRAM footprint reduction to enable larger models on accessible hardware.
* **Dedicated Serving Engines**: Compiling to fused CUDA kernels via specialized backends (vLLM, SGLang, Triton Inference Server).

> **🛑 Design Principle**: Always code to the interface (`AbstractLLMAdapter`), never to the implementation. If application code requires an explicit check for whether it is talking to OpenAI or vLLM, the abstraction has leaked.

---

## 📊 Governance & Project Tracking

All active task tracking, bug reports, feature implementations, and sprint backlogs are managed dynamically on our GitHub Project Board following a **7-Step Business Process Optimization (BPO)** methodology.

👉 **[Access the Project Board & Research Roadmap](../../projects)**

---

## 💻 Getting Started

### Prerequisites
* **Docker** and **Docker Compose**
* **Python** 3.10+
* **PostgreSQL** with `PGVector` extension enabled

### Setup with Docker Compose

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/brucethagwana/truthtable.git](https://github.com/brucethagwana/truthtable.git)
   cd truthtable

---

## 📜 License & Credits

Distributed under the **MIT License**. See [`LICENSE`](https://github.com/brucethagwana/truthtable/blob/main/LICENSE.txt) for full details.

* **Author & Lead Researcher**: [Bruce Thagwana](https://github.com/brucethagwana)
* **Core Focus**: Multi-Agent Logic Orchestration & Autonomous LLM Reasoning Research

---

### 💬 Citation & Acknowledgments

If you use this framework or research matrix in your work, please cite it as:

```bibtex
@software{thagwana2026truthtable,
  author = {Thagwana, Bruce},
  title = {Truth Table: Multi-Agentic Logic & Reasoning Framework},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  url = {[https://github.com/brucethagwana/truthtable](https://github.com/brucethagwana/truthtable)}
}
