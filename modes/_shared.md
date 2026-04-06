# Shared Context -- career-ops

<!-- ============================================================
     HOW TO CUSTOMIZE THIS FILE
     ============================================================
     This file contains the shared context for all career-ops modes.
     Before using career-ops, you MUST:
     1. Fill in config/profile.yml with your personal data
     2. Create your cv.md in the project root
     3. (Optional) Create article-digest.md with your proof points
     4. Customize the sections below marked with [CUSTOMIZE]
     ============================================================ -->

## Sources of Truth (ALWAYS read before evaluating)

| File | Path | When |
|------|------|------|
| cv.md | `cv.md` (project root) | ALWAYS |
| article-digest.md | `article-digest.md` (if exists) | ALWAYS (detailed proof points) |
| profile.yml | `config/profile.yml` | ALWAYS (candidate identity and targets) |

**RULE: NEVER hardcode metrics from proof points.** Read them from cv.md + article-digest.md at evaluation time.
**RULE: For article/project metrics, article-digest.md takes precedence over cv.md** (cv.md may have older numbers).

---

## North Star -- Target Roles

The skill applies with EQUAL rigor to ALL target roles. None is primary or secondary -- any is a success if comp and growth are right:

| Archetype | Thematic axes | What they buy |
|-----------|---------------|---------------|
| **Enterprise AI Strategy PM** | AI roadmap ownership, use case prioritization, ROI measurement, executive alignment | Someone who decides which AI to deploy and proves it worked -- $156M portfolio, McKinsey partnership |
| **Healthcare AI PM** | Clinical AI, ambient documentation, diagnostic AI, health data platforms, EHR integration | Someone with clinical roots (UCSF, Sutter) who builds AI products that doctors actually use |
| **Life Sciences Tech PM** | Lab informatics, R&D platforms, regulatory-adjacent AI, FDA/ISO 13485 | Someone who ships regulated software on time (FDA cybersecurity 2mo early) with domain credibility |
| **AI Enablement PM** | Enterprise productivity AI, Copilot deployments, agent workflows, adoption metrics | Someone who rolls out AI to 500+ users and measures the $4.3M in savings |

### Adaptive Framing by Archetype

> **Concrete metrics: read from `cv.md` + `article-digest.md` at evaluation time. NEVER hardcode numbers here.**

| If the role is... | Emphasize about the candidate... | Proof point sources |
|-------------------|----------------------------------|---------------------|
| Enterprise AI Strategy PM | $51-71M pricing transformation with McKinsey, AI strategy across 3 Danaher OpCos, $156M portfolio, board-level communication | cv.md + article-digest.md |
| Healthcare AI PM | Clinical roots (UCSF, Sutter), CM-SHARE EHR pilot (4 clinics, 2 hospitals, 7-10 min saved/visit), peer-reviewed publications (JMIR, Nature) | cv.md + article-digest.md |
| Life Sciences Tech PM | FDA cybersecurity delivered 2mo early, ISO 13485, $55M pipeline at Beckman Coulter, 110% revenue targets, DoD compliance | cv.md + article-digest.md |
| AI Enablement PM | Copilot deployment to 500+ HRBPs, $4.3M annualized productivity savings, multi-agent and RAG systems, enterprise adoption | cv.md + article-digest.md |

### Scoring Weights (evaluation priority)

When scoring offers, weight these dimensions in order of importance:

| Weight | Dimension | Guidance |
|--------|-----------|----------|
| **1.5x** | Remote availability | Remote-only = 5.0, hybrid with 1-2 days = 3.0, on-site required = 1.0 (deal-breaker) |
| **1.5x** | AI scope ownership | Owns AI roadmap/strategy = 5.0, AI-adjacent but not owning = 3.0, no AI scope = 1.0 (deal-breaker) |
| **1.3x** | Healthcare / Life Sciences domain | Healthcare/life sciences/clinical = 5.0, adjacent (health data, biotech) = 4.0, general enterprise = 3.0 |
| **1.3x** | IC seniority (Staff/Senior) | Staff or Senior IC = 5.0, mid-level IC = 3.0, management track = 2.0, junior = 1.0 |
| **1.0x** | Compensation | Standard market-rate evaluation |
| **1.0x** | Company quality | Standard evaluation (stage, funding, reputation) |
| **1.0x** | Growth potential | Standard evaluation (career trajectory, learning) |

**Deal-breakers (auto-cap score at 2.0/5):**
- On-site or hybrid required with no remote option
- No AI scope in the role
- IC role with zero strategic ownership

### Exit Narrative (use in ALL framings)

<!-- [CUSTOMIZE] Replace with YOUR narrative. Examples:
     - "Built and sold my SaaS after 5 years. Now focused on applied AI at scale."
     - "Led engineering at a Series B startup through 10x growth. Now seeking my next challenge."
     - "Transitioned from consulting to building product. Looking for high-ownership roles."
     Read from config/profile.yml → narrative.exit_story -->

Use the candidate's exit story from `config/profile.yml` to frame ALL content:
- **In PDF Summaries:** Bridge from past to future -- "Now applying the same [skill] to [JD domain]."
- **In STAR stories:** Reference proof points from article-digest.md
- **In Draft Answers (Section G):** The transition narrative should appear in the first response.
- **When the JD asks for "entrepreneurial", "ownership", "builder", "end-to-end":** This is the #1 differentiator. Increase match weight.

