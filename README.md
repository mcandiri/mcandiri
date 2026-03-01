# Mehmet Can Diri

Lead Software Engineer at [Veritas Education](https://veritasedu.net). I lead architecture and delivery for an education platform serving 1,500+ students, 350+ teachers, and 40+ staff daily.

## What I've Shipped

**Veritas2** — core education platform handling course registration, student tracking, attendance, grading, financial operations, and parent communication. Originally built in Windows Forms, currently migrating to .NET 8 + Blazor Server for remote access and multi-device support. SQL Server backend with 500+ tables and 2,000+ stored procedures.

**EduConsult** — multi-tenant SaaS platform for education consultancy firms. 38 modules including student CRM, application tracking, visa management, document generation, and financial reporting. Smart university matching recommends the best-fit schools based on student profile, academic history, budget, and preferences. Built for Turkish and international markets with 
full bilingual support (TR/EN).

**Verityprep** — student-facing exam preparation platform with AI-powered personalized study programs using spaced repetition. Identifies weak topics per student and generates targeted practice. AI-driven explanations adapt to each student's preferred learning style, and an unlimited question generator produces fresh exercises on demand. Uses a hybrid approach — custom fine-tuned models combined with commercial LLM APIs (OpenAI, Anthropic, Gemini) to produce the most accurate explanations and highest-quality questions.

**ChatAssist AI** — AI-powered chatbot SaaS (in development). ASP.NET Core + Vector DB + LLM API + SignalR real-time widget + Stripe billing. Dogfooding on Veritasedu before public launch.

**Mobile apps** — cross-platform mobile applications for Veritas Education built with Flutter. Published on both App Store and Google Play. Push notifications via Firebase, offline-capable.

**Digital exam system** — replaced paper-based exams with online testing: timed sessions, randomized questions, automated grading. What used to take staff 2–3 days of manual work now completes in under 15 minutes.

## Open Source

Tools I extracted from the projects above and open-sourced:

| Project | What it does | Lang |
|---------|-------------|------|
| [SQLForensic](https://github.com/mcandiri/sqlforensic) | Database static analysis — [real scan results](https://github.com/mcandiri/sqlforensic#real-world-results) | Python |
| [LLMForge](https://github.com/mcandiri/LLMForge) | Multi-provider LLM calls with failover and circuit breaker | C# |
| [ExamReader](https://github.com/mcandiri/ExamReader) | OCR exam grading + class analytics | C# |
| [DapperForge](https://github.com/mcandiri/DapperForge) | Convention-based SP toolkit — extracted from 200+ SP codebase | C# |
| [LiveSQL](https://github.com/mcandiri/LiveSQL) | SQL execution plan visualizer with animated flow diagrams | C# |
| [FlowForge](https://github.com/mcandiri/FlowForge) | Visual workflow builder with drag-and-drop canvas + C# export | C# |

Each project has CI and can run in demo mode without external dependencies.
