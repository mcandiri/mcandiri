# Mehmet Can Diri

Lead Software Engineer at [Veritas Education](https://veritasedu.net). I lead architecture and delivery for an education platform serving 1,500+ students, 350+ teachers, and 40+ staff daily.

## What I've Shipped

**Education platform** — built and maintain the full-stack system behind Veritas Education: course registration, student tracking, financial operations, and parent communication. Currently migrating from Windows Forms to .NET 8 + Blazor Server for remote access and mobile support.

**Digital exam system** — replaced paper-based exams with an online testing environment supporting timed sessions, randomized questions, and automated grading. Cut exam processing time from days to minutes.

**AI-powered study tools** — integrated LLM APIs to generate personalized study programs with spaced repetition. Built provider failover after an OpenAI outage disrupted service during peak exam period.

**Database health initiative** — wrote static analysis tooling to audit the production database. First scan surfaced hundreds of missing indexes and unused stored procedures that had accumulated over years of organic growth.

## Open Source

| Project | What it does | Lang | Tests |
|---------|-------------|------|-------|
| [SQLForensic](https://github.com/mcandiri/sqlforensic) | Database static analysis — [tested on production DB](https://github.com/mcandiri/sqlforensic#real-world-results) | Python | 289 |
| [LLMForge](https://github.com/mcandiri/LLMForge) | Multi-provider LLM calls with failover and circuit breaker | C# | 99 |
| [ExamReader](https://github.com/mcandiri/ExamReader) | OCR exam grading + class analytics | C# | 100+ |
| [DapperForge](https://github.com/mcandiri/DapperForge) | Convention-based SP toolkit — extracted from 200+ SP codebase | C# | ✅ |
| [LiveSQL](https://github.com/mcandiri/LiveSQL) | SQL execution plan visualizer with animated flow diagrams | C# | ✅ |
| [FlowForge](https://github.com/mcandiri/FlowForge) | Visual workflow builder with drag-and-drop canvas + C# export | C# | 118 |

All projects have CI, releases, and run without external dependencies in demo mode.
