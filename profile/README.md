# HER Solutions LLC

**We're building Farewell John**, the compassionate operating system for end-of-life care in America.

Death is a $20B industry where families are expected to make $10,000+ decisions in 24-72 hours, with no price transparency, no verified reviews, and no guidance. We're fixing that.

---

## What We're Building

**[Farewell John](https://farewelljohn.com)** is a platform that connects families to funeral homes, grief counselors, estate attorneys, and memorial services through:

- **Verified, review-ranked provider search** -- location-based discovery with transparent pricing and authentic user reviews across all end-of-life service categories
- **Jane** -- an AI assistant providing 24/7 emotional and practical support, from "what do I do in the next 72 hours" to long-term grief companionship
- **Family coordination tools** -- shared planning dashboards, task delegation, and document vaults for the people who need to coordinate across distance and grief
- **Partner portal** -- self-service lead management and analytics for funeral homes and care providers

---

## The Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js 15, TypeScript, Tailwind CSS 4 |
| API | Node.js / Express, PostgreSQL, Redis |
| Data pipelines | Apache Airflow, Google Places + Foursquare enrichment |
| Infrastructure | AWS (CloudFront, S3, SES, Secrets Manager), Docker |
| AI | Claude API -- context-aware grief support and content generation |
| Mobile | Expo (iOS/Android) |

Our data pipeline ingests and enriches funeral home records across the US, normalizing pricing, hours, services, and contact data from multiple sources into a single verified dataset.

---

## Engineering Approach

We operate lean -- a small team moving fast with production-grade infrastructure from day one:

- **Airflow-orchestrated ETL** for ongoing data freshness and anomaly detection across provider records
- **Event-driven observability** -- request ID propagation end-to-end, structured logging, DataDog integration
- **GitOps delivery** -- GHCR container registry, GitHub Actions CI/CD, CloudFront-fronted deployments
- **Privacy-first architecture** -- HIPAA/CCPA-aligned data handling; grief conversations stay encrypted and never used for ads

Most of our repos are private while we're pre-launch -- we'll open-source components of the data pipeline and tooling as we stabilize.

---

## Why This Market

73% of Americans want funeral price transparency. The average family has **less than 48 hours** to choose a funeral home -- under acute emotional distress, with no reliable information source. The incumbent comparison tools are thin directories with no reviews, no pricing data, and no human support layer.

We're building the infrastructure this market has never had.

---

## Status

Currently in active development. Demo live at **[farewelljohn.com/demo/](https://farewelljohn.com/demo/)**.

📍 Los Angeles, CA &nbsp;|&nbsp; 🌐 [farewelljohn.com](https://farewelljohn.com) &nbsp;|&nbsp; 📬 admin@hersolutions.live
