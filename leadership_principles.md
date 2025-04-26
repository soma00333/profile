---
title: Leadership Principles
nav_order: 12
layout: default
---

# Leadership Principles

[Leadership Principles](leadership_principles.md)

* TOC
{:toc}

## 1. Customer Obsession

- **Value:** Leaders earn and keep customer trust
- **Project:** CR1. Designed and developed custom metrics and improved observability
  - **At:** Cybereason
  - **Situation:**
    - A UI server has multi-components
    - Difficult to troubleshoot
  - **Action:** Improved observability
  - **Result:** Reduced MTTR for enterprise customers

## 2. Ownership

- **Value:** Leaders act on behalf of the entire company, beyond just one team
- **Project:** EN1. Developed a generator tool for manifests and Terraform configurations for new microservices
  - **At:** enechain Corporation
  - **Situation:**
    - Developers had to write manifests and Terraform configurations when creating new microservices
    - Slowed down the development speed
  - **Action:** Developed a generator tool for manifests and Terraform configuration
  - **Result:** Reduced time to first deploy for all teams

## 3. Invent and simplify

- **Value:** Leaders expect innovation and find ways to simplify
- **Project:** IT4. Migrated from a modular monolith to microservices architecture
  - **At:** Industry Technology
  - **Situation:**
    - Adopted a monolith architecture first
    - Write traffic on the database was increasing
  - **Action:** Migrated to microservices architecture and separated the responsibility
  - **Result:** Simplified the architecture and improved the database performance

## 4. Are right, a lot

- **Value:** Leaders have strong judgment and good instincts
- **Project:** GU1. Analyzed data from millions of users and designed A/B testing
  - **At:** Gunosy
  - **Situation:** User retention rates were declining
  - **Action:** Designed A/B testing scenario (Optimizing the first view) and implemented
  - **Result:** Increased user retention rate beyond the standard A/B testing

## 5. Learn and be curious

- **Value:** Leaders are never done learning and consistently seek to improve ourselves
- **Project:** EU1. Developed a processor that compiles user scripts into WebAssembly files and executes them efficiently on a wasm runtime
  - **At:** Eukarya
  - **Situation:**
    - Needed to create an extension for users to use their custom scripts
    - Needed to learn WebAssembly (Allows efficient execution of code written in various programming languages)
  - **Action:**
    - Researched and developed
    - Documented
  - **Result:** Provided users with useful features and built a knowledge base for the team.

## 6. Hire and develop the best

- **Value:** Leaders develop leaders and take seriously our role in coaching others
- **Project:** IT6. Migrated from MySQL 5.7 to MySQL 8.0
  - **At:** Industry Technology
  - **Situation:**
    - Needed to migrate MySQL 5.7 to MySQL 8.0
    - Encountered an incident
  - **Action:**
    - Resolved the incident and successfully migrated
    - Did pair programming with team members
  - **Result:** Led the project to success and built a knowledge base for the team

## 7. Insist on the highest standards

- **Value:** Leaders are continually raising the bar and driving their teams to deliver high-quality products
- **Project:** LX1. Developed an event-driven notification system within a closed network
  - **At:** LayerX
  - **Situation:**
    - Needed to develop a notification system to tell the workflow status to users
    - Our client was Japan's top financial institution, and we had the highest security requirement
  - **Action:**
    - Communicated with the financial institution's network manager
    - Developed the system
  - **Result:** Released the system with the highest security standards

## 8. Think big

- **Value:** Leaders create and communicate a bold direction that inspires results
- **Project:** IT1. Designed SLI/SLO and developed custom metrics and tracing
  - **At:** Industry Technology
  - **Situation:**
    - Got a chance to introduce the system to Japan's largest real estate company
    - But realized that the existing operation didn't meet the required level
  - **Action:**
    - Decided to sacrifice agility temporarily
    - Introduced SRE practices
  - **Result:** Got a contract with the enterprise customer

## 9. Bias for action

- **Value:** Speed matters in business. Leaders take calculated risks
- **Project:** EN2. Developed a system for local development by deploying Telepresence to the Kubernetes cluster
  - **At:** enechain Corporation
  - **Situation:**
    - Each microservice depended on the others
    - Slowed down the local development speed
  - **Action:**
    - Decided to introduce Telepresence (OSS to help create a local development environment)
    - It lowered security standards, so I limited the scope to the dev cluster and added security patches
  - **Result:** Minimized security risks and improved the development speed

## 10. Frugality

- **Value:** Leaders accomplish more with less
- **Project:** AL1. Developed a serverless training pipeline for LLMs
  - **At:** Algomatic
  - **Situation:**
    - Needed a training pipeline for fine-tuning LLMs
    - Needed costs efficient solution
  - **Action:**
    - Utilized serverless architecture
    - Developed a training pipeline
  - **Result:** Enabled fine-tuning LLMs efficiently

## 11. Earn trust

- **Value:** Leaders listen attentively, speak candidly, and treat others respectfully
- **Project:** 2. Analyzed thread dumps and heap dumps to troubleshoot a server
  - **At:** Cybereason
  - **Situation:**
    - A UI server crashed occasionally for an enterprise customer
    - This incident ticket involved with many teams
  - **Action:**
    - Gave instructions to other teams as an incident commander
    - Analyzed thread dumps and heap dumps
  - **Result:** Organized details about the incident response and solved the availability issue

## 12. Dive deep

- **Value:** Leaders operate at all levels, stay connected to the details
- **Project:** IT3. Tuned indexes and queries of databases and implemented read replica and cache
  - **At:** Industry Technology
  - **Situation:** Had frequent slow queries
  - **Action:**
    - Tuned indexes and queries of databases
    - Implemented read replica and cache
  - **Result:** Reduced the number of slow queries

## 13. Have Backbone; Disagree and Commit (Conflicts)

- **Value:** Leaders challenge decisions when we disagree. Once a decision is determined, we commit
- **Project:** (New) Migrated Google Cloud to Oracle Cloud
  - **At:** Cybereason
  - **Situation:** Executives planned to migrate from Google Cloud to Oracle Cloud
  - **Action:**
    - Disagree: Used number & vision
    - Commit:
  - **Result:** Created a better migration plan and reduced infrastructure costs

## 14. Deliver results

- **Value:** Leaders deliver outcomes with the right quality and in a timely fashion
- **Project:** IT2. Developed a group chat service and notification system
  - **At:** Industry Technology
  - **Situation:**
    - Needed to develop a group chat system
    - Schedule was tight
  - **Action:**
    - Adopted polling (Inefficient but Simple) instead of WebSocet (Efficient but Complicated) to simplify
    - Developed a group chat system
  - **Result:** Developed the expected system in time

## 15. Strive to be Earth's best employer

- **Value:** Leaders have a vision for and commitment to our employee's personal success
- **Project:** (New)
  - **At:** Industry Technology
  - **Situation:** One of our engineers repeatedly delayed the deadline for a feature development
  - **Action**
    - Communicated and found he was lack of understanding of the product code
    - Reassigned him to an important refactoring task with a more flexible deadline
  - **Result:** He became familiarized and started handling complex feature development tasks

## 16. Success and scale bring broad responsibility

- **Value:** Leaders create more than we consume and always leave things better than how we found them
- **Project:** IT4. Migrated from a modular monolith to microservices architecture
  - **At:** Industry Technology
  - **Situation:**
    - Adopted a monolith architecture first
    - Write traffic on the database was increasing as the business grows
  - **Action:** Migrated to microservices architecture and separated the responsibility
  - **Result:** Simplified the architecture and improved the database performance 