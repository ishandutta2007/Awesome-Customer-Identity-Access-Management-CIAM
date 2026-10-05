# Awesome-Customer-Identity-Access-Management-CIAM

# Awesome-Customer-Identity-Access-Management-CIAM

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Customer Authentication, Multi-Tenancy, SSO & User Management*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Identity & Access Management (CIAM)**. These tools help organizations authenticate and manage customer identities across applications, providing secure login, registration, social sign-on, and multi-tenant organization management.

**Examples** include Microsoft Entra External ID, Auth0, Okta Customer Identity, PingOne CIAM, Stytch, Clerk, Descope, Frontegg, ForgeRock CIAM, and Transmit Security (the category leaders).

**Open-source emphasis**: The open-source CIAM ecosystem is **exceptionally mature and production-proven**. **Keycloak** remains the de-facto OSS standard for enterprise self-hosting with Apache 2.0 licensing and broad protocol coverage . **Zitadel** leads in B2B Organizations and multi-tenancy modeling as first-class concepts . **Ory** provides Kubernetes-native, API-first identity with Zanzibar-style fine-grained authorization via Keto . **Authelia** delivers lightweight SSO/MFA for reverse proxies . **Logto** offers a developer-friendly Auth0 alternative with generous free tier (50,000 MAU) .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global CIAM market is estimated at **~$18B in 2026**, growing toward **~$45B by 2034** at a **~12% CAGR** . The sector is **moderately concentrated** — **Microsoft Entra External ID** offers **50,000 MAU free forever** , **Auth0** charges **overage at $0.07/MAU** , and **Clerk** starts at **$25/month** . **Descope** provides the most sophisticated visual passkey experience . No single vendor holds a winner-take-all position; enterprises typically run multi-vendor stacks.

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Microsoft Entra External ID](https://learn.microsoft.com/en-us/entra/external-id/customers/)** | **Microsoft's CIAM solution for customer-facing apps.** Successor to Azure AD B2C. Supports social logins, MFA, conditional access. | **Core offering free** for first **50,000 MAU** . Premium add-ons billed separately (no free tier for add-ons) . | **50,000 MAU free forever** for core offering. Add-ons have no free tier . | **~$281B revenue (Microsoft FY2025)** |
| **[Auth0](https://auth0.com/)** | **The CIAM category pioneer.** Authentication, authorization, social login, MFA, extensibility via Actions. | **Overage at $0.07/MAU** after plan limits . Entry plans typically **$23–$240/month** depending on MAU tier. | **Free tier**: **1,000 MAU**, unlimited logins, social connections. **No free tier for enterprise features**. | **Part of Okta (~$2.5B revenue)** |
| **[Okta Customer Identity](https://www.okta.com/)** | **Enterprise CIAM within Okta's identity platform.** Authentication, MFA, user management for customer-facing applications. | **Custom enterprise pricing** — quote required. Entry contracts typically **$2/user/month** for CIAM. | **Free tier**: **100 MAU** for developers. **30-day trial** for enterprise features. | **~$2.5B revenue (Okta FY2025)** |
| **[Clerk](https://clerk.com/)** | **Developer-focused CIAM with prebuilt UI components.** Strong React and Next.js support. | **Pro**: **$25/month** . Volume discounts for larger MAU counts. | **Free tier**: **10,000 MAU**, unlimited applications, prebuilt components. | **Private (~$100M+ raised)** |
| **[Stytch](https://stytch.com/)** | **Developer platform for authentication.** Passwordless, MFA, social login, fraud prevention APIs including device fingerprinting. | **Custom pricing** — quote required. Entry contracts typically **$50/month** for small deployments. | **Free tier**: **10,000 MAU**, all authentication methods, device fingerprinting. | **Private (~$145M raised)** |
| **[Descope](https://www.descope.com/)** | **No-code CIAM with drag-and-drop flow builder.** Most sophisticated visual passkey experience . | **Usage-based pricing** . Entry plans typically **$50/month** for small deployments. | **Free tier**: **7,500 MAU**, visual workflow builder, passwordless, MFA. | **Private (~$100M+ raised)** |
| **[Frontegg](https://frontegg.com/)** | **CIAM built for B2B SaaS.** Authentication, multi-tenancy, user management. | **Custom pricing** — quote required. Entry contracts typically **$500/month** for B2B SaaS. | **Free tier**: **1,000 MAU**, multi-tenancy, SSO, admin portal. | **Private (~$100M+ raised)** |
| **[PingOne CIAM](https://www.pingidentity.com/)** | **Enterprise CIAM with DaVinci orchestration engine.** WebAuthn nodes for passkey support . | **Custom enterprise pricing** — quote required. Entry contracts typically **$3/user/month**. | **Free trial**: 30-day trial with full platform access. **No perpetual free tier**. | **Private (~$500M+ revenue est.)** |
| **[ForgeRock CIAM](https://www.forgerock.com/)** | **Enterprise-grade CIAM (now part of Ping Identity).** Identity orchestration, fine-grained authorization. | **Custom enterprise pricing** — quote required. Entry contracts typically **$5/user/month**. | **Free trial**: 30-day trial available. **No perpetual free tier**. | **Part of Ping Identity** |
| **[Transmit Security](https://transmitsecurity.com/)** | **CIAM with identity orchestration and fraud prevention.** Focus on passwordless and account takeover defense. | **Custom enterprise pricing** — quote required. | **Free trial**: Available on request. **No perpetual free tier**. | **Private (~$500M+ raised)** |

## 🔓 Open-Source GitHub Projects

Sorted by star count (descending). Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|---|---|---|
| **[Keycloak](https://github.com/keycloak/keycloak)** — **The de-facto open-source CIAM standard.** Apache 2.0 licensed, broad protocol coverage (OIDC, OAuth 2.0, SAML 2.0), enterprise-scale deployments. **Heavier operations** and steeper admin learning curve than newer entrants, but the safest default when sovereignty and breadth matter most . | [![Stars](https://img.shields.io/github/stars/keycloak/keycloak?style=social&color=white)](https://github.com/keycloak/keycloak/stargazers) | ~28,000 |
| **[Zitadel](https://github.com/zitadel/zitadel)** — **Strongest B2B Organizations and multi-tenancy model in open source.** Apache 2.0 licensed, SCIM provisioning and detailed audit logs included in free self-hosted edition. Built around first-class B2B Organizations and multi-tenancy data model . **Younger ecosystem** than Keycloak . | [![Stars](https://img.shields.io/github/stars/zitadel/zitadel?style=social&color=white)](https://github.com/zitadel/zitadel/stargazers) | ~10,000 |
| **[Ory (Kratos/Hydra/Keto)](https://github.com/ory/kratos)** — **Kubernetes-native, API-first composable identity.** Apache 2.0 licensed, designed for cloud-native deployments. **Keto provides native Zanzibar-style relationship-based authorization** . Composable services mean you assemble and operate the pieces yourself . | [![Stars](https://img.shields.io/github/stars/ory/kratos?style=social&color=white)](https://github.com/ory/kratos/stargazers) | ~11,000 |
| **[Logto](https://github.com/logto-io/logto)** — **Developer-friendly Auth0 alternative.** Modern identity for apps and APIs, OIDC-based authentication, passwordless sign-in, social sign-in, RBAC, SSO, MFA, multi-tenancy via Organizations . **Free tier**: 50,000 MAU and 50K tokens . | [![Stars](https://img.shields.io/github/stars/logto-io/logto?style=social&color=white)](https://github.com/logto-io/logto/stargazers) | ~9,000 |
| **[SuperTokens](https://github.com/supertokens/supertokens-core)** — **Open-source auth with prebuilt and custom UI.** Apache 2.0 licensed core with **no user limits**. User data and password hashes live in your own PostgreSQL/MySQL. **Less of a full IAM platform** — no built-in SAML in open-source core, multi-tenancy and account linking sit behind paid managed tier . | [![Stars](https://img.shields.io/github/stars/supertokens/supertokens-core?style=social&color=white)](https://github.com/supertokens/supertokens-core/stargazers) | ~13,000 |
| **[Authentik](https://github.com/goauthentik/authentik)** — **Modern Keycloak replacement with nicer admin UI.** MIT licensed. Shipped the most coherent admin UI and SAML/OIDC depth in the OSS field . **Best suited to protecting internal tools** and self-hosted services, not customer-facing SaaS login . | [![Stars](https://img.shields.io/github/stars/goauthentik/authentik?style=social&color=white)](https://github.com/goauthentik/authentik/stargazers) | ~14,000 |
| **[Casdoor](https://github.com/casdoor/casdoor)** — **UI-first IdP supporting OIDC, OAuth, SAML, CAS.** Open-source identity and access management with modern UI. | [![Stars](https://img.shields.io/github/stars/casdoor/casdoor?style=social&color=white)](https://github.com/casdoor/casdoor/stargazers) | ~10,000 |
| **[Better Auth](https://github.com/better-auth/better-auth)** — **Framework-agnostic auth for TypeScript.** Comprehensive authentication framework with plugins. **Developer experience score**: 19.0/22 . | [![Stars](https://img.shields.io/github/stars/better-auth/better-auth?style=social&color=white)](https://github.com/better-auth/better-auth/stargazers) | ~15,000 |
| **[Stack Auth](https://github.com/stack-auth/stack)** — **Open-source Clerk/Auth0 alternative.** Developer-friendly, fully open-source authentication for Next.js and React. | [![Stars](https://img.shields.io/github/stars/stack-auth/stack?style=social&color=white)](https://github.com/stack-auth/stack/stargazers) | ~5,000 |
| **[Authelia](https://github.com/authelia/authelia)** — **Authentication and 2FA portal for reverse proxies.** Apache 2.0 licensed, single lightweight container. Adds TOTP, WebAuthn/passkeys, and Duo push MFA in front of apps. **Best suited for internal tools**, not customer-facing SaaS login . | [![Stars](https://img.shields.io/github/stars/authelia/authelia?style=social&color=white)](https://github.com/authelia/authelia/stargazers) | ~23,000 |
| **[WSO2 Identity Server](https://github.com/wso2/product-is)** — **Enterprise-grade open-source IAM.** Manages over one billion identities for 250+ customers. Available as IDaaS, installable software, or private cloud . **Developer experience score**: 13.0/22 . | [![Stars](https://img.shields.io/github/stars/wso2/product-is?style=social&color=white)](https://github.com/wso2/product-is/stargazers) | ~800 |

**Additional open-source options worth exploring:**

| Repo | Description |
|---|---|
| **[Tesseral](https://github.com/tesseral-labs/tesseral)** — Open-source auth infrastructure for B2B SaaS. Multi-tenant, API-first, works with any tech stack. Features: hosted login pages, SAML, SCIM, RBAC, MFA, passkeys, API keys . |
| **[Supabase Auth](https://github.com/supabase/auth)** — Auth (GoTrue) within Supabase platform. **Developer experience score**: 21.0/22 — highest in 2025 rankings . |
| **[Hanzo IAM](https://github.com/hanzoai/iam)** — AI-first IAM with MCP/A2A gateway, OAuth 2.1, OIDC, SAML, CAS, LDAP, SCIM, WebAuthn, TOTP, MFA, Face ID . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CIAM platforms handle sensitive customer identity and authentication data; ensure compliance with GDPR, CCPA, and relevant data protection regulations.
- **Open-source reality**: The open-source ecosystem for CIAM is **exceptionally mature and production-proven**. **Keycloak** is the de-facto OSS standard for enterprise self-hosting with Apache 2.0 licensing . **Zitadel** leads in B2B Organizations modeling . **Ory** provides Kubernetes-native, API-first identity with Zanzibar-style FGA . However, **commercial platforms** (Auth0, Okta, Clerk, Descope) provide **managed infrastructure, enterprise SLAs, and integrated fraud prevention** that open-source alternatives require significant operational investment to match. The open-source path is **genuinely viable** for organizations with strong engineering capacity seeking full data sovereignty.
- **Operational caveat**: The license is free; **the operations are not**. Self-hosted CIAM requires deployment, scaling, patching, and on-call engineering investment . Budget for the operational burden before committing.

---

**Made for security engineers, platform teams, full-stack developers, and identity architects.**
Let's make customer identity and access management more open, transparent, and developer-friendly.
