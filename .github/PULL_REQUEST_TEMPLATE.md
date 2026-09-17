## Description

### **Summary of Changes**

The leader must add a template file containing three core sections:

1. **Description:** A space for team members to explain what changes were made in their branch and cite any related issue.
2. **Type of Change:** Checkboxes to categorize the PR as a:
* Bug fix
* New feature
* Documentation update

3. **Checklist:** A review checklist ensuring the committer has:
* Followed project style guidelines and self-reviewed their code.
* Added inline comments for complex code segments.
* Updated the documentation (`README.md`).
* Confirmed that no new warnings or failing unit tests were introduced.

---

### **Related Issue Context**

* **The Issue Being Solved:** Merging individual developer branches directly into `main` without structured reviews risks introducing breaking bugs, unverified changes, or conflicting code into the shared project base.
* **How the PR Template Resolves It:** It enforces peer review, quality assurance, and accountability by requiring every team member to explicitly verify their work against a set checklist before their branch can be merged into the `main` branch.

---

## Type of Change

Select the option(s) that apply:

* [ ] **Bug fix** (non-breaking change fixing an issue)
* [✅] **New feature** (non-breaking change adding functionality)
* [ ] **Breaking change** (fix or feature that breaks existing functionality)
* [✅] **Documentation update** (changes or additions to project documentation)

---

## Checklist

Ensure all relevant items are completed before submitting your PR:

* [✅] My code follows the style guidelines of this project.
* [✅] I have performed a self-review of my own code.
* [✅] I have commented my code, particularly in hard-to-understand areas.
* [✅] I have made corresponding changes to the documentation.
* [✅] My changes generate no new warnings.
* [✅] I have added tests that prove my fix is effective or that my feature works.
* [✅] New and existing unit tests pass locally with my changes.
