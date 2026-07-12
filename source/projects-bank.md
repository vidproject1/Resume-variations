# Projects Bank

This file stores verified project facts and reusable resume material. Resume variations must not add technologies, metrics, users, revenue, or responsibilities that are not confirmed here.

## Only Pips Journal

### Project Identity

- **Project name:** Only Pips Journal
- **Product type:** Live vertical SaaS product for forex traders
- **Creator/developer:** Charles Kudzai Muguti
- **Live website:** https://onlypipsjournal.pro
- **Source repository:** https://github.com/vidproject1/onlypips-journal
- **Repository branch inspected:** `main`
- **Current status:** Live and working, based on information provided by Charles
- **Development dates:** To confirm
- **Solo or team project:** To confirm

### Verified Product Description

Only Pips Journal is a web-based trading journal and analytics platform that helps forex traders record trades, manage multiple trading accounts, review performance, follow growth plans, and use strategy execution checklists.

### Verified User-Facing Features

- Email/password account registration and login.
- Authenticated application routes protected by Supabase session state.
- Creation and management of multiple trading accounts.
- Separate account dashboards using account type and account name.
- Trade logging with currency pair, direction, entry price, exit price, profit or loss, outcome, notes, trade type, strategy, and account association.
- Automatic WIN, LOSS, and BREAK EVEN classification from submitted trade data.
- Trade screenshot uploads through Supabase Storage.
- Filtered trade history for the selected account.
- Real-time dashboard refreshes using Supabase PostgreSQL change subscriptions.
- Dashboard statistics, monthly recaps, charts, trading heatmaps, performance metrics, and trade history.
- Performance reports with strategy win rates, execution patterns, monthly frequency, holding duration, labels, and rule-generated insights.
- Growth plans with starting balance, target balance, current balance, risk level, risk percentage, estimated trades, profit and risk per trade, and completion tracking.
- Trading strategy management and execution checklists.
- Marketplace for paid strategy checklist templates.
- Proof-of-payment submission and administrator approval or rejection workflow.
- Automatic provisioning of an approved purchased checklist into a user's strategies and checklist items.
- Public trading blog with categories, post filtering, individual article routes, and published backtest results.
- Backtest administration and display of strategy name, win rate, risk/reward ratio, consistency score, number of tested trades, testing date, and notes.
- Vercel Web Analytics integration.
- Responsive component-based user interface.

### Verified Technical Stack

#### Frontend

- React 18
- TypeScript
- Vite
- React Router
- Tailwind CSS
- shadcn/ui and Radix UI
- React Hook Form
- Zod validation
- TanStack Query
- Recharts
- Lightweight Charts
- Lucide React

#### Backend and Data

- Supabase
- PostgreSQL
- Supabase Authentication
- Supabase Storage
- Supabase real-time PostgreSQL subscriptions

#### Product and Operations

- Vercel Web Analytics
- Vercel deployment is indicated by repository history; deployment configuration should be confirmed before using it as a formal resume claim.

### Engineering Work Demonstrated

- Built authenticated user flows and route protection.
- Designed data-driven workflows spanning accounts, trades, strategies, purchases, blog posts, backtest results, and growth plans.
- Implemented asynchronous database reads and writes with loading, success, and failure states.
- Added real-time synchronization for account trade dashboards.
- Implemented file upload and public URL handling for trade screenshots and payment evidence.
- Built data visualizations and rule-based performance analysis from user trade history.
- Built both customer-facing product surfaces and administrative workflows.
- Implemented a marketplace fulfillment workflow that converts approved purchases into user-accessible strategy data.
- Maintained a public content surface alongside the authenticated SaaS application.

### AI-Assisted Development Workflow

- Only Pips Journal does **not** contain an in-product LLM feature.
- No OpenAI, Anthropic, Gemini, GLM, chat-completions, or comparable model integration was verified in the deployed application code.
- Charles used **TRAE IDE** as an AI-assisted software-development environment while building the application over multiple months.
- Charles reports that TRAE provided access to models from multiple providers, including ChatGPT/OpenAI, Gemini, and GLM, and supported connecting additional model APIs.
- Charles used both **Claude Sonnet 4.6** and **Claude Opus 4.6** through API connections during development.
- Earlier in the project, Charles likely used one or more **GPT-4-family** models. The exact GPT model names and versions were not retained and should not be stated more precisely.
- Because the project spanned multiple months and available models changed during development, the complete model list and exact usage chronology cannot be reconstructed reliably.
- The confirmed distinction is: AI was used to help design and build the software; AI is not currently a feature delivered to the application's users.

### Resume-Safe Summary Draft

Creator and developer of Only Pips Journal, a live forex trading SaaS platform with multi-account trade logging, real-time analytics, performance reporting, growth planning, strategy checklists, marketplace fulfillment, administrative payment review, public content, and backtest publishing. Used TRAE IDE with multiple LLMs, including Claude Sonnet 4.6, Claude Opus 4.6, and GPT-4-family models, as an AI-assisted development environment.

### Candidate Resume Bullets

These bullets are usable after Charles confirms his exact ownership and contribution level:

- Built and launched a full-stack forex trading journal SaaS using React, TypeScript, Supabase, PostgreSQL, and Vercel-oriented tooling.
- Used TRAE IDE with multiple LLMs, including Claude Sonnet 4.6, Claude Opus 4.6, and GPT-4-family models, to support AI-assisted application design, implementation, debugging, and iteration.
- Implemented multi-account trade logging, screenshot uploads, real-time dashboard updates, and analytics across charts, heatmaps, monthly recaps, and performance reports.
- Developed authenticated customer workflows and administrative tools for paid checklist purchases, payment-evidence review, approval, and automatic content provisioning.
- Created rule-based trading performance analysis covering strategy win rates, execution consistency, trade frequency, holding duration, and generated user insights.
- Added growth-planning, backtesting, strategy checklist, marketplace, and database-backed public blog features within a unified product.

### Claims That Still Need Confirmation

- Charles's exact title for the project.
- Whether the project was built alone or with collaborators.
- Start date, launch date, and ongoing maintenance dates.
- Which features Charles personally designed and implemented.
- How AI assistance was used in practice: requirements, architecture, code generation, refactoring, debugging, database design, testing, deployment, content, or other work.
- Which Gemini, GLM, OpenAI, or other models Charles personally used on this project, rather than merely having access to them.
- Number of registered users and active users.
- Revenue, subscriptions, marketplace sales, or other commercial traction.
- Number of recorded trades, uploaded screenshots, strategies, plans, or blog readers.
- Performance, reliability, conversion, retention, or time-saving metrics.
- Exact hosting and deployment setup.
- Whether any roadmap or README-listed features are no longer active in the current routed product.

### Accuracy Notes

- The repository README mentions a market predictor and notification system, but those features were not fully verified in the current routed application during this inspection. Do not include them in a resume until their current implementation is confirmed.
- The performance-report system is rule-based TypeScript analysis, not an LLM feature.
- Do not phrase any model connection as an application integration. The models belonged to the development environment, not the user-facing SaaS product.
- Do not invent an exact GPT model version or a complete chronological model list when Charles no longer has reliable records of them.
