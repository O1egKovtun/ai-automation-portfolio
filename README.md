# AI Automation Portfolio
Freelance AI Engineer specializing in business automation, LLM integrations, and AI-powered workflows.
2+ years building production systems for B2B clients.
Stack: n8n · Make.com · OpenAI API · Gemini · Next.js · TypeScript
Contact: LinkedIn · Instagram

Projects
1. LinkedIn Lead Outreach Pipeline
Stack: n8n · PhantomBuster · Gemini 2.0 Flash · Airtable
Automated end-to-end B2B lead generation system. Scrapes target profiles from LinkedIn, scores and filters leads using Gemini, generates personalized outreach messages, and logs everything to Airtable CRM.

Reduced manual prospecting time by ~80%
Handles lead scoring, enrichment, and message personalization in one flow
Runs fully unattended on a self-hosted VPS


2. Sales Pipeline Suite
Stack: n8n · Gemini 2.0 Flash · Google Sheets · Calendly · Stripe · Brevo
5 interconnected workflows covering the full sales cycle: lead capture → CRM sync → AI qualification → meeting scheduling → payment processing → automated onboarding email sequence.

Replaced manual handoffs between 5 separate tools
Stripe + Calendly integration triggers onboarding automatically after payment
Google Sheets used as lightweight CRM with real-time sync


3. Dental Clinic Patient Acquisition Workflow
Stack: n8n · ManyChat · WhatsApp Business API
Automated patient acquisition funnel via WhatsApp. Captures leads from ads, qualifies them through a conversational flow in ManyChat, and books appointments — without any manual intervention from clinic staff.

Connected Meta Ads → WhatsApp → booking system in one pipeline
Handles FAQ responses, appointment confirmations, and reminders
Reduced response time from hours to under 2 minutes


4. Instagram DM Automation Agent
Stack: n8n · GPT-4o-mini · Meta Graph API
Conversational AI agent that handles Instagram DMs on behalf of a business. Maintains context across the full conversation thread, qualifies leads, answers product questions, and routes hot leads to a human.

GPT-4o-mini with conversation memory via message history injection
Integrated directly with Meta Graph API — no third-party middleware
Handles objections, FAQs, and lead qualification autonomously


5. AI-Driven CRM + Operational Data Hub
Stack: n8n · OpenAI API · Notion
Centralized operational system that pulls data from multiple sources, processes it with OpenAI, and syncs structured outputs into Notion databases. Used for task management, client tracking, and internal reporting.

Multi-source data aggregation in a single workflow
OpenAI used for data classification, summarization, and tagging
Notion as the single source of truth for operations


6. Content Management Dashboard
Stack: Next.js 15 · TypeScript · Tailwind CSS v4
Internal dashboard for managing and scheduling content across platforms. Built as a standalone web app with a clean UI for non-technical users.

Custom-built with Next.js 15 App Router
Fully typed with TypeScript
Deployed and used in production


Infrastructure
All automation projects are deployed on self-hosted infrastructure:

n8n on VPS (Hetzner) via Docker
Subdomain per client for isolated environments
Credentials and API keys owned by the client
