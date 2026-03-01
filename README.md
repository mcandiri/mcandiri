# Mehmet Can Diri

Lead Software Engineer building education technology that serves 1,500+ students daily.

10+ years shipping .NET systems — from database architecture to AI integrations. Currently running [Veritas Education](https://veritasedu.net), where I make the technical decisions and write the critical code.

## What I Work With

**.NET ecosystem** — ASP.NET Core, Blazor Server, Dapper, SQL Server. This is where most of my production experience lives.

**Database engineering** — stored procedures, execution plan optimization, schema design for multi-tenant education platforms.

**AI/LLM integration** — building reliable abstractions over OpenAI, Anthropic, and Gemini APIs with failover and retry logic.

**Python** — database forensics tooling, static analysis, CLI tools.

## Selected Projects

**[SQLForensic](https://github.com/mcandiri/sqlforensic)** — Database static analysis tool (Python). Scans SQL Server databases for missing indexes, dead code, circular dependencies, and schema issues. [Tested against a 499-table production database](https://github.com/mcandiri/sqlforensic#real-world-results).

**[LLMForge](https://github.com/mcandiri/LLMForge)** — Multi-provider LLM orchestration for .NET. Single interface across OpenAI, Anthropic, and Gemini with automatic failover and circuit breaker.

**[ExamReader](https://github.com/mcandiri/ExamReader)** — Exam grading engine with OCR, automatic scoring, and class analytics (difficulty index, discrimination index). Started as an Azure CV experiment, grew into a full analysis platform.

**[DapperForge](https://github.com/mcandiri/DapperForge)** — Convention-based stored procedure toolkit for Dapper. Extracted from a codebase with 200+ SPs.

**[LiveSQL](https://github.com/mcandiri/LiveSQL)** — SQL execution plan visualizer with animated flow diagrams and bottleneck detection. Blazor Server UI.

**[FlowForge](https://github.com/mcandiri/FlowForge)** — Visual workflow builder with drag-and-drop canvas, real-time execution trace, and C# code export. Blazor Server UI.

## Context

Most of these projects started as internal tools for [Veritas Education](https://veritasedu.net) — solving real problems like grading exams faster, debugging slow queries, or avoiding vendor lock-in on LLM providers. I extracted and open-sourced them because the patterns are useful beyond education.

I'm not trying to build the next framework ecosystem. These are focused tools that solve specific problems I've actually had.
