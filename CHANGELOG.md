# Changelog

All notable product changes to Profferio are documented here.
This is a public, customer-facing changelog — no source code is included.

The format is based on [Keep a Changelog](https://keepachangelog.com/).

## [Unreleased]
### Coming soon
- 🐳 Containerised deployment (Docker) for one-command self-hosting
- 📈 Additional report widgets and dashboard customisation
- 🌍 Full English UI localisation

---

## [1.0] — 2026-06-01
🎉 **First public release.** Profferio goes public with a customer-facing showcase, multi-company subdomain hosting and a year of features hardened for production.

### Added
- Public showcase and bilingual (🇬🇷/🇬🇧) documentation
- Isolated per-company instances on dedicated subdomains (`company.profferio.com`)

### Improved
- End-to-end stability, performance and security hardening across all modules
- Polished UI with light/dark themes throughout

---

## [0.9] — 2026-04-12
### Added
- 🤖 **AI Assistant "Chara"** — powered by advanced AI, with live tool-based access to tickets, roster, attendance and logs
- **Microsoft 365 SSO** for one-click sign-in
### Improved
- Persistent chat history and Greek-language responses

---

## [0.8] — 2026-03-08
### Added
- 📊 **Reports & Dashboards** — multi-dimensional pivot tables (by assignee, reporter, status, custom fields)
- Live KPI counters (total, created today, open, in progress, done)
- One-click **CSV export** and date-range filtering

---

## [0.7] — 2026-02-02
### Added
- 🌐 **Customer Portal** — branded self-service portal with guided forms and real-time ticket tracking
- 🔔 **Notifications** — real-time in-app alerts (Socket.io) and email on assignment, status change and comments
### Improved
- @mentions and internal notes in ticket comments

---

## [0.6] — 2026-01-15
### Added
- ⚙️ **Automation engine** — triggers on ticket created / status changed / comment added
- Conditions with AND/OR logic; actions for auto-assign, auto-comment, set field, transition status and cross-project escalation
- **Saved filters** — personal and shared, with custom column layouts
### Fixed
- Prevented automation loops with loop-safe execution

---

## [0.5] — 2025-11-20
### Added
- 🔀 **Workflow Builder** — custom statuses, categories, colours and transition rules
- Permission-aware transitions with required-field validation
- ⏱️ **SLA tracking** — first-response and resolution targets with live countdown timers

---

## [0.4] — 2025-10-10
### Added
- 📝 **Form Builder** — drag-and-drop editor with 8+ field types and form sections
- **Conditional logic** — show/hide fields and sections based on answers
- Field validation (email, phone, number, length, patterns) and a reusable field library
### Improved
- Form versioning with rollback and live preview

---

## [0.3] — 2025-09-05
### Added
- 🎫 **Service Management (PSM)** foundation — service projects with custom prefixes and auto-generated ticket keys (e.g. `SUPPORT-042`)
- **Kanban board** with drag-and-drop across statuses
- Per-ticket immutable audit trail

---

## [0.2] — 2025-07-18
### Added
- 🛠️ **Helpdesk / ticketing** — categories, priorities, file attachments and comment threads
- **Team monitoring** — live presence and team roster
- Login logs and session tracking
### Improved
- Role-based access (Admin / Manager / User)

---

## [0.1] — 2025-06-09
### Added
- 🚀 Initial release: secure JWT authentication and user management
- User dashboard with project-based shortcuts
- ⏱️ **Time tracking** — clock-in/break/resume/stop, shift schedules and day types
- Automated daily backups and scheduled background jobs
