# Web Infrastructure Design

## Background Context

This project focuses on the core concepts of web infrastructure, devops, and sysadmin. The objective is to design, draw, and explain a full web stack architecture. A key component of this project is the ability to present and defend these architectural choices through **whiteboarding sessions** within a strict time limit (30 minutes), practicing a vital skill for technical job interviews.

---

## Learning Objectives

By the end of this project, I will be able to confidently explain and whiteboard the following without referencing documentation:

- How to draw a comprehensive web stack diagram.
- The specific role and utility of every infrastructure component.
- The principles of system redundancy, high availability, and data persistence.
- Key industry acronyms and metrics.

### Key Acronyms to Know

- **LAMP:** **L**inux, **A**pache, **M**ySQL, **P**HP/Python/Perl (A classic web service stack).
- **SPOF:** **S**ingle **P**oint **o**f **F**ailure (Any component that, if broken, brings down the whole system).
- **QPS:** **Q**ueries **P**er **S**econd (A metric measuring the traffic/load handling of a server or database).

---

## Requirements & Methodology

### General Rules

- A `README.md` file at the root of the project folder is mandatory.
- **Whiteboarding:** For each task, diagrams must be drawn (on paper, a whiteboard, or digital software) and a screenshot/photo must be saved.
- **Strict Focus:** Avoid unnecessary over-engineering or verbosity. Deliver exactly what the interviewer/requirements ask for within the 30-minute exercise window.

### Technical Elements Covered

- **Networking Basics:** Protocols, IP Addresses, TCP/IP, and Ports.
- **Servers:** Differentiating physical/virtual servers from Web Servers (Nginx/Apache) and Application Servers.
- **DNS Management:** Understanding DNS translation, root vs. subdomains, and record types (`A`, `CNAME`, `MX`, `TXT`, `NS`, `SOA`).
- **Availability & Security:** Load Balancers, Active-Active vs. Active-Passive clusters, Firewalls, and HTTPS configurations.
- **Monitoring:** Practical implementation of system metrics and health alerts using industry tools (DataDog, Uptime Robot, NewRelic, etc.).

---

## Project Tasks & Diagrams

| Task                                            | Description                                                             | Diagram Link / Screenshot |
| :---------------------------------------------- | :---------------------------------------------------------------------- | :------------------------ |
| **0. Simple web stack**                         | One server, web server, application server, and code deployment basics. | _[Insert Link]_           |
| **1. Distributed web infrastructure**           | Adding a load balancer and separating server roles.                     | _[Insert Link]_           |
| **2. Secured and monitored web infrastructure** | Implementing Firewalls, HTTPS/SSL, and a monitoring stack.              | _[Insert Link]_           |
| **3. Scale up**                                 | Advanced redundancy and high availability implementation.               | _[Insert Link]_           |

> _Note: The answer files uploaded to GitHub contain the direct hosted links to the completed whiteboard screenshots as required for manual review._

---

## Interview Advice Kept in Mind

- **Be precise:** Answer exactly what is requested.
- **Manage time:** The architecture must be fully explained under 30 minutes.
- **Ask before deep-diving:** Always verify with the reviewer/interviewer if they want to explore technical granularities before spending time on them.

---

## Author

- **Véronique Beauvais** - _Student at Holberton School_
