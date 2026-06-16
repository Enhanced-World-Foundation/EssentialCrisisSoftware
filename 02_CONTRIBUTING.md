# Contributing to Essential Crisis Software

**Pro-bono · open source · mesh P2P modular system.**

> This is not a thought experiment. It is an engineering initiative.

Thank you for your interest in Essential Crisis Software (ECS). This is software and a data system for crisis scenarios, designed to be usable by people with no technical background — ideally guiding them by the hand. The modular, plugin-based architecture is meant to be shaped by the people who need it. We build infrastructure for environments where traditional networks fail, so the work is held to the standard those scenarios demand.

## Where to start

The first and most valuable contribution is usually **not code**: helping build a complete, validated description of the crisis scenarios. We need the set of circumstances, threats (including technical detail), environmental properties, demands, and possible sub-scenarios validated and expanded. See [`SCENARIOS.md`].

Beyond that, the project's scope is large enough to need almost every kind of specialist — for scenario modeling, skill and analog guidance, in-terrain advice, testing, and for growing the community itself, including inviting other developers. 

For coding contributors -> Please read this document, when we will start coding phase -> /GENERAL_CODING 
For not-coding contributors -> Please read this document, you can contribution ready data / analog solutions or starts discussion -> /GENERAL_ANALOG

## Roles & expertise

| Domain | What's needed |
| :--- | :--- |
| **Core / Mesh** | Rust / Kotlin, P2P protocols, Byzantine fault tolerance, node discovery, broadcasting & signal processing |
| **Cryptography** | Steganography, custom encryption, zero-knowledge proofs, kill-switch logic |
| **Hardware** | RF engineering, power management, node longevity & efficiency |
| **Analog** | Legacy and analog communication protocols; non-digital equivalents and fallbacks |
| **Survival** | Scenario modeling, civil-infrastructure resilience, field testing, utilities, in-terrain skills |
| **Linguistics / Data sciences** | Signal masking, encoding, data-obfuscation theory |
| **Non-coding** | Documentation, guides, hints, data archives, skill packs, translation, art, outreach |

The work splits into three streams:

- **A. Software / Hardware** — read this document and [`ARCHITECTURE.md`](ARCHITECTURE.md) for detail.
- **B. Analog protocols & documentation** — code/password generation methods, analog–digital encryption techniques, guides & procedures, survival & logistics alternatives.
- **C. Data packages (archives)** — offline maps & position databases, tools and repositories, skill and knowledge bases, real-world application procedures.

## Code of conduct

This project builds tools for high-stakes scenarios, and conduct here is held to the standard the work demands.

**Expected**

- Technical honesty — say what you know, flag what you don't.
- Respect for contributors regardless of skill level.
- Constructive critique of code and design, not of people.
- Discretion with anything marked restricted.

**Not tolerated**

- Publishing restricted material — code, parameters, or details marked Core or Vault. This is the most serious breach and results in immediate removal.
- Breaking a non-disclosure agreement — legal consequences follow.
- Harassment, discrimination, or personal attacks.
- Bad-faith disruption or sabotage of the work.
- Misrepresenting the project's capabilities to outsiders.

**Enforcement** — Minor issues (tone, off-topic) get a warning; repeated minor issues, temporary removal from channels; harassment, removal; publishing restricted material or breaching an NDA, a permanent ban and legal action where applicable. The Core team enforces this. Appeals: research@enhanced.world. This applies across GitHub, the project chat, and any project space.

## How to contribute

1. **Claim a problem.** Open an issue for what you want to work on, or comment on an existing one.
2. **Introduce yourself.** Tell us your background, your reasons, and what you care about.
3. **Build.** Submit your first pull request.
4. **Get credited.** Your name and your work are recorded permanently in the contributor registry.

### The three contribution paths

- **Open contribution.** Submit finished code, or a fragment, for review and advice. After three positive reviews it is marked *Validated*, attributed to you, used in further work, and eligible to become part of presets and listings.
- **Discussed contribution.** Post on GitHub Discussions about the topic and what you want to do. After discussion, advice, and possible collaboration, submit for review. Validated after two positive reviews.
- **Pipeline contribution.** Where paths A and B are about quality and your best work, this path is about what the project needs integrated now: ready modules and sections, integrations between finished parts, and priority functions or debugging.

A review from the **Security & Privacy team** is mandatory before any code is used in presets, official repositories, or labeled as verified. ** 

### Commit conventions

- **Editing.** At the top of the file, before any code, record the lines edited, the date, and your nick or ID. If there are more than six entries, move them to the end of the document.
- **Validation / review.** A reviewer adds the date, nick/ID among those entries.
- **`USAGE.md`.** When you copy/paste or base your code on a developed fragment, record the source and the place of use, with your nick/ID.
- **Change list.** Edits are marked in the edited files (in comments) and in the dedicated change list.

While working on a claimed fragment, post short updates on the techniques and alternatives you're using, so others know what's in progress. Provide documentation before listing, and add commentary to your code to make testing easier.

## Repository structure

```
PUBLIC/
├── README.md                     Project overview — read first
├── LICENSE.md                    License and usage terms
├── TECH_OVERVIEW.md              Technical summary
├── SCENARIOS.md                  Crisis circumstances & design principles (open discussion)
├── CONTRIBUTING.md               This document
├── GOVERNANCE.md                 Community, decisions, recognition
└── SUPPORT.md                    Non-code contribution & support


CODING_GENERAL/                   Work shared across multiple parts of the project
├── MVP/                          Priority software build
├── ARCHITECTURE.md               System summary, division, principles
├── RECOMMENDATIONS_SOLUTIONS.md  Community-agreed solutions & recommendations
├── USAGE.md                      Log of copied/reused code fragments
├── CODE_COMMITTING.md            Commit rules, good practice, verification
└── PIPELINE.md                   Current coding needs to close larger blocks

SCENARIO CUSTOM BUILDS
├── A_DEAD-INTERNET/
│   ├── A1_WORKFLOW/ · A2_WORKFLOW/   with ANALOG/ data sets, hints, guidelines
│   ├── SPECIFICATIONS_SA.md
│   ├── RECOMMENDATIONS_SOLUTIONS.md
│   ├── ANALOG_DEV_CALLS.md            UI/software implementation calls
│   └── NOTES.md
├── B_CIV-COLLAPSE/
├── C_WAR/
└── D_HYBRID/
```

## License & recognition

ECS is licensed under a hybrid model — the Business Source License 1.1 with custom amendments. Non-commercial use is free with mandatory attribution; commercial use requires a written agreement. Full terms in [`LICENSE.md`](LICENSE.md).

Your contribution is your reputation. We keep an audit log of all contributors, and every committed change goes through review by at least three independent reviewers, at least one from the Security & Privacy section. Proven contributors are invited into restricted work based on the quality and security of their output. 

## AI policy

> **Do not run online AI over whole modules, files, or repositories.** Using AI as help on limited fragments or blocks is fine. Only locally-run models may be used in development of the core framework and sensitive modules. Unauthorised AI usage or training on this work is a license violation.

---

**Questions?** Open a GitHub Discussion, or email research@enhanced.world.

**Karol Kwestarz-Maciejewski** — System Architect, Locally4Me / Enhanced.World
(https://github.com/Enhanced-World-Foundation/EssentialCrisisSoftware)
