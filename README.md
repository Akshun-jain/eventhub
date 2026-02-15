# EventHub - Multi-Group Event Reminder Platform

A production-ready, cross-platform event reminder application for families,
offices, schools, colleges, and communities.

## Features
- Multi-group system with admin/member roles
- Event management (birthdays, anniversaries, meetings, custom)
- Multi-channel notifications (Push, SMS, WhatsApp, Email)
- Cross-platform (Android, iOS, Web)
- Recurring events with timezone support
- Calendar view with search & filter

## Quick Start

### Prerequisites
- Node.js 20+
- PostgreSQL 15+
- Redis 7+
- Flutter 3.16+
- Docker & Docker Compose

### Backend Setup
```bash
cd backend
cp .env.example .env
# Edit .env with your credentials
npm install
npm run db:migrate
npm run db:seed
npm run dev