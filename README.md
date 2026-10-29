# n8n Workflows Portfolio

Hafiz Syed Shah Ali - AI Engineer · SOC Engineering & Security Automation, building n8n, AI agent and data workflows.
LinkedIn: https://www.linkedin.com/in/hafizsyedshahali
Email: mrali2813@gmail.com

This repository contains 26 n8n workflows I built for customer service, content, marketing, HR, reporting and security. Each workflow has its own folder with the exported `workflow.json` and a README that explains how it works and how to set it up. All credentials, IDs and personal data have been replaced with placeholders.

Several workflows started from n8n community templates and were extended and adapted for real use cases; each README notes this.

## Featured Projects

| Project | What it does |
|---|---|
| [Suspicious Login Detection](workflows/security/suspicious-login-detection/) | Enriches login events with GreyNoise, IP-API and UserParser, alerts Slack by priority and emails users about new locations or devices |
| [WhatsApp HR Assistant Multi-Agent System](workflows/ai-agents/whatsapp-hr-assistant-multi-agent/) | Routes WhatsApp messages to agents for leave, HR policy RAG, attendance, complaints and candidate shortlisting |
| [WhatsApp Voice Appointment Setter](workflows/customer-service/whatsapp-voice-appointment-setter/) | Books appointments from text or voice notes, syncs Google Calendar and Sheets, and sends reminders |
| [Multi-Agent SEO Blog Writer](workflows/content-automation/multi-agent-seo-blog-writer/) | Researches search results and writes a full SEO article with internal links into Google Docs |
| [Voice RAG Chatbot with ElevenLabs](workflows/ai-agents/voice-rag-chatbot-elevenlabs/) | Voice agent that answers from a Qdrant knowledge base built from Google Drive |

## All Workflows

### Security

| Workflow | Description | Integrations |
|---|---|---|
| [Suspicious Login Detection](workflows/security/suspicious-login-detection/) | Scores login risk and notifies Slack and the user | Webhook, Postgres, GreyNoise, IP-API, UserParser, Slack, Gmail |

### AI Agents

| Workflow | Description | Integrations |
|---|---|---|
| [WhatsApp HR Assistant Multi-Agent System](workflows/ai-agents/whatsapp-hr-assistant-multi-agent/) | Multi-agent HR assistant on WhatsApp | WhatsApp, OpenAI, Supabase, Google Sheets, Gmail, Google Calendar |
| [Voice RAG Chatbot with ElevenLabs](workflows/ai-agents/voice-rag-chatbot-elevenlabs/) | Voice Q&A over your documents | ElevenLabs, OpenAI, Qdrant, Google Drive |
| [AI CV Screening and Scoring](workflows/ai-agents/ai-cv-screening-scoring/) | Extracts, summarises and scores uploaded CVs | n8n Form, Gemini, Google Drive, Google Sheets |
| [RAG Chatbot with Supabase and Postgres](workflows/ai-agents/rag-chatbot-supabase-postgres/) | Chat agent with document search and chat memory | Gemini, Supabase, Postgres, Google Drive |

### Customer Service

| Workflow | Description | Integrations |
|---|---|---|
| [WhatsApp Voice Appointment Setter](workflows/customer-service/whatsapp-voice-appointment-setter/) | Appointment booking with voice notes and reminders | WhatsApp, Gemini, Google Calendar, Google Sheets, Gmail |
| [WhatsApp Salon Booking Agent](workflows/customer-service/whatsapp-salon-booking-agent/) | Salon receptionist for services, stylists and bookings | WhatsApp, Gemini, Google Sheets |
| [WhatsApp Restaurant Reservation Agent](workflows/customer-service/whatsapp-restaurant-reservation-agent/) | Takes reservations and sends confirmation or rejection | WhatsApp, Gemini, Google Sheets |
| [WhatsApp Restaurant Ordering Agent](workflows/customer-service/whatsapp-restaurant-ordering-agent/) | Menu, FAQs, orders and stock updates | WhatsApp, Gemini, Google Sheets |
| [WhatsApp Food Ordering Bot with Excel](workflows/customer-service/whatsapp-food-ordering-bot-excel/) | Ordering bot with Excel data and menu images | WhatsApp, OpenRouter, Microsoft Excel 365 |

### Content Automation

