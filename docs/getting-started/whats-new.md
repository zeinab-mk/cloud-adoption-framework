---
title: What's new 
description: Learn about recent updates to the Microsoft Cloud Adoption Framework for Azure. 
author: JanetCThomas 
ms.author: janet 
ms.date: 03/27/2020 
ms.topic: conceptual
ms.service: cloud-adoption-framework
ms.subservice: overview
---

<!-- markdownlint-disable MD024 -->

# What's new in the Microsoft Cloud Adoption Framework for Azure

Here's a list of recent changes made to the Cloud Adoption Framework.

This framework is built in collaboration with customers, partners, and internal Microsoft teams. New and updated content is released when it becomes available. These releases allow you to test, validate, and refine the guidance along with us. We encourage you to partner with us to build the Cloud Adoption Framework for Azure.

## April 14, 2020

We've brought all the Cloud Adoption tools and templates together in one place to make them easier to find. 

| Article | Description |
|----------|-------------|
| [Tools and templates](../reference/tools-templates.md) | Find the tools, templates and assessments that can help you accelerate your cloud adoption journey. | 

## April 4, 2020

Continued iteration of refinement to the Migrate and Ready guidance to more tightly align with feedback from Customers, Microsoft partners, and Internal Microsoft Programs.

### Migrate updates

| Article                                                                                                                 | Description                                                                                                                                                                                |
|-------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Migrate Methodology](../migrate/index.md)                       | These changes streamline the phases of the migration effort (Assess workloads, Deploy workloads, and Release workloads). The changes also remove the details regarding the migration backlog. Removing those details and referencing Plan, Ready, and Adopt methodologies instead creates flexibility for various different cloud adoption programs to better align with the methodology.  |
| Table of contents update                       | The Table of contents for the Azure Migration Guide and Process Improvements have been updated to reflect the changes to the methodology.  |

### Ready updates

| Article                                                                                                                 | Description                                                                                                                                                                                |
|-------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Refactor landing zones](../ready/landing-zone/refactor.md)                       | **New article:** Drawing from Ready workshops, this article demonstrates the theory of starting with an initial template, using decision trees and refactoring to expand the landing zone, and moving toward a future state of enterprise readiness. |
| [Expand your landing zone](../ready/considerations/index.md)                       | **New article:** Builds on the parallel iterations section of the refactoring article to show how various types of landing zone expansions would embed shared principles into the supporting platform. (Original content for this overview has been moved to the [Basic Landing Considerations](../ready/considerations/basic-considerations.md) node in the table of contents.) |
| [Test-driven development (TDD) for landing zones](../ready/considerations/test-driven-development.md)                       | **New article:** The refactoring approach is much improved through the adoption of a test-driven development cycle to guide landing zone development and refactoring. |
| [Landing zone TDD in Azure](../ready/considerations/azure-test-driven-development.md)                       | **New article:** Azure governance tools provide a rich platform for TDD cycles or Red/Green tests. |
| [Improve landing zone security](../ready/considerations/landing-zone-security.md)                       | **New article:** Overview to the best practices in this section, with a tie back to the TDD cycle. |
| [Improve landing zone operations](../ready/considerations/landing-zone-operations.md)                       | **New article:** List of best practices in the Manage methodology, with a transition to that modular approach to improving operations, reliability, and performance. |
| [Improve landing zone governance](../ready/considerations/landing-zone-governance.md)                       | **New article:** List of best practices related to Govern methodology, with a transition to that modular approach to improving governance, cost management, and scale. |
| [Start with enterprise scale](../ready/considerations/enterprise-scale.md)                       | **New article:** Demonstrate an approach that shows the differences in the process, when a customer starts with enterprise-scale landing zone templates. This article helps customers understand qualifiers that would support this decision. |
| Table of contents update                       | The Table of contents was updated to reflect the new articles.  |

## March 27, 2020

We've added guidance about the initial subscriptions you should create when you adopt Azure.

### Ready updates

| Article                                                                                                                 | Description                                                                                                                                                                                |
|-------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Create your initial Azure subscriptions](../ready/azure-best-practices/initial-subscriptions.md)                       | **New article:** Create your initial production and nonproduction subscriptions, and decide whether to create sandbox subscriptions, as well as a subscription to contain shared services. |
| [Create additional subscriptions to scale your Azure environment](../ready/azure-best-practices/scale-subscriptions.md) | Learn about reasons to create additional subscriptions, moving resources between subscriptions, and tips for creating new subscriptions.                                                   |
| [Organize and manage multiple Azure subscriptions](../ready/azure-best-practices/organize-subscriptions.md)             | Create a management group hierarchy to help organize, manage, and govern your Azure subscriptions.                                                                                         |

