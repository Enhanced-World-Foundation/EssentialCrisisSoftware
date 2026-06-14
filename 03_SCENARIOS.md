# Essential Crisis Software --- Community-Developed Open Source Initiative

SCENARIOS.md

##Introduction:
This document is divided in to sections: 

First and main support you can do is - help us on building comphrehensive description of in-scenarios details. 
We make inquires in to adequate CIRCUMSTANCES-SCN_X.md
|
A validation, completeness and expanding the set of related situation circumstances, treats (including technicalities) , properties and demands of environment / situation, possible sub-scenarios.

## Operational Scenarios - Sub-scenarios & Duration:

```Type of Crisis | Duration & Expected Functional Lifetime

A — Communication-Internet Outage
  A.1  Blackout / Serious Crisis     Short–Mid     days - months
  A.2  Dead-Internet                 Long          years / ever

B — Society / Manufacturing Collapse 
  B.1  Solar Flare / Supply Break    Mid-Long      few year (~2-3)
  B.2  Full "Fallout"                Extreme       as long as possible
Notes: hostile/sick population, proxy service needed 

C — All-in War
  C.1  Modern Army Invasion          Mid–Long      few years (~3-5)
  C.2  AI backed Total War "Skynet"  Long          decade+, active high threat
Notes: automated signal scanning, active node hunting 

D — Hybrid War + Internet Operational  
  D.1  CyberWar / Wild Hacking       Short–Mid     ~1-3 year
  D.2  Infiltrated Central / AI      Mid           up to 10 years

```
## Scenarios Descriptions and Community Insights Content - A LIVING DOCUMENT

Community input to -> adequate CIRCUMSTANCES-SCN_X.md file (X - is A-D):

    Topics Covered:
A. Circumstances (Descriptive -> Technical) 
A.1 Problems - holistic and user case sets.
A.2 Threats - full analysis: kind, intensity, rarity, technological level, severity of "punishment", range & area of danger / operations, expected monitoring technology and intensity, including environment and circumstance related;
B. User Needs In Context 
C. Scenario Consequences, Expected Time of Usage, Hints and Recommendations, 
D. Idea for Analog / Data Sets etc.
E. Sub scenarios - Ideas - Data & Analog & Other Notes form Community 
F. Extended Detailed Specifications & Technical recommendations and related notes; Power Plans (inc. undervoltage / long-run, and SOS-Over-voltage).
G. Ideas of External Utilities, and All level of Alternatives (Addons, Plugins, Modules/Submodules, Functionalities, Customization, Deployments).
H. Tests & Important Measurements (processing power and time, etc.) / solutions & technologies, a commentary.


--- [A PLACE HOLDER DISCUSSION START DRAFT] ---

Each scenario has:
- **Communication** - recommended type transmission
- **Context** — what triggered it, what the world looks like
- **Threats** — active dangers to nodes and users
- **Monitoring** — who is watching, what equipment, what intensity
- **Activity patterns** — when threats are highest/lowest
- **Hardware realities** — what devices survive, what fails
- **Open questions** — problems not yet solved, add yours here

Contributors: add entries under relevant sections.
Use `[UNVERIFIED]` tag for assumptions not yet validated.
Use `[NEEDS RESEARCH]` for gaps that need expert input.

## SCENARIO A — "Dead-Internet"

WiFi mesh (up 2 km)
    ↓ (fallback)
LoRa Meshtastic (7–10 km)
    ↓ (inter-town)
HF 40m NVIS (regional)

### A.1 — Crisis / Malfunction (days → months)

**Context:**
- Regional or national ISP failure
- Physical infrastructure damage (floods, earthquakes, storms)
- Government-ordered shutdown (partial or full)
- Submarine cable cuts

**Expected threats to users:**
- [ ] Social disorder in extended outages (looting, panic)
- [ ] Price gouging on communication devices
- [ ] Misinformation spreading without correction layer
- [ ] [ADD MORE]

