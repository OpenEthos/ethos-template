# **Contributing to OpenEthos**

First off, thank you for taking the time to contribute\! Your involvement is what makes the OpenEthos framework robust, secure, and truly open. We appreciate all forms of contribution—from code and documentation to bug reports and community support.

By participating in this project, you are expected to uphold our [Code of Conduct](CODE_OF_CONDUCT.md).

## **1\. Ways to Contribute**

There are many valuable ways to help the OpenEthos project:

* **Code**: Submit pull requests for bug fixes, new features, or performance enhancements in the core engine, agents, or APIs.  
* **Documentation**: Improve our guides, tutorials, installation instructions, and API references (in the ethos-docs repository).  
* **Policy Content**: Contribute new policy sets (e.g., CIS benchmarks for new services) or refine existing ones (in the ethos-policies repository).  
* **Report Issues**: Report bugs or suggest feature ideas using the GitHub Issues tracker.

## **2\. Getting Started**

### **2.1 Reporting Bugs**

If you find a bug in any OpenEthos component (e.g., ethos-engine, ethos-agent-aws, ethos-cli), please use the GitHub Issues tracker of the relevant repository.

* **Search First**: Check the existing issues to see if the bug has already been reported.  
* **Clarity**: Provide a clear, descriptive title.  
* **Steps to Reproduce**: Detail the exact steps and environment configuration needed to reproduce the issue.  
* **Expected vs. Actual**: Clearly describe what you expected to happen and what actually happened.  
* **Environment**: Include version information for the component and the operating system/cloud service involved.

### **2.2 Suggesting Enhancements**

If you have an idea for a new feature or improvement:

* **Use GitHub Discussions**: We prefer feature discussions to start in the main organization's **Discussions** tab under a "Feature Ideas" category to gather community feedback before committing to implementation.  
* **Scope**: Clearly define the scope and purpose of the enhancement. Explain the problem it solves and why it's important for the OpenEthos mission.

## **3\. Pull Request (PR) Workflow**

For code and documentation contributions, please follow these steps:

1. **Fork** the repository (e.g., OpenEthos/ethos-engine) to your personal GitHub account.  
2. **Clone** your fork locally:  
   git clone git@github.com:\<YourUserName\>/ethos-engine.git

3. **Create a New Branch**: Base your work off the main branch.  
   git checkout \-b feature/my-new-agent-check  
   \# OR  
   git checkout \-b fix/auth-bug-in-api

4. **Implement Changes**: Write your code, update documentation, or modify policy files.  
5. **Test**: Add or update unit and integration tests to cover your changes. All continuous integration (CI) tests must pass.  
6. **Commit**: Write clear, descriptive commit messages. We use the conventional commit specification (e.g., fix(agent): Corrected AWS S3 bucket naming validation).  
7. **Push** your changes to your fork.  
8. **Create a Pull Request**: Submit a PR from your branch to the main branch of the original OpenEthos repository.

## **4\. Pull Request Standards**

To ensure a smooth review process, please adhere to these standards:

* **One Feature/Fix Per PR**: Keep your PR focused on a single logical change. Larger features should be broken down into smaller, manageable pull requests.  
* **Testing**: New features **must** include tests. Bug fixes **should** include a regression test to prevent the issue from recurring.  
* **Documentation**: If you change functionality, you must update the associated documentation (code comments, README.md, or the ethos-docs repository if applicable).  
* **Clear Description**: Fill out the PR template completely, explaining the *what* and *why* of your changes.

## **5\. Coding Style and Conventions**

Consistency is key for maintainability.

* **Language Standards**: Adhere to the idiomatic style for the repository's language (e.g., go fmt for Go, standard linters for Python).  
* **Readability**: Prioritize clean, readable, and well-commented code.  
* **Dependencies**: Minimize the introduction of new external dependencies. Any new dependency must be thoroughly justified.

## **6\. License**

By submitting a Pull Request, you assert that:

* You are submitting your work under the same [LICENSE](LICENSE) that is used by the OpenEthos project.  
* You have the right to contribute the code under this license.

We look forward to collaborating with you\!
