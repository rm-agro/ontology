# Contributing to the RMAGRO Ontology

Thank you for your interest in contributing to the RMAGRO Ontology! Contributions are essential to improve the ontology and make it more useful for the community. We appreciate your efforts to help make this project better. Please take a moment to review the following guidelines before making your contribution.

---

## Branching and Workflow

To maintain a structured development process, we use the following branching strategy:

1. **Main Branch**:
   - The `main` branch contains the stable, production-ready version of the ontology.
   - Changes can only be merged into `main` from the `staging` branch after thorough review.

2. **Staging Branch**:
   - The `staging` branch is the primary integration branch where features and fixes are tested.
   - All changes from developer branches must be merged into `staging` for review before they can be merged into `main`.

3. **Developer Branches**:
   - Each developer has their own branch, named `developer-<name>` (e.g., `developer-jane`).
   - Developer branches must be based on `staging` and can only merge back into `staging`.

### Workflow Diagram

Here’s a diagram representing the branching strategy:

       Developer Branches
       (developer-jane, developer-john, etc.)
                 |
                 v
           Staging Branch
                 |
                 v
            Main Branch


### Workflow Steps

1. **Work in Your Developer Branch**:
   - Create a branch based on `staging`:
     ```bash
     git checkout staging
     git checkout -b developer-<name>
     ```
   - Make your changes in this branch.

2. **Open a Pull Request to Staging**:
   - Push your branch to the remote repository:
     ```bash
     git push origin developer-<name>
     ```
   - Open a pull request targeting the `staging` branch.
   - Ensure your pull request includes a clear description of your changes.

3. **Review and Test on Staging**:
   - The team reviews your pull request, and automated tests are run if applicable.
   - Once approved, your changes are merged into `staging`.

4. **Integrate into Main**:
   - Periodically, the `staging` branch is reviewed and merged into `main` after final testing and approval.

---

## How Can You Contribute?

### 1. Reporting Issues
If you find a bug, have a feature request, or notice something that could be improved, please [open an issue](https://github.com/rm-agro/ontology/issues). Provide as much detail as possible, including steps to reproduce the problem, and relevant versions of software and dependencies.

### 2. Suggesting Enhancements
We welcome suggestions for new features or improvements to existing features. To suggest an enhancement, [open an issue](https://github.com/rm-agro/ontology/issues) and describe your idea, why it would be useful, and how it could be implemented.

### 3. Submitting Pull Requests
If you are ready to contribute code or documentation, you can submit a pull request. Here’s how:
- Follow the branching and workflow process outlined above.
- Ensure your code adheres to the project's standards.

### 4. Improving Documentation
Good documentation helps users understand how to use the ontology and contribute to it. You can help by:
- Fixing typos, grammar, or formatting issues.
- Expanding the README or other documentation files.
- Translating documentation into other languages.

### 5. Reviewing Pull Requests
You can contribute by reviewing other contributors' pull requests. Provide constructive feedback, suggest improvements, or test changes.

---

## Guidelines for Contributing

- **Coding Standards:** Ensure your code adheres to the project’s coding style. Consistency is key.
- **Commit Messages:** Write clear and descriptive commit messages.
- **Testing:** Add tests for your changes, if applicable.
- **Documentation:** Update or add documentation as needed.

---

## Code of Conduct

By participating in this project, you agree to uphold the [Code of Conduct](link-to-code-of-conduct-file), which outlines the standards for respectful and inclusive behavior within our community.

---

## Contact

If you have any questions or need further assistance, feel free to contact the RMAGRO project team at [info@rmagro.org].

Thank you for your contributions!