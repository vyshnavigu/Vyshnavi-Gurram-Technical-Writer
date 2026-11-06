# Vyshnavi Gurram: Technical Writing Portfolio

Source for my [technical writing portfolio](https://vyshnavi-gurram-technical-writer.vercel.app/), featuring API documentation, conceptual and implementation guides, documentation engineering, AI-related case studies, and UX writing.

I am a technical writer with experience documenting enterprise software and banking applications for developers, administrators, support teams, and end users. My approach is to understand the product and the reader's task first, then organize the information into clear, usable documentation.

The portfolio website is built with HTML and CSS, maintained in GitHub, and hosted on Vercel. It is a collection of selected writing samples and project case studies, not a production documentation portal.

## What's inside

| Section | Sample | Intended audience |
| --- | --- | --- |
| [API documentation](mfa-api.html) | Multi-Factor Authentication API reference, including endpoints, examples, response codes, and troubleshooting | Developers and integration teams |
| [Conceptual guide](eda-guide.html) | Event-Driven Architecture: concepts, terminology, topologies, and examples | Developers, technical teams, and readers learning EDA |
| [Implementation guide](deployment-guide.html) | Application Server Deployment Guide: WildFly and Maven on Linux | System administrators and deployment teams |
| [Documentation engineering case study](docflow-ai-case-study.html) | DocFlow AI: a personal proof of concept for OpenAPI-driven documentation generation, validation, and AI-assisted drafting review | Documentation teams, developers, and hiring managers |
| [RAG agent case study](jira-case-study.html) | Jira Summarizer with Microsoft Copilot RAG: Agent Alpha | Documentation teams and people exploring AI-assisted knowledge retrieval |
| [UX writing case study](session_navigator_ux_case_study.html) | Designing a Session Navigator for AI Chat Interfaces | Product designers, UX writers, and product teams |

Some samples use fictional applications, endpoints, or scenarios to demonstrate documentation methods. Case studies describe hands-on experiments and design work; they are not claims of production deployment.

## How this portfolio is organized

The main portfolio groups samples by **document type** so visitors can go directly to the kind of writing they want to review. Each sample opens as a separate HTML page.


Vyshnavi-Gurram-Technical-Writer/
│
├── index.html
│   └── Portfolio homepage and sample categories
│
├── mfa-api.html
│   └── API documentation sample
│
├── eda-guide.html
│   └── Event-Driven Architecture conceptual guide
│
├── deployment-guide.html
│   └── Application server deployment guide
│
├── docflow-ai-case-study.html
│   └── Documentation engineering case study
│
├── jira-case-study.html
│   └── RAG agent case study
│
├── session_navigator_ux_case_study.html
│   └── UX writing and content design case study
│
└── README.md
    └── Repository overview and portfolio information

All listed HTML files are located in the repository root.

The documentation pages use a consistent visual approach, including a contents sidebar, headings, examples, tables, and callouts where they help the reader. The main site uses category cards to make the samples easy to find.

## Documentation and project approach

- **Start with the audience.** Identify what the reader needs to understand or complete.
- **Choose the right document type.** Use an API reference for integration details, a conceptual guide for explanation, and a procedure for a task the reader must perform.
- **Use examples to clarify.** Provide scenarios, code, diagrams, or troubleshooting notes when they improve understanding.
- **Review technical claims.** Distinguish validated behaviour from assumptions and proposed functionality.
- **Maintain source history.** Use GitHub to track changes to portfolio pages and project material.

## DocFlow AI: source repository

The [DocFlow AI repository](https://github.com/vyshnavigu/docflow-ai) contains the separate proof-of-concept project. It includes an OpenAPI definition, Python scripts, generated documentation, GitHub Actions validation, and AI draft evaluation examples.

The documented workflow covers generating API documentation from an OpenAPI specification, checking for drift, reviewing an AI-generated draft against a proposed change ticket, and testing draft checks using known-bad and clean examples.

**Scope:** DocFlow AI is a personal learning project. The AI draft was not approved for publication, and the project does not autonomously open pull requests or publish reviewed documentation. The automated checks in this repository should not be mistaken for a complete independent editorial review.

Read the [portfolio case study](docflow-ai-case-study.html) for the problem, process, findings, and limitations.

## Preview and publishing

These are static HTML pages. To preview the portfolio locally, open `index.html` in a browser and follow the sample links. You can also use a local static web server for testing.

The public site is hosted on [Vercel](https://vercel.com/). Changes to the website are made through the portfolio repository and published through the site's deployment configuration. The DocFlow AI source project is maintained in its own repository.

## Tools and technologies represented

HTML, CSS, Markdown, GitHub, GitHub Actions, Python, OpenAPI, Swagger, documentation validation, Microsoft Copilot, and retrieval-augmented generation (RAG).

## Contact

- [Portfolio website](https://vyshnavi-gurram-technical-writer.vercel.app/)
- [GitHub profile](https://github.com/vyshnavigu)

© 2026 Vyshnavi Gurram
