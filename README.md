# AWS Certified AI Practitioner (AIF-C01) — Study Plan

An 8-week, week-by-week learning plan for the **AWS Certified AI Practitioner (AIF-C01)** exam, built around three sources:

- **Official exam guide** — [AWS Certification: AIF-C01](https://docs.aws.amazon.com/aws-certification/latest/ai-practitioner-01/ai-practitioner-01.html)
- **AWS SkillBuilder** — [AI Practitioner Learning Plan](https://skillbuilder.aws/learning-plan/G8ENMJ5QBE/aws-artificial-intelligence-practitioner-learning-plan/SU2A1EJM1A)
- **KodeKloud notes** — [AWS Certified AI Practitioner notes](https://notes.kodekloud.com/docs/AWS-Certified-AI-Practitioner/Introduction/Introduction/page)

The plan is sequenced by the five exam domains and weighted toward the heaviest ones. Domain 3 (28%) gets two weeks; Domains 4 and 5 (14% each) share a week. **Week 0 is an optional cloud-basics primer** for anyone not already at AWS Cloud Practitioner level.

---

## How to use this plan

- **Pace:** ~5–7 hours/week (one focused weekday session + one weekend session). Adjust the calendar, not the content.
- **Baseline:** comfort with core AWS services (EC2, S3, Lambda, IAM) at roughly AWS Cloud Practitioner level. If that's new to you, start with **[Week 0](week-00-cloud-basics-primer.md)**.
- **Weekly rhythm that works well:**
  1. Watch/read the SkillBuilder module for the week.
  2. Read the matching KodeKloud lesson(s) and take your own short notes.
  3. Do the hands-on task (most are free-tier friendly).
  4. Take the end-of-week self-check before moving on.
- **A note on sources:** the KodeKloud lesson titles in each week are exact. SkillBuilder course names and ordering can change — treat the SkillBuilder references as "do the module covering this topic" and follow the exact sequence inside the linked learning plan.

---

## Exam snapshot

| Item | Detail |
|---|---|
| Exam code | AIF-C01 |
| Scored questions | 65 ( 50 plus 15 unscored) |
| Question types | Multiple choice, multiple response, ordering, matching |
| Scoring | 100–1,000 scaled; **700 to pass** |
| Result | Pass/fail; compensatory scoring (no per-domain pass needed) |

## Domain weightings

| Domain | Topic | Weight | Covered in |
|---|---|---|---|
| 1 | Fundamentals of AI and ML | 20% | Weeks 1–2 |
| 2 | Fundamentals of Generative AI | 24% | Weeks 3–4 |
| 3 | Applications of Foundation Models | 28% | Weeks 4–6 |
| 4 | Guidelines for Responsible AI | 14% | Week 7 |
| 5 | Security, Compliance, and Governance | 14% | Week 7 |
| — | Review + mock exams | — | Week 8 |

---

## The plan, week by week

| Week | Focus | File |
|---|---|---|
| 0 | Cloud-basics primer (optional) | [week-00-cloud-basics-primer.md](weeks/week-00-cloud-basics-primer.md) |
| 1 | AI/ML Fundamentals (Part 1) + account setup | [week-01-ai-ml-fundamentals-part-1.md](weeks/week-01-ai-ml-fundamentals-part-1.md) |
| 2 | AI/ML Fundamentals (Part 2) | [week-02-ai-ml-fundamentals-part-2.md](weeks/week-02-ai-ml-fundamentals-part-2.md) |
| 3 | GenAI Fundamentals (Part 1) | [week-03-genai-fundamentals-part-1.md](weeks/week-03-genai-fundamentals-part-1.md) |
| 4 | GenAI wrap-up + FM Applications (Part 1) | [week-04-genai-wrapup-and-fm-applications-part-1.md](weeks/week-04-genai-wrapup-and-fm-applications-part-1.md) |
| 5 | Prompting, RAG & Customization | [week-05-prompting-rag-customization.md](weeks/week-05-prompting-rag-customization.md) |
| 6 | Fine-tuning & Evaluation + lab day | [week-06-finetuning-and-evaluation.md](weeks/week-06-finetuning-and-evaluation.md) |
| 7 | Responsible AI + Security/Compliance/Governance | [week-07-responsible-ai-and-security-governance.md](weeks/week-07-responsible-ai-and-security-governance.md) |
| 8 | Review + mock exams + **exam** | [week-08-review-and-mock-exams.md](weeks/week-08-review-and-mock-exams.md) |

---

## Progress tracker

- [ ] Week 0 — Cloud-basics primer *(skip if already at Cloud Practitioner level)*
- [ ] Week 1 — AI/ML Fundamentals Part 1 + account setup
- [ ] Week 2 — AI/ML Fundamentals Part 2
- [ ] Week 3 — GenAI Fundamentals Part 1
- [ ] Week 4 — GenAI wrap-up + FM Applications Part 1
- [ ] Week 5 — Prompting, RAG & Customization
- [ ] Week 6 — Fine-tuning & Evaluation + lab day
- [ ] Week 7 — Responsible AI + Security/Compliance/Governance
- [ ] Week 8 — Review + mock exams + **exam booked**

**Readiness bar:** consistently scoring **~80%+** on practice questions across all five domains, and able to explain every term in the Domain 1 and Domain 2 glossaries unprompted.

---

## Core resources

| Resource | Link |
|---|---|
| Official exam guide (AIF-C01) | https://docs.aws.amazon.com/aws-certification/latest/ai-practitioner-01/ai-practitioner-01.html |
| Certification page | https://aws.amazon.com/certification/certified-ai-practitioner/ |
| AWS SkillBuilder learning plan | https://skillbuilder.aws/learning-plan/G8ENMJ5QBE/aws-artificial-intelligence-practitioner-learning-plan/SU2A1EJM1A |
| KodeKloud notes | https://notes.kodekloud.com/docs/AWS-Certified-AI-Practitioner/Introduction/Introduction/page |
| In-scope AWS services list | https://docs.aws.amazon.com/aws-certification/latest/ai-practitioner-01/aif-01-in-scope-services.html |

## Supplementary courses (optional)

These come from [DeepLearning.AI](https://www.deeplearning.ai/) and [Anthropic Academy](https://anthropic.skilljar.com/). They are **not required to pass** — the AIF-C01 tests AWS-specific service knowledge that these courses don't cover. What they *do* offer is deeper conceptual grounding and real hands-on for the GenAI material in Domains 2 and 3 (transformers, FM lifecycle, prompting, RAG, fine-tuning, evaluation, agents). Treat them as depth, not coverage.

> Most DeepLearning.AI short courses are paid/subscription; the flagship below runs on Coursera (audit-free option available). Most Anthropic Academy courses are free with a certificate.

### Top picks

| Course | Provider | Maps to | Pairs with |
|---|---|---|---|
| **Generative AI with Large Language Models** (built with AWS; labs run in AWS) | DeepLearning.AI + AWS | Domains 2 + 3 — FM lifecycle, prompting, fine-tuning, evaluation, deployment | Weeks 3–6 |
| **Claude with Amazon Bedrock** (most AWS-relevant Anthropic course) | Anthropic Academy | Domain 3 — tool use, RAG, agents, Bedrock production patterns | Weeks 5–6 |

### Worth a look, by topic

| Course | Provider | Maps to | Pairs with |
|---|---|---|---|
| Generative AI for Everyone | DeepLearning.AI | Domain 2 — capabilities, limitations, business value | Weeks 3–4 |
| AI Capabilities and Limitations | Anthropic Academy | Domain 2 — strengths/weaknesses of LLMs | Weeks 3–4 |
| Introduction to Model Context Protocol (MCP) | Anthropic Academy | Domain 2 — MCP & agentic concepts (now named in the exam guide) | Weeks 3–4 |
| Finetuning Large Language Models | DeepLearning.AI | Domain 3 — fine-tuning & customization | Week 6 |
| Building Applications with Vector Databases / RAG courses | DeepLearning.AI | Domain 3 — RAG & vector stores | Week 5 |
| Red Teaming LLM Applications | DeepLearning.AI | Domain 5 — prompt injection, jailbreaking | Week 7 |

**Minimal add-on if you only want depth, not a course backlog:** take *Generative AI with Large Language Models* as the conceptual backbone for Weeks 3–6, and *Claude with Amazon Bedrock* for hands-on reinforcement. Skip the rest unless a specific topic isn't clicking.

> Course names, availability, and pricing on both platforms change often — confirm on the provider's site before enrolling.

---

## Other References 
- [Generative-AI](https://aws.amazon.com/what-is/generative-ai/)
- [Generative-AI-in-Business](https://aws.amazon.com/generative-ai/)
- [Generative-AI-Tools-on-AWS](https://aws.amazon.com/blogs/machine-learning/announcing-new-tools-for-building-with-generative-ai-on-aws/)

---

*Plan structured around the AIF-C01 exam domains and their official weightings. Pace and dates are suggestions — adjust to your schedule.*
