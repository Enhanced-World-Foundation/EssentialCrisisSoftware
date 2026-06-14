Essential Crisis Software - Open Source Project   

ARCHITECTURE.md

## **Stage 0: Preparations** 
We need to discuss, update and formulate basics of technical details - scenario conditions, impact and design principles, individually customized functional architecture details - including modular division of code & functional copies - along all alternations, reducing time needed. Work pipeline, technical methodologies and guidelines, for "smooth" flow and progress. 

DO NOT US ONLINE AI ON THESE FILES! THIS FILE OR DATA SHOULD NOT BE MADE PUBLIC OUTSIDE OF THIS REPOSITORY

Table of Contents:
## A1. The Priority - Minimal Viable Product (a Helpful App)

## A2. Architecture Overview
### A2.1 General Principles
### A2.2 General Functionalities 
### A2.3 SYSTEM - Diversity of Optimized Network Software 
### A2.4 Modular Principle - Structure 

## A3. Github Folder Structure & Workflow
### A3.1 Committing Code, Reviews & Lists 

## 4. LIST OF WORK-IN-PROGRESS / FINISHED / REVIEWED

---

## A1. The Priority - Minimal Viable Product (a Helpful App)
This version should be suited for a short-to-medium crisis—such as a large-scale blackout, natural disaster, suplychain distrup ments, blocked internet, disabled phone networks, or unavailable electronic payment systems. A ECS Client MVP will use BLT technology. MVP + Customized Systems Architectures + Power Plans (Scenario Based), Alternative Sub-Modules, Plugins, Extras-Utilities, Presets & Custom Setups—UIs, Data Packs & Guidelines.

### 📦 ECS MVP - Core Framework + UI:
* **Groups System:** Open / Closed group differentiation.
* **Identification:** Custom and standard network ID generation.
* **Routing - Bypass - Sharing:** Data/Message relay and opportunistic data distribution.
* **Communication:** Pre-defined compressed messages, group chat, and local forum structures.
* **SOS Signal:** Emergency "Need Help" broadcasting mode.
* **Advert / Note System Board:** Divided by visibility: Open / Geographically tagged / Group-Only + **EMERGENCY NEED PIN** tiered integration.
* **Map:** Local operational maps with Open / Group layers.

### 🚀 MVP 1.1 (Updated Version - Client)
* **Privacy & Security Protection:** Advanced encryption / steganography, obfuscation.
* **Extra Types of Emitter-Receiver Networks:** Low-level integration for alternative transmission mediums.
* **Service-Barter-Time-Favor-Agreement + Reputation:** Decentralized offline relation - favor system.
* **Maps & Non-Satellite Assisted Navigation:** Local celestial and visual terrain orientation without GPS dependencies.
* **Data Sets:** Helpful in-case single file data sets and downloading script.

Basic Framework - BLT MESH - Basic Logic, Functions and Variables-Templates. 

## A2. Architecture Overview

### A2.1 General Principles
**Human applicable - AI resistant**:
- **Interoperability** by design — works in *any* environment
- **Modularity**— swap components without breaking the system
- **Accessibility** — no technical prerequisites for basic users

**State-of-Art Enginering Challange**:
- Variety, Optimization, Customization, Utility, Safety (VOCUS)

### A2.2 General Functionalities 
The exact realization, and technologies depends on scenario and possibilities of hardware / tests.

0. Connection / Detection / External Device Interactions
A. Communication 
B. Exchange - Relations - Reputation
C. Maps 
D. Community 
E. Storage - Update - Data - Setting Groups / Nodes 
Processing/etc
F. Suspended - Proxy - Alt Versions - Automations
G. Analog, Advice, Extras, Utilities, Warnings 
H. Online Modes & Services + Connection sharing

### A2.3 SYSTEM - Diversity of Optimized Network Software 

#### 1. **ECS Client** (Portable / Installation)
- Main P2P client/node utility - customized to scenario or as personal packs.
- Compilations that could run on: PC, mobile, embedded devices, unconventional electronics, DIY
  
#### 2. **Network Forwarding Node (NFN)**
- Active or sleeping relay node,
- Possibly other system services like for ex. data processing and storadge
- Continuous or intermittent power operation
- Extends network range and redundancy, control over devices (ex. camera)

#### 3. **Pocket Point of Network (PPN | Out-of-ECS Network)**
- Dedicated hardware deployed in terrain, delivering services for the network/group.
- Ex. Functions: autonomous message exchange board, data synchronization, also control over devices or data processing.
- Independent power, unattended operation
- Variants: PPN1 (full spectrum), PPN2 (minimal)

#### 4. Scenario B&C: **HQ** 
- Software to connect directly and change any scrap electronics / DIY / emitter device into a permanent: Network Forwarding Node / Pocket Point.
- Custom compilation assistance for network roles types 1-2-3. 
- Form of: hardware-dedicated device/ USB / mobile. Critical for post-collapse scenarios, inc. re-purposing: chips and devices.

### A2.4 Modular Principle - Structure 

