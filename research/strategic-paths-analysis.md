# Glima Strategic Paths: Expand from FNOL
*Analysis prepared for Morten | February 2026*

---

## Executive Summary

- **Path A (Insurance Operations Platform):** Start with FNOL, expand to automate the full claims lifecycle and policy servicing workflow — adjuster assignment, reserve setting, fraud triage, document handling, subrogation. This is the Pace playbook. Pace just raised $10M from Sequoia (Jan 2026) doing exactly this.
- **Path B (Horizontal Call Center Platform):** Use FNOL as an insurance-specific wedge, then expand voice AI automation to adjacent verticals — warranty, roadside, healthcare, retail. This is the Bland AI / Retell AI direction.
- **The key difference:** Path A bets on insurance domain depth; Path B bets on voice AI horizontal scale. Path A means becoming a vertical SaaS; Path B means becoming infrastructure.
- **Path A is more crowded at the platform layer** (Guidewire, Duck Creek, Snapsheet all have head starts), but the *agentic AI-native BPO wedge* that Pace is running — and that Glima already has with FNOL — is the most defensible entry.
- **Recommendation: Pursue a modified Path A.** Own insurance operations automation, starting with FNOL + claims intake, and build depth before breadth. The insurance vertical has large, sticky contracts, clear ROI, and a defined acquisition path to Guidewire/Duck Creek/Majesco. A 2-person team cannot win the horizontal call center infrastructure war against Bland ($65M raised), Retell, and VAPI.

---

## Path A: FNOL → Insurance Operations Platform

### What This Means

"Insurance operations" is everything that happens after a policy is sold and before it is fully settled. For claims specifically:

