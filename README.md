# Awesome-Public-Key-Infrastructure-Identity-Federation

## Top Public Key Infrastructure & Identity Federation Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Certificate Management, Machine Identity & Self-Hosted PKI*  

**Last updated: October 2026**



This repository tracks notable **commercial PKI and identity federation platforms** and **open-source projects** that manage certificates, cryptographic keys, and machine identities — enabling secure authentication between workloads, devices, and services without static credentials.



**Examples** include AWS Roles Anywhere, HashiCorp Vault, SPIFFE/SPIRE, Teleport, Smallstep, Venafi, Keyfactor, CyberArk Conjur, Okta Workforce Identity, and Akeyless (the category leaders).



**Open-source emphasis**: PKI and identity federation is one of the strongest open-source security domains. **SPIFFE/SPIRE** leads as the standard for workload identity, **Smallstep** provides modern certificate management, **step-ca** delivers a full ACME CA, **Teleport** brings certificate-based infrastructure access, **OpenBao** offers a Vault fork, and **Cert-Manager** automates Kubernetes certificates. **CFSSL**, **EJBCA**, **Boulder**, and **Dogtag** provide CA foundations. **Keycloak** and **Authentik** handle identity federation. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Venafi](https://venafi.com/)**  

  **The enterprise standard for machine identity management** — certificate lifecycle automation at scale . **Best for large enterprises** .



- **[Keyfactor](https://www.keyfactor.com/)**  

  **Machine and IoT identity platform** — PKI, certificate management, and code signing . **Best for enterprise and IoT** .



- **[HashiCorp Vault (HCP)](https://www.hashicorp.com/products/vault)**  

  **Managed Vault with PKI secrets engine** — certificate authority and secret management . **Best for Vault users** .



- **[AWS Roles Anywhere](https://aws.amazon.com/rolesanywhere/)**  

  **AWS's IAM Roles Anywhere** — use X.509 certificates to access AWS . **Best for hybrid AWS access** .



- **[Okta Workforce Identity](https://www.okta.com/)**  

  **Identity federation and SSO** — SAML, OIDC, and directory integration . **Best for workforce identity** .



- **[CyberArk Conjur Enterprise](https://www.cyberark.com/)**  

  **Secrets management with certificate authority** — policy-as-code . **Best for enterprise secrets** .



- **[Akeyless](https://www.akeyless.io/)**  

  **SaaS secrets management with PKI** — zero-knowledge architecture . **Best for hybrid and multi-cloud** .



## Open-Source GitHub Projects



### Workload Identity & SPIFFE



- **[SPIFFE/SPIRE](https://github.com/spiffe/spire)**  

  **The standard for cryptographic workload identity**, Apache-2.0 licensed with **1,700+ GitHub stars** . **SPIFFE ID framework with SPIRE server and agent** . **Automatic certificate rotation and attestation** . **The de facto open-source workload identity solution** — used by Uber, Netflix, and Bloomberg . **Best for zero-trust workload identity** .



- **[Teleport](https://github.com/gravitational/teleport)**  

  **Identity-based access for infrastructure**, Apache-2.0 licensed with **16,000+ GitHub stars** . **Certificate-based access to SSH, Kubernetes, databases, and web apps** . **No static credentials** . **Best for infrastructure access** .



- **[OpenBao](https://github.com/openbao/openbao)**  

  **Linux Foundation fork of HashiCorp Vault**, MPL-2.0 licensed . **PKI secrets engine and secret management** . **Community-driven under open governance** . **Best for Vault without BSL** .



### Certificate Authorities & PKI



- **[Smallstep](https://github.com/smallstep/certificates)**  

  **Modern open-source certificate authority**, Apache-2.0 licensed with **6,000+ GitHub stars** . **ACME, OIDC, and X.509 certificate issuance** . **step-ca** is a full ACME CA . **Best for modern PKI** .



- **[step-ca](https://github.com/smallstep/certificates)** — Already listed. **ACME certificate authority** .



- **[Cert-Manager](https://github.com/cert-manager/cert-manager)**  

  **Kubernetes certificate management**, Apache-2.0 licensed with **12,000+ GitHub stars** . **Automates TLS certificate issuance and renewal** . **Supports Let's Encrypt, Vault, Venafi, and private CAs** . **Best for Kubernetes certificates** .



- **[CFSSL](https://github.com/cloudflare/cfssl)**  

  **Cloudflare's PKI and TLS toolkit**, BSD-2-Clause licensed with **8,000+ GitHub stars** . **Certificate signing, verification, and bundling** . **Best for custom PKI** .



- **[EJBCA](https://github.com/Keyfactor/ejbca-ce)**  

  **Enterprise Java Bean Certificate Authority**, LGPL-2.1 licensed . **Full-featured CA with OCSP, SCEP, and ACME** . **Best for enterprise PKI** .



- **[Boulder](https://github.com/letsencrypt/boulder)**  

  **Let's Encrypt's ACME CA implementation**, MPL-2.0 licensed . **The CA behind Let's Encrypt** . **Best for ACME CA implementation** .



- **[Dogtag PKI](https://github.com/dogtagpki/pki)**  

  **Red Hat's certificate system**, GPL-2.0 licensed . **Enterprise PKI with certificate lifecycle** . **Best for enterprise PKI** .



- **[OpenXPKI](https://github.com/openxpki/openxpki)**  

  **Open-source PKI with workflow engine**, Apache-2.0 licensed . **Best for complex PKI workflows** .



- **[XCA](https://github.com/chris2511/xca)**  

  **X Certificate and Key Management**, BSD-3-Clause licensed . **GUI for certificate management** . **Best for desktop PKI** .



### Identity Federation & Authentication



- **[Keycloak](https://github.com/keycloak/keycloak)**  

  **The leading open-source identity provider**, Apache-2.0 licensed with **36,000+ GitHub stars** . **SSO, MFA, OIDC, SAML, and identity brokering** . **Best for identity federation** .



- **[Authentik](https://github.com/goauthentik/authentik)**  

  **Flexible open-source identity provider**, MIT/GPL licensed with **10,000+ GitHub stars** . **OAuth2, SAML, LDAP, and proxy support** . **Best for identity federation** .



- **[Zitadel](https://github.com/zitadel/zitadel)**  

  **Identity infrastructure with multi-tenancy**, Apache-2.0 licensed . **OIDC, OAuth2, SAML2, and SCIM** . **Best for modern identity** .



- **[Dex](https://github.com/dexidp/dex)**  

  **Open-source OIDC identity provider**, Apache-2.0 licensed . **Federated identity for Kubernetes** . **Best for Kubernetes OIDC** .



### Additional Strong Open-Source Options



- **OpenSSL** — Cryptography and certificate toolkit .

- **LibreSSL** — OpenBSD's OpenSSL fork .

- **BoringSSL** — Google's OpenSSL fork .

- **mTLS** — Mutual TLS for service authentication .

- **Istio** — Service mesh with mTLS .

- **Linkerd** — Service mesh with mTLS .

- **Consul** — Service mesh with Connect certificates .

- **Vault PKI** — Vault's PKI secrets engine .

- **AWS Private CA** — Managed private certificate authority .

- **Let's Encrypt** — Free ACME CA .



**Frameworks for building custom PKI and identity federation solutions**: Combine **SPIFFE/SPIRE** for workload identity with automatic certificate rotation . Use **Smallstep** or **step-ca** for modern ACME certificate authority . Deploy **Cert-Manager** for Kubernetes certificate automation . Choose **Teleport** for certificate-based infrastructure access . Integrate **Keycloak** or **Authentik** for identity federation . Use **OpenBao** for Vault-compatible PKI and secrets . Note that true enterprise PKI with managed certificate lifecycle, compliance validation, and vendor-supported SLAs (Venafi, Keyfactor) remains primarily commercial territory; open-source stacks provide strong certificate authority, workload identity, and federation foundations that require integration for complete machine identity management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- PKI and identity federation platforms manage cryptographic keys and certificates that provide access to critical systems. Self-hosted solutions require proper security hardening, key management, and backup procedures.

- **Certificate authority private keys are extremely sensitive** — compromise allows impersonation of any service. HSM-backed key storage is recommended for production CAs .

- **License considerations**: SPIFFE/SPIRE uses Apache-2.0, Smallstep uses Apache-2.0, OpenBao uses MPL-2.0, and Keycloak uses Apache-2.0. Verify licensing against your use case before committing .

- **Certificate rotation is critical** — short-lived certificates reduce compromise impact but require automation. SPIRE, Cert-Manager, and Smallstep provide rotation capabilities .

- The open-source ecosystem provides strong certificate authority, workload identity, and federation foundations, but **managed certificate lifecycle, compliance validation, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for security engineers, platform teams, and organizations seeking PKI and identity federation sovereignty.**  

Let's make public key infrastructure and identity federation more open, transparent, and secure.
