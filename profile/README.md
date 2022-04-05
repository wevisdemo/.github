# WeVis: We visualize data for democracy

See our live projects at https://wevis.info/

## Getting Started

A guide for getting started with WeVis project

### 1. Set up the repository on WeVis GitHub
- If you don't have a permission on [WeVis Github Org](https://github.com/wevisdemo), asked the maintainer to create a repo for you.
- WeVis project is opensource (public) by default, but please confirm with the project manager.
  - Add MIT license for opensource project. [Adding a license to a repository
](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository)

### 2. Add the design system

- WeVis provide design system and components library for React, Svelte and Vue. After setting up tools/framework for the project, please follow the [official guide](https://wevisdemo.github.io/design-systems/).
- WeVis don't force the tools or framework. Feel free to choose the one that is suitable for each project.

### 3. Setup staging environment
- Staging environment is a non-production deployment allowing team members to see the process while underdevelopment.
- On opensource project, we recommend to use [Github Action](https://github.com/features/actions) with [Github Page](https://pages.github.com/)
  - [GitHub Pages action](https://github.com/marketplace/actions/github-pages-action) can be used in Github Action's workflow file to deploy code to Github Page
  - Staging is updated (workflow is triggerd) when code is pushed to main branch by default. ([example workflow file](https://github.com/wevisdemo/design-systems/blob/main/.github/workflows/update-doc.yml))
  - Some project that require manual update from PM can use [manual trigger](https://docs.github.com/en/actions/managing-workflow-runs/manually-running-a-workflow). ([example workflow file](https://github.com/wevisdemo/reconstitution/blob/main/.github/workflows/staging.yml))
    - Only people with at least write permission in the repository can trigger workflow.

### 4. Production deployment
- Please contact the maintainer for production deployment.
