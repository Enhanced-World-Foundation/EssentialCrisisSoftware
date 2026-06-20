# Essential Crisis Software Open Source Initiative — Hybrid License Crowd Development

## Business Source License 1.1 + Custom Amendments

---

## Preamble

This software ("ECS") is licensed under a hybrid model designed to:

- Encourage open-source development and community contributions.
- Protect non-commercial users with clear attribution requirements.
- Enable commercial use through explicit licensing agreements.
- Support a modular architecture with plugin-based cryptographic backends.

The model combines the Business Source License 1.1 with custom amendments specific to the ECS operational-security model.

---

## Part 1 — Business Source License 1.1 (foundation)

The full text of the Business Source License 1.1 is published at https://mariadb.com/bsl11/ and is incorporated here by reference. The amendments below apply on top of it.

### 1.1 Definitions

- **"Licensor"** — Karol Kwestarz-Maciejewski and the ECS Core Contributors.
- **"The Software"** — all code, documentation, and components in the Essential Crisis Software repository.
- **"Non-commercial use"** — use for research, educational, personal, or community purposes where no direct or indirect monetary benefit is received.
- **"Commercial use"** — any use that generates revenue, forms part of a business service, or occurs in a for-profit context.
- **"Change of License Date"** — three years from the first public release of the Software.

### 1.2 License grant

**For non-commercial use**, you are granted a non-exclusive, worldwide, royalty-free license to use, copy, modify, and distribute the Software, and to create derivative works, for personal, educational, and community projects, subject to the following conditions.

1. **Attribution (required).** You must include visible attribution containing:
   - The name "Essential Crisis Software (ECS)".
   - A link to the official repository: https://github.com/Enhanced-World-Foundation/EssentialCrisisSoftware
   - The copyright notice: "© 2026–present Enhanced.World / Locally4Me | Essential Crisis Software".

   Attribution must appear in README files, documentation, user-facing materials where applicable, and in source-code headers of at least the main files.

2. **Required visible links.** Your implementation must display or link to:
   - The official ECS repository — https://github.com/Enhanced-World-Foundation/EssentialCrisisSoftware
   - The project organization — https://enhanced.world

   These links must be accessible to end users of your implementation.

3. **Modifications.** If you modify the Software, you must document your changes clearly and maintain attribution to the original authors. Sharing improvements back with the community is recommended but not required.

**For commercial use**, you must obtain explicit written permission and enter into a Commercial License Agreement with the Licensor before any commercial deployment or distribution. Commercial use includes, but is not limited to: integration into paid SaaS platforms; use in consulting services with direct client deployment; resale or white-label redistribution; incorporation into proprietary products; and any service where end users pay for access.

To request a commercial license, contact research@enhanced.world with a description of the intended use, the expected scale and user base, and your proposed terms.

---

## Part 2 — Modular architecture & plugin system

### 2.1 Core modules (fully open)

The following are permanently open-source under the non-commercial terms above:

- The ECS mesh protocol (discovery, routing, P2P).
- Node architecture (basic templates).
- Scenario A and B implementations.
- Documentation and threat models.
- Operational guides (non-restricted).

### 2.2 Pluggable cryptographic backends

ECS implements cryptography as a plugin system (the LETE plugin model) with selectable, API-compatible backends. Switching plugins requires no code changes, and the security and performance characteristics of each are documented. Plugin creators decide whether they make free files of payed on own behalf.

---

## Part 3 — Security-sensitive modules

### 3.1 Scenario C & D — strategic disclosure

Scenario C implements anti-detection mechanisms against AI-powered surveillance. For security reasons, the project publishes the threat model (assumed adversary capabilities), the defense strategy in strategic terms, known limitations, and safe-deployment recommendations. It does **not** publish specific implementation parameters, exact algorithms and configurations, or operational procedures that would instruct adversaries . A white paper is available in the public repository; the full implementation is available to verified researchers under NDA.

---

## Part 4 — Change of License (BSL conversion)

On the Change of License Date (three years from the first public release, unless an earlier date is announced), all modules under these terms automatically convert to one of: the Apache License 2.0 (for core modules), the GPL 3.0 (for community-driven forks), or another open license chosen by the Licensor at that time. The Licensor will announce the conversion at least 30 days in advance.

Classified (Part 3.2) modules may remain closed-source indefinitely, or convert on a separate timeline at the Licensor's discretion.

Even after conversion, the original copyright notice — "© 2024–present Enhanced.World / Locally4Me | Essential Crisis Software" — remains, and derivative works must maintain the attribution chain.

---

## Part 5 — Contribution & verification

### 5.1 Becoming a verified contributor

To access Backend C and other restricted modules, you must:

1. Maintain an active GitHub profile with a meaningful public contribution history and a clean code-review record.
2. Submit at least one accepted pull request to a public ECS repository.
3. Sign the ECS Contributor NDA (provided on request).
4. Pass Core-team review (typically 2–4 weeks).

On approval, team membership grants access to the relevant restricted repositories and Backend C documentation.

### 5.2 Loss of verified status

Verified status is revoked if you publish restricted information, breach the NDA, become inactive for 12 or more months, or demonstrate malicious intent.

---

## Part 6 — Disclaimer & warranty

The Software is provided "as is", without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement.

In no event shall the Licensor be liable for any claim, damages, or other liability, whether in contract, tort, or otherwise, arising from or in connection with the Software or its use.

**No guarantee of security.** This software is built for resilience and security research. It is not guaranteed to protect against nation-state actors with unlimited resources, quantum cryptanalysis, physical attacks on hardware, side-channel attacks, or social engineering. Users are responsible for assessing whether it meets their security requirements.

---

## Part 7 — Commercial licensing

For commercial use, a separate agreement is negotiated with the Licensor, covering the license fee model (per-deployment, subscription, or revenue-share), the scope of included modules, the level of support, sublicensing rights, modification rights, confidentiality of proprietary algorithms, indemnification, term, and termination conditions. A template is provided on inquiry to research@enhanced.world.

---

## Part 8 — Contact & governance

- **License inquiries:** research@enhanced.world, or open a GitHub issue tagged "License Question".
- **License changes:** the Licensor may update this license; major changes are announced at least 30 days in advance. For non-commercial users, changes apply to new downloads; for commercial licensees, changes apply per their agreement.
- **Dispute resolution:** disputes are first addressed through good-faith discussion, then mediation, and if necessary arbitration under the laws of Estonia.

---

## Summary table

| Use case | Non-commercial | Commercial | Backend access | Verification required |
|---|---|---|---|---|
| Personal use | ✅ with attribution | ❌ | A, B | No |
| Research | ✅ with attribution | ❌ | A, B | No |
| Educational | ✅ with attribution | ❌ | A, B | No |
| Company deployment | ❌ | ✅ with agreement | A, B, C | Yes |
| Community contribution | ✅ with attribution | N/A | A, B, C | Maybe |
| Security research | ✅ with attribution | Contact Licensor | A, B, C, D | Case-by-case |
| Fork & redistribute | ✅ non-commercial only | ❌ | A, B | No |

---

## Acceptance

By downloading, installing, or using the Software, you accept all terms and conditions of this license. Commercial use additionally requires acceptance of a separate Commercial License Agreement.

---

**Version 1.0**
**Licensor:** Karol Kwestarz-Maciejewski and the ECS Core Contributors
**Repository:** https://github.com/Enhanced-World-Foundation/EssentialCrisisSoftware
**Website:** https://enhanced.world · https://locally4me.org
