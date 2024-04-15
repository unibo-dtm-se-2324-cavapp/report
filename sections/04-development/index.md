---
title: Development
has_children: false
nav_order: 5
---

# Development

## DVCS
To track the development of our project, we used a Github repository and created a dedicated organization called `unibo-dtm-se-2324-cavapp`. The main repository is `Cavapp`, which was divided into several branches: the `main` branch contains project releases, and the `develop` branch was used for ongoing development. For each necessary feature that needed to be added, a new branch was created from `develop` called `feature/feature-name`, and the same was done for bug fixes.

![GitFlow](/imgs/git-flow.png)

Commits were written following the [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/) approach. A commit is therefore written in the following format:

```bash
<type>[optional scope]: <description>
```

The types of commits that have been adopted in our case are as follows:

- **build**: for changes related to the build system or external dependencies;
- **chore**: for changes that do not affect the production code;
- **ci**: for changes related to continuous integration;
- **docs**: for changes that only affect the documentation;
- **feat**: for the addition of a new feature;
- **fix**: when a bug is fixed;
- **perf**: for changes made to the code to improve performance;
- **refactor**: for changes to the code that do not relate to either bug fixes or the addition of a new feature (e.g., moving a method from one class to another);
- **style**: for changes that do not affect the meaning of the code (e.g., removing white spaces, formatting, etc.);
- **test**: for the addition of new tests or correction of existing tests.

## Implementation details

- Describe anything new AND relevant that you learned and are willing to report
    - For example, a class of which you are particularly proud

