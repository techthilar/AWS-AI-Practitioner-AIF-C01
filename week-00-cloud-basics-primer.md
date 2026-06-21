# Week 0 — Cloud-Basics Primer (optional)

[← Back to README](README.md) · **Next:** [Week 1 →](week-01-ai-ml-fundamentals-part-1.md)

> **Skip this week if** you already hold (or are comfortable at the level of) the **AWS Cloud Practitioner (CLF-C02)**. The AI Practitioner exam guide lists familiarity with core AWS services, the shared responsibility model, IAM, and pricing models as recommended prerequisites — this week gets you there.

**Goal:** be comfortable with the AWS building blocks the rest of the plan assumes, so you're learning AI concepts rather than fighting the console.

---

## Topics

- **What the cloud is:** on-demand compute/storage/networking; the value props (elasticity, pay-as-you-go, managed services, global reach)
- **Regions & Availability Zones:** how AWS is laid out geographically and why it matters for latency, data residency, and resilience
- **Core compute & storage:**
  - **Amazon EC2** — virtual servers
  - **Amazon S3** — object storage (where training data and documents commonly live)
  - **AWS Lambda** — serverless functions (event-driven compute)
- **Identity & access:**
  - **IAM** — users, groups, roles, policies; least privilege; why you don't use the root account day-to-day
- **The AWS shared responsibility model** — what AWS secures ("of the cloud") vs. what you secure ("in the cloud")
- **Pricing & cost basics** — pay-as-you-go, the Free Tier, AWS Budgets and Cost Explorer
- **How you interact with AWS** — Management Console, CLI, SDKs (just awareness)

---

## Resources

- **AWS SkillBuilder** — *AWS Cloud Practitioner Essentials* (or the cloud-fundamentals module that introduces EC2, S3, IAM, pricing, and the shared responsibility model)
- **KodeKloud** — if you have access, the *AWS Cloud Practitioner (CLF-C02)* course is the natural companion; otherwise skim the AI Practitioner intro module
- **AWS docs** — [What is AWS?](https://aws.amazon.com/what-is-aws/) and the [Free Tier](https://aws.amazon.com/free/) page

---

## Hands-on

- Create an AWS account if you don't have one.
- **Secure the root account:** enable MFA on root, then create an **IAM admin user** and use that for everything afterward.
- Set up an **AWS Budget** with an email alert (e.g., alert at $5) so labs never surprise you.
- Create an **S3 bucket** and upload a file; delete it afterward. This is the storage layer most AI labs touch.

---

## Self-check

- In one sentence each: what are EC2, S3, Lambda, and IAM for?
- Under the shared responsibility model, who is responsible for patching the **guest OS** on an EC2 instance — you or AWS? (You.) Who secures the **physical data center**? (AWS.)
- Why should you avoid using the root account for daily work?

---

[← Back to README](README.md) · **Next:** [Week 1 →](week-01-ai-ml-fundamentals-part-1.md)
