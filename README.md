# Documentation on PR

<img width="448" height="217" alt="Image" src="https://github.com/user-attachments/assets/96d41f17-a26e-418b-9550-e10340fcf71a" />

---

## Author Information
| Last Updated On | Version | Author           | Level           | Reviewer               |
|-----------------|---------|------------------|-----------------|------------------------|
| 01-08-2025      | V1.0    | Kawalpreet Kour  | Internal Review | Pritam                 |
|                 |         | Kawalpreet Kour  | L0              | Shreya/Sharvari        |
|                 |         | Kawalpreet Kour  | L1              | Abhishek V             |
|                 |         | Kawalpreet Kour  | L2              | Abhishek Dubey/Rishabh sharma |

---
<details>
  <summary><strong>Table of Contents</strong></summary>

- [What is a Pull Request?](#what-is-a-pull-request)
- [Why Use a Pull Request?](#why-use-a-pull-request)
- [Advantages & Disadvantages](#advantages--disadvantages)
- [Best Practices](#best-practices)
- [Conclusion](#conclusion)
- [Contact Information](#contact-information)
- [References](#references)

</details>

---

## What is a Pull Request?

A Pull Request (PR) is a collaborative feature used in Git-based repositories like GitHub, GitLab, and Bitbucket. It enables contributors to propose changes they've made in a separate branch to be reviewed and merged into the main or target branch.

Pull Requests play a key role in maintaining code quality, fostering collaboration, and ensuring that all changes go through proper peer review before becoming part of the production codebase.

---

## Why Use a Pull Request?

|   Purpose                         | Description                                                                                  |
|-----------------------------------|----------------------------------------------------------------------------------------------|
| Collaborate on shared codebases   | Allows multiple developers to work on different features without directly affecting `main`. |
| Ensure code quality               | Enables reviewers to verify logic, style, and functionality before code is merged.          |
| Catch bugs early                  | Encourages early detection of issues through peer reviews and CI checks.                    |
| Keep main branch stable           | Prevents untested or incomplete code from being pushed directly to production.              |


---
## Advantages & Disadvantages

### Advantages

|   Benefits                       | Description                                                                                      |
|-------------------------------------|--------------------------------------------------------------------------------------------------|
| Enables code review and feedback    | Helps teams spot bugs early and improve code quality.                                            |
| Tracks changes and accountability   | Makes it easier to understand project history and who made which change.                         |
| Prevents breaking main branch       | Changes are reviewed and tested before merging.                                                  |
| Supports CI/CD integration          | Pull Requests can trigger automated testing pipelines.                                           |



### Disadvantages

|   Limitations                       | Description                                                                                      |
|-------------------------------------|--------------------------------------------------------------------------------------------------|
| Slower than direct commits          | Requires approvals and reviews, which may delay the merging process.                             |
| Possible merge conflicts            | Happens when multiple developers modify the same part of the codebase.                           |
| Needs communication & discipline    | Developers must review code properly and communicate clearly.                                    |

---

## Best Practices

|   Recommended Guidelines                             | Description                                                                                  |
|------------------------------------------------|----------------------------------------------------------------------------------------------|
| Create PR from feature branches                | Avoid raising PRs directly from `main`; use isolated branches for changes.                  |
| Write clear PR titles and descriptions         | Helps reviewers understand what the PR is about.                                             |
| Ensure your code compiles and passes tests     | Don’t raise a PR with broken or untested code.                                               |
| Keep PRs small and focused                     | Makes review easier and reduces the chance of bugs.                                          |
| Tag reviewers and respond to comments          | Keeps the review process active and collaborative.                                           |
| Link related issues or tickets                 | Helps track progress and gives context to reviewers.                                         |
| Use draft PRs when work is in progress         | Signals that the PR is not yet ready for a full review.                                      |


---

## Conclusion

Pull Request workflows promote clean, maintainable, and collaborative development. They are essential for teams practicing version control with Git and tools like GitHub or GitLab.

---

## Contact Information

| Name             | Email                          |
|------------------|--------------------------------|
| Kawalpreet Kour  | kawalpreet.kour.snaatak@mygurukulam.co |

---

## References

| Description                     | Link                                                                                          |
|---------------------------------|-----------------------------------------------------------------------------------------------|
| GitHub Docs – About Pull Requests | [GitHub Docs](https://docs.github.com/en/pull-requests)                                        |
| Atlassian Git Tutorials          | [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials/making-a-pull-request)      |
| GitLab – Merge Request Guide     | [GitLab Docs](https://docs.gitlab.com/ee/user/project/merge_requests/)                        |



---
