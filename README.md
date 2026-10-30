# Erdem Süren

### Full-Stack Software Engineer · .NET & React/Next.js

**AI-native, end to end.** I design, build and run business software, from the database and APIs to the interface and the servers it runs on. Based in İstanbul, Türkiye; happy to work in English or Turkish.

## What I build

- **Web applications and e-commerce:** admin panels, company websites, and online stores with payment, e-invoice, shipping and marketplace integrations.
- **Integrations and workflow automation:** state-machine workflows, plus ERP, SAP S/4HANA and Active Directory/LDAP integrations.
- **AI features inside products:** tool-using assistants, AI media generation and AI-written reports, with usage allowances and credit metering.
- **The delivery around it:** CI/CD on self-hosted GitHub Actions runners, separate test and production servers, IIS and Cloudflare.

## Now

- **Software Development Specialist, BELBİM** (since July 2025): I built the corporate websites [belbim.istanbul](https://belbim.istanbul/) and [istanbulkart.istanbul](https://istanbulkart.istanbul/), and I'm a member of the İstanbulkart mobile app team. My work there includes rebuilding a legacy Umbraco system as a headless CMS with a Next.js front end ([case study](https://erdemsuren.com/en/projects/belbim-headless-cms/)).
- **Founder, [Eribitech](https://eribitech.com)** (since May 2025, alongside my job): I build Eribi, the company's multi-tenant e-commerce platform, and the AI products around it. They run on test and production servers I set up and run myself.

**Earlier:** Software Developer at İGDAŞ (Dec 2023 – Jul 2025), where I modeled the field-operation workflows of a 24/7 platform as state machines covering 150+ operational scenarios, and worked on the SAP S/4HANA and Active Directory integrations. Before that I worked in game development with Unity and C# at Tiramisu Studios, as part of the team on the Drift Max mobile racing games.

## Case studies

- **[Eribi: multi-tenant e-commerce platform](https://erdemsuren.com/en/projects/eribi/)**: a database per store, automated store provisioning (database, DNS, SSL, IIS site), and payment, e-invoice, shipping, marketplace and ERP integrations split into services behind a YARP API gateway.
- **[Eribi Creative: AI media studio](https://erdemsuren.com/en/projects/eribi-creative/)**: a web studio where agencies generate images, video and audio with AI models through fal.ai, with weekly usage allowances and a shared media library.
- **[Eribi Growth: lead discovery and AI outreach](https://erdemsuren.com/en/projects/eribi-growth/)**: lead lists by sector and city, website-analysis reports written with Claude, and an AI-written first e-mail sent with DKIM signing.
- **[DarkPost Agency website](https://erdemsuren.com/en/projects/darkpost/)** (client project): a Next.js 16 site for a marketing and e-commerce agency. Store applications reach the Eribi partner API through a server-side layer, so the API key never reaches the browser.
- **[Olser Bilişim company website](https://erdemsuren.com/en/projects/olser-bilisim/)** (client project): a company website and content admin for a software firm that serves accountants and the finance sector. First built with React/Vite and a .NET API, then rewritten in Next.js 16.

*Most of my work is private: my company's platform and client projects live in private repositories, and employer code stays with the employer. That is why my contribution graph is busy while the public list is short. The case studies above show that work.*

## How I work with AI

I build software with AI coding agents. At Eribitech, most of my commits since May 2026 are co-written with Claude Code. Agents are only as good as the environment they work in, and building that environment is my job:

- **I build the environment.** Clear layers, project docs, tests, separate test and production servers, automated deploys.
- **I own the architecture and the release.** I decide what gets built and within which limits, review the changes and decide when they go live.
- **Risky changes can be rolled back.** Cutovers sit behind feature flags; database work starts with backups and restore drills.
- **I measure, then improve.** For example, I cut the production server's idle memory use from 72% to 60% after measuring where it went.

## Stack

| Area | Tools |
|---|---|
| Backend | C#, .NET 8, ASP.NET Core, Entity Framework Core, Hangfire |
| Frontend | React, Next.js, TypeScript, Tailwind CSS |
| Data | SQL Server, PostgreSQL |
| Infrastructure | GitHub Actions (self-hosted runners), IIS, Cloudflare, PowerShell, Windows Server |
| AI | Claude Code, Gemini API, Claude API, fal.ai |
| Testing | xUnit, Moq, FluentAssertions, Vitest, Testing Library |

## Contact

Write to me about a role or a project: [erdemsurentr@gmail.com](mailto:erdemsurentr@gmail.com) · [LinkedIn](https://www.linkedin.com/in/erdemsurentr/) · [erdemsuren.com](https://erdemsuren.com/en/)
