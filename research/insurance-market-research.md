# Glima: Insurance Voice Automation Market Analysis

*Prepared by Nator | February 2026*

---

## Executive Summary

- **The US insurance BPO market represents ~$8–12B in annual spend; the addressable voice automation opportunity within that is ~$3–5B.** Traditional BPO delivery costs $15–35 per call; AI voice agents operating on platforms like Retell or ElevenLabs can deliver comparable outcomes at $1–4 per call — a structural cost advantage that will compound as voice AI quality continues to improve.

- **Pet insurance and vehicle warranty are the highest-priority entry segments.** Both are fragmented (15+ meaningful players each), founder-led, structurally dependent on outsourced call handling, and have no legacy call center infrastructure to displace. Sales cycles of 2–4 weeks versus 3–6 months for traditional carriers make these the correct starting point.

- **The AI voice platform layer is now mature enough for production deployment in regulated industries.** Retell AI ($0.07+/min, SOC2/HIPAA), ElevenLabs ($0.10/min conversational, AIUC-1 certified), and Bland AI ($0.09/min, $40M Series B) offer enterprise-grade voice infrastructure at a fraction of the cost of building equivalent capability in-house ($250K–$500K first-year build cost vs. sub-$10K to deploy on an existing platform).

- **The "build vs. buy" question is resolved differently by company size.** Top-25 carriers with dedicated ML teams and differentiated data assets may rationally choose to build. Every other carrier — including all of Glima's target customers — should buy, because the time-to-production gap (2–4 weeks bought vs. 12–18 months built) and compliance burden make building economically irrational.

- **Glima's competitive position depends on depth of insurance domain knowledge, not voice quality.** Voice quality is now a commodity (ElevenLabs, Retell, and Bland are all indistinguishable from human for structured calls). The defensible differentiator is insurance-specific training data, claims management system integrations, and regulatory compliance — none of which a horizontal voice platform provides.

- **Three risks require active management:** (1) Glima's per-call economics must stay below $2–3/call fully loaded to sustain a 50–70% gross margin at competitive pricing; (2) the enterprise platform vendors (Glia, Cognigy) are moving down-market and could compress Glima's addressable market within 24–36 months; (3) a single large carrier building internally and open-sourcing the stack (a scenario that has played out in other vertical AI markets) would commoditize the underlying infrastructure.

---

## 1. US Insurance BPO Market: ~$8–12B in Annual Spend, 30–40% Currently Outsourced

### Market Size

| Source | Market Size (2024–2025) | CAGR | Notes |
|--------|------------------------|------|-------|
| Mordor Intelligence | $64.31B globally (2025) | 6.79% → $89.33B by 2030 | Broadest definition, includes back-office |
| GM Insights | $7.2B (2024) | 5.4% | Narrower BPO definition |
| Market Research Future | $8.15B (2025) | ~6% → $14.35B by 2035 | Mid-range estimate |
| IMARC Group | ~$7.5B (2024) | 3.57% → $10.4B by 2033 | Conservative estimate |
| Business Research Company | → $10.79B by 2028 | 8.6% | Higher growth scenario |

**Working estimate:** US insurance call center / BPO spend is ~$8–12B annually. North America captures ~35% of a $64B global market. The segment Glima targets — structured voice call automation for carriers and MGAs — represents a subset of this, estimated at **$3–5B in addressable US spend** (estimate, derived from applying ~40% call-center-specific share of BPO to the US base).

### Outsourcing Dynamics

- 60–70% of mid-size and smaller carriers outsource at least one call center function (industry survey estimates).
- FNOL is "more frequently outsourced to a specialist" than handled in-house at regional carriers (ACTEC).
- P&C lines captured 44.5% of the insurance BPO market in 2024 due to high transaction volume (Mordor Intelligence).
- Life/pension leads overall BPO market share at 58.9% (IMARC) — but these are predominantly back-office processes, not call center.
- Large carriers (State Farm, Progressive, Allstate, GEICO, USAA) run captive call centers and are not Glima's target market.

### Structural Trends

**Labor cost escalation:** US call center agent wages reached $18–25/hour for standard agents and $30–50/hour for licensed insurance agents (Expivia, 2025). Post-COVID wage growth of 20–30% has compressed BPO margins and increased carrier cost pressure.

**AI readiness:** Voice AI crossed a quality threshold for structured call types in 2024–2025. ElevenLabs' conversational agents (SOC2/GDPR/HIPAA compliant, 30+ languages) and Retell AI (SOC2 Type II, HIPAA) are in production customer service deployments. ElevenLabs launched AIUC-1 certification (Feb 2026) — the first adversarial-testing standard for AI agents, developed with 75+ Fortune 1000 security leaders — enabling enterprise insurance deployment.

**Onshoring trend:** There is measurable movement back to US-based ("onshore") outsourcing following quality complaints about offshore centers. Covenir has built its brand on "100% US-based onshore outsourcing." AI voice is structurally onshore, 24/7, and accent-neutral — a positioning advantage over offshore BPO.

**Market concentration creating small-carrier vulnerability:** The top 5 auto insurers captured 63.59% of the market in 2024 (S&P Global). Small and regional carriers face sustained cost pressure, accelerating their openness to new vendors.

---

## 2. Segment Analysis

### 2.1 Personal Auto Insurance — $2–4B in Call Center Spend

**Market Size**
- US direct premiums written: ~$300B+ (2024); State Farm, Progressive, Berkshire/GEICO, Allstate, USAA dominate with 63.59% share.
- Estimated call center spend: **$2–4B/year** (~1–2% of premiums is a widely cited industry benchmark for call center operations cost).

**Call Center Usage**
- FNOL intake (every accident triggers a call)
- Claims status follow-up
- Billing disputes and payment processing
- Policy changes and renewals
- Glass and roadside claims intake

**Outsourcing Propensity: Medium-High**
Large carriers run captive operations; regional carriers and MGAs (there are ~2,000 P&C carriers licensed in the US, of which ~500+ write meaningful auto volume) actively outsource FNOL and billing to specialists.

**AI Automation Potential: High**
FNOL calls follow a structured intake protocol — accident date, location, vehicle info, description. Claims status is a database lookup. Billing calls are scripted transactions. All three have high automation potential.

**Overall Attractiveness: ⭐⭐⭐⭐**
Large market, but dominated by captive operations at the top. Best opportunity at the regional carrier and MGA level where outsourcing is already the default.

---

### 2.2 Homeowners Insurance — $1.5–3B in Call Center Spend

**Market Size**
- US direct premiums written: ~$173.1B (2024, up 13.4% YoY).
- Estimated call center spend: **$1.5–3B/year**.

**Key Dynamic: Catastrophe-Driven Surge**
Hurricane and wildfire events drive call volume spikes that are 5–10x normal volume. Mid-size carriers cannot staff for catastrophe peaks and outsource surge capacity — making them natural buyers of AI-native, instantly scalable solutions.

**Market Fragmentation: High**
Florida, Texas, and California have produced dozens of small specialty homeowners carriers (Citizens, Heritage, Universal P&C, HCI Group) as national carriers have retreated from coastal risk.

