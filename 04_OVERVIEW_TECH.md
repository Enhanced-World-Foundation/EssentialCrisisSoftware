# Essential Crisis Software --- Community-Developed Open Source Initiative

# OVERVIEW_TECH.md - A Technical Summary

## Infrastructure of Last Resort

**Essential Crisis Software (ECS)** is an open-source ecosystem designed to help communities communicate, coordinate and retain critical knowledge when conventional infrastructure becomes unreliable or unavailable.

The project focuses on situations such as:

* large-scale blackouts,
* long term internet disruptions,
* Emergency while telecommunications fails (SOS, Request),
* natural disasters,
* supply-chain breakdowns,
* wartime and hybrid crisis environments.

Instead of building another messaging application, ECS aims to provide a modular resilience ecosystem combining software, procedures, knowledge and communication infrastructure - suited for exact situation scenario and individual needs.

## Highlights:
* Resilience and Safety
* Modularity
* Offline-first operation
* Decentralized services
* Human usability - easy approach
* Scenario-driven customization

---

 ┌───────────────────────────────────────┐
 │           ECS CLIENT                  │
 │  User communication & coordination    │
 └─────────────────┬─────────────────────┘
                   │
                   ▼
 ┌───────────────────────────────────────┐
 │ CORE FRAMEWORK - Module Data Flow     │
 │ Routing • Connection I/O • UI Frame   │
 └─────────────────┬─────────────────────┘
                   │
                   │
                   ▼
 ┌────────────────────────────┐
 │ SECURITY & PRIVACY Module  │
 │ Set of General Services    │
 │ Sub-Modules / Plugins      │ 
 │ Generators and Gen. of Gen.│
 └─────────────────┬──────────┘
      ┌────────────┼────────────┼─────────┼──────────┼───  ───  ─┼─ ─ ─ ─
      ▼            ▼            ▼         ▼          ▼ 

 Communication    Maps      Community  Connection  Utilities   
    Module        Module      Module    Module
                                       
      ▼            ▼           

Sub Modules / Plugins Layer - including own data encryption / processing.

      ▼            

Data Packs / Presets & Setups 

---

# Main Software Types

## ECS Client

Portable user application.

Functions:

* Messaging
* SOS alerts
* Group coordination
* Local maps
* Information sharing
* Community boards

Platforms:

* Mobile
* PC
* Embedded devices


## Network Forwarding Node (NF)
Relay infrastructure.

Purpose:
* Extend network range
* Store-and-forward messaging
* Synchronization
* Other Device integration

NFV1 - Standard & NFV2 - Transforms existing hardware into a relay node.
Examples:
* old phones
* routers
* SBC devices
* DIY electronics

## Pocket Point (PON)
Autonomous service node deployed in terrain.

### PONR1 - Community Service Point
Features:
* communication board "advertisements"
* trade and barter coordination
* maps
* reputation

### PONR2 - Data Service Point
Features:
* file distribution / local repositories,
* synchronization
* verification
* compression / processing
* mini-server services

---

## HQ

Infrastructure management software.

Used for:
* deployment,
* administration,
* device conversion, DIY
* emergency network planning.

---

# Layer Architecture - Open

L1 Build Package -> Compilations
│
├─ ECS Client
├─ NF 
├─ PON
└─ HQ

L2 Core Framework
│
├─ Inter Modules Data Flow
├─ Routing / Bypassing 
├─ Orchestration and Plugin Frame
├─ UI / Storage
├─ Device I/O
└─ Process Management and Monitoring

L3 Big / Basic - "important" Modules referenced by other.
│
├─ Groups / Users Network, Handshake and ID 
│
├─ System Background Utilities Orchestration & Managment
│
├─ Data Encryption & Steganography 
│
├─ Privacy and Security
├─ Power Plans
└─ Networks Activity Patterns and Components Usage

L4 Modules - various size, often with on UI.
│
├─ Communication
├─ Maps
├─ Community
├─ Reputation
└─ Data Exchange

L4.5 Sub-Modules - smaller, used inside modules or as their extension, often with on UI.
L5 Plugins - small change, alternative equation / matrix / algorithm or just a custom UI.
│
├─ Encryption or Handshake 
├─ Compression
├─ Transmission / Modulation
└─ Detail or fragment.

---

# Encryption Group Layers

OPEN LAYER
│
├─ Public communication
├─ Public information
└─ Discovery

PRIVATE GROUP LAYERS
│
├─ Membership based
├─ Shared keys
├─ Verification methods
└─ Local trust systems

VERIFIED NETWORK LAYER
│
├─ Trusted nodes
├─ Restricted transfer
├─ Security policies
└─ Validation mechanisms

SOS OVERDRIVE LAYER
│
├─ Emergency broadcasts
├─ Priority routing
└─ Crisis communication


                HUMAN RESILIENCE

                       │

     ┌─────────────────┼─────────────────┐
     ▼                 ▼                 ▼

  Software        Procedures       Knowledge

     ▼                 ▼                 ▼

 Communication   Analog Protocols   Data Packs

     └─────────────────┼─────────────────┘
                       ▼

              Crisis Preparedness

      
  