## March 20, 2020

We've added prescriptive guidance that includes the tools, programs, and content categorized by persona to drive successful deployment of applications on Kubernetes, from proof of concept to production, followed by scaling and optimization.

### Kubernetes

| Article                                                                                     | Description                                                                                                                                                                           |
|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Application development and deployment](../innovate/kubernetes/application-development.md) | **New article:** Provides checklists, resources, and best practices for planning application development, configuring CI/CD pipelines, and implementing site reliability engineering for Kubernetes. |
| [Cluster design and operations](../innovate/kubernetes/cluster-design-operations.md) | **New article:** Provides checklists, resources, and best practices for cluster configuration, network design, future-proof scalability, business continuity, and disaster recovery for Kubernetes. |
| [Cluster and application security](../innovate/kubernetes/cluster-application-security.md) | **New article:** Provides checklists, resources, and best practices for Kubernetes security planning, production, and scaling. |

## March 2, 2020

In response to feedback about continuity in the migration approach through multiple sections of the Cloud Adoption Framework, including Strategy, Plan, Ready, and Migrate, we've made the following updates. These updates are designed to make it easier for you to understand planning and adoption refinements as you continue a migration journey.

### Strategy updates

| Article                                                                       | Description                                                                                                                                    |
|-------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| [Balance the portfolio](../strategy/balance-the-portfolio.md)                 | Moved this article to appear earlier in the Strategy methodology. This gives you visibility into the thought process earlier in the lifecycle. |
| [Balancing&nbsp;competing&nbsp;priorities](../strategy/balance-competing-priorities.md) | **New article:** Outlines the balance of priorities across methodologies to help inform your strategy.                                         |

### Plan updates

| Article                                                             | Description                                                                                                                                                                           |
|---------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Assessment&nbsp;best&nbsp;practice](../plan/contoso-migration-assessment.md) | Moved this article to the new "Best Practices" section of the Plan methodology. This gives you visibility into the practice of assessing local environments earlier in the lifecycle. |

### Ready updates

| Article                                                                   | Description                                                                                                              |
|---------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| [What&nbsp;is&nbsp;a&nbsp;landing&nbsp;zone?](../ready/landing-zone/index.md)                 | **New article:** Defines the term landing zone.                                                                          |
| [First landing zone](../ready/landing-zone/first-landing-zone.md)         | **New article:** Expands on the comparison of various landing zones.                                                     |
| [Migrate landing zone](../ready/landing-zone/migrate-landing-zone.md)     | Separated the definition of the Cloud Adoption Framework blueprint from the selection of the first landing zone.         |
| [Terraform landing zone](../ready/landing-zone/terraform-landing-zone.md) | Moved to the new "Landing Zone" section of the Ready methodology, to elevate Terraform in the landing zone conversation. |

### Migration updates

| Article                                                                                          | Description                                                                                                                                                             |
|--------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Overview](../migrate/azure-migration-guide/index.md)                                            | Updated with a clearer description of the guide and fewer steps.                                                                                                        |
| [Assess](../migrate/azure-migration-guide/assess.md)                                             | Added a "Challenging Assumptions" section to demonstrate how this level of assessment works with the incremental assessment approach mentioned in the Plan methodology. |
| [Classification during assess processes](../migrate/migration-considerations/assess/classify.md) | **New article:** Outlines the importance of classifying every asset and workload prior to migration.                                                                    |
| [Migrate](../migrate/azure-migration-guide/migrate.md)                                           | Added a reference to UnifyCloud in the third-party tool options, in response to feedback at tier 1 conferences.                                                         |
| [Test,&nbsp;optimize,&nbsp;and&nbsp;promote](../migrate/azure-migration-guide/optimize-and-transform.md)        | Aligned the title of this article with other process improvement suggestions.                                                                                           |
| [Assess overview](../migrate/migration-considerations/assess/index.md)                           | Updated to illustrate that the assessment in this phase focuses on assessing the technical fit of a specific workload and related assets.                               |
| [Planning checklist](../migrate/migration-considerations/prerequisites/planning-checklist.md)    | Updated to clarify the importance of operations alignment during planning for migration efforts to ensure a well-managed workload following migration.                  |

<!-- test:ignoreNextStep -->