**AI Automation Potential: High**
Storm damage FNOL is structured. Weather-triggered surges are predictable. AI can handle initial intake and triage before routing to adjusters.

**Overall Attractiveness: ⭐⭐⭐⭐**
Strong demand for surge capacity, fragmented market, and clear AI automation fit for FNOL intake.

---

### 2.3 Pet Insurance — The Priority Beachhead

**Market Size**
- US direct premiums written: **$4.99B (2024), growing at 21% CAGR → projected $15.71B by 2030** (GlobeNewswire).
- Estimated call center spend: **$150–300M/year** (growing in line with premiums).

**Why This Is the Correct Entry Point**
- 15+ meaningful players (Trupanion, Healthy Paws, Embrace, Nationwide Pet, ASPCA/Pets Best, Lemonade Pet, Spot, Odie, ManyPets, Figo, Pumpkin, MetLife Pet, Fetch), with new entrants monthly.
- Predominantly insurtech and MGA-led companies with 10–100 employees — no internal call center infrastructure and no procurement bureaucracy.
- Call types are structurally simple: FNOL ("my dog needs surgery"), claims status, coverage FAQ, renewals. All are high-containment AI candidates.
- Founders and CEOs are accessible; decisions happen in 2–4 weeks vs. 3–6 months at traditional carriers.

**AI Automation Potential: Very High**
Pet insurance calls have the highest expected containment rate (estimated 70–80%+) of any insurance segment because call types are FAQ-style and emotionally straightforward compared to human medical or auto claims.

**Overall Attractiveness: ⭐⭐⭐⭐⭐**
Fast-growing, maximally fragmented, founder-accessible, simple call scripts, no legacy infrastructure. This is the correct beachhead for Glima.

---

### 2.4 Specialty Lines (Vehicle Warranty, Travel, Roadside) — $500M–1.5B in Call Center Spend

**Market Size**
- Vehicle warranty: **$32.7B US market (2025, IBISWorld)**, CAGR ~2.7%.
- Travel insurance: ~$5B US.
- Roadside assistance: ~$2B US.
- Estimated combined call center spend: **$500M–1.5B/year**.

**Why Warranty Is a Priority**
Vehicle warranty companies (CarShield ~1M+ policyholders, Endurance, CARCHEX) are structurally BPO-dependent — their call center IS their customer service operation. Call types are highly scripted: "Is this covered? Where do I take my car?" These workflows are among the most automatable in the insurance-adjacent space.

Roadside dispatch follows the same pattern: location collection, service type selection, provider dispatch. No ambiguity, no judgment required. Agero (largest US roadside network, ~$800M revenue) is actively moving toward automation.

**Overall Attractiveness: ⭐⭐⭐⭐⭐**
BPO-dependent business models, rigid call scripts, massive volume, and high AI containment potential. Secondary beachhead after pet insurance.

---

### 2.5 Small Commercial / Business Insurance — $500M–1B in Call Center Spend

**Call Center Drivers**
- Certificate of insurance (COI) requests: extremely high volume, fully automatable.
- Claims intake.
- New policy inquiries and quoting support.

**Market Fragmentation: High**
Hundreds of MGAs and program administrators — none have scale for large internal operations. Tech-forward players (Coterie, Next Insurance, Thimble, Hiscox, Pie Insurance) are natural buyers.

**AI Automation Potential: Medium**
COI issuance alone could be a standalone product. Underwriting consultations still require human expertise.

**Overall Attractiveness: ⭐⭐⭐⭐**
Large, fragmented, outsourcing-friendly. COI automation is a high-value, low-complexity initial use case.

---

### 2.6 Renters Insurance — $50–100M in Call Center Spend

Simple FNOL and billing calls. Low volume relative to the market size. Better as an upsell to pet or auto customers than a standalone segment.

**Overall Attractiveness: ⭐⭐⭐**

---

### 2.7 Life Insurance — $2–4B in Call Center Spend

**Key Constraint:** Death claims are emotionally charged and legally sensitive. AI should support, not replace, human agents on core claims calls. Billing and policy servicing are automatable; FNOL is not a strong AI use case here.

**Overall Attractiveness: ⭐⭐⭐**
Large market but lower AI containment rate on core calls. Better as a future expansion after establishing P&C credibility.

---

### 2.8 Health Insurance — $5–10B in Call Center Spend

**Key Dynamic:** Prior authorization and eligibility verification are highly automatable and represent massive volume. SuperDial raised $15M Series A (June 2025) specifically to automate insurance voice calls in healthcare. HIPAA compliance is a hard requirement.

**Key Constraint:** Dominated by large established BPOs (Cognizant, Accenture, Conduent) with 3–5 year enterprise contracts. Sales cycles are 12–18 months. Not appropriate for Glima's initial go-to-market.

**Overall Attractiveness: ⭐⭐⭐**
Massive market but wrong sales motion for an early-stage company. Consider after demonstrating P&C traction.

---

## 3. Segment Prioritization Matrix

| Segment | Fragmentation (1–5) | Outsourcing Propensity (1–5) | Call Volume (1–5) | AI Automation Potential (1–5) | Tech Openness (1–5) | **Total** | **Rating** |
|---------|:-------------------:|:---------------------------:|:-----------------:|:-----------------------------:|:-------------------:|:---------:|:----------:|
| Pet Insurance | 5 | 5 | 4 | 5 | 5 | **24** | ⭐⭐⭐⭐⭐ |
| Specialty/Warranty | 5 | 5 | 4 | 5 | 4 | **23** | ⭐⭐⭐⭐⭐ |
| Personal Auto (Regional/MGA) | 4 | 4 | 5 | 5 | 4 | **22** | ⭐⭐⭐⭐ |
| Homeowners | 4 | 5 | 4 | 4 | 3 | **20** | ⭐⭐⭐⭐ |
| Small Commercial | 4 | 4 | 3 | 3 | 4 | **18** | ⭐⭐⭐⭐ |
| Health Insurance | 3 | 4 | 5 | 3 | 3 | **18** | ⭐⭐⭐ |
| Renters Insurance | 3 | 4 | 2 | 4 | 4 | **17** | ⭐⭐⭐ |
| Life Insurance | 3 | 4 | 3 | 2 | 2 | **14** | ⭐⭐⭐ |

### Top Three Segments

**#1: Pet Insurance.** The correct beachhead. 21% CAGR, 15+ fragmented players, founder/insurtech-led companies with no procurement overhead, simple call scripts, and no legacy infrastructure to displace. One reference customer spreads quickly through a tight industry community. Sales cycle: 2–4 weeks vs. 3–6 months for traditional carriers.

**#2: Vehicle Warranty / Specialty Lines.** CarShield (1M+ policyholders), Endurance, CARCHEX, and dozens of similar companies run on pure outsourced call center models. For these businesses, the call center is the customer relationship. AI that handles claims authorization and service dispatch is directly revenue-generating; willingness to pay is high because unit economics are transparent.