| Workflow | Description | Integrations |
|---|---|---|
| [Multi-Agent SEO Blog Writer](workflows/content-automation/multi-agent-seo-blog-writer/) | Multi-step SEO article writer with internal links | Airtable, Tavily, Claude, OpenAI, Google Docs, Google Drive |
| [AI Social Media Post Publisher](workflows/content-automation/ai-social-media-post-publisher/) | Daily AI post and image to X, LinkedIn and Facebook | OpenAI, Google Sheets, X, LinkedIn, Facebook |
| [AI Document to PDF Generator](workflows/content-automation/ai-document-to-pdf-generator/) | Turns a topic into a formatted PDF in Drive | n8n Form, Gemini, Google Drive |
| [AI Prompt to Image Generator](workflows/content-automation/ai-prompt-to-image-generator/) | Expands an idea into prompts and generates images | Gemini, Pollinations.ai |

### Marketing

| Workflow | Description | Integrations |
|---|---|---|
| [Google Ads PPC Performance Monitor](workflows/marketing/google-ads-ppc-performance-monitor/) | Daily campaign scoring, alerts and action plans | Google Ads, Google Sheets, Slack, SMTP |
| [Product Research and SEO Content Generator](workflows/marketing/product-research-seo-content-generator/) | Competitor search and SEO product copy | Google Custom Search, Gemini, Google Sheets |
| [Instagram Comment Auto-Reply Agent](workflows/marketing/instagram-comment-auto-reply-agent/) | AI replies to new Instagram comments | Instagram Graph API, OpenRouter |

### CRM

| Workflow | Description | Integrations |
|---|---|---|
| [AI Sales Leaderboard for HighLevel](workflows/crm/ai-sales-leaderboard-highlevel/) | Per-rep sales summary, Notion page and Slack messages | HighLevel, Azure OpenAI, Notion, Slack, Google Sheets |

### Lead Generation

| Workflow | Description | Integrations |
|---|---|---|
| [Facebook Lead Ads to Salesforce Sync](workflows/lead-generation/facebook-lead-ads-salesforce-sync/) | Logs new leads and creates them in Salesforce | Facebook Lead Ads, Google Sheets, Salesforce |

### Data Sync

| Workflow | Description | Integrations |
|---|---|---|
| [Invoice OCR Extraction to Sheets](workflows/data-sync/invoice-ocr-extraction-to-sheets/) | OCR and AI extraction of invoices into a ledger | Google Drive, OCR.Space, OpenAI, Google Sheets |

### Reporting

| Workflow | Description | Integrations |
|---|---|---|
| [AI Data Analyst Chart Reports](workflows/reporting/ai-data-analyst-chart-reports/) | Chat question to emailed chart report | Gemini, Google Sheets, QuickChart, Gmail |

### Email

| Workflow | Description | Integrations |
|---|---|---|
| [AI News Research Newsletter Agent](workflows/email/ai-news-research-newsletter-agent/) | Researches a topic and emails an HTML newsletter | OpenRouter, Perplexity, Gmail |
| [Gmail Duplicate Candidate Detector](workflows/email/gmail-duplicate-candidate-detector/) | Flags repeat job applicants in Slack | Gmail, Google Sheets, Slack |

### Education

| Workflow | Description | Integrations |
|---|---|---|
| [Student Absence Alerts and Reports](workflows/education/student-absence-alerts-reports/) | Daily absence alerts to parents and reports | Google Sheets, Gmail, WhatsApp |
| [Website Course FAQ Chatbot](workflows/education/website-course-faq-chatbot/) | Course and FAQ chatbot for a website | OpenRouter, Google Sheets |

### Healthcare

| Workflow | Description | Integrations |
|---|---|---|
| [Blood Bank Low Stock Alerts](workflows/healthcare/blood-bank-low-stock-alerts/) | Daily WhatsApp alerts for low blood stock | Google Sheets, WhatsApp |

## How to import a workflow into n8n

1. Open the workflow folder and download `workflow.json` (or copy its contents).
2. In n8n, create a new workflow, open the menu (three dots) and choose **Import from File**. You can also paste the JSON directly onto the canvas.
3. Create the credentials listed in the workflow's README and select them in each node. The export uses names like `YOUR_GOOGLE_SHEETS_CREDENTIAL` to show where a credential is needed.
4. Replace every `{{PLACEHOLDER}}` value (IDs, emails, phone numbers, URLs) with your own.
5. Run the workflow once manually, then activate it.

## Repository structure

```
workflows/
  <category>/
    <workflow-name>/
      workflow.json
      README.md
```

## Tech stack

n8n, LangChain AI agents, OpenAI, Google Gemini, Anthropic Claude, OpenRouter, ElevenLabs, Supabase, Qdrant, Postgres, WhatsApp Cloud API, Google Workspace, Slack, Airtable, Notion, HighLevel, Salesforce.

## License

[MIT](LICENSE)
