# common-core
![Powered by](https://img.shields.io/badge/Powered%20by-Mulesoft-535597.svg)
  ![Unit test](https://gist.githubusercontent.com/jpontdia/2f22ca2ddf1ba473d6e2cff61cc2fba9/raw/common-core-ut.svg)
  ![Code coverage](https://gist.githubusercontent.com/jpontdia/2f22ca2ddf1ba473d6e2cff61cc2fba9/raw/common-core-cc.svg)
  ![Build](https://github.com/jpontdia/common-core/actions/workflows/build.yml/badge.svg)
  ![Build job](https://gist.githubusercontent.com/jpontdia/2f22ca2ddf1ba473d6e2cff61cc2fba9/raw/common-core-wf.svg)
<br>

Shared Mule library that provides reusable flows, resources and configuration settings common for all applications.

  > This project follows the standards defined in the Development Process Document in Anypoint Exchange. The details to compile and package the asset are in the Build Environment section. 

## Table of contents
1. [Description](#description)
1. [Configuration](#configuration) 

## Description

Multiple common components like flows, sub-flows, etc. to be re-used across the Mule projects. For example, common sub-flows can be used for logging, error-handling, shared business logic, etc.

1. Reusability: Common assets allow you to reuse existing components across multiple projects. This reduces development time and effort since you don't need to recreate the same functionality from scratch each time. By leveraging common assets, you can ensure consistency, standardization, and maintainability across your projects.

2. Consistency: When you have common assets, you establish a consistent development approach and design patterns across different projects. This promotes uniformity and makes it easier for developers to understand and maintain the codebase. It also helps in enforcing best practices and following established architectural guidelines.

3. Efficiency: By having a library of common assets, you can accelerate development cycles and deliver projects faster. Instead of reinventing the wheel, developers can focus on building business-specific logic while leveraging existing, tested, and reliable components.

4. Maintainability: When changes or updates are required, having common assets simplifies the maintenance process. You only need to modify the common asset in one place, and the changes will propagate to all projects using it. This reduces the effort required to fix issues, implement enhancements, or apply security patches.

5. Scalability: Common assets enable scalability by providing a foundation for building complex integration solutions. They allow you to easily add new features or functionalities to your projects without starting from scratch. As your organization grows and requirements evolve, having reusable components becomes even more crucial for efficiently managing the integration landscape.

6. Collaboration: Common assets foster collaboration among developers and teams. When everyone works with the same set of components, it promotes knowledge sharing, reusability, and collaboration across projects. Developers can learn from each other's work, share insights, and contribute to improving the common assets, which ultimately benefits the entire organization.

In summary, having a project with common assets like flows, configurations, and other reusable components brings numerous benefits, including reusability, consistency, efficiency, maintainability, scalability, and collaboration. It empowers developers to build integration solutions more effectively, accelerates development cycles, and ensures high-quality and reliable outcomes.

## Configuration

The next properties must be provided to run the service:

| Property                  | Description               |
| ------------------------- | ------------------------- |
| salesforce.keystore       | Keystore with cetificates to connect with Salesforce. Salesforce JWT Authentication |
| salesforce.consumerkey    | Salesforce Consumer Key   |
| salesforce.principal      | Salesforce User           |
| salesforce.storepassword  | Password for the keystore |

<br>

---

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Mulesoft Documentation](https://docs.mulesoft.com/general/)