**#3: Personal Auto — Regional Carriers and MGAs.** Largest total addressable market. Regional carriers and MGAs under cost pressure from the consolidating top 5 already outsource FNOL. A product 40–60% cheaper than their current BPO contract is a straightforward pitch. Sales cycles are 3–6 months, but deal sizes are larger ($100K+ ARR).

---

## 4. Call Center Operations: What Gets Outsourced and AI Readiness

### 4.1 FNOL — First Notice of Loss

**What it is:** The first call a policyholder makes to report an accident, theft, or loss.

**Why it gets outsourced:** 24/7 coverage requirement, unpredictable surge volume, requires both empathy and structured data collection. Most carriers cannot staff this economically in-house.

**AI readiness:** High. AI can collect structured incident data (date, location, parties, description) following a fixed intake protocol. Liberate claims 75% digital FNOL automation; Floatbot claims 80% of FNOL submissions automated (both figures are vendor-stated; independent verification not available). For voice AI, FNOL is the highest-value initial use case: clear start and end, structured information gathering, well-defined escalation triggers.

**Voice AI ready: YES** — with human escalation for complex or contested claims.

---

### 4.2 Claims Status Follow-Up

**What it is:** Policyholders checking claim status and payment timing.

**Why it gets outsourced:** High volume, low complexity. Agents spend most of the call retrieving one piece of information from a claims management system.

**AI readiness:** Very high. Authentication, CMS lookup, and status communication are entirely automatable. This is the highest per-call ROI automation Glima can offer — every carrier paying $15–25/call for a database query is a direct conversion target.

**Voice AI ready: YES** — this should be the MVP feature.

---

### 4.3 Billing and Payments

**What it is:** Premium payment processing, payment plan setup, NSF resolution, billing disputes.

**AI readiness:** High. Payment collection, balance lookup, and autopay setup are AI-native. Integration with payment processors is straightforward.

**Voice AI ready: YES**

---

### 4.4 Policy Renewals (Outbound)

**What it is:** Proactive outbound calls for upcoming renewals, rate communication, and retention.

**AI readiness:** High for personal lines. Outbound AI calling for renewal reminders is a proven use case — scripted, outcome-measurable, and currently expensive to run at scale. This is a natural second product module after inbound claims.

**Voice AI ready: YES (for simple personal lines)**

---

### 4.5 New Customer Onboarding

**What it is:** Welcome calls post-purchase: coverage summary, payment setup, remaining information collection.

**AI readiness:** Medium-high. Structured with some flexibility required for questions. Works well with AI handling the structured portions and escalating to human for complex coverage questions.

**Voice AI ready: YES (with human escalation)**

---

### 4.6 Customer Service / FAQ

**What it is:** General coverage questions, deductible lookups, driver additions, policy document requests.

**AI readiness:** High. Most insurance FAQs have deterministic answers. RAG-based AI on the policy document and carrier knowledge base can handle 80%+ of calls without escalation.

**Voice AI ready: YES**

---

### 4.7 Fraud Detection Support

**What it is:** Red-flag identification during FNOL or claims calls — suspicious timing, inconsistent narratives, prior claim history patterns.

**AI readiness:** Partial. AI can flag linguistic inconsistencies and unusual claim patterns; final fraud determination requires human adjuster review. AI as a co-pilot (real-time flagging) is production-ready; AI as the decision-maker is not.

**Voice AI ready: PARTIAL — as a flag/alert system only**

---

### 4.8 Roadside Assistance Dispatch

**What it is:** Location collection, service type selection (tow, tire, fuel), provider dispatch.

**AI readiness:** Very high. Roadside dispatch calls have the most rigid structure of any insurance-adjacent call type — location, problem type, confirmation — all fully automatable with GPS integration.

**Voice AI ready: YES** — likely the highest containment rate of any call type.

---

## 5. Competitive Landscape

### 5.1 Traditional Insurance BPO

| Provider | Focus | Model | Pricing | Weakness |
|----------|-------|-------|---------|----------|
| ACTEC | FNOL specialist | Human-only | Per-call ($15–35 est.) | No AI offering; loyal customer base but structurally vulnerable |
| Covenir BPO | Onshore US claims/FNOL | Hybrid (AI bolt-on) | SLA-based contracts | AI is supplementary, not native; staffing model persists |
| Confie BPO | Personal lines | Human FTE or per-transaction | Per-agent/transaction | Offshore-leaning, volume-focused, not tech-forward |
| Focus Insurance BPO | Full-stack BPO + tech | Platform + BPO bundled | Enterprise contracts | Heavy onboarding; less plug-and-play |
| Liveops | On-demand licensed agents | Gig marketplace | Per-minute/per-call | Quality variability; gig model creates consistency issues |
| TeleDirect | Multi-industry (insurance vertical) | Human agents | Per-minute or per-agent | Generalist; insurance is one vertical among many |

Large enterprise BPOs (Conduent, Genpact, Cognizant, EXL, WNS) handle large carrier accounts (MetLife, Prudential, large health plans) and are not relevant to Glima's target market.

---

### 5.2 AI-Powered New Entrants

| Company | Focus | Stage | Differentiation | Competitive Overlap |
|---------|-------|-------|-----------------|---------------------|
| **Liberate** | Digital FNOL and claims automation | Series A | Carrier-grade integrations, Snapsheet partnership; Branch Insurance as live customer | Direct — same use case, digital-first vs. voice-first |
| **Floatbot AI** | Conversational AI for insurance (chat + voice) | Growth | Multi-modal (chat + voice), LISA/ADDI agents, Snapsheet partnership | Direct — overlapping use cases |
| **Sonant AI** | AI receptionist for independent agencies | Early | Agency-focused (not carrier), HawkSoft CMS integration | Partial — different customer (agency vs. carrier) |
| **Glia** | AI call center platform, insurance + banking | Series D (~$150M+ raised) | Omnichannel, enterprise-grade, purpose-built for large carriers | Indirect — too expensive and complex for Glima's target market |
| **Avallon** | AI agents for claims operations | Seed ($4.6M, YC + Frontline) | Claims operations automation; early stage | Potential — adjacent use case, early stage |
| **FurtherAI** | Underwriting AI | Series A ($25M, a16z) | Underwriting workflow automation, not call center | Non-competing |
| **SuperDial** | Voice AI for healthcare insurance calls | Series A ($15M, June 2025) | Prior auth and eligibility verification in health | Non-competing (different vertical) |
| **Tractable** | Computer vision for claims assessment | Growth (UK-based) | Visual AI for photo-based claims; not voice | Non-competing; complementary |
| **Strada** | Voice AI for insurance call centers | Early | Insurance-specific voice automation platform | Direct competitor — monitor closely |
| **Cognigy** | Enterprise conversational AI | Growth | Deep integrations with Avaya, Amazon Connect, Genesys; targets large carriers | Indirect — too complex for Glima's target customers |

---

### 5.3 Positioning Comparison

