# Profferio — Feature Overview

A deeper look at what Profferio does. For the short version, see the [README](../README.en.md).

---

## 🎫 Service Management (PSM)

A complete alternative to Jira Service Management.

- **Custom workflows** — define statuses, categories (Open / In Progress / Done), colours and transition rules.
- **Permission-aware transitions** — control who can move a ticket and when, with required-field validation before a transition is allowed.
- **Kanban boards** — drag-and-drop tickets between columns, with live updates for everyone on the board.
- **SLA tracking** — first-response and resolution targets with live countdown timers.
- **Saved filters** — personal and shared/public filters, custom column layouts, multi-criteria filtering.
- **Audit trail** — every change to a ticket is recorded immutably.

## 📝 Dynamic Form Builder

- Drag-and-drop builder with sections for organisation.
- Field types: text, textarea, dropdown, radio, checkbox group, date, file upload and more.
- **Conditional logic**: show or hide fields and entire sections based on the values of other fields (AND/OR matching).
- Validation: email, phone, number, URL, alphabetic, min/max length and choices.
- Form versioning with rollback and live preview.

## ⚙️ Workflow Automation

- **Triggers**: ticket created, status changed, comment added.
- **Conditions**: AND/OR logic on any form field (equals, not equals, contains, empty, not empty).
- **Actions**: add a comment, set a field value, assign a user, clear assignee, transition status, or create a linked ticket in another project (escalation).
- Loop-safe execution so automations never cascade uncontrollably.

## 🌐 Customer Portal

- Self-service portal where your customers submit requests through guided forms.
- Customers see only their own tickets and assigned projects.
- Real-time status updates and attachment downloads.

## 🤖 AI Assistant — "Chara"

- Powered by advanced AI.
- Answers questions about tickets, team roster, attendance, login activity and audit logs.
- Uses live, tool-based data access — it queries the real data rather than guessing.

## ⏱️ Time Tracking & Payroll

- Clock-in / break / resume / stop with millisecond precision.
- Shift schedules with two shifts per day supported.
- Day types: work, day-off (repo), sick, vacation, absent, left.
- Late-arrival alerts to team leaders and admins.
- Month-to-date aggregation for payroll.

## 📊 Reports & Dashboards

- Multi-dimensional pivot tables: rows by assignee, reporter, status or any custom field.
- Live KPI counters: total, created today, open, in progress, done.
- Date-range filtering and one-click CSV export.

## 🔔 Notifications & Collaboration

- Real-time in-app notifications via Socket.io.
- Email alerts on assignment, status change and new comments.
- @mentions, internal notes and complete activity history per ticket.

## 🔐 Security & Administration

- Role-based access control: Admin, Manager, User, Customer.
- Microsoft 365 single sign-on.
- Rate limiting, input sanitisation and security headers.
- Immutable audit logging and automated daily backups.

---

## 🏗️ Architecture & deployment

Each company runs as an **isolated instance** on its own subdomain
(`company.profferio.com`) with fully separated code and data.

| Model | Where it runs | Managed by |
|---|---|---|
| **Cloud** | Profferio infrastructure | Profferio |
| **Self-hosted** | Your servers | You |
| **Hybrid** | App and data split per your compliance needs | Shared |

**Tech stack:** React · Node.js · Express · MongoDB · Socket.io · AI.

---

> Questions? Visit [www.profferio.com](https://www.profferio.com) or [open a ticket](../../../issues/new/choose).
