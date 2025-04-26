---
title: Leadership Principles
nav_order: 12
layout: default
---

# Leadership Principles

[Leadership Principles](leadership_principles.md)

* TOC
{:toc}

## Principles

<table>
  <thead>
    <tr>
      <th>Key</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>1. Customer Obsession</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders earn and keep customer trust</li><li><strong>Project:</strong> CR1. Designed and developed custom metrics and improved observability</li><li><strong>At:</strong> Cybereason</li><li><strong>Situation:</strong><ul><li>A UI server has multi-components</li><li>Difficult to troubleshoot</li></ul></li><li><strong>Action:</strong> Improved observability</li><li><strong>Result:</strong> Reduced MTTR for enterprise customers</li></ul></td>
    </tr>
    <tr>
      <td><strong>2. Ownership</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders act on behalf of the entire company, beyond just one team</li><li><strong>Project:</strong> EN1. Developed a generator tool for manifests and Terraform configurations for new microservices</li><li><strong>At:</strong> enechain Corporation</li><li><strong>Situation:</strong><ul><li>Developers had to write manifests and Terraform configurations when creating new microservices</li><li>Slowed down the development speed</li></ul></li><li><strong>Action:</strong> Developed a generator tool for manifests and Terraform configuration</li><li><strong>Result:</strong> Reduced time to first deploy for all teams</li></ul></td>
    </tr>
    <tr>
      <td><strong>3. Invent and simplify</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders expect innovation and find ways to simplify</li><li><strong>Project:</strong> IT4. Migrated from a modular monolith to microservices architecture</li><li><strong>At:</strong> Industry Technology</li><li><strong>Situation:</strong><ul><li>Adopted a monolith architecture first</li><li>Write traffic on the database was increasing</li></ul></li><li><strong>Action:</strong> Migrated to microservices architecture and separated the responsibility</li><li><strong>Result:</strong> Simplified the architecture and improved the database performance</li></ul></td>
    </tr>
    <tr>
      <td><strong>4. Are right, a lot</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders have strong judgment and good instincts</li><li><strong>Project:</strong> GU1. Analyzed data from millions of users and designed A/B testing</li><li><strong>At:</strong> Gunosy</li><li><strong>Situation:</strong> User retention rates were declining</li><li><strong>Action:</strong> Designed A/B testing scenario (Optimizing the first view) and implemented</li><li><strong>Result:</strong> Increased user retention rate beyond the standard A/B testing</li></ul></td>
    </tr>
    <tr>
      <td><strong>5. Learn and be curious</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders are never done learning and consistently seek to improve ourselves</li><li><strong>Project:</strong> EU1. Developed a processor that compiles user scripts into WebAssembly files and executes them efficiently on a wasm runtime</li><li><strong>At:</strong> Eukarya</li><li><strong>Situation:</strong><ul><li>Needed to create an extension for users to use their custom scripts</li><li>Needed to learn WebAssembly (Allows efficient execution of code written in various programming languages)</li></ul></li><li><strong>Action:</strong><ul><li>Researched and developed</li><li>Documented</li></ul></li><li><strong>Result:</strong> Provided users with useful features and built a knowledge base for the team.</li></ul></td>
    </tr>
    <tr>
      <td><strong>6. Hire and develop the best</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders develop leaders and take seriously our role in coaching others</li><li><strong>Project:</strong> IT6. Migrated from MySQL 5.7 to MySQL 8.0</li><li><strong>At:</strong> Industry Technology</li><li><strong>Situation:</strong><ul><li>Needed to migrate MySQL 5.7 to MySQL 8.0</li><li>Encountered an incident</li></ul></li><li><strong>Action:</strong><ul><li>Resolved the incident and successfully migrated</li><li>Did pair programming with team members</li></ul></li><li><strong>Result:</strong> Led the project to success and built a knowledge base for the team</li></ul></td>
    </tr>
    <tr>
      <td><strong>7. Insist on the highest standards</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders are continually raising the bar and driving their teams to deliver high-quality products</li><li><strong>Project:</strong> LX1. Developed an event-driven notification system within a closed network</li><li><strong>At:</strong> LayerX</li><li><strong>Situation:</strong><ul><li>Needed to develop a notification system to tell the workflow status to users</li><li>Our client was Japan's top financial institution, and we had the highest security requirement</li></ul></li><li><strong>Action:</strong><ul><li>Communicated with the financial institution's network manager</li><li>Developed the system</li></ul></li><li><strong>Result:</strong> Released the system with the highest security standards</li></ul></td>
    </tr>
    <tr>
      <td><strong>8. Think big</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders create and communicate a bold direction that inspires results</li><li><strong>Project:</strong> IT1. Designed SLI/SLO and developed custom metrics and tracing</li><li><strong>At:</strong> Industry Technology</li><li><strong>Situation:</strong><ul><li>Got a chance to introduce the system to Japan's largest real estate company</li><li>But realized that the existing operation didn't meet the required level</li></ul></li><li><strong>Action:</strong><ul><li>Decided to sacrifice agility temporarily</li><li>Introduced SRE practices</li></ul></li><li><strong>Result:</strong> Got a contract with the enterprise customer</li></ul></td>
    </tr>
    <tr>
      <td><strong>9. Bias for action</strong></td>
      <td><ul><li><strong>Value:</strong> Speed matters in business. Leaders take calculated risks</li><li><strong>Project:</strong> EN2. Developed a system for local development by deploying Telepresence to the Kubernetes cluster</li><li><strong>At:</strong> enechain Corporation</li><li><strong>Situation:</strong><ul><li>Each microservice depended on the others</li><li>Slowed down the local development speed</li></ul></li><li><strong>Action:</strong><ul><li>Decided to introduce Telepresence (OSS to help create a local development environment)</li><li>It lowered security standards, so I limited the scope to the dev cluster and added security patches</li></ul></li><li><strong>Result:</strong> Minimized security risks and improved the development speed</li></ul></td>
    </tr>
    <tr>
      <td><strong>10. Frugality</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders accomplish more with less</li><li><strong>Project:</strong> AL1. Developed a serverless training pipeline for LLMs</li><li><strong>At:</strong> Algomatic</li><li><strong>Situation:</strong><ul><li>Needed a training pipeline for fine-tuning LLMs</li><li>Needed costs efficient solution</li></ul></li><li><strong>Action:</strong><ul><li>Utilized serverless architecture</li><li>Developed a training pipeline</li></ul></li><li><strong>Result:</strong> Enabled fine-tuning LLMs efficiently</li></ul></td>
    </tr>
    <tr>
      <td><strong>11. Earn trust</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders listen attentively, speak candidly, and treat others respectfully</li><li><strong>Project:</strong> 2. Analyzed thread dumps and heap dumps to troubleshoot a server</li><li><strong>At:</strong> Cybereason</li><li><strong>Situation:</strong><ul><li>A UI server crashed occasionally for an enterprise customer</li><li>This incident ticket involved with many teams</li></ul></li><li><strong>Action:</strong><ul><li>Gave instructions to other teams as an incident commander</li><li>Analyzed thread dumps and heap dumps</li></ul></li><li><strong>Result:</strong> Organized details about the incident response and solved the availability issue</li></ul></td>
    </tr>
    <tr>
      <td><strong>12. Dive deep</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders operate at all levels, stay connected to the details</li><li><strong>Project:</strong> IT3. Tuned indexes and queries of databases and implemented read replica and cache</li><li><strong>At:</strong> Industry Technology</li><li><strong>Situation:</strong> Had frequent slow queries</li><li><strong>Action:</strong><ul><li>Tuned indexes and queries of databases</li><li>Implemented read replica and cache</li></ul></li><li><strong>Result:</strong> Reduced the number of slow queries</li></ul></td>
    </tr>
    <tr>
      <td><strong>13. Have Backbone; Disagree and Commit (Conflicts)</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders challenge decisions when we disagree. Once a decision is determined, we commit</li><li><strong>Project:</strong> (New) Migrated Google Cloud to Oracle Cloud</li><li><strong>At:</strong> Cybereason</li><li><strong>Situation:</strong> Executives planned to migrate from Google Cloud to Oracle Cloud</li><li><strong>Action:</strong><ul><li>Disagree: Used number & vision</li><li>Commit:</li></ul></li><li><strong>Result:</strong> Created a better migration plan and reduced infrastructure costs</li></ul></td>
    </tr>
    <tr>
      <td><strong>14. Deliver results</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders deliver outcomes with the right quality and in a timely fashion</li><li><strong>Project:</strong> IT2. Developed a group chat service and notification system</li><li><strong>At:</strong> Industry Technology</li><li><strong>Situation:</strong><ul><li>Needed to develop a group chat system</li><li>Schedule was tight</li></ul></li><li><strong>Action:</strong><ul><li>Adopted polling (Inefficient but Simple) instead of WebSocet (Efficient but Complicated) to simplify</li><li>Developed a group chat system</li></ul></li><li><strong>Result:</strong> Developed the expected system in time</li></ul></td>
    </tr>
    <tr>
      <td><strong>15. Strive to be Earth's best employer</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders have a vision for and commitment to our employee's personal success</li><li><strong>Project:</strong> (New)</li><li><strong>At:</strong> Industry Technology</li><li><strong>Situation:</strong> One of our engineers repeatedly delayed the deadline for a feature development</li><li><strong>Action:</strong><ul><li>Communicated and found he was lack of understanding of the product code</li><li>Reassigned him to an important refactoring task with a more flexible deadline</li></ul></li><li><strong>Result:</strong> He became familiarized and started handling complex feature development tasks</li></ul></td>
    </tr>
    <tr>
      <td><strong>16. Success and scale bring broad responsibility</strong></td>
      <td><ul><li><strong>Value:</strong> Leaders create more than we consume and always leave things better than how we found them</li><li><strong>Project:</strong> IT4. Migrated from a modular monolith to microservices architecture</li><li><strong>At:</strong> Industry Technology</li><li><strong>Situation:</strong><ul><li>Adopted a monolith architecture first</li><li>Write traffic on the database was increasing as the business grows</li></ul></li><li><strong>Action:</strong> Migrated to microservices architecture and separated the responsibility</li><li><strong>Result:</strong> Simplified the architecture and improved the database performance</li></ul></td>
    </tr>
  </tbody>
</table> 