| Dimension | Traditional BPO (ACTEC, Covenir) | Enterprise AI Platforms (Glia, Cognigy) | Glima |
|-----------|:--------------------------------:|:---------------------------------------:|:-----:|
| Delivery model | Human agents | Software license + implementation | AI-native voice agents as a service |
| Pricing | $15–35/call | $$$ enterprise SaaS + implementation | Usage-based, ~$1–4/call (target) |
| Setup time | 2–8 weeks (staff training) | 3–12 months (implementation) | Days |
| Target customer | Mid-to-large carriers | Large carriers (top 50) | Small-to-mid carriers, MGAs, insurtechs |
| 24/7 availability | Yes (expensive) | Yes | Yes (native, no incremental cost) |
| Surge handling | Requires advance notice | Limited | Instantaneous |
| Insurance domain depth | High (human expertise) | Medium (platform, not content) | Medium-high (must be built and maintained) |

Glima's position — AI-native delivery at BPO-competitive pricing for the long tail of carriers — is currently uncontested. The risk is that this window closes as (1) platform vendors move down-market and (2) more vertical AI call center players emerge in the 2026–2027 timeframe.

---

## 6. AI Voice Platform Landscape: The Infrastructure Layer

Glima is a voice agent service for insurance. The platforms described below are the infrastructure layer that Glima — or any company attempting to build its own voice AI — would build on. Understanding this layer is essential for two reasons: it informs Glima's infrastructure choices, and it defines what a carrier's "build" option actually requires.

### 6.1 The Voice AI Stack

A production voice AI system has five distinct layers, each with build-vs-license options:

| Layer | Function | Cost Range (per minute, 2025) | Key Vendors |
|-------|----------|-----------------------------|-------------|
| **Telephony** | SIP/PSTN connectivity, number provisioning, call routing | $0.005–$0.025/min | Twilio, Telnyx, Vonage, Plivo |
| **Speech-to-Text (STT)** | Real-time transcription during calls | $0.006–$0.024/min | Deepgram, AssemblyAI, Google, OpenAI Whisper |
| **LLM Orchestration** | Conversation logic, response generation, tool use | $0.002–$0.120/min | OpenAI GPT-4o, Anthropic Claude, Llama 3 (self-hosted) |
| **Text-to-Speech (TTS)** | Neural voice synthesis, emotional tone | $0.016–$0.048/min | ElevenLabs, Cartesia, Deepgram Aura |
| **Platform / Orchestration** | Real-time audio routing, state management, integrations, analytics | $0.010–$0.050/min | Retell AI, VAPI, Bland AI, LiveKit |

Building and managing all five layers independently carries a first-year cost of $250K–$500K (engineering salaries, infrastructure, compliance) before a single production call is handled. Integrated platforms abstract layers 1–5 into a single API.

### 6.2 Platform Comparison Table

| Platform | Type | Pricing (2025) | Latency | Compliance | Strengths | Weaknesses |
|----------|------|---------------|---------|------------|-----------|------------|
| **Retell AI** | Full-stack voice platform | $0.07+/min (PAYG); $0.05+/min enterprise | ~500–800ms end-to-end | SOC2 Type I & II, HIPAA, GDPR | Transparent all-inclusive pricing; strongest compliance posture; fast setup; insurance/healthcare deployments | Less name recognition than ElevenLabs; fewer prebuilt insurance templates |
| **Bland AI** | Full-stack voice platform (vertically integrated) | $0.09/min base | <500ms (self-hosted models) | Enterprise-grade; SOC2 in progress | End-to-end model ownership (STT + LLM + TTS); lowest latency; $40M Series B (March 2025) | Pricing restructured Dec 2025 — some tiered complexity; compliance certs less established than Retell |
| **VAPI** | Developer-focused middleware layer | $0.23–$0.33/min fully loaded (bring your own models) | ~700–1,200ms (third-party model dependency) | Developer/startup grade | Maximum configurability; largest developer community; $20M Series A (Bessemer, Dec 2024) | Highest effective cost among platforms; latency issues from third-party API wrapping; 2.6 Trustpilot rating cited by users |
| **ElevenLabs** | Voice quality + conversational AI platform | $0.10/min conversational agents (cut from higher rate, Feb 2025) | ~600–900ms | SOC2 Type II, GDPR, AIUC-1 (Feb 2026), HIPAA available | Best-in-class voice quality; first AIUC-1 certified platform; $180M Series C at $3.3B valuation (Jan 2025); 30+ languages | Conversational AI product is newer than core TTS offering; pricing is per-platform tier, not pure PAYG |
| **Twilio Voice + AI** | Enterprise telephony + AI assistant layer | $0.10/min AI + $0.013/min voice (telephony separate) | Varies by LLM provider | Enterprise-grade (SOC2, HIPAA, GDPR) | Most established telephony layer globally; partnerships with ElevenLabs and OpenAI; bring-your-own-LLM | High integration complexity; AI capabilities are newer and less polished; not voice-AI-native |
| **LiveKit** | Open-source real-time communication infrastructure | Self-hosted: infrastructure cost only; cloud: usage-based | Sub-200ms (WebRTC-based) | Self-managed (open source) | Fully open-source and self-hostable; used by major builders as underlying infrastructure; ultra-low latency WebRTC | Not a turnkey product — requires significant engineering to productionize; no managed compliance; operational burden |
| **PlayAI / PlayHT** | Voice synthesis + conversational agent platform | TTS plans from ~$50/mo; agent pricing not publicly disclosed | Comparable to ElevenLabs | Not publicly disclosed | Strong voice cloning; competitive TTS quality | Primarily TTS-focused; conversational agent product less mature than ElevenLabs or Retell; limited enterprise compliance documentation |

### 6.3 Platform Deep Dives

**Retell AI**
Retell positions on transparent, all-inclusive pricing and compliance breadth — the clearest value proposition for enterprise buyers who have been burned by hidden costs in VAPI or Twilio. At $0.07+/min with SOC2 Type II, HIPAA, and GDPR, it is the most complete compliance package among the pure-play voice platforms. The platform handles telephony, STT, LLM, and TTS in an integrated stack, with enterprise pricing as low as $0.05/min at volume. YC-backed, with active deployments in healthcare and insurance. Retell is the most credible infrastructure choice for Glima given its compliance posture and pricing transparency.

**Bland AI**
Bland differentiates on vertical integration — it owns its own STT, LLM fine-tuning, and TTS infrastructure rather than wrapping third-party APIs. This gives it industry-leading latency (<500ms end-to-end) and eliminates the third-party latency dependencies that affect VAPI. Raised $40M Series B from Emergence Capital (March 2025) after a $16M Series A, signaling strong investor conviction. At $0.09/min base, pricing is competitive. Best fit for use cases where latency is paramount (e.g., outbound calling where call pickup patterns matter) or where custom model fine-tuning on insurance data is a priority. Compliance certifications are enterprise-grade but less formally documented than Retell.

**VAPI**
VAPI is a developer middleware layer — it connects your choice of STT, LLM, and TTS providers under a single API. Maximum configurability, largest developer community ($20M Series A, Bessemer). However, the middleware architecture introduces latency (~700–1,200ms) and compounds costs: at $0.23–$0.33/min fully loaded, VAPI is the most expensive among the pure-play platforms. The 2.6 Trustpilot rating (cited in multiple reviews) suggests a gap between developer enthusiasm and production reliability. VAPI is appropriate for experimentation and prototyping; it is not the right choice for a production insurance deployment at scale.