**Distribution:** 📦 An Archive "ECS Scenario X Edition XX.XX: [Preset / Custom Collection YY.YY]"
Including compilations, optimized software, custom presets and settings, UI's and Data Sets / Tools.

┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│ Level 1. Build Package "App" (ex. HQ, Node, Client; Scenario A-D / Version) :                    │
│ Contains: Custom Set of - Framework + Modules + UI + Plugins + Data Pack & Presets;              │
│                                                                                                  │
│ ┌──────────────────────────────────────────────────────────────────────────────────────────────┐ │
│ │ L2. Core Framework & L3. Basic Modules                                                       │ │
│ │ - General Build Code, Data Flow, a structure orchestrator for Modules,                       │ │
│ │ - Customization Protocol, Process Masking and General Security, I/O gate.                    │ │
│ └──────────────────────────────────────────────────────────────────────────────────────────────┘ │
│                                                                                                  │
│ ┌──────────────────────────────────────────────────────────────────────────────────────────────┐ │
│ │ L3. Functional Modules (inc. UI):                                                            │ │
│ │ - Data Flow Inner                                                                            │ │
│ │ - Structure and Specification for Plugins and Sub Modules (Security, Stealth etc.)           │ │
│ │ Ex. General UI / Light Terminal gate for Plugin UI incorporation; Generators of generators   │ │
│ │ frame.                                                                                       │ │
│ │                                                                                              │ │
│ │ ┌──────────────────────────────────────────────────────────────────────────────────────────┐ │ │
│ │ │ L4. Plugins & Sub Modules (with Mini UI):                                                │ │ │
│ │ │ Inside Modules some solutions can be customized by the plugins – short methodology /     │ │ │
│ │ │ code Inject-matrix (these expand / change methodology or details used for example        │ │ │
│ │ │ algorithm or short message matrix).                                                      │ │ │
│ │ │                                                                                          │ │ │
│ │ │ Sub Modules – more advanced technological solution with various plugins own data flow,   │ │ │
│ │ │ UI – functions but less than complete module (extra data processing, new function,       │ │ │
│ │ │ methodology or customization of module).                                                 │ │ │
│ │ │                                                                                          │ │ │
│ │ │ Ex.                                                                                      │ │ │
│ │ │ Change of encryption modules / frequencies.                                              │ │ │
│ │ │                                                                                          │ │ │
│ │ │ Tutorial & Guide and Advice.                                                             │ │ │
│ │ └──────────────────────────────────────────────────────────────────────────────────────────┘ │ │
│ └──────────────────────────────────────────────────────────────────────────────────────────────┘ │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘

###Stand Alone Solutions / Utilities and Functionalities:

┌───────────────────────────────────┐
│ Analog Advice and Sets of Steps   │
├───────────────────────────────────┤
│ An. - Digi. Multi-layer Protocols │
├───────────────────────────────────┤
│ Data / Skill / Map Packs          │ 
├───────────────────────────────────┤
│ Silent Backup / Reputation        │
├───────────────────────────────────┤
│ Extras, optimization & processing │
├───────────────────────────────────┤
│ Online Services                   │
└───────────────────────────────────┘


## A3. Github Folder Structure & Workflow

For: General Data Flow - Principalities and Architecture Design & Priorities in Specific Scenario Workflow Files SPECIFICATIONS_SX.md 
For: Technical Application and Methods of Choice, Safety and Privacy Standards look -> RECOMMENDATIONS&SOLUTIONS.md 
For: Any uncovered issues and current look -> CODING_GENERAL/NOTES.md
For: Co-work rules, reviewing and verification -> CODING_GENERAL/CODE_COMMITTING.md
For: Current in demand tasks and challenges -> CODING_GENERAL/PIPELINE_DD.md
For modules, plugins and alternatives we use folders or/and private repositories.

├──PUBLIC ECB/
│   ├── LICENSE.md (license and usage guidelines)
│   ├──>SCENARIOS.md (Extensive description of circumstances - table with possible situations and needs - related GH Discussions)
│   └ ─ ─ COMMUNITY&GOVERNANCE.md (Community related description, commitment and impact listing guidelines etc.)
│   └ ─ ─ ─ ─ TEST/
│
├── ANALOG_GENERAL (Data Sets, Skills Hints & Tips, Guidelines; Developers can look on folders and decide on implementation by your self.) 
│   └────── SOFTWARE-CALLS.md (a list of calls for developer implementation, copies from similar files from scenario folders)
│
├── CODING_GENERAL (here we work on parts or whole modules that are similar in multiple places of the project)
│   ├────── MVP/ (Priority software build)
│   ├── ARCHITECTURE.md (system summary, division, principles and general architecture)
│   ├── RECOMMENDATIONS&SOLUTIONS.md - community agreed solutions, recommendations for contributing developers.  
│   ├── USAGE.md - every time some part of code is copied and used - should be marked in this file; 
│   └── CODE_COMMITTING.md - how to commit code and what to do along it, rules and good practices, verification process, GH Discussions usage. 
│   └ ─ ─ PIPELINE_DD.md (modules and coding needs for closing bigger blocks of code)
│
│   -- -- -- SCENARIO CUSTOM BUILDS -- -- -- 
├── A_DEAD-INTERNET
│   ├────────── A1_WORKFLOW/
│   ├────────────── ANALOG/ (Data Sets, Skills Hints & Tips, Guidelines;)
│   │     └────── SPECIFICATIONS_SA.md  
│   ├────────── A2_WORKFLOW/
│   ├────────────── ANALOG/
│   │     └────── SPECIFICATIONS_SB.md
│   ├──── RECOMMENDATIONS&SOLUTIONS.md 
│   ├──── ANALOG_DEV_CALLS.md (UI/software implementation calls here!)  
│   └── NOTES.md 
├── B_CIV-COLLAPSE
├── C_WAR
├── D_HYBRID
│
│
├─ ECB_BB/ (GitHub Private Repo)