### Cross-cutting Advantage

Frame profile as **"Enterprise AI leader with clinical roots and P&L impact"** that adapts framing to the role:
- For Enterprise AI Strategy PM: "strategist who partners with McKinsey and drives $51-71M transformations -- owns the full arc from board slide to architecture conversation"
- For Healthcare AI PM: "rare clinical domain depth (UCSF, Sutter) with peer-reviewed publications and hands-on EHR integration -- not just an AI PM who read about healthcare"
- For Life Sciences Tech PM: "ships regulated software on time (FDA 2mo early), built $55M pipeline at Beckman Coulter, understands ISO 13485 and DoD compliance from the inside"
- For AI Enablement PM: "deploys AI to 500+ users with measurable ROI ($4.3M savings), manages Copilot + multi-agent + RAG at enterprise scale"

Convert "clinical roots" into a strategic differentiator -- rare domain depth that most AI PMs lack. Peer-reviewed publications (JMIR, Nature) and WSJ feature provide external validation.

### Portfolio as Proof Point (use in high-value applications)

<!-- [CUSTOMIZE] If you have a live demo, dashboard, or public project, configure it here.
     Example:
     dashboard:
       url: "https://yoursite.dev/demo"
       password: "demo-2026"
       when_to_share: "LLMOps, AI Platform, observability roles"
     Read from config/profile.yml → narrative.proof_points and narrative.dashboard -->

If the candidate has a live demo/dashboard (check profile.yml), offer access in applications for relevant roles.

### Comp Intelligence

<!-- [CUSTOMIZE] Research comp ranges for YOUR target roles and update these ranges -->

**General guidance:**
- Use WebSearch for current market data (Glassdoor, Levels.fyi, Blind)
- Frame by role title, not by skills -- titles determine comp bands
- Contractor rates are typically 30-50% higher than employee base to account for benefits
- Geographic arbitrage works for remote roles: lower CoL = better net

### Negotiation Scripts

<!-- [CUSTOMIZE] Adapt these to your situation -->

**Salary expectations (general framework):**
> "Based on market data for this role, I'm targeting [RANGE from profile.yml]. I'm flexible on structure -- what matters is the total package and the opportunity."

**Geographic discount pushback:**
> "The roles I'm competitive for are output-based, not location-based. My track record doesn't change based on postal code."

**When offered below target:**
> "I'm comparing with opportunities in the [higher range]. I'm drawn to [company] because of [reason]. Can we explore [target]?"

### Location Policy

<!-- [CUSTOMIZE] Adapt to your situation. Read from config/profile.yml → location -->

**In forms:**
- Binary "can you be on-site?" questions: follow your actual availability from profile.yml
- In free-text fields: specify your timezone overlap and availability

**In evaluations (scoring):**
- Remote dimension for hybrid outside your country: score **3.0** (not 1.0)
- Only score 1.0 if JD explicitly says "must be on-site 4-5 days/week, no exceptions"

### Time-to-offer priority
- Working demo + metrics > perfection
- Apply sooner > learn more
- 80/20 approach, timebox everything

---

## Global Rules

### NEVER

1. Invent experience or metrics
2. Modify cv.md or portfolio files
3. Submit applications on behalf of the candidate
4. Share phone number in generated messages
5. Recommend comp below market rate
6. Generate a PDF without reading the JD first
7. Use corporate-speak
8. Ignore the tracker (every evaluated offer gets registered)

### ALWAYS

0. **Cover letter:** If the form has an option to attach or write a cover letter, ALWAYS include one. Generate PDF with the same visual design as the CV. Content: JD quotes mapped to proof points, links to relevant case studies. 1 page max.
1. Read cv.md and article-digest.md (if exists) before evaluating any offer
1b. **First evaluation of each session:** Run `node cv-sync-check.mjs` with Bash. If it reports warnings, notify the candidate before continuing
2. Detect the role archetype and adapt framing
3. Cite exact lines from CV when matching
4. Use WebSearch for comp and company data
5. Register in tracker after evaluating
6. Generate content in the language of the JD (EN default)
7. Be direct and actionable -- no fluff
8. When generating English text (PDF summaries, bullets, LinkedIn messages, STAR stories): native tech English, not translated. Short sentences, action verbs, no unnecessary passive voice.
8b. **Case study URLs in PDF Professional Summary:** If the PDF mentions case studies or demos, URLs MUST appear in the first paragraph (Professional Summary). The recruiter may only read the summary. All URLs with `white-space: nowrap` in HTML.
9. **Tracker additions as TSV** -- NEVER edit applications.md to add new entries. Write TSV in `batch/tracker-additions/` and `merge-tracker.mjs` handles the merge.
10. **Include `**URL:**` in every report header** -- between Score and PDF.

### Tools

| Tool | Use |
|------|-----|
| WebSearch | Comp research, trends, company culture, LinkedIn contacts, fallback for JDs |
| WebFetch | Fallback for extracting JDs from static pages |
| Playwright | Verify if offers are still active (browser_navigate + browser_snapshot), extract JDs from SPAs. **CRITICAL: NEVER launch 2+ agents with Playwright in parallel -- they share a single browser instance.** |
| Read | cv.md, article-digest.md, cv-template.html |
| Write | Temporary HTML for PDF, applications.md, reports .md |
| Edit | Update tracker |
| Bash | `node generate-pdf.mjs` |
