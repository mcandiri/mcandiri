# Mehmet Can Diri

Lead Software Engineer at [Veritas Education](https://veritasedu.net). I lead architecture and delivery for an education platform serving 1,500+ students, 350+ teachers, and 40+ staff daily.

## What I've Shipped

**Education platform (10+ years)** — multi-tenant system handling course management, digital exams, student tracking, and financial operations across 499 database tables, 1,851 stored procedures, and 6.4M rows. Migrated core modules from Windows Forms to .NET 8 + Blazor Server.

**Exam automation** — reduced manual grading time from ~4 hours to under 10 minutes per exam cycle using OCR-based answer sheet processing with per-question analytics (difficulty index, discrimination index).

**LLM integration** — built a provider abstraction layer after an OpenAI outage during peak exam period took down AI-assisted study features. Now failover between OpenAI, Anthropic, and Gemini happens automatically.

**Database optimization** — identified 183 tables missing primary keys and 363 missing foreign key indexes in a 499-table production database using custom static analysis tooling. Reduced slow query incidents after targeted index additions.

## Open Source

| Project | What it does | Lang | Tests |
|---------|-------------|------|-------|
| [SQLForensic](https://github.com/mcandiri/sqlforensic) | Database static analysis — [real scan results from 499-table production DB](https://github.com/mcandiri/sqlforensic#real-world-results) | Python | 289 |
| [LLMForge](https://github.com/mcandiri/LLMForge) | Multi-provider LLM calls with failover and circuit breaker | C# | 99 |
| [ExamReader](https://github.com/mcandiri/ExamReader) | OCR exam grading + class analytics | C# | 100+ |
| [DapperForge](https://github.com/mcandiri/DapperForge) | Convention-based SP toolkit — extracted from 200+ SP codebase | C# | ✅ |
| [LiveSQL](https://github.com/mcandiri/LiveSQL) | SQL execution plan visualizer with animated flow diagrams | C# | ✅ |
| [FlowForge](https://github.com/mcandiri/FlowForge) | Visual workflow builder with drag-and-drop canvas + C# export | C# | 118 |

All projects have CI, releases, and run without external dependencies in demo mode.
