# :octicons-play-16: Continuous deployments, the GitHub way

<!-- markdownlint-disable MD030 MD033 -->

Although continuous deployment is a well-practiced concept in the industry, it appears many organization are still faced with the challenge of realising an effective and simplified implementation. This workshop, _"Continuous deployments, the GitHub way"_ demonstrates an archetypal implementation that gives due consideration to security and compliance; and achieves simplicity by identifying _bounded contexts_ (1) in the CI/CD domain that are fitting to relatable business value streams and mapping respective contexts to appropriate GitHub events.
{ .annotate }

1.  !!! question "🧐 What is _Bounded Context_?"

    > Bounded Context is a term from Domain-Driven Design (DDD), which refers to a decomposed part of a larger system where individual business models and their associated software artifacts can evolve independently. It promotes a clear separation of concerns, reduces complexity, and enhances flexibility within the system.
    >
    > ~ [What is Bounded Context?](https://www.dremio.com/wiki/bounded-context/){target="\_blank"}

    📚 Other thoughts on Bounded Context

    - [Bounded Context](https://martinfowler.com/bliki/BoundedContext.html){target="\_blank"} by Martin Fowler
    - [Using domain analysis to model microservices](https://learn.microsoft.com/en-us/azure/architecture/microservices/model/domain-analysis#define-bounded-contexts){target="\_blank"} by Microsoft Learn
    - [Domain Driven Design](https://medium.com/@johnboldt_53034/domain-driven-design-the-bounded-context-1a5ea7bcb4a4){target="\_blank"} — The Bounded Context by John Boldt

Essentially, the workshop is self-paced and can be can be independently completed anytime. During the live GitHub Universe session however, you will have the opportunity to directly interact with a GitHub expert and a super-user enterprise customer who already implemented the concepts with a successful outcome.

This workshop assumes participants already have some knowledge of GitHub Actions. Nevertheless, it is possible to follow and understand the demonstrations without prior experience of GitHub Actions or participants may refer to [**GitHub DevSecOps Fundamentals**](https://gh-devsecops.github.io/fundamentals){target="\_blank"} self-paced workshop to address basic gaps.

## What you will learn

- [ ] Apply event-driven system design thinking to continuous deployment
- [ ] Ensure compliance provenance and attestation for build artifacts
- [ ] Harden security of integration with a target cloud environment, using Open-ID Connect for implementation of identity federation

## Structure

The workshop has three main parts, namely

- **Prerequisites** This outlines requirements to take into consideration for a full learning experience. We aim to inspire confidence by presenting a scenario that is quite close to a regular experience in an average enterprise, for this reason a real cloud services environment is targeted for deployment in the workshop. However, to enable us make the best use of the time available for the live session, please do the prerequisites steps before the workshop begins.

- **Exercises** Before diving into the exercises, we will get an opportunity to see what the steps to a successful outcome looks like as demonstrated by an expert user.

- **Learning outcomes** At the end of the workshop, we will summarise learning achievements and give sometime for discussions. We have created a community to continue discussions beyond the live sessions, please feel free to use the Discussions to ask questions, share feedback about what you found valuable in the workshop and provide suggestions to help us continue to improve the workshop.

## Scope of the live session

Although the concepts presented in the workshop are applicable to the majority of cloud service providers and GitHub, we currently only support Microsoft Azure. However, since the workshop is open-source, we welcome you contributions and collaboration to support more cloud services provider.
