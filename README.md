# Ranveer Singh

Customer Success Director at EazyStock, a B2B SaaS company specialising in inventory optimisation. Based in Warwick, UK.

My role covers two things: making sure our customers get value from EazyStock, and leading AI adoption across our internal teams. Before EazyStock I spent six years at Syncron, delivering more than 25 enterprise supply chain implementations for customers including JCB, Perkins and Mazda.

Most of what I build is in Microsoft Copilot Studio and M365 Copilot. These are agents that take repetitive work off people's plates in customer success, sales and implementation.

## Projects

| Project | Problem | What it does | Status |
|---|---|---|---|
| Model Evaluation Tool | Choosing a model means trading accuracy against cost and speed, usually by guesswork | Sends the same prompt to up to 13 current Claude and OpenAI models and logs cost, response time and token usage, with a log viewer for comparing runs. Accuracy scoring in progress. Built with Claude Code. | Live, being extended |
| AI Chief of Staff | Hard to see daily priorities across email, calendar and Gainsight | Plans my day, putting sales opportunities and at-risk customers first | Live |
| Prospecting Agent | Researching prospects by hand is slow and inconsistent | Checks companies against our ICP, finds contacts and prepares Outlook drafts for business development to review | In progress |
| Data Reviewer Agent | Data issues found late, during implementation | Checks customer files against a library of known issues | Live, being extended |
| SQL Query Assistant | CSMs wait on specialists for routine queries | Writes SQL from our schema and business context | Live |
| AI Adoption Playbook | Teams unsure where AI fits | Champions, governance and a Workflow Intake agent | In progress |
| Churn Analysis Agent | Churn analysis varies from one person to the next, and risks are spotted late | Analyses churn factors consistently and suggests which accounts to include in the forecast | Live |
| Claude Skills | Recurring CS tasks done inconsistently | Reusable skills, starting with Value Review prep | Planned |

**Status key:** Planned (scoped, not started) · In progress (being built or tested) · Pilot (small group using it) · Live (in regular use) · Paused (on hold) · Retired (stopped because the value or adoption didn't justify continuing; the reason is given in the project repo)

Each project will have its own repository, linked here once it is documented. All examples use synthetic data.

## How I approach AI work

I follow Anthropic's AI Fluency framework, which covers four areas.

**Delegation.** Deciding which work suits AI and which needs a person. The Prospecting Agent does the research and drafting, but nothing is sent until someone in business development has reviewed it.

**Description.** Giving agents the context they need to do the job properly. The SQL Query Assistant works from our actual schema and a business context document rather than a generic prompt.

**Discernment.** Testing outputs before trusting them. I test the Data Reviewer against files with deliberate errors in them and add new issue types to its knowledge as they come up.

**Diligence.** Being responsible for what gets built. I wrote EazyStock's AI governance framework, and each agent only has access to the data it needs.

## Measuring value and cost

I assess each project on what it saves against what it costs to build and run.

| Value | Cost |
|---|---|
| Time saved per task | Time to build and test |
| Fewer errors and less rework | Licences and Copilot Studio usage |
| Adoption and user feedback | Ongoing maintenance |
| Business outcomes, e.g. faster go-lives and earlier churn warnings | Risk, including data exposure and incorrect outputs |

Each project repository sets out its baseline, current results and estimated payback.

## Tools

Microsoft Copilot Studio, M365 Copilot, Claude, Claude Code, Claude API, OpenAI API, GitHub Copilot, Gainsight, Salesforce, SQL

## Learning

**Anthropic (Claude Academy)**
- [Building with the Claude API](https://academy.claude.com/verify/edd56b36984ebd15aae7f88528222728)
- [Introduction to Model Context Protocol](https://academy.claude.com/verify/efc980b33429df37634c3434ae3d4ee4)
- [Claude Code 101](https://academy.claude.com/verify/942b1ce9f8d6cedcf0e8626e4dbec544)
- [AI Fluency: Framework & Foundations](https://academy.claude.com/verify/5396f033c02e757afcdaa87841e01975)
- [AI Capabilities and Limitations](https://academy.claude.com/verify/d189e8be2f205e4a5b9aceda3535469e)
- [Claude 101](https://academy.claude.com/verify/4cfaa6b2787b4566867dbbc291352668)

**OpenAI Academy**
- [Agents and Workflows](https://oaiacademy.credential.net/38592756-f955-4cbe-8975-60d4f773d8b8)
- [Applied AI Foundations](https://academy.openai.com/public/certificate/9fp91jym90)

**Microsoft and LinkedIn**
- Career Essentials in Generative AI
- Learning Microsoft 365 Copilot for Work
- Ethics in the Age of Generative AI

Currently working through Andrej Karpathy's nanoGPT to understand how language models are built from the ground up.

## Talks

- **Build and buy: why SMEs shouldn't build AI alone.** Presentation to Microsoft Business Central partners on combining in-house AI with specialist software such as inventory optimisation (2026).

## Personal experiments

I use AI outside work as well, mostly as a place to try out techniques before using them in the agents I build at EazyStock.

- **Workout planner:** a Claude Project that writes my training plans and tracks progress over time. It has helped me learn how to write project instructions and how to keep context consistent across conversations.
- **AI word search generator (planned):** an LLM generates words for any category and places them in a grid according to the difficulty level, with a mode where words can run in any direction.

## Contact

[LinkedIn](https://www.linkedin.com/in/ranveer-singh-10)