**Monitoring intensity:** LOW
- No active adversary scanning for mesh nodes
- Standard RF regulations still apply
- ISPs may monitor recovery traffic [UNVERIFIED]

**Activity patterns:**
- Peak need: first 72 hours
- Secondary peak: week 2-3 when people realize it's extended
- [ADD MORE]

**Hardware realities:**
- Grid power: mostly functional
- Mobile devices: functional, but cell networks down
- WiFi infrastructure: functional locally
- [ADD MORE]

**Open questions:**
- [ ] What is realistic range for BLE/WiFi mesh in urban environment?
- [ ] How to handle firmware updates without internet?
- [ ] [ADD YOUR QUESTIONS]

---

### A.2 — Dead-Internet Long Term (years)

**Context:**
- Sustained infrastructure collapse
- No expectation of restoration
- Society adapts to offline-default

**Expected threats:**
- [ ] Physical theft of functioning communication devices
- [ ] Emergence of local "communication monopolies" (who controls mesh = power)
- [ ] Hardware degradation without supply chains
- [ ] [ADD MORE]

**Monitoring intensity:** LOW → MEDIUM (as new power structures emerge)

**Activity patterns:**
- Early phase: chaotic, high demand
- Mid phase: community structures form, stable nodes emerge
- Long phase: maintenance becomes critical
- [ADD MORE]

**Hardware realities:**
- Power: solar/battery dependent
- Device repair: manual, limited
- Storage: local-only, physical media becomes valuable
- [ADD MORE]

**Open questions:**
- [ ] How long does consumer hardware realistically last without replacement parts?
- [ ] Battery degradation models for long-term mesh nodes?
- [ ] [ADD YOUR QUESTIONS]

---

## SCENARIO B — "Fallout"
LoRa Meshtastic SF12 (daily, low detection)
    ↓ (urgent)
HF 40m SSB (inter-regional, low power)
    ↓ (despair)
Morse heliograf (day, LOS)

### B.1 — Medium Solar Flare (few years)

**Context:**
- Carrington-class event or moderate EMP effect
- Partial grid failure, some electronics survive
- Slow recovery (years, not months)

**Expected threats:**
- [ ] Surviving electronics become extremely valuable → theft, violence
- [ ] Medical equipment failure → hostile/sick population
- [ ] Food/water distribution breakdown → desperation
- [ ] [ADD MORE]

**Monitoring intensity:** LOW (infrastructure for monitoring also damaged)
- State actors may retain some capacity [UNVERIFIED]
- Local power structures may attempt to control communications
- [ADD MORE]

**Activity patterns:**
- First weeks: survival priority, comms secondary
- Month 2-6: community formation, mesh becomes critical
- Year 1+: stable mesh = power
- [ADD MORE]

**Hardware realities:**
- EMP-hardened devices only (Faraday cage storage critical)
- Solar charging: primary power source
- Pre-EMP devices with shielding: most valuable
- [ADD MORE]

**Open questions:**
- [ ] Which consumer devices survive moderate EMP without shielding?
- [ ] Realistic Faraday cage construction for node storage?
- [ ] [ADD YOUR QUESTIONS]

---

### B.2 — Full Fallout / Extreme (as long as possible)

**Context:**
- Nuclear exchange or equivalent civilizational disruption
- Radiation zones, contamination
- Population: sick, hostile, fragmented
- No expectation of global recovery

**Expected threats:**
- [ ] Physical danger from hostile survivors
- [ ] Radiation damage to electronics
- [ ] Complete supply chain collapse
- [ ] Proxy communication critical (you cannot identify yourself safely)
- [ ] [ADD MORE]

**Monitoring intensity:** FRAGMENTED
- State monitoring effectively zero (states collapsed)
- Local warlord-level monitoring possible [UNVERIFIED]
- [ADD MORE]

**Activity patterns:**
- All activity is high-risk
- Night operation preference [UNVERIFIED]
- Burst transmission model (minimal time on air)
- [ADD MORE]

**Hardware realities:**
- Radiation: shielded storage mandatory
- Power: extreme scarcity
- Repair: improvised only
- [ADD MORE]

