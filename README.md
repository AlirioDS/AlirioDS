# Alirio Jose Diaz Sanchez

**Senior Full-Stack Software Engineer** · Ruby on Rails · React · PostgreSQL
📍 Santiago, Chile (UTC-3/UTC-4, full US time zone overlap) · English and Spanish

[![Website](https://img.shields.io/badge/Website-aliriods.github.io-2563eb?style=flat-square&logo=googlechrome&logoColor=white)](https://aliriods.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-alirio--diaz-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alirio-diaz)
[![Stack Overflow](https://img.shields.io/badge/Stack_Overflow-alirio--diaz-f48024?style=flat-square&logo=stackoverflow&logoColor=white)](https://stackoverflow.com/users/6620037/alirio-diaz)
[![Email](https://img.shields.io/badge/Email-aliriodiaz111%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:aliriodiaz111@gmail.com)

## Who I am

I've been building production software since 2014. Today I work as a senior full-stack engineer at **LegalAtoms** (Seattle, remote) on a legal-tech platform, across Rails, Angular, AWS messaging, and real-time systems.

Before that I spent three years at **Rankmi**, first as a full-stack developer and then as Engineering Team Lead: a team of 4 engineers in 2 squads on an HR-tech platform serving 100,000+ users, where we migrated 10+ microservices, reduced bugs by 75% in a year, and cut deployment times by 50%.

I also build and operate my own products through **[Byteploy](https://byteploy.com/)**, the software company I founded.

## Stack

| Area | Tools |
| --- | --- |
| Backend | Ruby on Rails, Node.js, REST APIs, GraphQL, Sidekiq, Solid Queue, AnyCable, Action Cable |
| Frontend | React (Hooks, Redux, Context), Angular, Hotwire, TypeScript, vanilla JavaScript |
| Databases | PostgreSQL, MySQL, MongoDB, Redis |
| Cloud & DevOps | AWS (EC2, S3, SQS, SNS, SES, CloudWatch), GCP, Cloudflare, Docker, Linux, GitHub Actions |
| Architecture | Microservices, event-driven workflows with AWS SQS/SNS, multi-tenant SaaS, real-time systems |
| Testing | RSpec, TDD, end-to-end testing |
| AI & LLM | MCP server development, OpenAI API (structured outputs, streaming), Claude Code, Cursor |

## Makundal

**[makundal.com](https://makundal.com/)** is a multi-tenant SaaS/ERP for food and retail businesses that I designed, built, and run in production. It connects point of sale, inventory, purchasing, production, cash control, and analytics in one platform.

Architecture in short:

- **Rails 8 monolith** on **PostgreSQL**, with **Hotwire** for the UI
- **Multi-tenancy** with subdomain-based tenant isolation and role-based access control
- **Action Cable** for real-time updates and **Solid Queue** for background jobs
- TOTP two-factor authentication, audit trails, and English/Spanish/Portuguese localization
- About **5,000 automated tests** running in CI on **GitHub Actions**

It went from active development to its first production sale in about 2 months, and has since recorded 2,000+ sales, 26,000+ stock movements, and 800+ production batches. The code is private; I'm happy to walk through it in a call.

## Self-hosted multi-agent AI platform

I run a self-hosted platform where multiple AI agents do real work through the **Model Context Protocol (MCP)**:

- **11 MCP servers** that I wrote myself, each exposing a specific set of tools
- **Per-agent permissions**, so every agent only reaches the tools and data it needs
- **Human approval before execution**: agents propose actions and a person approves them before anything runs

## Get in touch

I'm open to full-time senior remote roles with US/EU companies.

- 🌐 [aliriods.github.io](https://aliriods.github.io)
- 💼 [linkedin.com/in/alirio-diaz](https://www.linkedin.com/in/alirio-diaz)
- ✉️ [aliriodiaz111@gmail.com](mailto:aliriodiaz111@gmail.com)
