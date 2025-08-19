## Awesome Forge 
![Awesome](https://awesome.re/badge.svg) [![Linkspector](https://github.com/andrei-pisklenov/awesome-forge/actions/workflows/action.yml/badge.svg)](https://github.com/andrei-pisklenov/awesome-forge/actions/workflows/action.yml) [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
![](./media/awesome-forge-intro.png)

> Curated list of libraries, examples, tools and learning material for building [Atlassian Forge](https://developer.atlassian.com/platform/forge/) apps ✨

Forge lets you build secure, scalable apps for Jira, Confluence, and more without managing infrastructure. 
Below you'll find everything you need to go from “Hello World” to Marketplace-ready.

---

## Contents

- [Awesome Forge](#awesome-forge)
- [Contents](#contents)
  - [Official Resources](#official-resources)
  - [Community](#community)
  - [Starter Template](#starter-templates)
  - [Official Examples](#official-examples)
  - [Community Examples](#community-examples)
  - [Articles](#articles)

---

### Official Resources

- [Official Guide](https://developer.atlassian.com/platform/forge/) - Main hub for Forge development documentation.
  - [Getting Started with Forge](https://developer.atlassian.com/cloud/jira/software/getting-started-with-forge/) - Official beginner tutorial for building your first Forge app in Jira, Confluence, or JSM.
  - [Automate Jira with Triggers](https://developer.atlassian.com/platform/forge/tutorials-and-guides/) - Learn to respond to Jira issue events with Forge triggers and backend functions.
  - [Build a Custom UI App (Confluence or Jira)](https://developer.atlassian.com/platform/forge/tutorials-and-guides/) - A practical walkthrough for building apps using Custom UI in Forge.
- [Forge Modules](https://developer.atlassian.com/platform/forge/manifest-reference/modules/) - Learn about available modules you can use in Forge apps.
- [Youtube: Atlassian Developer channel](https://www.youtube.com/@AtlassianDeveloper/videos) - Videos and tutorials directly from Atlassian engineers.
  - [Patterns for Integrating Forge with External Services](https://www.youtube.com/watch?v=IsxVoOK7wH0) - queues, remotes, and event handling.
  - [Atlassian presents Forge in 5](https://www.youtube.com/watch?v=34HHK58nvVA) - Atlassian presents Forge in 5 | Episode 1: Intro to building Atlassian apps.
- ["Get the most out of Forge" learning path](https://community.atlassian.com/learning/path/get-the-most-out-of-forge) - Official structured learning journey for developers.
- [Forge Roadmap](https://developer.atlassian.com/platform/forge/roadmap) – See what's coming next for Forge.
- [Changelog](https://developer.atlassian.com/platform/forge/changelog/) - The source of truth for all changes to the Forge platform that affect people developing Forge apps.
- Cloud REST APIs
  - [Jira REST API](https://developer.atlassian.com/cloud/jira/platform/rest/v3)
  - [Confluence REST API](https://developer.atlassian.com/cloud/confluence/rest/v2)
  - [Bitbucket REST API](https://developer.atlassian.com/cloud/bitbucket/rest/intro)
- Tools / Libraries
  - [Forge CLI](https://developer.atlassian.com/platform/forge/cli-reference/) - Command-line tool for developing and deploying Forge apps.
  - [UI Kit docs](https://developer.atlassian.com/platform/forge/ui-kit/) - Build UIs quickly with pre-built Atlassian components.
  - [Custom UI docs](https://developer.atlassian.com/platform/forge/extend-ui-with-custom-options/) - Build fully customized frontends using React.
  - [Atlassian Design System](https://atlassian.design/) - Design guidelines and components for building Atlassian-like interfaces.
  - [Forge Tunnel](https://developer.atlassian.com/platform/forge/tunneling/) - Enable live development and debugging of Forge apps.
- Marketplace & Monetisation
  - [Developer console](https://developer.atlassian.com/platform/forge/manage-your-apps/) - Manage your Forge apps and track metrics.
  - 💰 [Atlassian Marketplace Partner Program](https://developer.atlassian.com/platform/marketplace/marketplace-partner-program/) - Learn how to publish and monetize your apps.
- Security & Compliance
  - [Security for Forge apps](https://developer.atlassian.com/platform/forge/security/) - Best practices and security models.
  - [Data residency](https://developer.atlassian.com/platform/forge/data-residency/) - Understand where customer data is stored and how to comply.

---

### Community

- [Developer Community](https://community.developer.atlassian.com/c/forge/45) - Ask questions and share knowledge with other Forge developers.
- [Slack: Marketplace Clarity - Forge](https://marketplace-vendors.slack.com/archives/CMVD09M7U) - Private Slack for Marketplace Partners (invite required).

---

### Starter Templates

- [Forge Starter](https://github.com/andrei-pisklenov/forge-starter) - TypeScript, React 19, Vite, yarn monorepo with shared packages and build tooling. Great for scaling multiple apps.
- [forge-dev-kit](https://github.com/finesoftware/forge-dev-kit) - TypeScript, React, Emotion, Next.js.

---

### Official Examples

- [Official Examples (Bitbucket)](https://bitbucket.org/atlassian/workspace/projects/FE) – Collection of reference implementations provided by Atlassian.
  - [forge-jql-function-example](https://bitbucket.org/atlassian/forge-jql-function-example/src/master/) - Jira, JQL function.
  - [Forge Issue Countries](https://bitbucket.org/atlassian/forge-issue-countries/src/master/) - Jira, UI Kit, Issue Panel, REST calls.
  - [Forge UI modifications example](https://bitbucket.org/atlassian/forge-ui-modifications-example/src/master/) - Jira, UI Modifications, multiple Custom Ui's.
  - [forge-ui-kit-frame-project-logo-designer](https://bitbucket.org/atlassian/forge-ui-kit-frame-project-logo-designer/src) - Confluence, Macro, Global Page, UI Kit, External permissions.
  - [Question generator app - i18n for UI Kit](https://bitbucket.org/atlassian/question-generator-app-i18n-for-ui-kit/src) - Confluence, Macro, UI Kit, i18n.
  - [Forge UI Kit Frame Clean Slate](https://bitbucket.org/atlassian/forge-ui-kit-frame-clean-slate/src) - Confluence, Global Page, Frame, Custom UI in UI Kit.
  - [Macro auto convert app for UI Kit](https://bitbucket.org/atlassian/macro-auto-convert-app-for-ui-kit/src/master/) - Confluence, Macro, Autoconvert, UI Kit.
  - [book-management-typescript](https://bitbucket.org/atlassian/forge-sql-examples/src/main/book-management-typescript/) - Confluence, Macro, Forge SQL, Scheduled Trigger, App Trigger, Web Trigger, Eslint, TSConfig.
- [Official Examples (Github)](https://github.com/atlassian-labs) - Atlassian Labs' GitHub repository featuring various examples and libraries, including several Forge-related projects.
  - [Issue Status Helper](https://github.com/atlassian-labs/issue-status-helper) - Jira, Trigger, Admin Page, Project Page, Custom UI, Jira REST API (requestJira), Storage (old).

---

### Community Examples

- [A few app examples](https://github.com/andrei-pisklenov/forge-by-example) – A collection of simple real-world examples and recipes to speed up Forge development.
  - [all-modules-in-one-app](https://github.com/andrei-pisklenov/forge-by-example/tree/main/all-modules-in-one-app) - manifest file example with almost all modules, permissions, and Custom UI.
  - [custom-field-attachments-count](https://github.com/andrei-pisklenov/forge-by-example/tree/main/custom-field-attachments-count) - Jira, Custom Field, Jira REST API.
  - [custom-field-attachments-size](https://github.com/andrei-pisklenov/forge-by-example/tree/main/custom-field-attachments-size) - Jira, Custom Field, Jira REST API.
  - [performance-checks](https://github.com/andrei-pisklenov/forge-by-example/tree/main/performance-checks) - Jira, Webtrigger, Entity Properties, Storage (old).
- [Forge Todo App with Privacy-First Analytics](https://github.com/sherlockscore/forge-todo-example-with-analytics-app) - Jira, Issue Panel, Scheduled Trigger, Async Event, External Permissions, Custom UI, kvs.

---

### Articles

- ["Forge Explained: Supercharge Jira Work Item with Custom Actions" by Andrei Pisklenov](https://www.linkedin.com/pulse/forge-explained-supercharge-jira-work-item-custom-andrei-pisklenov-jgkwf/) – A deep dive into Custom UI, deploy best practices, and error handling (April 2025).
- ["Building an enterprise-grade Jira bulk operations Forge app" by Dugald Morrow](https://www.atlassian.com/blog/developer/building-an-enterprise-grade-jira-bulk-operations-forge-app-2) – Case study on architecture and scaling strategies (July 2025).
- ["The basics of creating a Forge AI app" by Dugald Morrow](https://www.atlassian.com/blog/developer/forge-ai-basics) – Quickstart for building apps that leverage AI in Forge (September 2023).
- [Kickstart Your Next App: Tips for Developing on Forge](https://www.atlassian.com/blog/it-teams/kickstart-your-next-app-tips-for-developing-on-forge) - Real-world tips comparing Custom UI vs UI Kit, deployment, and tooling strategies (January 2022).
- [Three Lessons from Building 80 Forge Apps](https://www.atlassian.com/blog/developer/forge-on-forge-three-lessons-we-learned-building-80-forge-apps) - Lessons from Atlassian’s internal team after building dozens of Forge apps (October 2022).
- [How to Build Observability for Forge Applications](https://www.easyagile.com/blog/how-to-build-observability-for-atlassian-forge-applications) - Logging, metrics, and monitoring best practices for production-grade Forge apps (March 2025).
- [Why Use Atlassian Forge? Benefits, Pricing & Use Cases](https://titanapps.io/blog/atlassian-forge) - High-level overview comparing Forge with other frameworks and monetization options (March 2025).
- [Developing a Jira App: Three Tips for Atlassian Forge App Development](https://www.moserit.com/blog/three-tips-for-atlassian-forge-app-development) - UI Kit vs. Custom UI, check Forge license, Personal Data Handling Requirements (July 2024)

---

> 💡 Do you know a useful resource, template, or example? Feel free to open a PR and contribute to this list!
