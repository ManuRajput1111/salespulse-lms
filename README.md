# SalesPulse LMS

A full-stack Lead Management System (CRM) built with Supabase + vanilla JavaScript — designed for a sales team to manage their entire pipeline, automate follow-ups, and track performance.

🔗 **Live Demo:** [salespulse-lms-demo.netlify.app]
👀 **Try it instantly:** Click "Continue as Guest" on the login screen — no signup needed.

## Features
- Role-based access control (Admin / Sales / KAM) with PostgreSQL Row-Level Security
- Guest/View-only demo mode for public showcasing
- Full lead pipeline (Cold → Warm → Hot → Deal Closed / Lost) with stage-based mandatory fields
- Bulk Excel import/export with duplicate detection & merge tool
- Automated daily email follow-up reminders (SendGrid + Supabase Edge Functions)
- Real-time analytics: trend charts, win rate, lead source effectiveness, priority scoring
- Full activity log / audit trail
- Existing-client upsell/cross-sell tracker
- Dark mode, mobile-responsive, XSS-protected

## Tech Stack
Frontend: HTML, CSS, Vanilla JS, Chart.js
Backend: Supabase (PostgreSQL, Auth, RLS, Storage, Edge Functions)
Email: SendGrid | Hosting: Netlify

