<p align="center">
  <img src="assets/logo.png" alt="getOne logo" width="320">
</p>

<h3 align="center">Unifying B2B e-commerce, end to end</h3>

<p align="center">
  Our mission: bring every piece of B2B e-commerce — shopping, data mining &amp; enrichment, order placement, logistics management, ERP integration, and SAML-based enterprise auth — together under one platform, <b>getOneThink</b>. 🚀
</p>

<br>

## 🧱 Tech Stack

| Layer | Technology |
|---|---|
| **Backend** | Java 25 · Spring Boot 4.1 · Spring Modulith (Maven multi-module monorepo) |
| **Frontend** | Vue 3 · Nuxt.js 4 · PrimeVue · Tailwind CSS (yarn monorepo) |
| **Database** | PostgreSQL + Liquibase migrations |
| **Search** | OpenSearch |
| **Cache** | Redis |
| **Inter-service calls** | Spring Cloud OpenFeign (synchronous HTTP, no broker) |
| **Auth** | OAuth2 authorization server (JWT) |

## 🎯 Focus areas

| Area | Status |
|---|---|
| Storefront / shopping | ✅ live |
| Order checkout | ✅ live |
| Product discovery & search | ✅ live |
| Data mining & enrichment | 🚧 planned |
| Logistics management | 🚧 planned |
| ERP integrations | 🚧 planned |
| SAML SSO | 🚧 planned (OAuth2/JWT live today) |
| Multi-cloud infra (Azure, GCP, AWS, DigitalOcean) via Terraform | 🚧 planned |
| Deployment management via Ansible | 🚧 planned |

## 📦 Repositories

- **platform-api** — backend services: auth server, user/tenant, product discovery, product availability, shopping cart, order checkout, mail
- **ecom-web** — storefront and landing site (Nuxt.js monorepo)

## 🤝 Based on

Built and maintained by the getOne team.