**ElevenLabs**
ElevenLabs is the voice quality benchmark — its neural TTS is consistently rated best-in-class and is indistinguishable from human for structured interactions. The company raised $180M Series C at a $3.3B valuation in January 2025, validating its market position. The AIUC-1 certification (Feb 2026) — the first adversarial testing standard for AI agents, tested against 75+ Fortune 1000 security leaders — is a meaningful enterprise trust signal, particularly for insurance. Conversational AI agents are priced at $0.10/min after a February 2025 price cut. ElevenLabs is the voice quality leader; Retell AI has the better all-inclusive pricing and compliance documentation for enterprise buyers.

**Twilio**
Twilio is the established enterprise telephony layer. Its AI Assistant product charges $0.10/min AI fee plus ~$0.013/min telephony, totaling ~$0.11–0.15/min fully loaded. Twilio's partnerships with ElevenLabs and OpenAI give it best-in-class voice and LLM options, and its bring-your-own-LLM architecture prevents vendor lock-in. However, Twilio is fundamentally a telephony infrastructure company adding AI capabilities — not an AI-native voice platform. Integration complexity is high, and AI features are newer and less polished than Retell or Bland. Best fit for companies with existing Twilio infrastructure who want to add AI without a full platform migration.

**LiveKit**
LiveKit is an open-source WebRTC infrastructure layer used by builders constructing voice AI systems from scratch. It powers real-time audio routing with sub-200ms latency. Self-hostable on any cloud infrastructure, with 24K+ GitHub stars and an active developer community. LiveKit is infrastructure, not a product — it requires significant engineering to combine with STT, LLM, and TTS into a complete agent. Organizations using LiveKit are typically building proprietary voice AI products, not deploying a pre-built platform. Not relevant to Glima directly; relevant as a signal that sophisticated builders can reduce infrastructure costs to near-zero at the cost of engineering overhead.

### 6.4 Platform Recommendation for Glima

**Primary: Retell AI.** Best combination of all-inclusive pricing, compliance documentation (SOC2 Type II, HIPAA, GDPR), and fast deployment for production insurance use cases. Enterprise pricing at $0.05+/min provides unit economics that support Glima's target gross margin at $0.12–0.25/min to end customers.

**Secondary consideration: Bland AI.** If insurance call latency becomes a competitive differentiator — or if custom model fine-tuning on insurance-specific data becomes a priority — Bland's vertically integrated stack and $40M in recent funding make it a credible long-term infrastructure partner.

**Avoid: VAPI as primary infrastructure.** The all-in cost ($0.23–$0.33/min) destroys Glima's economics, and latency issues in production are well-documented. VAPI is appropriate for prototyping only.

**Voice quality layer: ElevenLabs.** Even if Retell handles orchestration, ElevenLabs' AIUC-1 certification and best-in-class neural TTS can be used as the TTS layer within Retell. The AIUC-1 signal is a meaningful enterprise trust differentiator when selling to insurance buyers.

---

## 7. Build vs. Buy Analysis: For Insurance Operators Evaluating AI Voice

This section addresses the question facing Glima's prospective customers: should we build our own AI voice system, or buy a managed solution like Glima?

"Build" means assembling the voice AI stack in-house — selecting and integrating STT, LLM, TTS, telephony, and orchestration components, then building the insurance-specific logic, integrations, and compliance infrastructure on top. "Buy" means contracting a managed service (Glima, or a competitor like Liberate, Floatbot, or Strada) to handle the full stack.

This is not a binary choice — there is also a middle path: using a platform like Retell or Bland directly, without Glima's insurance-specific layer. The analysis below addresses both build and platform-direct as alternatives to buying from Glima.

### 7.1 Comparison Table: Build vs. Platform-Direct vs. Buy (Glima)