**Open questions:**
- [ ] Radiation tolerance of common microcontrollers?
- [ ] Minimum viable mesh node (lowest power, smallest footprint)?
- [ ] Proxy identity architecture — how to verify without revealing?
- [ ] [ADD YOUR QUESTIONS]

---

## SCENARIO C — "Total War"
Optical FSO laser (1550 nm eye-safe, point-to-point)
↓ (daily)
 HF 40m CW Ultra-QRP / "Directional-alt" / "Wake-Up Network Repeater"
↓ (Reserve)
Fallback: analog paper + courier / symbols + hybrid PON solutions.

LoRa SF12 + frequency hopping + encryption
HF CW ultra-low-power 100 mW
Visual code (flags, mirrors, smoke)

64 Miles Human Heart Pulse Detection Range!


### C.1 — Modern Invasion (few years)

**Context:**
- Active military occupation or near-front conditions
- State-level adversary with full signals intelligence capability
- Civilian communication monitored as potential partisan activity

**Expected threats:**
- [ ] Direction-finding (DF) equipment locating transmitters
- [ ] IMSI catchers, fake cell towers
- [ ] Traffic analysis even without content decryption
- [ ] Physical raids on identified nodes
- [ ] Informants / social engineering
- [ ] [ADD MORE]

**Monitoring intensity:** HIGH
- Military-grade spectrum analysis
- 24/7 in contested areas [UNVERIFIED]
- Graph analysis of communication patterns
- [ADD MORE]

**Activity patterns:**
- Curfew hours: highest risk for RF activity
- Daytime: some cover from background RF noise
- Pattern: unpredictable transmission schedule mandatory
- [ADD MORE]

**Hardware realities:**
- Consumer devices: trackable via IMEI, MAC, etc.
- Dedicated hardware: lower profile
- Physical destruction of compromised nodes: mandatory protocol
- [ADD MORE]

**Open questions:**
- [ ] Realistic DF range for low-power mesh nodes?
- [ ] MAC/IMEI spoofing reliability across platforms?
- [ ] Minimum transmission time to complete handshake?
- [ ] [ADD YOUR QUESTIONS]

---

### C.2 — AI / Total War (decade+, active high threat)

**Context:**
- Automated systems actively hunting human activity
- AI-powered signal classification at scale
- Drone/sensor network covering territory
- Adversary: not human operators but automated systems

**Expected threats:**
- [ ] ML classifiers trained on mesh protocol signatures
- [ ] Acoustic/thermal/visual detection of hardware
- [ ] Graph topology analysis identifying node clusters
- [ ] Predictive modeling of human activity patterns
- [ ] Quantum-assisted cryptanalysis [UNVERIFIED timeline]
- [ ] [ADD MORE]

**Monitoring intensity:** EXTREME / CONTINUOUS
- No rest periods
- Automated response (no human decision cycle)
- [ADD MORE]

**Activity patterns:**
- All patterns are adversarial input — randomization mandatory
- Background noise mimicry: primary defense
- Topology must change faster than AI retraining cycle [NEEDS RESEARCH]
- [ADD MORE]

**Hardware realities:**
- RF emissions: minimize or eliminate where possible
- Physical footprint: minimal
- Li-Fi / laser / acoustic alternatives: [NEEDS RESEARCH]
- [ADD MORE]

**Open questions:**
- [ ] What is realistic AI retraining cycle for signal classifiers?
- [ ] Can consumer Li-Fi hardware be adapted for mesh relay?
- [ ] Acoustic mesh: feasible range and bandwidth?
- [ ] Statistical profile of true background RF noise (urban/rural)?
- [ ] [ADD YOUR QUESTIONS]

---

## SCENARIO D — "Online Hostility Crisis"

### D.1 Hybrid War / Mass Hostile Hacking (~5 year)

**Context:**
- Partial threat conditions - geographical or prolonged unavailability of cretin services
- Very high hacking activity also by infiltrating enemy 
- Civil unrest, surveillance state, targeted repressions, limited transport and movement, closed areas 
- Internet Services and Economy is operating but can be limited or used against the user, GPS might be distrupted 

