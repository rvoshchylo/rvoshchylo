<p align="center">
  <img src="./assets/terminal.svg" width="100%" alt="$ whoami — Ruslan Voshchylo, Full-Stack Developer (backend-leaning). Payments, subscription billing, integrations that fail loudly, not silently." />
</p>

<p align="center">
  <a href="mailto:ruslan.voshchylo2@gmail.com"><img src="https://img.shields.io/badge/POST-%2Femail-3ddc97?style=for-the-badge&labelColor=0b1020&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/ruslan-voshchylo-5060522a9/"><img src="https://img.shields.io/badge/GET-%2Flinkedin-8b7bff?style=for-the-badge&labelColor=0b1020&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://t.me/rvoshchylo"><img src="https://img.shields.io/badge/WS-%2Ftelegram-26A5E4?style=for-the-badge&labelColor=0b1020&logo=telegram&logoColor=white" alt="Telegram" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-open_to_offers-3ddc97?style=flat-square&labelColor=0b1020" alt="Open to offers" />
  <img src="https://img.shields.io/badge/region-Ternopil,_UA_·_remote-8b7bff?style=flat-square&labelColor=0b1020" alt="Ternopil, Ukraine · remote" />
  <img src="https://img.shields.io/badge/english-B2-ffcb6b?style=flat-square&labelColor=0b1020" alt="English B2" />
  <img src="https://komarev.com/ghpvc/?username=rvoshchylo&style=flat-square&color=ff7ab2&label=requests" alt="Profile views" />
</p>

---

### `GET /about`

```http
HTTP/1.1 200 OK
Content-Type: application/json
X-Handled-By: ruslan-voshchylo
```
```jsonc
{
  "role": "Full-Stack Developer",          // backend-leaning
  "currently": "SoftKit",                   // 07/2025 → now
  "domain": ["payments", "subscription billing", "integrations"],
  "beliefs": [
    "every webhook will be delivered twice — handle it once",
    "state transitions are explicit or they are bugs",
    "if it fails, it should fail loudly"
  ],
  "also_ships": "LLM-backed features with structured output + graceful degradation",
  "studying": "MSc Cybersecurity"
}
```

### `GET /career` &nbsp;<sub>— modelled the only way I know: as a state machine</sub>

<p align="center">
  <img src="./assets/career.svg" width="100%" alt="Career state machine: INIT (2015, Computer Engineering) → SECURED (2022, BSc Cybersecurity) → SHIPPED (2024, VISO) → CAPTURED (2025, SoftKit, payments) → NEXT (your team?)" />
</p>

---

### `GET /events?limit=2` &nbsp;<sub>— experience, as a webhook log</sub>

<details open>
<summary><code>🟢 role.active</code> &nbsp;<b>SoftKit</b> — Full-Stack Developer &nbsp;·&nbsp; <i>07/2025 → present</i></summary>
<br />

| `event.type` | What happened |
| --- | --- |
| `payment.flow.migrated` | Vehicle sales flow **v2**: Safepay v2 migration, deal payment service on an **explicit state machine**, financing & manual payments, **zero-downtime** v1 compatibility |
| `insurance.module.created` | Car insurance **from scratch**: external API, Stripe checkout & webhooks, certificates, admin invoicing — **PCI DSS** compliant |
| `billing.stripe.integrated` | Subscriptions, promo codes, refunds, **idempotent webhooks**, automated invoices |
| `crm.sync.bidirectional` | **Pipedrive** two-way sync, **Twilio** SMS, email/IP deliverability monitoring (Spamhaus, IPQS) → **Slack** alerts |
| `jobs.background.scheduled` | Ownership monitoring, debt checks, auto-delisting — heavy work moved off the request cycle |
| `admin.tools.shipped` | Price adjustments, document uploads, user verification, invoicing |
| `frontend.modules.shipped` | Insurance purchase flow, multi-step deal stepper, subscription UI, image editor (crop · rotate · drag-and-drop) |
| `platform.hardened` | **Vitest** added to CI/CD · **Node 20 → 24** + Terraform updates — CVEs closed, faster runtime |

