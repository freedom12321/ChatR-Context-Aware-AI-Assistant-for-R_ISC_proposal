# ChatR Skills: Modular R Assistance Through Reusable Skills and MCP-Wrapped Tools

📄 [View the detailed proposal here](https://freedom12321.github.io/ChatR-Context-Aware-AI-Assistant-for-R_ISC_proposal/)

## Overview

ChatR Skills is a modular open-source project for improving AI assistance in R programming across agentic IDEs such as Claude Code, Cursor, Windsurf, and Codex. Instead of building one monolithic assistant, the project develops reusable R-focused skills and lightweight MCP-wrapped tools that help AI agents inspect R sessions, understand datasets, examine local packages, and query CRAN package metadata.

The long-term vision is to make AI assistance for R more reliable, context-aware, and useful for real analytical workflows, package development, and contribution-oriented work.

## Why This Matters

General-purpose AI coding assistants can write simple R code, but they often fail when tasks depend on the user’s actual R session, installed package versions, object structure, documentation, and analysis workflow. These limitations are especially important in R, where users often work with complex data objects, package-specific APIs, statistical workflows, and reproducible research pipelines.

ChatR Skills addresses this gap by giving agents structured, inspectable, and reusable ways to access R-specific context. This can reduce hallucinated functions, improve package-aware recommendations, and help users move from vague coding assistance toward reliable workflow-level support.

## Project Impact

This project can benefit several groups in the R and open-source ecosystem:

- **R users and data analysts** can receive more accurate assistance that reflects their actual data, objects, and package environment.
- **R package developers** can use agent support for package structure, documentation, exported functions, dependencies, and development workflows.
- **R contributors and educators** can build on reusable skills and tools rather than starting from a single closed assistant interface.
- **Agentic IDE users** can reuse the same R-focused skills across multiple environments, including Claude Code, Cursor, Windsurf, and Codex.

The project is designed to create infrastructure, not just a one-time demo. Each skill and MCP tool will be independently usable, testable, and extensible, making the work valuable beyond the initial proposal period.

## Core Deliverables

- R-focused skills written in `SKILL.md` format
- MCP-wrapped tools for R session introspection
- Dataset introspection tools
- Local package library inspection tools
- CRAN package index query tools
- Documentation and usage examples for each skill/tool
- Representative example tasks for mentor evaluation
- A final demo showing how the skills and tools support realistic R workflows

## Initial Skills

1. **Expert End-to-End Data Analyst**  
   Helps an agent inspect datasets, understand variable roles, identify suitable packages, and plan or implement analysis workflows.

2. **R Package Developer**  
   Helps an agent inspect package structure, exported functions, documentation, dependencies, and development conventions.

3. **R Core Contributor**  
   Supports source-oriented reasoning and contribution workflows related to R itself, beginning with a focused scope and expanding if time permits.

## Development Approach

The project will be developed incrementally and openly on GitHub. Each skill and tool will be independently usable, testable, and reviewable, allowing mentors and users to evaluate progress throughout the project.

The development plan emphasizes practical weekly progress:

- Start with the core repository structure and R session introspection.
- Add dataset introspection and the first data analysis skill.
- Add local package inspection and package developer support.
- Add CRAN package search/query functionality.
- Polish documentation, examples, tests, and final demo materials.

## Funding Request

This proposal requests **$3,000** to support the development of ChatR Skills as an open-source modular infrastructure project.

The requested funding will support:

- Development time for implementing reusable R skills and MCP-wrapped tools
- Testing across realistic R workflows and agentic IDE environments
- Documentation, examples, and setup instructions
- Preparation of mentor-reviewable demos and final project materials
- Repository maintenance and open-source project organization

The funding will help ensure that the project is delivered as a usable, documented, and extensible contribution rather than only as a conceptual prototype.

## Expected Outcomes

By the end of the project, the repository should include:

- A working set of reusable R skills in `SKILL.md` format
- MCP-wrapped tools for R session, dataset, package, and CRAN introspection
- Example workflows demonstrating how agents can use these tools in realistic R tasks
- Tests or validation examples for core functions
- Clear documentation for users, mentors, and future contributors
- A final demo showing the value of modular context-aware R assistance

## Long-Term Vision

ChatR Skills is intended to serve as the reusable infrastructure layer for future context-aware R assistants. Future extensions could include deeper RStudio or VS Code integration, richer package recommendation workflows, domain-specific statistical analysis skills, and broader support for reproducible research pipelines.

Rather than replacing existing R tools, ChatR Skills aims to help AI agents understand and use them more accurately.