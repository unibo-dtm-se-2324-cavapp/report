---
title: CI/CD
has_children: false
nav_order: 9
---

# CI/CD

## High-level description

In our software project, we've implemented a robust CI/CD pipeline to ensure the integrity and quality of our codebase. Each component of the project is equipped with its own set of tests, covering functionality, edge cases, and integration scenarios.

Whenever a developer attempts to push new changes, typically via a pull request to the main branch, our CI/CD system springs into action. First, it runs a battery of code checks, including linting and formatting validations, to maintain consistency and adherence to our coding standards. Following this, the system executes the suite of tests associated with the modified code, ensuring that new changes don't inadvertently break existing functionality.

Furthermore, we incorporate code coverage analysis into our pipeline, generating comprehensive reports to gauge the effectiveness of our test suite. If all checks pass successfully, the pipeline automatically triggers the creation of a new release version. Leveraging semantic release specifications, this versioning process is seamlessly tied to the commit history, providing clear and meaningful version increments. The newly minted release is then published directly to our GitHub repository, making it accessible to stakeholders and users.

In the event that any of the checks fail, the CI/CD pipeline acts as a gatekeeper, preventing the merge of faulty code into the main branch. By enforcing this automated process, we ensure that our codebase remains coherent over time, aligned with the established development conventions agreed upon by the team. Moreover, it facilitates the early detection of potential errors introduced by new modifications, enhancing the overall stability and reliability of our software.

