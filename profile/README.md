# CostReveal

**Cost attribution for AI, cloud, and API spend. Every figure reconciled. Every basis labeled.**

Know what every dollar of spend is for.

[Website](https://costreveal.com) · [Documentation](https://docs.costreveal.com) · [Blog](https://blog.costreveal.com) · [Sign up](https://app.costreveal.com/signup)

---

## What it is

CostReveal answers one question with precision: what did this feature, customer, workflow, or model actually cost?

Cloud bills tell you what you spent. AI bills are harder: tokens, models, endpoints, and no clear line from spend to the thing that caused it. CostReveal attributes AI, cloud, and API spend to the team, feature, customer, or model responsible, and labels the evidence behind every figure.

## No SDK. No agents. No code changes.

CostReveal reads each provider's billing and usage through that provider's own mechanism. There is nothing to install, no code to instrument, and no agent running in your infrastructure. Connect a provider, and attribution starts from the billing data you already have.

## Every figure carries its evidence basis

| Basis | Meaning |
|-------|---------|
| DIRECT | Taken straight from the provider's bill. |
| INFERRED | Derived from your tags, accounts, and recorded owners. |
| ALLOCATED | Shared costs split by measured usage share. |
| UNKNOWN | The evidence ran out. Shown openly, never guessed away. |

Most cost tools force every dollar into a bucket. A confident guess is still a guess. CostReveal shows UNKNOWN where the evidence ends, so you always know what is proven and what is not.

## Reconciliation, not just reporting

Every number in CostReveal reconciles against two things: the internal ledger, and each provider's own total.

- Open months stay pending until the provider's billing closes.
- A closed month with a difference is a visible variance, not a rounding error.

We verify this on real accounts before a connector ships. On our own AWS account (44,274 billing lines), the ledger total of $1,845.6462531687 agreed exactly across three independent calculations: the CostReveal ledger, AWS Cost Explorer, and a separate DuckDB computation. Every connector is held to the same bar: its figures must reconcile exactly with the provider's invoice before release.

## Connectors

Dedicated connectors for AI, cloud, and API providers:

- **AI:** Anthropic, OpenAI, Cursor
- **Cloud:** AWS, Azure, Google Cloud, Oracle
- **Data:** Snowflake, Databricks
- **Observability:** Datadog, New Relic, Grafana
- **APIs:** Twilio, Cloudflare, Stripe

Pass-through coverage: AWS Bedrock through the AWS connector, Google Gemini through the Google Cloud connector, Azure OpenAI through the Azure connector. Kubernetes has its own intake.

Each connector is released only after its figures reconcile exactly with the provider's invoice.

## Pricing

Flat pricing, never a percentage of your bill. A cost tool that takes a cut of your spend earns more when you waste more.

- **Starter** — $99/month
- **Pro** — $299/month
- **Enterprise** — from $999/month

7-day free trial. No credit card required.

## Connect

- [X](https://x.com/CostReveal)
- [LinkedIn](https://www.linkedin.com/company/costreveal)
- [YouTube](https://www.youtube.com/@CostReveal)
- [Instagram](https://www.instagram.com/costreveal)
- [TikTok](https://www.tiktok.com/@costreveal)
- [Bluesky](https://bsky.app/profile/costreveal.bsky.social)

---

**CostReveal** — Know what every dollar of spend is for.
