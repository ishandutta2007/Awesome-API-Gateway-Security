# Awesome-API-Gateway-Security

# Awesome-API-Gateway-Security

# Awesome-API-Gateway-Security 🛡️ 🔗

<p align="center">
  <img src="assets/banner.svg" alt="Awesome API Gateway Security Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-API-Gateway-Security"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-API-Gateway-Security?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-API-Gateway-Security/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-API-Gateway-Security?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-API-Gateway-Security/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-API-Gateway-Security?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top API Gateway Security Ecosystem

**Curated List of Commercial API Gateway Platforms & Open-Source Security Tools**  
*Focused on API Discovery, Runtime Protection, Rate Limiting, Bot Defense, API Posture Management & Self-Hosted Gateway Security*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **API gateway security platforms**, **open-source API protection tools**, and **runtime API defense frameworks**. Whether you are looking for enterprise-grade commercial solutions (such as *Cloudflare API Shield*, *Salt Security*, and *Noname Security*), or self-hostable open-source alternatives (like *Kong Gateway*, *Apache APISIX*, and *Tyk*), this list covers category leaders, API discovery, and privacy-respecting API security.

**Key Market Context:**
- **Apache APISIX** is the **most feature-complete open-source gateway** with **100+ plugins**, **native MCP support for AI agents**, and **full Apache-2.0 licensing with no feature gating**.
- **Kong Gateway OSS** is the **plugin breadth leader** with **100+ plugins**, but **OIDC and advanced plugins are Enterprise-only**.
- **Tyk Gateway** is **MPL 2.0 licensed** — **file-level copyleft** that permits proprietary plugins — with **5M+ DockerHub pulls** and **6M+ GitHub stars**.
- **Cloudflare API Shield** requires **Enterprise subscription** for API Discovery.
- **Apigee X** subscription starts at **~$1,500/month** with **$40K–$60K+ professional services** for implementation and **10–50ms added latency per call**.
- **AWS API Gateway HTTP APIs** cost **$1.00 per million requests** vs **REST APIs at $3.50 per million** — a **71% cost reduction**.
- **KrakenD CE** is the **only open-source gateway with zero database dependency** — **stateless, declarative, +70K reqs/s on a single instance, under 50MB memory**.
- **kgateway** is the **most mature cloud-native API gateway** with **dual control plane for Envoy and agentgateway**, **MCP and Agent-to-Agent Gateway**, and **AI Gateway for LLM consumption**.

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The API gateway security market spans **hyperscaler-native gateways** (AWS API Gateway, Apigee X) that provide **managed infrastructure with enterprise features**, **edge security platforms** (Cloudflare API Shield, Salesforce Flex Gateway) that combine **API discovery, runtime protection, and DDoS mitigation**, and **specialized API security platforms** (Salt Security, Noname Security, Cequence) that focus on **API posture management and runtime attack detection**. **Cloudflare API Shield** requires **Enterprise subscription** for API Discovery . **Apigee X** subscription starts at **~$1,500/month** with **$40K–$60K+ professional services** . **AWS API Gateway** HTTP APIs start at **$1.00/million requests** .

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Salesforce MuleSoft Flex Gateway](https://www.mulesoft.com/)** ☁️ | Salesforce | ~$250 Billion | **$4,800–$6,200/vCore/year** (entry, list); **$3,200–$4,400** (negotiated)  | **30-day free trial of Anypoint Platform**  | **Enterprise integration gateway** — **Flex Gateway runs on customer infrastructure (K8s), licensed per gateway node, not per vCore** . **Add-on to Plus or Titanium editions** . **Implementation costs 30–50% above license** . |
| **[Cloudflare API Shield](https://www.cloudflare.com/api-shield/)** 🟠 | Cloudflare Inc. | ~$30 Billion | **Enterprise-only** for API Discovery | **No free tier for API Shield** | **Edge API security** — **Schema validation, sequence mitigation, and API Discovery** . **API Discovery requires active API Shield subscription at account and zone level** . **DDoS + rate limiting at the edge** . |
| **[Apigee X](https://cloud.google.com/apigee)** 🔵 | Google (Alphabet) | ~$2.0 Trillion | **Subscription: ~$1,500/month** (Standard tier)  | **No free tier**; trial available | **Enterprise API management** — **Standard API proxy calls: $20/million; Extensible: $100/million** . **Environment charges per region per hour** . **Professional services: $40K–$60K+** for implementation . **10–50ms added latency per call** . |
| **[AWS API Gateway](https://aws.amazon.com/api-gateway/)** ☁️ | Amazon | ~$2.0 Trillion | **HTTP: $1.00/million requests** (first 300M)  | **Free tier: 1M calls/month for 12 months**  | **AWS-native API gateway** — **HTTP APIs cut cost by 71% vs REST APIs** . **REST APIs: $3.50/million** . **WebSocket: $1.00/million messages + $0.25/million connection-minutes** . |
| **[Kong Konnect](https://konghq.com/)** 🦍 | Kong Inc. | Private | **Enterprise pricing**; **Kong Gateway OSS free**  | **Free: Kong Gateway OSS**  | **Managed API gateway platform** — **Kong Gateway Enterprise and Konnect cloud** . **100+ plugins (advanced = Enterprise)** . **OIDC and advanced plugins are Enterprise-only** . |
| **[Tyk Cloud](https://tyk.io/)** 🎯 | Tyk | Private | **$79/month** (starting)  | **Free: 5M API calls/month**  | **Managed API gateway** — **Open-source gateway with cloud management** . **REST, GraphQL, TCP, and gRPC support** . **MPL 2.0 licensed gateway** . |
| **[Cequence Security](https://www.cequence.ai/)** 🎯 | Cequence Security | Private | **Custom enterprise pricing** | **Demo available** | **API security and bot management** — **Unified API protection platform** . **Runtime attack detection and mitigation** . |
| **[Salt Security](https://salt.security/)** 🧂 | Salt Security | Private | **Custom enterprise pricing** | **Demo available** | **API security posture management** — **Runtime attack detection and API discovery** . **Uses ML to detect anomalous API behavior** . |
| **[Noname Security](https://nonamesecurity.com/)** 🔵 | Akamai (Acquired) | ~$15 Billion (Akamai) | **Custom enterprise pricing** | **Demo available** | **API security platform** — **Discovery, posture management, and runtime protection** . **Acquired by Akamai** for API security depth . |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[Apache APISIX](https://github.com/apache/apisix)** [![Stars](https://img.shields.io/github/stars/apache/apisix?style=social&color=white)](https://github.com/apache/apisix/stargazers)  
  **Cloud-Native API Gateway and AI Gateway**, Apache-2.0 licensed. **15,352 GitHub stars** — **the Apache Software Foundation top-level project** . **Built on NGINX and LuaJIT** . **Traditional mode uses etcd for dynamic route and plugin configuration; standalone mode loads declarative configuration** . **Rich authentication & authorization**: **key-auth, JWT, basic-auth, wolf-rbac, casbin, keycloak, casdoor, OpenID Connect (Auth0, Okta)** . **IP whitelist/blacklist, Referer restriction, limit-req, limit-count, limit-concurrency, CORS, URI blocker, request validator, CSRF** . **Anti-ReDoS built-in** . **Zipkin tracing, Apache SkyWalking APM, external service discovery (Consul, Nacos, Eureka, Zookeeper)** . **Native MCP support for AI agents** . **The most feature-complete open-source gateway** . 🚀

- **[Kong Gateway](https://github.com/Kong/kong)** [![Stars](https://img.shields.io/github/stars/Kong/kong?style=social&color=white)](https://github.com/Kong/kong/stargazers)  
  **The most widely deployed open-source API gateway**, Apache-2.0 licensed. **Built on NGINX/OpenResty with PostgreSQL or DB-less mode** . **100+ plugins** for authentication, rate limiting, and API management . **Full API lifecycle: developer portal, analytics, transformation** . **Limitations: PostgreSQL dependency adds operational overhead, OIDC and advanced plugins are Enterprise-only** . **DB-less mode removes database at the cost of clustering and Admin API features** . **The plugin breadth leader** . 🦍

- **[KrakenD Community Edition](https://github.com/krakend/krakend-ce)** [![Stars](https://img.shields.io/github/stars/krakend/krakend-ce?style=social&color=white)](https://github.com/krakend/krakend-ce/stargazers)  
  **High-performance, stateless, declarative API Gateway written in Go**, Apache-2.0 licensed. **The only open-source gateway with no database dependency** — **stateless design means every node operates independently without coordination or centralized persistence** . **+70K reqs/s on a single instance** . **Under 50MB memory at 1,000+ concurrent connections** . **True linear scalability** . **Native multi-backend aggregation (BFF pattern)** — merge, filter, and reshape multiple backends into one response . **Declarative JSON with hot-reload** . **The best gateway for API aggregation and operational simplicity** . 🚀

- **[kgateway](https://github.com/kgateway-dev/kgateway)** [![Stars](https://img.shields.io/github/stars/kgateway-dev/kgateway?style=social&color=white)](https://github.com/kgateway-dev/kgateway/stargazers)  
  **The most widely deployed gateway in Kubernetes for microservices and AI agents**, Apache-2.0 licensed. **Dual control plane implementing the Kubernetes Gateway API for both Envoy and agentgateway** . **Omni-directional API connectivity spanning traditional HTTP/gRPC workloads to advanced AI agent orchestration** . **CNCF Sandbox project** (formerly Gloo) . **MCP and Agent-to-Agent Gateway** for federating Model Context Protocol tool services . **AI Gateway for LLM consumption** with prompt guards . **The most mature cloud-native API gateway** . ☸️

- **[Traefik](https://github.com/traefik/traefik)** [![Stars](https://img.shields.io/github/stars/traefik/traefik?style=social&color=white)](https://github.com/traefik/traefik/stargazers)  
  **Cloud-native application proxy**, MIT licensed. **Written in Go with provider integrations** for Docker, Kubernetes, and Consul . **Automatic TLS certificate provisioning via ACME** . **Middleware system for authentication, rate limiting, header manipulation, and circuit breaking** . **The simplest cloud-native gateway** . 🚦

- **[Tyk Gateway](https://github.com/TykTechnologies/tyk)** [![Stars](https://img.shields.io/github/stars/TykTechnologies/tyk?style=social&color=white)](https://github.com/TykTechnologies/tyk/stargazers)  
  **Enterprise-level open source API gateway at no cost**, MPL-2.0 licensed. **6M+ GitHub stars, 5M+ DockerHub pulls** . **Supports REST, GraphQL, TCP, and gRPC** . **Built for CI/CD integration and open standards** . **No vendor lock-in** . **MPL 2.0 file-level copyleft permits proprietary plugins** . **The best balance of freedom and enterprise features** . 🎯

- **[Envoy Proxy](https://github.com/envoyproxy/envoy)** [![Stars](https://img.shields.io/github/stars/envoyproxy/envoy?style=social&color=white)](https://github.com/envoyproxy/envoy/stargazers)  
  **Cloud-native high-performance edge/middle/service proxy**, Apache-2.0 licensed. **CNCF graduated project** — **the data plane for Istio and modern service meshes** . **Filter-chain model with built-in HTTP/network filters and Wasm extensions** . **xDS discovery APIs for dynamic configuration** . **The service mesh data plane standard** . 🔷

- **[Couper](https://github.com/coupergateway/couper)** [![Stars](https://img.shields.io/github/stars/coupergateway/couper?style=social&color=white)](https://github.com/coupergateway/couper/stargazers)  
  **Lightweight API gateway for developers**, open-source. **Designed to support developers in building and operating API-driven Web projects** . **Centralized access-control layer**: Basic-Auth, JWT, SAML2, OAuth2, OpenID Connect . **mTLS support (server and backend)** . **Runs on Linux, macOS, Windows, Docker, and Kubernetes** . 🛠️

- **[STOA Platform](https://github.com/stoa-platform/stoa)** [![Stars](https://img.shields.io/github/stars/stoa-platform/stoa?style=social&color=white)](https://github.com/stoa-platform/stoa/stargazers)  
  **AI-native open-source API gateway for the MCP era**, Apache-2.0 licensed. **MCP Gateway for secure AI agent access to enterprise tools** . **Multi-tenant isolation with RBAC (6 personas, 12 scopes)** . **GitOps-native with ArgoCD support** . **35 MCP tools for platform operations** . **European sovereignty and zero vendor lock-in** . **The first open-source gateway with native MCP support** . 🤖

- **[Aastro](https://github.com/voidrunner3074/aastro)** [![Stars](https://img.shields.io/github/stars/voidrunner3074/aastro?style=social&color=white)](https://github.com/voidrunner3074/aastro/stargazers)  
  **Extensible API Gateway written in Go**, open-source. **Parallel fan-out to any number of upstreams** bounded by `parallel_upstreams` . **`merge`, `array`, or `namespaced` response strategies** . **Per-upstream timeouts, retries, and circuit breakers** . **Partial responses with `206 Partial Content` and `X-Partial-Errors` header** when `best_effort` is on . **Everything described in YAML — no code required to add a route** . ⚡

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new API gateway security platforms or open-source API protection software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-API-Gateway-Security&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-API-Gateway-Security&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this API gateway security repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow API engineers, security teams, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Kong Gateway OSS is Apache-2.0, but OIDC and advanced plugins are Enterprise-only** . **Apache APISIX is fully Apache-2.0 with no feature gating** — the **most permissively licensed enterprise-grade gateway** . **Tyk Gateway is MPL-2.0 and free forever** .
- **Apigee X is expensive and complex** — **$40K–$60K+ professional services** for implementation, **10–50ms added latency per call**, and **GCP infrastructure costs billed separately** . **AWS API Gateway HTTP APIs cost 71% less than REST APIs** — **choose HTTP unless you need WAF, caching, or usage plans** .
- **MuleSoft entry tier commits to 4–10 vCores at $4,800–$6,200/vCore/year** — **Flex Gateway is licensed per gateway node, not per vCore**, and **many buyers use it to move gateway burn off the vCore pool** . **Budget 30–50% above license for implementation, training, and connectors** .
- **Open-source gateways are not turnkey** — **Kong requires PostgreSQL or DB-less configuration and plugin management** . **APISIX requires etcd and plugin configuration** . **KrakenD requires declarative JSON and Go binary deployment** . **Always validate gateway security, performance, and failover with a proof-of-concept** before production deployment. 🔗

---

<p align="center">
  <b>Made with ❤️ for API engineers, security teams, and open-source gateway advocates.</b>
</p>
