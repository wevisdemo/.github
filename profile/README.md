![WeVis: We visualize data for democracy](https://wevis.info/wp-content/uploads/2022/03/og-3.png)

See our live projects at https://wevis.info/

## Getting Started

A guide for getting started with the WeVis project

### 1. Set up the repository on WeVis GitHub
- If you don't have permission on [WeVis Github Org](https://github.com/wevisdemo), ask the maintainer to create a repo for you.
- Create `README.md` with [README Template](readme-template.md) to describe the project.

### 2. Add the design system

- WeVis provides a design system and components library for React, Svelte, and Vue. After setting up the tools/framework for the project, please follow the [official guide](https://wevisdemo.github.io/design-systems/).
- WeVis doesn't force the tools or framework. Feel free to choose the one that is suitable for each project.

### 3. Setup staging environment
The staging environment is a non-production deployment allowing team members to see the process while under development.
- On the opensource project, we recommend using [Github Action](https://github.com/features/actions) with [Github Page](https://pages.github.com/)
  - [GitHub Pages action](https://github.com/marketplace/actions/github-pages-action) can be used in GitHub Action's workflow file to deploy code to Github Page
  - Staging is updated (workflow is triggered) when code is pushed to the main branch by default. ([example workflow file](https://github.com/wevisdemo/design-systems/blob/main/.github/workflows/update-doc.yml))
  - Some projects requiring manual PM updates can use [manual trigger](https://docs.github.com/en/actions/managing-workflow-runs/manually-running-a-workflow). ([example workflow file](https://github.com/wevisdemo/reconstitution/blob/main/.github/workflows/staging.yml))
    - Only people with at least written permission in the repository can trigger workflow.
- If you belong to the PunchUp organization, Cloudflare Pages can also be used.

### 4. Production deployment
- Don't hesitate to contact the maintainer for production deployment.