**Expected threats:**
- [ ] Mass hacking - individuals, teams, AI/Autonomous Virus
- [ ] Mobile Hackers / Signal Distributors of different association
- [ ] Mass surveillance (metadata collection) - Pegasus / Video Network / WiFi's

**Monitoring intensity:** MEDIUM (passive mass, active targeted)

**Open questions:**
- [ ] Legal status of mesh networking by jurisdiction? [NEEDS RESEARCH]
- [ ] [ADD YOUR QUESTIONS]

---

### D.2 — Custom / Mixed / Theft and AI: Privacy (~10 years)

**Context:**
- User-defined threat model. Configurable preset combining A/B/C elements
- Online Service - Operational
- Preset Mix - "alternatives and a future" compared to D.1 it's lower punishment, lower dedicated threat units, more criminal and AI dangers, spying and type of threat - privacy, personality, related. More stable online and more tech infrastructure.  

**Expected threats:**
- [ ] Military-AI Grade - over existing infrasturcture (hacked/repurposed on chip level or central level):
Very High Detection, Monitoring. Medium severity treat. Privacy and Spying. Hacked Future Infrastructure.
- [ ] Organized Criminals - Fraud, Hacking, Brutal Crime, Data-Personality-Theft, Scam. Vectors: OSINT / Specialised Mobile Gangs.

**Status:** Work in progress.

**Open questions:**
- [ ] How to design custom model UI for non-technical operators?
- [ ] [ADD YOUR QUESTIONS]

---

## CROSS-SCENARIO PROBLEMS (apply to multiple scenarios)

**To be solved regardless of scenario:**
- [ ] Node discovery without internet (mDNS, BLE, RF scanning)
- [ ] Identity verification without central authority
- [ ] Firmware update mechanism offline
- [ ] Battery life optimization for continuous operation
- [ ] Graceful degradation when nodes drop
- [ ] Encryption key management without PKI
- [ ] [ADD MORE]

---

## HOW TO CONTRIBUTE TO THIS DOCUMENT

1. Add entries under relevant section
2. Tag uncertain claims: `[UNVERIFIED]`
3. Tag research gaps: `[NEEDS RESEARCH]`
4. Add open questions to relevant section
5. Don't delete — mark outdated: `[DEPRECATED: reason]`
6. Cite sources where possible

We use WF_CIRCUMSTANCES.md for detailed description and technicalities. 


This document feeds directly into module specification.
Open questions here = future GitHub Issues in private repo.


---

## Contact

**Karol** — Founder, Locally4Me / Enhanced.World
- Email: research@enhanced.world 
- GitHub: [@TianLongLun](https://github.com/TianLongLun)
https://github.com/Enhanced-World-Foundation

Questions? Reply in GHD, Reddit or Discord thread.

https://enhanced.world
https://locally4me.org
https://github.com/Enhanced-World-Foundation/EssentialCrisisSoftware
   
**Version 1.01** | Last updated: 04 April 2026

                  ___                          (_)
                _/XXX\
 _             /XXXXXX\_                                    __
 X\__    __   /X XXXX XX\                          _       /XX\__      ___
     \__/  \_/__       \ \                       _/X\__   /XX XXX\____/XXX\
   \  ___   \/  \_      \ \               __   _/      \_/  _/  -   __  -  \__/
  ___/   \__/   \ \__     \\__           /  \_//  _ _ \  \     __  /  \____//
 /  __    \  /     \ \_   _//_\___     _/    //           \___/  \/     __/
 __/_______\________\__\_/________\_ _/_____/_____________/_______\____/_______
                                   /|\
                                  /'| \
                                 / '|  \
                                /'' |*  \
                               /  $ | '' \
                              /# #  |     \
                             /      |  $   \
                            /       | 99;.  \
                           
[ASCII https://www.asciiart.eu/collections/best-of-the-ascii-pics-1-0]                          
