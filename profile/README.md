# NatureAlpha code base

For managing projects and collaborating within NatureAlpha. Please read the guidelines and update the Repository 

## Repository Overview

| Repository | Description | Owner |
|------------|-------------|-------------|
| [app-tnfd](https://github.com/NatureAlphaAI/app-tnfd) | TNFD (Corp/FI) website | Carlos Mimoso
| [libs-ts](https://github.com/NatureAlphaAI/libs-ts) | TypeScript Libraries | Carlos Mimoso
| [libs-multiverse](https://github.com/NatureAlphaAI/libs-multiverse) | Nature+industry projects and wide-table metrics pipelines | Jasper Hajonides


### General Guidelines

- **Consistent Naming**:
  - When creating a new repository, use a prefix followed by a descriptive name:
    - `app-<app-name>`: For applications and end-user interfaces.
    - `libs-<library-name>`: For libraries and reusable code modules.
    - `data-<dataset-name>`: For datasets or data management scripts.
    - `tools-<tool-name>`: For utilities and scripts that support development and operations.
    - `docs-<documentation-name>`: For documentation, guides, and tutorials.
  - Example: `app-forest-monitor`, `libs-geo-utils`, `data-environmental-records`, `tools-deployment-scripts`, `docs-contribution-guidelines`.

- **Documentation**:
  - Ensure each repository has a comprehensive `README.md` file.
  - At a minimum, the `README.md` should describe the repository's purpose.
  - If applicable, include instructions on how to run the code, installation steps, usage examples, and any dependencies.

- **Branching, Commits, and Issues**:
  - Write branches, commits, and issues as descriptively as possible.
  - Branches should follow a consistent naming convention, such as `feature/short-description` or `bugfix/short-description`.
  - Commit messages should be meaningful and describe what the commit does. Use the format: `type(scope): message`.
  - Issues should clearly state the problem or feature request, including relevant details and context.
  - Merge requests (MRs) should clearly describe what is being added or changed. They should be issue-specific and not aggregate months of work.
  - Ensure that each MR is focused on a single issue or feature to facilitate easier reviews and integrations.


---

*This document is a living document and will be updated regularly to reflect the current practices and guidelines of the NatureAlphaAI organisation.*
