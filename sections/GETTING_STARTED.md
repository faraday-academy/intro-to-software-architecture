# Getting Started

## What is Software Architecture

Planning for, and making, technical decisions about the design of a system based off of the business or user requirements. This can include system design, devops, infrastructure, and technologies.

*In simpler terms:*

Planning and making decisions about how you will build something; technically leading and giving the direction for the design of the software. These decisions should take into account the requirements for the project.

**Performing architecture work will usually require the following steps:**

1. A lot of researching and interacting with other people (subject matter experts, stakeholders, etc.) to 'investigate' the best possible solutions based off of the requirements.
1. Going into a deep state of focus to analyze solutions and tradeoffs and come up with a plan.
1. Writing up a plan in the format of a design doc or proposal document.
1. Getting feedback and buy-in from key technical people and other stakeholders at the company.
1. Iterating on the plan based off of feedback (if necessary).
1. Helping engineering leadership create a plan to implement the architecture.

**Who is responsible for software architecture on a project?**

Sometimes a company will have an architect or a team(s) that are responsible for software architecture. These are people who specialize in architecture for software systems and work on independant teams that are usually managed separately from the engineering teams.
Other companies, especially smaller ones, might have someone on each team that has the role of software architect or another dual-purpose role like tech lead who does some development work and is also responsible for architecture decisions. They will be working closely with the rest of the engineering team to make plans for implementing those decisions.

## Common Types of Architecture

## 1. Monolith

### Pros:
- **Simplicity**: Easy to develop, test, deploy, and scale initially.
- **Unified Workflow**: All parts of the application are in one place, simplifying development and troubleshooting.

### Cons:
- **Scalability Issues**: As the application grows, it can become too large and complex, making it difficult to scale efficiently.
- **Limited Flexibility**: Hard to implement new technologies or frameworks into the existing stack.

### Best for:
Small companies or startups looking for a simple, quick way to get their product off the ground. Applications with a limited scope where a single, unified codebase can remain manageable.

## 2. Microservices

### Pros:
- **Scalability**: Each service can be scaled independently based on demand.
- **Flexibility**: Easy to implement new technologies and make updates to individual components without impacting the entire system.

### Cons:
- **Complexity**: Managing multiple services can become complex, requiring robust monitoring and DevOps practices.
- **Network Latency**: Communication between services over the network can introduce latency.

### Best for:
Medium to large companies that need to scale parts of their application independently. Teams that want to use different technologies and work independently of each other.

## 3. Serverless

### Pros:
- **Cost-Effective**: You only pay for the resources you use.
- **Scalability**: Automatically scales with the application's needs without manual intervention.
- **Maintenance-Free**: No need to manage servers or infrastructure.

### Cons:
- **Vendor Lock-In**: You're dependent on a specific cloud provider's tools and services.
- **Performance Issues**: Cold starts can delay the execution of your application.

### Best for:
Startups and small to medium-sized businesses looking for a cost-effective solution with minimal infrastructure management. Applications with variable or unpredictable traffic.

## 4. Evolutionary Architecture

**Definition**: Evolutionary architecture supports guided, incremental change across multiple dimensions in the system. It's about building systems that are flexible and can evolve with changing requirements and technologies.

### Pros:
- **Adaptability**: Easily adapts to changing business requirements and technologies.
- **Incremental Change**: Allows for gradual improvements without the need for large-scale rewrites.
- **Risk Management**: Reduces risk by validating changes in small, manageable increments.

### Cons:
- **Complexity Management**: Can become complex as the system evolves, requiring careful oversight and good governance.
- **Initial Overhead**: May require more upfront planning and effort to create a flexible and adaptable system.
- **Dependency Management**: Needs careful management of dependencies to avoid issues as the system evolves.

### Best for:
- Companies in rapidly changing industries where business requirements frequently shift.
- Projects where the future requirements are uncertain or expected to change.
- Teams looking to continuously improve and iterate on their systems.

## Understand Different Types of Projects

You will often have to jump into different kinds of projects, each with its own set of challenges and requirements. Here are two common scenarios:

**Greenfield**: These are projects that start from scratch. Imagine an empty field where you can build anything. There's more freedom and fewer constraints, but also more unknowns.

**Brownfield**: These projects involve adding to or modifying existing systems. It's like renovating an old house; you need to work with what's already there and be mindful of its limitations.

## What to pay attention to?

Requirements: Make sure you understand what's needed fully. Review thoroughly, consider edge cases, and question anything that might be missing. It's your blueprint for what to build.

Tradeoffs: Every decision has its pros and cons. Be aware of the complexity your choices might add and whether it's worth it.

Design: Plan your systems to be adaptable to future changes. The only constant in technology is change, so design flexibility into your system from the start.

## Things to Learn

Write a design doc: This is your plan and documentation for a piece of software. It helps you organize your thoughts, do proper research, and communicate your ideas to others. Here's what to focus on:

- Organize: Clearly outline the problem, proposed solution, and any alternatives you considered. Break it down into sections that are easy to follow.

- Do proper research: Back up your decisions with data and research. Understand the pros and cons of each choice you're making.

Learn how to diagram: Diagrams are a universal language in software and architecture. They help you visualize complex systems and communicate how different parts interact. Practice different types of diagrams like flowcharts, sequence diagrams, and architecture diagrams. They're essential tools for thinking and communicating about systems.