1. **FNOL intake** — voice/digital capture of loss event (Glima's current product)
2. **Claims triage and routing** — assigning to adjuster, setting priority, flagging fraud indicators
3. **Reserve setting** — AI-assisted initial reserve estimation based on loss type, historical data
4. **Document handling** — ingesting police reports, repair estimates, medical records; extracting structured data
5. **Adjuster assignment and task management** — creating and routing work items
6. **Coverage verification** — checking policy terms against the reported loss
7. **Vendor dispatch** — routing to body shops, inspectors, restoration crews
8. **Subrogation identification** — flagging third-party liability recovery opportunities
9. **Settlement and payment automation** — straight-through processing for low-complexity claims

Beyond claims, "insurance ops" also includes:
- **Submission intake** (commercial lines): ingesting broker submissions, extracting risk data
- **Policy servicing**: endorsements, cancellations, renewals, billing inquiries
- **Reporting and compliance**: bordereaux, regulatory filings

### Market Opportunity

- The global Insurance BPO market was **$64.3 billion in 2025**, projected to reach **$89.3 billion by 2030** (6.8% CAGR). This is the spend Pace explicitly targets — replacing offshore BPO labor with AI agents.
- A more specific lens: US P&C insurers spend an estimated **$70 billion/year on operations** (Pace's own cited figure in fundraising materials). Claims handling is 30–40% of that.
- The addressable opportunity for an AI-native claims automation vendor is **$15–25B** in the US alone, with enterprise contracts ranging from $500K–$5M ARR per carrier.
- Automation sequence by ROI/feasibility: FNOL intake first (structured, high-volume), then document extraction, then coverage verification, then reserve recommendation, then adjuster orchestration. Subrogation and fraud triage come later (require more model sophistication).
- Insurance ops is defensible because: (1) data is highly proprietary, (2) compliance requirements create switching costs, (3) carrier integrations (Guidewire, Duck Creek, Majesco) are expensive to rebuild, (4) insurance domain expertise is genuinely scarce.

### Who's Doing This (Competitive Landscape)

| Company | What They Do | Stage / Funding | Key Customers | Trajectory | Threat to Glima |
|---|---|---|---|---|---|
| **Pace** | AI-native BPO: submission intake, FNOL, claims handling, data entry, policy servicing via agentic AI | Series A — $10M (Sequoia, Jan 2026) | Prudential Financial | Explicitly replacing offshore BPO; most direct Path A competitor | **HIGH** — same lane, well-funded, Sequoia brand |
| **Snapsheet** | Claims management SaaS: workflow orchestration, adjuster tools, vendor routing, reserve setting | ~$100M+ raised (Series C, 2021) | Many P&C carriers | Expanding AI automation; 15% cost reduction claim; adding AI agents via Agentech partnership | **HIGH** — broad claims platform, established |
| **Five Sigma** | Cloud-native claims management SaaS with AI-driven workflow and omnichannel comms | ~$50M raised | Mid-market carriers | Building AI claims orchestration; competes with Snapsheet | **MEDIUM** — less US market share than Snapsheet |
| **Gradient AI** | Predictive AI for underwriting and claims severity/reserves | ~$87M raised (Series C) | 100+ insurers incl. WR Berkley | Claims reserve prediction, underwriting risk scoring | **LOW** — analytics layer, not workflow automation |
| **Tractable** | Computer vision for auto and property damage assessment | ~$200M raised ($65M Series C, 2021); $1B valuation | Covéa, Ageas, top 10 US auto insurers | Expanding from photos to full repair cost estimation | **LOW** — visual damage vertical, not voice/FNOL |
| **Guidewire** | Full P&C core platform: policy, billing, claims | Public ($GW); $10B+ market cap | Top 500 P&C carriers globally | Adding AI/ML via partner marketplace; not rebuilding natively | **MEDIUM** — distribution channel OR acquirer |
| **Duck Creek** | P&C core platform (policy + claims), cloud-native | Acquired by Vista Equity (2023) | Mid-to-large US carriers | Expanding AI capabilities; investing in agentic tools | **MEDIUM** — platform player; potential acquirer |
| **Majesco** | Insurance digital transformation platform (L&H + P&C) | Public (MJCO); mid-cap | Mid-market carriers | AI-augmented policy and claims servicing | **LOW-MEDIUM** — smaller market share, less AI-forward |
| **Sprout.ai** | Claims document AI: policy checking, coverage verification | ~$20M raised | UK/EU carriers | Document-heavy claims automation | **LOW** — UK-focused, document layer only |
| **Strada** | Insurance workflow automation (voice + post-call actions) | Early stage | SMB agencies/carriers | Post-call automation; FNOL adjacent | **MEDIUM** — early, similar wedge |

### Path A POV

**Strengths for Glima:**
- Glima already has an insurance customer generating live FNOL data — this is the hardest thing to get, and most competitors don't start here.
- FNOL is the natural entry to claims ops: every subsequent step in the claims workflow is triggered by FNOL data that Glima already captures.
- Insurance carrier sales cycles are long (9–18 months), but contract values are high ($300K–$3M ARR). One or two large accounts = real business.
- The BPO displacement thesis (Pace's framing) is economically tight: a carrier paying $2M/year to a BPO for FNOL + data entry will pay $600K–$1M to an AI vendor for the same output. That's a compelling ROI case.
- Data moat: every claim processed trains models on Glima's proprietary loss data.

**Weaknesses / Risks:**
- Pace is 12–18 months ahead and just raised $10M from Sequoia. They have Prudential as a customer. Glima cannot outspend them.
- Moving from FNOL voice to full workflow automation requires document AI, system integration (Guidewire APIs), adjuster-facing UI, and compliance tooling — that's 18+ months of product work for a 2-person team.
- Insurance buyers are risk-averse. A 2-person startup without SOC 2, E&O coverage, or a track record of enterprise-scale operations will get filtered out early in procurement.
- The market is increasingly competitive: every major carrier is either building in-house or selecting a platform.

**What Glima Would Need to Build:**
1. SOC 2 Type II certification (6–9 months; required for enterprise deals)
2. Native integrations with Guidewire ClaimCenter and Duck Creek Claims (the two dominant systems)
3. Document extraction layer (police reports, repair estimates, medical records)
4. Adjuster-facing task UI / claims intake dashboard
5. Analytics/reporting for claims ops managers

**Likely Exit:**
- **Guidewire** or **Duck Creek** are the most logical acquirers of a best-in-class AI-native claims intake vendor — they have the distribution but lack the AI-native architecture.
- **Verisk** or **Mitchell International** could acquire for data + AI synergies.
- **Strategic carriers** (large US P&C carriers) occasionally acquire technology vendors for competitive advantage.
- Exit multiples for insurance SaaS/AI: 8–15x ARR (based on Finro 2025 data for profitable insurtech). At $5M ARR, this is a $40–75M exit. At $15M ARR with strong growth, $120–200M is plausible.

**Honest Assessment:**
A 2-person team *can* win Path A if they stay disciplined. The key constraint is not building too fast. The defensible strategy is: (1) go deep on FNOL + claims intake only, (2) get 3–5 carrier customers with real data, (3) build the integrations that make switching painful, (4) raise a seed/Series A once the data moat is visible. Do not try to build full workflow automation. Be the best FNOL-to-claims-intake product in the market, then expand. Pace is a more serious competitor than most, but they're pursuing large enterprise (Prudential-scale) accounts. Glima can own the regional/mid-market tier where Pace won't focus initially.

---

## Path B: FNOL → Horizontal Call Center Platform

### What This Means

The horizontal call center platform vision: build voice AI infrastructure flexible enough to serve any inbound/outbound call automation use case, regardless of industry. FNOL in insurance is proof-of-concept; the platform then serves:
- **Warranty claims** (appliances, electronics, vehicles)
- **Roadside assistance** dispatch
- **Healthcare** appointment scheduling, prior auth, patient intake
- **Retail/e-commerce** order tracking, returns
- **Financial services** balance inquiries, fraud reporting
- **Utilities** outage reporting, service requests

The platform vision is developer-facing APIs + no-code agent builder + telephony infrastructure. The business model is usage-based (minutes/calls) + platform fees.

### Market Opportunity

- Global call center AI market: **$2.1–2.4 billion in 2024-2025**, growing to **$7–12.8 billion by 2030–2033** at ~22–24% CAGR (Grand View Research, Fortune Business Insights, IMARC Group data).
- The broader US call center outsourcing market is ~$30B/year, of which voice automation is still <10% penetrated.
- Most attractive verticals after insurance (by call volume + automation readiness): (1) healthcare (high volume, clear scripted workflows), (2) warranty/home services (transaction-heavy), (3) roadside/dispatch (time-critical, structured).
- Horizontal is appealing because TAM is larger and sales cycles can be shorter for SMB/mid-market; product-led growth is possible via API consumption.
- Horizontal is hard because: (1) every vertical has different compliance requirements, (2) no vertical-specific data advantage, (3) competing against infrastructure players with 10–100x more capital.

### Who's Doing This (Competitive Landscape)

| Company | What They Do | Stage / Funding | Customers / Scale | Differentiation | Threat to Glima |
|---|---|---|---|---|---|
| **Bland AI** | Horizontal AI phone call automation; APIs for businesses to build voice agents | $65M total ($40M Series B, Emergence Capital, Jan 2025) | Fortune 500 companies; millions of calls | Scale, Fortune 500 relationships, developer-first | **VERY HIGH** — well-funded, same infrastructure layer |
| **Retell AI** | Voice agent platform + omni-channel customer comms automation | $7.2M revenue, 41-person team (2025); undisclosed funding | Multi-vertical; trending toward enterprise | Omni-channel expansion; QA tooling ("Retell Assure") for enterprise | **VERY HIGH** — fastest-growing, enterprise-focused |
| **VAPI** | Developer-focused voice AI platform (build/test/deploy agents) | $20M Series A (Bessemer, Dec 2024); $25M total | Developer-heavy; SMB to mid-market | Maximum developer control, custom LLM backend | **HIGH** — developer infrastructure; Glima would be a VAPI customer, not a competitor |
| **ElevenLabs** | Voice synthesis infrastructure; increasingly building agent tooling | $180M Series C (Jan 2025); **$3.3B valuation** | Global; multi-vertical | Best-in-class voice quality; moving up the stack | **HIGH** — Glima uses ElevenLabs as a vendor; could become a direct competitor at platform layer |
| **Glia** | AI contact center platform with insurance-specific call center product (launched Oct 2024) | ~$150M raised; late stage | Banks, insurers, credit unions | Omni-channel (voice + digital + AI); insurance vertical | **HIGH** — explicitly targeting insurance call centers, similar wedge |
| **Talkdesk** | Cloud contact center platform; AI-first since 2022 | ~$500M raised; unicorn ($10B valuation, 2021) | 1,800+ enterprises globally | Enterprise reliability, CRM integrations, AI agent builder | **MEDIUM** — enterprise-focused, Glima too small to compete directly |
| **Five9** | Cloud contact center SaaS | Public ($FIVN); ~$600M revenue | Large enterprises | AI-augmented agents, CRM integrations | **MEDIUM** — public company, different price point |
| **Genesys** | CCaaS platform (on-prem + cloud) | ~$1.8B raised; $21B valuation | 7,500+ enterprises globally | Full-stack contact center; Genesys AI | **LOW** — enterprise, legacy infrastructure; not direct competition |
| **Vonage/Ericsson** | CPaaS + contact center | Acquired by Ericsson ($6.2B, 2022) | Telco + enterprise | Communications API platform | **LOW** — infrastructure, not AI-native agent builder |

### Path B POV

**Strengths for Glima:**
- Horizontal TAM is genuinely larger. Call center AI is a $10B+ market by 2030.
- FNOL is a strong proof point: if you can automate a high-stakes insurance intake call, you can automate most service calls.
- Usage-based pricing scales with customer success; low friction to start, high ceiling per customer.
- The ElevenLabs + n8n stack Glima is already running is the same stack that horizontal platforms are being built on — technical credibility is real.

**Weaknesses / Risks:**
- Bland AI has $65M, a Fortune 500 customer base, and 2+ years head start. Retell has $7.2M in revenue and growing fast. VAPI has Bessemer. Glima cannot win a head-to-head infrastructure race.
- No vertical-specific data advantage: without insurance domain knowledge, Glima is just another voice AI wrapper.
- Sales motion becomes highly fragmented: selling into healthcare, warranty, roadside, and retail simultaneously requires different personas, compliance knowledge, and integrations.
- ElevenLabs — Glima's current TTS provider — is building up the stack. At $3.3B valuation and $180M in the bank, they can build what Glima builds.
- Commoditization risk is high: the voice AI infrastructure layer (TTS, ASR, LLM routing) is becoming a commodity, driving pricing pressure on horizontal platforms.

**What Glima Would Need to Build:**
1. Multi-tenant voice agent builder (no-code + API)
2. Telephony infrastructure (PSTN integration, SIP trunking, number provisioning)
3. Vertical-specific compliance modules (HIPAA for healthcare, etc.)
4. CRM integrations across verticals (Salesforce, HubSpot, ServiceNow, etc.)
5. Analytics dashboard + QA tooling
6. Developer documentation + SDKs

This is a **$10M+ engineering build** before you have a competitive platform. Not feasible at 2 people.

**Likely Exit:**
- **Talkdesk, Five9, or Genesys** could acquire a fast-growing horizontal voice AI platform for AI capabilities.
- **Twilio** or a CPaaS player for voice AI to add to communications stack.
- **Salesforce** or CRM players seeking to own voice.
- Exit multiples for SaaS/AI call center platforms: 10–20x ARR at growth stage, but commoditization risk compresses this over time.

**Honest Assessment:**
Glima does not have a realistic path to building a competitive horizontal call center platform from scratch in 2026. The players with capital ($65M+ Bland, $3.3B ElevenLabs, unicorn-status Talkdesk) will out-execute on platform breadth. The only viable version of Path B for Glima is *staying narrow in insurance* and positioning as the best insurance-specific voice automation layer — which is Path A with better marketing. Pure Path B is a capital-intensive infrastructure race that a 2-person team cannot win.

---

## Head-to-Head Comparison

| Dimension | Path A: Insurance Ops Platform | Path B: Horizontal Call Center |
|---|---|---|
| **Market size (TAM)** | ~$15–25B (US insurance ops automation / BPO displacement) | ~$7–12B call center AI by 2030; broader contact center market $30B+ |
| **Competition intensity** | High at platform layer (Pace, Snapsheet, Five Sigma); moderate at agentic-BPO wedge | Extreme at infrastructure layer (Bland $65M, Retell growing fast, VAPI $20M, ElevenLabs $3.3B) |
| **Sales motion complexity** | High: 9–18 month enterprise cycles; compliance-heavy; carrier procurement is complex | Varies: SMB is fast (self-serve), enterprise is complex; multi-vertical means no repeatable playbook |
| **Time to $1M ARR** | 12–18 months (2–3 mid-market carrier deals at $300–500K each) | 18–30 months (need volume of SMB customers OR 1 large platform deal) |
| **Time to $10M ARR** | 36–48 months (10–15 carrier contracts; requires SOC 2, Guidewire integrations) | 36–60 months (requires platform scale; many smaller accounts OR a few large ones) |
| **Required team/capabilities** | Insurance domain expertise + agentic AI + claims workflow knowledge | Voice AI infra engineering + multi-vertical sales + developer relations |
| **Moat / defensibility** | High: insurance domain data, carrier integrations, compliance certifications create lock-in | Low-to-medium: horizontal voice AI is rapidly commoditizing; no data moat without vertical depth |
| **Exit multiple / acquirer profile** | 8–15x ARR; acquirer likely Guidewire, Duck Creek, Verisk, or large P&C carrier | 10–20x ARR (if growing fast); acquirer likely Talkdesk, Twilio, Salesforce, or Five9 |
| **Risk of commoditization** | Low-medium: insurance compliance + data create differentiation over time | High: TTS/ASR/LLM costs dropping, horizontal competitors racing to zero on infra pricing |
| **Fit with current MVP** | **Direct:** FNOL is step 1 of claims ops; existing Texas customer = proof point; natural workflow expansion | Indirect: FNOL is 1 of 100 use cases; would require repositioning away from insurance identity |

---

## Recommendation

### Which Path: Path A, with a specific lane

Glima should pursue Path A — but not by trying to build a full insurance operations platform. The winning strategy for a 2-person team is:

**Be the best AI-native FNOL-to-claims-intake product for regional and mid-market P&C carriers in the US.**

Pace is targeting Prudential. That means the Fortune 500 carrier segment is being contested by a Sequoia-backed company. Glima should not fight that battle yet. The US has 2,500+ P&C insurers. Carriers with $100M–$2B in premium written (the mid-market) are underserved by Pace, Snapsheet, and Five Sigma, who all have minimum deal sizes that filter out this segment.

### Sequencing

1. **Now–6 months:** Get 2–3 more mid-market carrier customers using the FNOL product. Focus on personal auto (Texas + adjacent states). Use each customer to add one more claims workflow step (e.g., FNOL → document request → adjuster assignment notification). Prove a 40–60% reduction in FNOL handling cost vs. human agents or offshore BPO.
2. **6–12 months:** Build native integration with Guidewire ClaimCenter (the dominant claims system). This alone makes Glima far more deployable and creates switching costs. Begin SOC 2 Type II process.
3. **12–18 months:** With 3–5 live carrier customers and Guidewire integration, raise a seed/Series A of $3–5M. Use it to hire 2–3 engineers, a claims domain expert, and a carrier sales rep.
4. **18–36 months:** Expand claims workflow automation (document AI, reserve assist, vendor dispatch). Build toward the full claims intake layer that Pace is building from the top down — Glima builds from the live FNOL data up.

**Do not pursue Path B unless a specific horizontal use case (e.g., warranty, roadside assistance) emerges organically from a customer request.** If that happens, treat it as an expansion revenue opportunity, not a strategic pivot.

### 3 Most Important Strategic Bets in the Next 6 Months

1. **Sign 2 more mid-market carrier contracts** (not the Texas insurer's competitors — different states, different lines). Proof that the product works across carriers is more important than product depth right now. Target personal auto and homeowners carriers with 50–500 adjusters.

2. **Instrument every FNOL call to build a proprietary dataset.** With the Texas customer live, Glima is generating real FNOL data — loss types, locations, call durations, resolution outcomes. This dataset is worth more than any feature. Instrument it now, annotate it, and use it to differentiate model performance vs. generic voice AI. This is the data moat.

3. **Map the Guidewire integration path.** Talk to 5 mid-market carriers about their claims tech stack. Most will be on Guidewire or Duck Creek. Understand the API surface for ClaimCenter. Do a prototype integration. This is the single highest-leverage technical bet for enterprise deployability and switching costs.

---

*Research based on public sources, February 2026. Competitive data accurate as of stated funding rounds and public announcements.*
