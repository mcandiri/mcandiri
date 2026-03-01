# Mehmet Can Diri

Lead Software Engineer at [Veritas Education](https://veritasedu.net). I lead architecture and delivery for an education platform serving 1,500+ students, 350+ teachers, and 40+ staff daily.

## What I've Shipped

**Education platform** — built and maintain the system behind Veritas Education: course registration, student tracking, financial operations, and parent communication. Currently migrating from Windows Forms to .NET 8 + Blazor Server for remote access and mobile support.

**Digital exam system** — replaced paper-based exams with an online testing environment supporting timed sessions, randomized questions, and automated grading. What used to take staff 2–3 days of manual work now completes in under 15 minutes.

**LLM provider failover** — an OpenAI outage during peak exam period took down AI-assisted study features for ~2 hours. Built a multi-provider abstraction with automatic failover (OpenAI → Anthropic → Gemini), circuit breaker for transient failures, and rate-limit aware retry. No single provider outage has caused downtime since.

**Database health audit** — wrote static analysis tooling to audit the production database. First scan of 499 tables and 1,851 stored procedures surfaced 183 tables without primary keys, 363 missing foreign key indexes, and 1,726 stored procedures with no internal references. Targeted index additions based on the report.


## Open Source

| Project | What it does | Lang |
|---------|-------------|------|
| [SQLForensic](https://github.com/mcandiri/sqlforensic) | Database static analysis — [real scan results](https://github.com/mcandiri/sqlforensic#real-world-results) | Python |
| [LLMForge](https://github.com/mcandiri/LLMForge) | Multi-provider LLM calls with failover and circuit breaker | C# |
| [ExamReader](https://github.com/mcandiri/ExamReader) | OCR exam grading + class analytics | C# |
| [DapperForge](https://github.com/mcandiri/DapperForge) | Convention-based SP toolkit — extracted from 200+ SP codebase | C# |
| [LiveSQL](https://github.com/mcandiri/LiveSQL) | SQL execution plan visualizer with animated flow diagrams | C# |
| [FlowForge](https://github.com/mcandiri/FlowForge) | Visual workflow builder with drag-and-drop canvas + C# export | C# |


Each project has CI and can run in demo mode without external dependencies.