## A3.1 Committing Code, Reviews & Lists 
Contributing Files - Marks and Comments:
- **Editing** - At the top of the file, before any code every developer committing should enter lines edited, date, nick or id, and if there are more entries than 6 move them to the end of the document.
- **Validation / Review** - among entries before the code validator puts date, nick/id, score.

Listing Files - Workflow of Copies:
- **USADGE_LIST.md** - using copy/paste, or basing own code on developed fragments should be marked in this file, marking source and usage place, nick/ID.
- **EDITS_LISTS.md** - edits should be marked in the edited files, in the comments and in dedicated change list.

DO NOT US ONLINE AI ON THESE FILES! THIS FILE OR DATA SHOULD NOT BE MADE PUBLIC OUTSIDE OF THIS REPOSITORY

### General System Components - Software Overview

**Distribution:** 📦 "ECS Scenario X Edition XX.XX: [Preset / Custom Collection YY.YY]"
**A. Software** + **B. "Analog Protocols"** + **C. Data Packages ("Archives")**
 
├─ A. Software Core | Priority: Highest
│  ├─ L1: Build Package (Scenario-specific app type Node / Client / HQ)
│  ├─ L2: Core Framework (Orchestrator, I/O, process masking)
│  ├─ L3: Modules (Communication, Maps, Storage, Community)
│  └─ L4: Plugins (Swappable encryption, algorithms, presets)
│
├─ B. Analog Protocols & Documentation | Priority: Medium
│  ├─ Code/password generation methods
│  ├─ Analog-digital encryption techniques
│  ├─ Guides & procedures
│  └─ Survival & logistics alternatives
│
└─ C. Data Packages (Archives) | Priority: Medium
   ├─ Offline maps & position databases
   ├─ Tools, drivers, repositories
   ├─ Skill packs & knowledge bases
   └─ Real-world application procedures

#### Software - Extras / Utilities | Priority: Low

- **E1** – Software, useful in the Scenario 
- **E2** – Custom UI / Settings - Guidelines
- **E2** – Network-Addon, Optimization / Processing Portable-Standalone Software
- **E3** – New functions - modules for the main framework but because of some reason not imported into main validated ecosystem

#### Priority Pipeline

0. **MVP** (Useful tool, Frame & Documentation)
1. **Scenario-Specific Architectures MVP** (Foundation)
2. **Complete Release & Power Plans** (Scenario-based optimization)
3. **Alternative Sub-modules & Plugins** (Flexibility)
4. **UI, Data Packs & Guidelines** (Accessibility)
5. **Custom Presets & Advanced Configurations** (Specialization)

--> CODING_GENERAL/PIPELINE_DD.md

## 4. LIST OF WORK-IN-PROGRESS / FINISHED / REVIEWED
- From the most recent updates - addons, date. 
- When a block or a module is complete, mark appropriate. Labeled Verified will be moved to list in VERIFIED.md. 

[Template to be add soon.]








--------------------------------------------------------------
## Contact

**Karol** — Founder, Locally4Me / Enhanced.World
- Email: research@enhanced.world 
- GitHub: [@TianLongLun](https://github.com/TianLongLun)

Questions? Reply in GHD, Reddit or Discord thread.

   
**Version 1.00** | Last updated: 05 April 2026

---


                              /
                   __       //
                   -\= \=\ //
                 --=_\=---//=--
               -_==/  \/ //\/--
                ==/   /O   O\==--
   _ _ _ _     /_/    \  ]  /--
  /\ ( (- \    /       ] ] ]==-
 (\ _\_\_\-\__/     \  (,_,)--
(\_/                 \     \-
\/      /       (   ( \  ] /)
/      (         \   \_ \./ )
(       \         \      )  \
(       /\_ _ _ _ /---/ /\_  \
 \     / \     / ____/ /   \  \
  (   /   )   / /  /__ )   (  )
  (  )   / __/ '---`       / /
  \  /   \ \             _/ /
  ] ]     )_\_         /__\/
  /_\     ]___\
 (___)

ASCII From: STEVEN_SULLIVAN_OFFICE_WANG_COM ("Steven M Sullivan")


