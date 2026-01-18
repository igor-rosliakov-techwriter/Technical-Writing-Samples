# Developer-Focused Technical Writing Samples

This repository contains a curated collection of my technical writing samples,
focused on developer-facing documentation and technical explanations.

The materials cover backend systems, Python programming, APIs, asynchronous
execution models, security concepts, and infrastructure-related workflows.
Most of the content is designed to explain how systems work under the hood and
to help engineers build a clear mental model, not just follow step-by-step instructions.

The original articles are published in Russian. For each piece, I provide an
English summary to give international readers quick access to the context,
technical scope, and key ideas.

## Background Asynchronous Tasks in FastAPI

This article explains how background asynchronous tasks can be implemented
in FastAPI and how their execution can be monitored in production environments.

It covers common approaches to running background jobs, typical pitfalls related
to reliability and observability, and practical monitoring strategies. The focus
is on real-world backend workflows, showing how asynchronous tasks behave outside
of simple request-response scenarios.

The material is intended for backend engineers and technical writers who need
to understand how background processing fits into a production system and how
to document such workflows clearly.

[Original article (RU)](https://habr.com/ru/companies/kts/articles/816757/)

## Message Processing Architecture in a Chatbot Platform

This article describes the architecture of a message processing system using
a chatbot platform as an example.

It explains how incoming messages move through the system, how responsibilities
are divided between components, and how message handling logic is organized.
The focus is on system design considerations, data flow, and practical backend
workflows rather than chatbot-specific features.

The material can be used as a reference for backend engineers and technical writers
working on message-driven systems or onboarding documentation for similar platforms.

[Original article (RU)](https://habr.com/ru/companies/kts/articles/697024/)

## Extending JupyterHub with Kubeflow Features Without Full Integration

This article explains how selected Kubeflow features can be implemented on top
of JupyterHub without performing a full Kubeflow integration.

It focuses on architectural decisions, system constraints, and practical trade-offs
when building an ML platform on existing infrastructure. The article shows how
complex platform functionality can be introduced incrementally, avoiding unnecessary
operational overhead.

The material is relevant for platform engineers and technical writers documenting
Kubernetes-based systems, internal platform tooling, and infrastructure architecture.

[Original article (RU)](https://habr.com/ru/companies/kts/articles/832084/)

## Using npm and yarn link for Local Library Development

This article explains how npm and yarn link can be used to connect local libraries
to a project during development.

It covers common use cases, typical pitfalls, and practical workflows for testing
and debugging libraries without publishing them to a registry. The focus is on
developer productivity and understanding how local dependency linking works in
real-world projects.

The material is relevant for frontend and full-stack developers, as well as
technical writers documenting development workflows and developer tooling.

[Original article (RU)](https://habr.com/ru/companies/kts/articles/821111/)

## Educational Materials

### Backend & DevOps Training Course (Yandex Cloud)

I contributed to the creation of a training course for mid-level DevOps engineers,
focused on practical cloud infrastructure workflows and platform usage.

- Part 1: [Deploying infrastructure using the GitOps model](https://yandex.cloud/ru-kz/training/deploy)
- Part 2: [Planning and preparing the production environment](https://yandex.cloud/ru-kz/training/production)
- Part 3: [Load testing](https://yandex.cloud/ru-kz/training/loadtesting)