</details>

<details>
<summary><code>⚪ role.completed</code> &nbsp;<b>VISO</b> — Full-Stack Developer &nbsp;·&nbsp; <i>2024 → 2025 · Lviv</i></summary>
<br />

| `event.type` | What happened |
| --- | --- |
| `ai.assignments.generated` | **Teach Aid** — assignment generation on the **OpenAI API**: prompt design, structured output parsing, fallbacks for malformed/failed responses |
| `auth.implemented` | NestJS auth (JWT + refresh tokens), Google OAuth, email sign-up with auto-generated profiles |
| `api.crud.shipped` | REST API on **Prisma + PostgreSQL**, RBAC, multi-school support, class management |
| `social.platform.launched` | **Tripami** — travel journaling & community: media upload pipeline, recommendations, following, sharing tips |

</details>

---

### `GET /stack`

| layer | tools |
| :-- | :-- |
| **backend** | <img src="https://skillicons.dev/icons?i=nodejs,nestjs,ts,postgres,prisma&theme=dark" height="36" alt="Node.js, NestJS, TypeScript, PostgreSQL, Prisma" /><br /><sub>TypeORM · REST · OpenAPI/Swagger · Passport.js · JWT</sub> |
| **frontend** | <img src="https://skillicons.dev/icons?i=react,ts,tailwind,vite,styledcomponents&theme=dark" height="36" alt="React, TypeScript, Tailwind, Vite, Styled Components" /><br /><sub>Zustand · React Hook Form · Zod · Ant Design · React Router · Recharts · dnd-kit</sub> |
| **cloud & ops** | <img src="https://skillicons.dev/icons?i=aws,terraform,docker,githubactions&theme=dark" height="36" alt="AWS, Terraform, Docker, GitHub Actions" /><br /><sub>SQS · Lambda · CI/CD · Sentry</sub> |
| **money & messages** | ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![Safepay](https://img.shields.io/badge/Safepay-0b1020?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white) ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white) ![SendGrid](https://img.shields.io/badge/SendGrid-1A82E2?style=flat-square) ![Pipedrive](https://img.shields.io/badge/Pipedrive-017737?style=flat-square) ![Slack](https://img.shields.io/badge/Slack_API-4A154B?style=flat-square&logo=slack&logoColor=white) ![S3](https://img.shields.io/badge/Uppy_/_S3-569A31?style=flat-square&logo=amazons3&logoColor=white) |
| **quality** | <img src="https://skillicons.dev/icons?i=jest,vitest,git&theme=dark" height="36" alt="Jest, Vitest, Git" /><br /><sub>AI-assisted development with Claude Code</sub> |

---

### `GET /education`

```diff
+ 2024 → now    MSc · Cybersecurity                        Ternopil Ivan Puluj National Technical University
+ 2022 → 2024   BSc · Cybersecurity                        Ternopil Ivan Puluj National Technical University
+ 2015 → 2020   Junior Specialist · Computer Engineering   Technical College of TNTU
```

### `GET /metrics`

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=rvoshchylo&bg_color=0b1020&color=8b7bff&line=3ddc97&point=ff7ab2&area=true&area_color=8b7bff&hide_border=true&custom_title=commits%20processed%20per%20day" width="100%" alt="Contribution activity graph" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=rvoshchylo&background=0b1020&ring=8b7bff&fire=ff7ab2&currStreakLabel=3ddc97&sideLabels=8b7bff&currStreakNum=e6e9f5&sideNums=e6e9f5&dates=7d89b0&stroke=26304f&hide_border=true" alt="Contribution streak" />
</p>

---

<p align="center">
  <img src="./assets/footer.svg" width="100%" alt="HTTP/1.1 200 OK — safe to re-read this page, it is idempotent" />
</p>
