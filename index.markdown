---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Welcome to The Return of the Consumer.

---

Do you want to save money for choosing a test strategy that requires subscription?

Do you want to be less dependent on your E2E- and integration tests?

Are you struggling with contract testing your gateways?

Are you struggling with contract testing against your external provider’s APIs?

Do you want an easy and proven method for implementing Consumer-driven contract testing in an organisation?

## Prerequisites

Are your company currently using or plan to use microservices architecture? If not, you should stick with traditional monolith tests.

Are you a medium sized or large sized company (50 + employees in IT)? If not, you can must likely implement CDCT following Pact without our extension.

Are you using Docker, Kubernetes or similar in your infrastructure? If not, you should investigate what Pact in itself has to offer. 

Do you have the ressources for implementing a new test strategy in your organisation? If not, you can use traditional tests. 

Do you have the following prequisite knowledge? If not, you should properly choose a different test strategy.


<details>
<summary>Prerequisite knowledge</summary>

- Basic understanding of how APIs communicate (request/response, HTTP methods, payloads)

- Experience with testing APIs

- A development workflow that includes version control and CI/CD

- The ability to run and manage multiple services (e.g., using Docker or similar tools)

</details>
 

## When should you use this method?
- You should consider this method if your organisation experiences one or more of the following:
- You rely heavily on end-to-end or integration tests that are slow, unstable, or difficult to maintain
- You want faster feedback in your CI/CD pipeline
- You have multiple services that communicate through APIs and need a reliable way to verify compatibility
- You find it difficult to manage contracts across API gateways or between frontend, gateway, and backend services
- You depend on external APIs and want a safer way to validate integrations without relying on full system tests
- You want a structured and practical approach to adopting Consumer-Driven Contract Testing (CDCT) in an organisation

## When should you NOT use this method?
- This method is not suitable in the following cases:
- Your system is a monolith with limited or no service-to-service communication
- Your system has very few services and low integration complexity
- Your current testing setup is fast, stable, and provides sufficient feedback
- You do not have the resources to introduce and maintain a new testing approach


## What type of organization is this for?
This method is designed for:
- Organizations using microservice architectures
- Teams working on multiple independent services
- Environments with CI/CD pipelines and API-based communication
- Smaller teams or simple systems can often adopt CDCT directly using existing tools such as Pact without additional structure.

