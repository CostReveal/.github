<div align="center">

# CostReveal - Unified Spend Observability

CostReveal is the system of record for infrastructure cost. It answers one question with precision:

**What did this feature, customer, workflow, or integration actually cost us?**

[Get Started](https://costreveal.com) • 
[Documentation](https://docs.costreveal.com) • 
[Blog](https://blog.costreveal.com)

</div>

## Overview

CostReveal is a developer-first platform that combines runtime application telemetry with infrastructure cost data to deliver real-time, feature-level cost attribution.

Provider dashboards show total spend.

CostReveal shows:
- which feature generated the cost  
- which user or customer triggered it  
- which team owns it  

This enables teams to reason about cost in business terms—not raw invoices.

## Why CostReveal

Provider dashboards tell you what you spent.

CostReveal tells you **why you spent it**.

A single user action can trigger:
- multiple AI model calls  
- multiple API requests  
- multiple infrastructure operations  

Each one adds cost.

CostReveal connects all of them back to:
- the feature  
- the user  
- the team  

So you can understand cost as part of your product — not just your bill.

## What CostReveal is Built For

Teams adopt CostReveal to:

- Attribute AI, cloud, and API spend to features, users, projects, or customers  
- Detect cost regressions before month-end through budgets and alerts  
- Connect cost and revenue signals to understand unit economics  
- Give engineering, finance, and product teams a shared view of cost behavior  

## How CostReveal Works

CostReveal operates across two data paths.

### 1. Application Telemetry

SDKs capture runtime events from your application and send structured usage data.

- Supported SDKs: Python, Node.js, Go, Java  
- Common fields: `feature`, `userId`, `tenantId`, `action`, `metadata`  
- Enables feature-level and user-level attribution  

### 2. Native Integrations

CostReveal connects directly to infrastructure and SaaS systems for cost and operational data.

| Category | Integrations |
|----------|-------------|
| Cloud Cost Sync | AWS, Azure, Google Cloud Platform |
| AI Providers | OpenAI, Anthropic, Google Gemini, AWS Bedrock, Azure OpenAI, Mistral |
| Vector / AI Infra | Pinecone |
| Voice / Media AI | ElevenLabs |
| Revenue Sync | Stripe |
| Alerting | Slack Alerts, Email |
| Communication APIs | Twilio |
| Identity & Access | SSO / SAML, MFA |
| Governance | Audit Logs |

## Core Platform Capabilities

### Cost Attribution
Understand cost by:
- feature  
- user  
- customer  
- team  
- project  

Move beyond provider-level billing into product-level visibility.

### Cost Optimization
- Identify cost regressions early  
- detect inefficient workflows  
- evaluate model and service usage  
- surface savings opportunities  

### Cost Intelligence
- Real-time anomaly detection  
- budget tracking and alerts  
- cost trends and insights  

### Governance & Control
- API keys and access control  
- audit logs and activity tracking  
- SSO / SAML for enterprise environments  

### Unit Economics
- cost per user  
- cost per feature  
- cost vs revenue (via Stripe integration)  
- feature-level profitability insights  

## What You’ll See

After integration, CostReveal shows:

- Cost per feature (e.g. “Search → $4,200/month”)  
- Cost per user or customer  
- AI model cost breakdown (input/output tokens)  
- API cost attribution (Stripe, Twilio, etc.)  
- Real-time anomalies and budget alerts  

This is where teams move from:
"our bill increased"

to:
"this feature caused it"

## Getting Started

CostReveal is designed for rapid adoption.

### 1. Create a Project
Set up a CostReveal project for your product or environment.

### 2. Instrument Your Application
Install an SDK and add attribution context where required.

```bash
npm install @costreveal/node
```

```typescript
import { CostReveal } from "@costreveal/node";

const cr = new CostReveal({
  apiKey: process.env.COSTREVEAL_API_KEY,
});
```

### 3. Connect Integrations

Connect cloud, AI, and API providers such as:

- AWS / Azure / GCP
- OpenAI / Anthropic / Gemini
- Stripe / Slack

### 4. Validate Data

Review:

- Overview dashboard
- Cost pages
- Budgets and alerts

### 5. Operationalize

Use CostReveal in:

- engineering reviews
- budgeting workflows
- cost optimization decisions

## What to Expect

CostReveal provides a practical operating layer on top of raw billing data.

- **Attribution:** cost mapped to real product behavior
- **Optimization:** clear visibility into cost drivers
- **Governance:** control via alerts, budgets, and access
- **Unit Economics:** cost aligned with revenue and usage

## What CostReveal Does Not Replace

CostReveal complements existing systems.

It does not:

- replace AWS, Azure, GCP, or Stripe billing systems
- require request payload or PII capture
- sit in the request path as a hard dependency

## Sign Up

You can get started in minutes.

- No complex setup
- No infrastructure changes required
- First insights available shortly after integration

**Create an account:**
[https://costreveal.com](https://app.costreveal.com/signup)

## Documentation

- **Getting Started:** [https://docs.costreveal.com](https://docs.costreveal.com/getting-started/introduction)
- **SDKs:** [https://docs.costreveal.com](https://docs.costreveal.com/sdks/overview)
- **Integrations:** [https://docs.costreveal.com](https://docs.costreveal.com/integrations/overview)

## Comparison

CostReveal complements and extends existing tools.

| Tool | What it does | What it misses |
|------|-------------|----------------|
| AWS / GCP / Azure | Billing and usage reports | No feature or user-level attribution |
| AI tracing tools | Model-level insights | No cloud or API cost visibility |
| FinOps tools | Cost allocation dashboards | Limited real-time and AI-native tracking |

CostReveal unifies all three layers into a single system.

## Category Definition

CostReveal defines a new category: **Unified Spend Observability**

A system of record for infrastructure cost across:

- cloud platforms
- AI systems
- third-party APIs

This is not a dashboard.

It is an operational intelligence layer for modern software systems.
or developers. Trusted by finance.</p>
