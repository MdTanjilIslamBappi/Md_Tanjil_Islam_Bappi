## Md Tanjil Islam Bappi

**I build AI products and run the infrastructure they live on.**

Ten years designing and operating enterprise virtualization and storage (VMware
vSphere, vSAN, NSX, SAN) — now applying that same operational discipline to shipping
production AI systems end to end: the app, the pipeline, the servers, the monitoring,
and the on-call.

Most teams hire two people for that. I'm one.

📍 Dhaka, Bangladesh (UTC+6) · working with clients across EU/US time zones
📫 **[Reach me on LinkedIn](https://www.linkedin.com/in/tanjil360/)**

---

### What I do for clients

**AI product engineering**
Retrieval-grounded chatbots and assistants that answer from *your* data, not from a
generic model. Multi-provider LLM routing with automatic fallback so one vendor outage
doesn't take your product down. Image and voice understanding. Structured extraction
(turning messy conversations into clean records).

**Platform & DevOps**
Dockerized deployments, CI/CD, Postgres/Redis/object storage, zero-downtime cutovers,
Prometheus/Grafana/Loki observability with real alerting. VPS and cloud migrations with
a written rollback plan.

**Infrastructure & virtualization**
VMware vSphere/vSAN/NSX design, implementation and troubleshooting. Storage and DR
(Zerto). Host and network hardening. The unglamorous work that keeps revenue online.

---

### Currently building: BuraqBee

An AI auto-reply SaaS for Facebook Messenger, serving small retailers in Bangladesh —
designed, built, deployed and operated solo.

It answers customers instantly in Bangla, Banglish or English, grounded in each
business's own product catalog; understands photos and voice notes; extracts orders
from conversation automatically; and hands off to a human on one click.

**Under the hood:** FastAPI · Celery/Redis · Postgres + pgvector · Next.js · Docker
Compose (16 services) · multi-provider LLM chain with per-tenant fallback and usage
metering · Prometheus/Grafana/Loki + alerting · GitHub Actions CI/CD to a hardened VPS

**Live and real:** production Messenger traffic flowing end to end · multi-tenant with
role-based access · load-tested (p99 11 ms at the webhook layer) · 100+ automated tests
· a security audit that found and closed a connection-hijack path, an SSRF gap and
unbounded uploads before launch

*Source is private (it's a commercial product). Happy to walk through the architecture
or the design docs on a call — HLD, LLD, security model and ops runbook are all
written.*

---

### Tech

**Backend** Python · FastAPI · Celery · SQLAlchemy · Alembic · pytest
**Data** PostgreSQL · pgvector · Redis · MinIO/S3
**AI** RAG & embeddings · multi-provider orchestration (Gemini, Groq, OpenRouter) ·
vision & speech-to-text · structured extraction
**Frontend** Next.js · TypeScript · Tailwind
**Ops** Docker · GitHub Actions · Prometheus · Grafana · Loki · Cloudflare Tunnel ·
Tailscale · Linux hardening
**Virtualization** VMware vSphere · vSAN · NSX · Hyper-V · SAN storage · Zerto ·
PowerCLI

---

### Certifications

VCIX-DCV 2022 · VMware Certified Master Specialist — HCI 2023 · VMware Certified
Master Specialist — VMware Cloud on AWS 2022 · VCAP-DCV Design & Deploy · VCP-DCV ·
VCP-NV · Zerto Certified Associate

<details>
<summary>See the verified badges</summary>

<!--START_SECTION:badges-->
[![VMware Certified Master Specialist - HCI 2023](https://images.credly.com/size/90x90/images/f7ba7f4b-0eb6-4329-a473-9201bbe6a9de/image.png)](http://www.credly.com/badges/b5580b22-9bf3-40c9-8e00-a7bd8287743e "VMware Certified Master Specialist - HCI 2023")
[![Zerto Certified Associate](https://images.credly.com/size/90x90/images/b497d307-a9ce-4221-8cc0-39bb23b823e0/image.png)](http://www.credly.com/badges/0e014d65-bbe0-4230-b306-b03077e3ff48 "Zerto Certified Associate")
[![IT Academy: Network Virtualization Concepts](https://images.credly.com/size/90x90/images/930cc3e4-8a2e-41ae-84b8-40fcf471f786/image.png)](http://www.credly.com/badges/0127fb43-98b9-4bb1-94f1-2014240ca414 "IT Academy: Network Virtualization Concepts")
[![VMware Certified Implementation Expert - Data Center Virtualization 2022](https://images.credly.com/size/90x90/images/a8187184-27a6-4fd7-b024-3051bb723a43/VCIX-DCV_2022_600x600.png)](http://www.credly.com/badges/c05132c2-104e-4002-9cc8-71d51bfbc509 "VMware Certified Implementation Expert - Data Center Virtualization 2022")
[![VMware Certified Advanced Professional - Data Center Virtualization Design 2022](https://images.credly.com/size/90x90/images/846f8bc7-f9dd-4df1-be14-46919b5c24fc/image.png)](http://www.credly.com/badges/e96bf8d6-9590-43d2-994a-a37014efcd23 "VMware Certified Advanced Professional - Data Center Virtualization Design 2022")
[![VMware Certified Master Specialist - VMware Cloud on AWS 2022](https://images.credly.com/size/90x90/images/24c8c8bc-b699-4284-983e-bbcf0e4729cc/image.png)](http://www.credly.com/badges/3ea3b2c5-ddf5-4fa9-9bee-d25b0d11d62e "VMware Certified Master Specialist - VMware Cloud on AWS 2022")
[![VMware Skyline Advisor Pro Technologist: Intermediate](https://images.credly.com/size/90x90/images/97ec6ce0-a4ff-45da-9a63-1c74702a7553/image.png)](http://www.credly.com/badges/0cf44025-cd9d-4f91-be0b-0bfda4560d91 "VMware Skyline Advisor Pro Technologist: Intermediate")
[![VMware Certified Advanced Professional - Data Center Virtualization Deploy 2021](https://images.credly.com/size/90x90/images/0b0aa108-35f7-4f5f-b973-daac3f243c07/VMware_Cert_AP_DCV_Dep.png)](http://www.credly.com/badges/ea46cb41-37c3-49ae-8329-f9505ccd4e02 "VMware Certified Advanced Professional - Data Center Virtualization Deploy 2021")
[![VMware Certified Professional - Network Virtualization 2021](https://images.credly.com/size/90x90/images/dad0ad6d-cbb9-4498-99fd-cddb3dc2ee6c/VMware_Cert_P_NV.png)](http://www.credly.com/badges/2e1a6db3-4ad7-4c9a-aadd-f533b3f2e7bb "VMware Certified Professional - Network Virtualization 2021")
[![VMware Certified Professional - Data Center Virtualization 2021](https://images.credly.com/size/90x90/images/d17db04c-7c17-4bb6-ac91-e287dfb3340c/VMware_Cert_P_DCV.png)](http://www.credly.com/badges/05308ea8-8750-4c88-809a-27834190891e "VMware Certified Professional - Data Center Virtualization 2021")
[![Double VCP - Data Center Virtualization & Network Virtualization](https://images.credly.com/size/90x90/images/a1508378-d359-4d23-8636-9bd1708b8795/image.png)](http://www.credly.com/badges/941b7ae0-ee56-4e12-82bc-33ed61b28849 "Double VCP - Data Center Virtualization & Network Virtualization")
<!--END_SECTION:badges-->

</details>

---

### Working together

I take on a small number of engagements at a time — build-outs, migrations, and
"we need this to actually stay up" work. If you have something in mind, tell me the
problem and the deadline and I'll tell you honestly whether I'm the right fit.

**[Message me on LinkedIn](https://www.linkedin.com/in/tanjil360/)**

<sub>Off the clock I over-engineer my coffee brewing and travel whenever I can.</sub>
