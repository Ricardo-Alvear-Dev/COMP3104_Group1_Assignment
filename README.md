# COMP3104 — DevOps Group Assignment

> Collaborative Git workflows, branching strategies, and CI/CD integration.

---

## 👥 Project Team

| Role | Name | Student ID | GitHub Profile |
| :--- | :--- | :---: | :--- |
| **Team Lead** | Ricardo Alvear | `101536306` | [@ricardoalvear](https://github.com/ricardoalvear) |

---

## Git Branching Strategy

We follow a strict branch-and-merge workflow to maintain code quality:

* **Naming Convention:** `101536306-Ricardo-Alvear`
* **Integration:** Direct commits to `main` are restricted. All features and updates must be merged into `main` via **Pull Requests**.

---

## CI/CD Pipeline

Continuous Integration is automated via **GitHub Actions**. 

* **Workflow Config:** `.github/workflows/main.yml`
* **Trigger:** Runs automated checks and builds on every push or Pull Request to `main`.

---

## Quickstart & Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ricardo-Alvear-Dev/COMP3104_Group1_Assignment
   cd COMP3104_Group1_Assignment