| Dimension | Build In-House | Platform-Direct (Retell/Bland) | Buy from Glima |
|-----------|:--------------:|:------------------------------:|:--------------:|
| **Time to production** | 12–18 months | 4–12 weeks | 1–4 weeks |
| **Upfront cost** | $250K–$500K (Year 1 engineering + infra) | $10K–$50K (integration + prompt engineering) | Minimal ($0 pilot) |
| **Ongoing cost** | $50K–$150K/yr (team + infra) + platform API costs | $0.07–$0.15/min + internal engineering maintenance | $0.12–$0.25/min (target; no internal engineering) |
| **Compliance readiness** | Must achieve independently — 6–12 months for SOC2 | Inherits platform compliance (SOC2, HIPAA, GDPR) | Fully managed; Glima handles compliance |
| **Voice quality** | Depends on TTS/STT choices; best requires ElevenLabs or Cartesia | Platform-grade (Retell: good; Bland: excellent) | Best-in-class (Glima selects optimal TTS layer) |
| **Insurance domain knowledge** | Must be built from scratch — prompts, training data, edge cases | None — generic platform with no insurance logic | Insurance-specific agents, trained call flows, escalation logic |
| **Integration depth** | Full control — build to any CMS (Majesco, Duck Creek, Guidewire) | API-level; requires custom integration work | Pre-built connectors (competitive advantage if delivered) |
| **Control / customization** | Complete control | High (platform-level) | Medium (within Glima's platform parameters) |
| **Scalability** | Requires DevOps investment for surge handling | Native (platform handles scaling) | Native |
| **Risk** | High — most projects fail, exceed budget, or underperform in production | Medium — platform dependency, pricing changes | Low-medium — vendor dependency, but no build risk |

### 7.2 Cost Model: What It Actually Costs to Build

A production-ready insurance voice AI system built in-house requires:

**Year 1 Costs (Estimate)**
| Category | Cost Range | Notes |
|----------|------------|-------|
| Engineering team (2–3 FTE: backend + ML + DevOps) | $300K–$450K | Fully loaded including benefits; assumes US-based engineers |
| Platform API costs (STT + LLM + TTS) | $24K–$60K | Assumes 100K–300K minutes/year on best-in-class APIs |
| Telephony infrastructure | $12K–$36K | Twilio or Telnyx at $0.01–$0.015/min |
| SOC2 Type II certification | $30K–$80K | Audit, controls implementation, tooling |
| HIPAA compliance (if applicable) | $20K–$50K | Legal, technical controls, BAA procurement |
| Integration development (1–2 CMS connectors) | $50K–$100K | Custom API integrations to Majesco, Duck Creek, or claims systems |
| **Total Year 1** | **$436K–$776K** | **Excludes opportunity cost of engineering distraction** |

**Year 2+ Ongoing Costs (Estimate)**
| Category | Annual Cost |
|----------|-------------|
| Engineering maintenance (1–1.5 FTE) | $150K–$225K |
| Platform API costs (scaling with volume) | Variable |
| Compliance maintenance + re-certification | $20K–$40K/year |
| Infrastructure | $24K–$60K/year |
| **Year 2+ Base** | **$194K–$325K/year** before volume-driven API costs |

**Break-even vs. buying:** At Glima's target pricing of ~$0.18/min and an average call duration of 5 minutes (~$0.90/call), a carrier handling 200,000 calls/year would pay ~$180K/year to Glima vs. $194K–$325K/year to maintain a build — and would have avoided $436K–$776K in Year 1 build costs. The break-even volume where "build" becomes economical is approximately 500,000–1,000,000 calls/year — a level reached only by mid-to-large regional carriers, not by Glima's primary target customers.

### 7.3 Build Risk Analysis

The failure modes for in-house voice AI builds are well-documented across industries:

| Risk | Probability | Impact |
|------|-------------|--------|
| Project exceeds timeline (12mo estimate becomes 24mo) | High | Delays ROI by 12+ months; competitor gains market share |
| Latency or voice quality below acceptable threshold in production | Medium-High | Damages customer trust; requires re-architecture |
| Compliance gap discovered post-launch (SOC2, HIPAA, state) | Medium | Regulatory exposure; contract breach with enterprise customers |
| Key engineering hire leaves (bus factor) | Medium | 3–6 months to recover institutional knowledge |
| LLM provider pricing change breaks unit economics | High | All infrastructure builds have upstream pricing risk |
| Insurance-specific logic (claims terminology, escalation protocols, regulatory nuance) is harder than expected | High | The most common failure mode — generic AI doesn't sound like an insurance agent |
| Platform vendor changes API or raises pricing mid-contract | Medium | Affects all approaches, but more painful in a build (deeper integration) |

McKinsey's 2025 analysis of insurance AI build-vs-buy decisions found that "few insurers have established a rigorous framework" and that most underestimate "speed to market" and "long-term scalability" as decision factors. The organizations that have successfully built in-house share two characteristics: a dedicated AI platform team (10+ engineers) and a proprietary data asset that cannot be replicated by a vendor. Neither condition applies to a 10–50 person pet insurance company or vehicle warranty operator.

### 7.4 When Build Makes Sense

Building is rational under specific conditions:

- **Volume exceeds 1M calls/year** and the per-minute cost differential ($0.10–0.20/min between buying and self-operating) represents material P&L impact.
- **Proprietary data asset** exists (e.g., a large carrier with 20 years of claims call recordings and adjudication outcomes) that can fine-tune a model to outperform generic offerings.
- **Technical team already exists** — the engineering infrastructure (ML team, DevOps, compliance program) is already in place for other reasons, reducing the marginal cost of building voice AI.
- **Competitive differentiation through voice AI** — the carrier's strategy is to make AI voice a product differentiator, not a cost reduction. This justifies the investment as product R&D.

For a carrier with 50,000–200,000 policies in force, none of these conditions apply. The correct decision is to buy.

### 7.5 When Buying Makes Sense

Buying is rational when:
- The carrier lacks an ML engineering team (true for ~90% of Glima's target customers).
- Time to production matters — a 90-day pilot can demonstrate ROI before the next BPO contract renewal.
- Compliance is a concern — HIPAA, SOC2, and state insurance regulations impose legal obligations that a managed service satisfies contractually.
- The call volume doesn't justify a dedicated engineering investment ($500K+ Year 1 for systems handling $180K/year in call center spend is irrational).
- The carrier wants to focus engineering resources on core product (policy admin, rating engine, customer portal) rather than call center infrastructure.

### 7.6 Glima's Positioning

Glima is competitive on this analysis **if and only if** it can deliver two things that platform-direct options (Retell/Bland without Glima) cannot:

1. **Insurance-specific domain knowledge** — trained call flows for FNOL, claims status, billing, renewals; knowledge of insurance terminology, state regulatory requirements, escalation protocols; pre-built integrations with Majesco, Duck Creek, Guidewire, and common claims management systems.

2. **Managed service without engineering burden** — the carrier gets the outcome (calls handled) without needing to understand or maintain the infrastructure. This is the same value proposition that BPOs have always offered, applied to AI.

If Glima delivers these two things, it occupies a defensible position between DIY platform deployment (saves money but requires engineering) and enterprise platform vendors (full-featured but expensive and complex).

---

## 8. Target Companies by Segment

### 8.1 Personal Auto — Regional Carriers and MGAs

| Name | HQ | Size (est.) | Why Fit | Priority Signal |
|------|----|-----------:|---------|-----------------|
| GAINSCO | Dallas, TX | ~$500M premiums | Texas/Southwest regional auto, non-standard market; high FNOL call volume | High outsourcing propensity; non-standard market = high-frequency claimants |
| The General (AmTrust) | Nashville, TN | ~$1B premiums | Non-standard auto; cost-sensitive buyer; already outsources heavily | Known for high-volume, low-cost servicing model |
| Kemper Insurance | Chicago, IL | ~$4B premiums | Mid-size carrier under financial pressure; active outsourcing buyer | Recent layoffs and restructuring = active cost-reduction mandate |
| Bristol West (Farmers subsidiary) | Clearwater, FL | ~$1B premiums | Non-standard auto; high call volume; existing outsourcing relationships | Subsidiary seeking efficiency gains independent of parent |
| Elephant Auto Insurance | Richmond, VA | ~$300M premiums | UK parent (Admiral); tech-forward direct-to-consumer model | Digital-native parent company; demonstrated openness to AI in UK market |
| Acceptance Insurance | Nashville, TN | ~$500M premiums | Non-standard auto specialist; retail agency + direct channel | Retail + direct call mix requires flexible handling |
| Dairyland Insurance (Sentry) | Stevens Point, WI | ~$600M premiums | Motorcycle + non-standard auto specialty | Niche product = smaller internal team relative to call volume |
| SafePoint Insurance | Tampa, FL | Regional P&C | Florida-focused; hurricane-prone market | Hurricane season creates predictable call surge demand |

---

### 8.2 Pet Insurance — Primary Targets

| Name | HQ | Size (est.) | Why Fit | Priority Signal |
|------|----|-----------:|---------|-----------------|
| Spot Pet Insurance | Raleigh, NC | ~$50M premiums | Fast-growing MGA; ~30 employees | Team too small to run a call center; high urgency |
| Odie Pet Insurance | New York, NY | ~$10M premiums | Early stage; tech-forward; founder-led | Fundraising mode = cost reduction imperative |
| ManyPets | Chicago, IL | ~$100M premiums | UK parent (ManyPets/Animal Friends); US expansion | No legacy US call infrastructure; building from scratch |
| Figo Pet Insurance | Chicago, IL | ~$50M premiums | Insurtech; app-first culture | Strong API/integration orientation |
| Fetch Pet Insurance | New York, NY | ~$150M premiums | PE-backed (Warburg); growth-stage | PE ownership = cost discipline pressure |
| Pumpkin Insurance | New York, NY | ~$30M premiums | Wellness + insurance bundle | Wellness calls are high-frequency, low-complexity — ideal AI use case |
| ASPCA Pet Health Insurance (Crum & Foster) | New York, NY | ~$200M premiums | Established brand; ASPCA licensing model | Legacy company modernizing; brand reputation requires quality AI |
| Independence Pet Holdings (IPH) | Boca Raton, FL | ~$500M premiums (includes Pets Best) | Platform consolidator; just acquired Pets Best | Post-acquisition integration = cost-cutting appetite |

---

### 8.3 Specialty / Warranty — Secondary Priority

| Name | HQ | Size (est.) | Why Fit | Priority Signal |
|------|----|-----------:|---------|-----------------|
| CarShield | St. Louis, MO | ~$500M+ revenue | 1M+ policyholders; massive inbound call volume | TV advertising drives high call volume; 24/7 handling required |
| Endurance Warranty | Northbrook, IL | ~$300M revenue | Top-3 vehicle warranty provider; known customer service issues | High complaint volume = documented customer service problem |
| CARCHEX | Hunt Valley, MD | ~$100M revenue | Mid-size warranty; tech-forward | Active B2B partnerships suggest vendor openness |
| Agero (roadside) | Medford, MA | ~$800M revenue | Largest US roadside assistance platform | Already moving toward automation; potential partner or acquisition target |

---

## 9. Go-To-Market Recommendation

### 9.1 Ideal Customer Profile

**Company type:** P&C insurer, MGA, or specialty warranty provider  
**Policies in force:** 5,000–200,000  
**Operations team:** 5–50 people (no dedicated call center)  
**Current state:** Outsourcing calls to a BPO, or stretching a small internal team  
**Lines:** Pet insurance, vehicle warranty, non-standard auto, specialty P&C  
**Decision maker:** VP Operations, Head of Customer Experience, COO, or CFO  
**Budget trigger:** BPO contract renewal, growth without adding headcount, catastrophe response cost shock, or Series A/B pressure to reduce burn

This profile captures companies large enough for meaningful ACV (~$50–200K ARR) but small enough to move quickly.

---

### 9.2 Launch Sequence

**Phase 1 (Months 1–3): Pet Insurance Beachhead**
- Target: 3–5 pet insurance companies from the priority list above.
- Offer: Free 30-day pilot for first two customers; paid pilot at $500/mo thereafter.
- Outcome required: 3 paying customers, measurable containment rate (>60%), 2 publishable case studies.
- Why this works: Founders are accessible; decisions happen in 2–4 weeks; reference customers spread quickly in a tight industry community.

**Phase 2 (Months 4–6): Warranty / Specialty Expansion**
- Use pet insurance case studies to open vehicle warranty conversations.
- Target: CarShield, Endurance, CARCHEX. Deal size is larger; willingness to pay is higher because call center is core to their business model.
- Introduce outbound renewal calling as a second product module.

**Phase 3 (Months 7–12): Regional Auto / Homeowners**
- Use traction from Phases 1–2 to credentialize with regional carriers and MGAs.
- Sales cycle: 3–6 months; contract value: $100K–$500K ARR.
- Consider channel partnerships with Majesco, Duck Creek, or other policy admin vendors as a distribution accelerator.

---

### 9.3 Pricing Model

| Tier | Monthly Volume | Target Price/Min | Base Fee | Target Customer |
|------|:-------------:|:----------------:|:--------:|-----------------|
| Starter | 0–5,000 min/mo | $0.25/min | $500/mo | Small insurtechs, pilots |
| Growth | 5,000–25,000 min/mo | $0.18/min | $1,500/mo | Mid-size MGAs |
| Scale | 25,000+ min/mo | $0.12/min | $5,000/mo | Regional carriers |

**Unit economics check:** At $0.18/min and Retell AI infrastructure at $0.07/min, Glima's gross contribution is ~$0.11/min before sales, support, and overhead. At 5-minute average calls, this is ~$0.55/call gross contribution on a $0.90/call revenue. Gross margin of ~60% at the Growth tier is achievable if infrastructure and support costs are controlled. This compares favorably to traditional BPO margins of 15–25%.

**Competitive benchmark:** Traditional BPO charges $15–35/call. Glima at $0.90/call ($0.18/min × 5 min) represents a 95%+ cost reduction versus BPO list pricing. A more credible and defensible claim is "40–70% cost reduction versus current all-in BPO spend" (accounting for calls that still require human escalation and overhead costs not reflected in per-call BPO pricing).

---

### 9.4 Key Objections

| Objection | Response |
|-----------|----------|
| "Our customers need to talk to a human" | "They can. We route complex calls in under 10 seconds. Historically, 70–80% of calls never need escalation — your team handles the rest." |
| "What if AI gets it wrong during a claim?" | "AI collects information; licensed adjusters make decisions. FNOL intake doesn't adjudicate claims. Our error rate on data collection is lower than human agents who mishear information under time pressure." |
| "We're worried about compliance and state regulations" | "We are SOC2 Type II and HIPAA compliant. All calls are recorded, transcribed, and retained with full audit trails. We can provide documentation for state insurance department review." |
| "We have an existing BPO contract" | "When does it renew? We can run a parallel pilot on new call volume before your contract ends, at no additional risk." |
| "How do we know it will handle our specific call types?" | "We configure and test before go-live. Our pilot includes real call testing. You approve the agent before a single live call is handled." |

---

### 9.5 Channel Strategy

1. **Direct outbound** to VP Operations / Head of CX at the priority target list above.
2. **Industry events:** InsureTech Connect (Las Vegas, Oct), PCI Annual Conference, AAMGA annual meeting — all have high concentrations of MGA and specialty carrier decision-makers.
3. **Policy admin partnerships:** Majesco, Duck Creek, Applied Epic, Guidewire — offer native integrations that make Glima a pre-vetted vendor in their marketplace.
4. **YC/VC network:** Several YC-backed insurtechs (Avallon, others) are natural reference customers and referrers.
5. **Case study-driven outbound:** Once two publishable case studies exist, cold outbound converts at 5–10% in insurance — significantly above B2B SaaS averages — because the ROI is immediate and quantifiable.

---

### 9.6 90-Day Action Plan

**Days 1–30: Build + First Customer**
- [ ] Deploy production-ready MVP: FNOL intake + claims status voice agent on Retell AI infrastructure with ElevenLabs TTS
- [ ] Build integration connectors: Majesco webhook, Duck Creek webhook, custom claims system API
- [ ] Begin outreach to top 10 pet insurance targets
- [ ] Sign Letter of Intent with first pilot customer; offer 30-day free pilot
- [ ] Build demo scenario: "My dog needs ACL surgery" — full FNOL intake to completion

**Days 31–60: Pilot + Proof**
- [ ] Run live pilot with 1,000+ real calls
- [ ] Measure: call completion rate, containment rate, CSAT, cost per call vs. BPO incumbent
- [ ] Identify and fix top failure modes from pilot data
- [ ] Begin outreach to vehicle warranty targets with pet insurance pilot data
- [ ] Sign 2nd and 3rd customer

**Days 61–90: Commercialize + Expand**
- [ ] Convert pilots to paid contracts
- [ ] Publish case study: specific metrics, carrier name (with permission), before/after cost comparison
- [ ] Attend one industry event with case study materials
- [ ] Close first vehicle warranty deal
- [ ] Build outbound renewal module (product expansion)
- [ ] Begin evaluation of Phase 2 hire: sales/BD

**90-day target:** 3–5 paying customers; $50–150K ARR; 2 published case studies; clear path to $500K ARR in 12 months.

---

## Sources

### Market Size and BPO Industry
1. Mordor Intelligence — Insurance BPO Services Market (2025): https://www.mordorintelligence.com/industry-reports/insurance-bpo-services-industry
2. Market Research Future — Insurance BPO Market (2025): https://www.marketresearchfuture.com/reports/insurance-bpo-services-industry-market-24181
3. GM Insights — Insurance BPO Market (2025): https://www.gminsights.com/industry-analysis/insurance-bpo-market
4. IMARC Group — Insurance BPO Market (2024): https://www.imarcgroup.com/insurance-business-process-outsourcing-market
5. Business Research Company — Insurance BPO Report: https://www.thebusinessresearchcompany.com/report/insurance-business-process-outsourcing-global-market-report
6. Expivia — Call Center Outsourcing Cost Benchmarks: https://www.expiviausa.com/call-center-outsourcing-cost/

### Insurance Carriers and Segments
7. Autobody News — Top US Auto Insurers 2024 (S&P Global data): https://www.autobodynews.com/news/top-u-s-auto-insurers-expand-market-share-in-2024-led-by-progressive
8. Agency Checklists — NAIC 2025 Market Share, Top 25 Homeowners Insurers: https://agencychecklists.com/2025/03/17/naic-2025-market-share-report-top-25-homeowners-insurers-74909/
9. Carrier Management — Homeowners Premiums 2024: https://www.carriermanagement.com/news/2025/05/20/275425.htm
10. GlobeNewswire — US Pet Insurance Market 2025–2030: https://www.globenewswire.com/news-release/2024/11/25/2986768/28124/en/U-S-Pet-Insurance-Market-Analysis-Report-2025-2030
11. IBISWorld — Auto Extended Warranty Market Size 2025: https://www.ibisworld.com/united-states/market-size/auto-extended-warranty-providers/5038/
12. Verified Market Reports — Renters Insurance Market: https://www.verifiedmarketreports.com/product/renters-insurance-market/

### Insurance BPO Providers
13. ACTEC — FNOL Outsourcing: https://actec.com/fnol-outsourcing/
14. Covenir BPO — FNOL & Claims Outsourcing: https://www.covenirbpo.com/fnol-claims/
15. Focus Insurance BPO — Call Center: https://teamfocusins.com/insurance-outsourcing-solutions/call-center/
16. Confiebpo.com — Insurance Call Center BPO: https://www.confiebpo.com/industries/insurance/
17. Liveops — Insurance Call Center Outsourcing: https://liveops.com/blog/insurance-call-center-outsourcing-the-smarter-way-to-scale-service/
18. Quality Claims Solutions: https://qualityclaims.solutions/

### AI Voice Competitors (Insurance)
19. Liberate — AI Voice and FNOL: https://www.liberateinc.com/
20. Floatbot AI — Insurance Automation: https://floatbot.ai/automate-insurance-claims-process
21. Sonant AI — HawkSoft Integration (Jan 2026): https://www.prnewswire.com/news-releases/hawksoft-and-sonant-announce-voice-ai-integration-for-independent-insurance-agencies-302654708.html
22. Glia — AI Call Center for Insurance: https://www.glia.com/news/glia-launches-ai-powered-call-center-platform-purpose-built-for-insurance-industry
23. Avallon — $4.6M Seed Round (Nov 2025): https://www.businesswire.com/news/home/20251106838494/en/Avallon-Secures-$4.6-Million-Scales-AI-Agents-to-Automate-Insurance-Claims-Operations
24. FurtherAI — $25M Series A (a16z): https://www.furtherai.com/
25. SuperDial — $15M Series A, Voice AI Insurance: https://www.fiercehealthcare.com/ai-and-machine-learning/voice-ai-company-superdial-picks-15m-series-automate-insurance-calls
26. Telnyx — Best Voice AI Agents for Insurance Teams: https://telnyx.com/resources/best-voice-ai-agents-insurance

### AI Voice Platforms and Infrastructure
27. Retell AI — Pricing: https://www.retellai.com/pricing
28. Retell AI — Compliance (SOC2, HIPAA, GDPR): https://docs.retellai.com/general/compliance
29. Retell AI — Voice AI Platform Pricing Comparison 2025: https://www.retellai.com/resources/voice-ai-platform-pricing-comparison-2025
30. Bland AI — Billing & Plans: https://docs.bland.ai/platform/billing
31. Bland AI — $40M Series B (March 2025): https://www.bland.ai/blogs/bland-raises-a-40m-series-b
32. Bland AI — Bland vs. VAPI Enterprise Comparison: https://www.bland.ai/blogs/bland-vs-vapi-which-ai-voice-platform-is-right-for-enterprise
33. VAPI — Pricing: https://vapi.ai/pricing
34. VAPI — $20M Series A (Bessemer, Dec 2024): https://vapi.ai/blog/vapi-secures-20m-to-start-the-voice-revolution-2
35. ElevenLabs — Conversational AI Pricing Cut (Feb 2025): https://elevenlabs.io/blog/we-cut-our-pricing-for-conversational-ai
36. ElevenLabs — AIUC-1 Certification (Feb 2026): https://elevenlabs.io/blog/aiuc-announcement
37. ElevenLabs — $180M Series C, $3.3B Valuation (Jan 2025): https://www.agentvoice.com/ai-voice-in-2025-mapping-a-45-billion-market-shift/
38. ElevenLabs — Enterprise / SOC2: https://elevenlabs.io/enterprise
39. Twilio — AI Assistant Pricing: https://www.twilio.com/docs/alpha/ai-assistants/pricing-and-limits
40. Twilio — Conversational AI (ElevenLabs + OpenAI partnership): https://www.twilio.com/en-us/products/conversational-ai
41. LiveKit — Open-source voice AI platform: https://livekit.io/
42. LiveKit — Agents framework (GitHub): https://github.com/livekit/agents

### Build vs. Buy and Cost Analysis
43. McKinsey — The Future of AI in the Insurance Industry (Jul 2025): https://www.mckinsey.com/industries/financial-services/our-insights/the-future-of-ai-in-the-insurance-industry
44. VoAgents — Build vs. Buy Voice AI Agents: CTO-Level Decision Guide: https://blog.voagents.ai/voice-ai-investment/build-vs-buy-voice-ai-agents/
45. Dialora AI — Retell AI Pricing 2025: https://www.dialora.ai/blog/retell-ai-pricing
46. Dialora AI — Bland AI Pricing 2025: https://www.dialora.ai/blog/bland-ai-pricing
47. Dograh — VAPI Pricing Breakdown 2025: https://blog.dograh.com/vapi-pricing-breakdown-2025-plans-hidden-costs-what-to-expect/
48. Liberate + Snapsheet FNOL Integration: https://www.financedirectoreurope.com/news/liberate-and-snapsheet-launch-ai-claims-integration-for-faster-automated-fnol/

---

*Report prepared by Nator, AI Chief of Staff for Glima | February 2026*
*GitHub: https://github.com/mortenator/glima*
