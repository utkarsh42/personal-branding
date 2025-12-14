# Content Mining Guide: Extracting Stories from Your Work

**Created**: December 12, 2025
**Purpose**: Transform daily work into weekly content (no extra work required)

---

## The Goldmine: Your Recent Work

You have **exceptional content** already created in your daily work across 4 projects. This guide shows you exactly where to mine it.

**Rule**: Every piece of work = 1-3 content pieces. No extra research needed.

---

## Ask Inc42 Content Mine (40% of content)

### Where to Look
- `ask-inc42/docs/fixes/OPT-0XX-*.md` - Every optimization is a case study
- `ask-inc42/CHANGELOG.md` - Version history with results
- `ask-inc42/README.md` - Current metrics and status
- `ask-inc42/scripts/*.sh` - Automation examples
- `ask-inc42/docs/benchmarks/` - Quality baselines and analysis
- Git commits - Daily progress and decisions

### Content Extraction Formula

**From OPT Documentation:**

1. **Read**: `docs/fixes/OPT-068-IMPLEMENTATION.md`
2. **Extract**:
   - Problem: Validation sub-workflow failing (0% success)
   - Investigation: ID extraction errors, parallel execution issues
   - Solution: Sequential execution architecture
   - Results: 0% → 80% success rate, 4/4 tests passed
   - Trade-offs: +1-2s latency
3. **Post Title**: "OPT-068: Fixing Datalabs Validation (0% → 80% Success)"
4. **Time**: 30 min to draft (content already written in OPT doc)

**From CHANGELOG:**

1. **Read**: Version history for v2.7.0 → v2.7.3
2. **Extract**:
   - v2.7.0: Time filtering + hallucination prevention
   - v2.7.1: Extended to production (no public release)
   - v2.7.2: Tool timeout alignment (+10.7pp)
   - v2.7.3: Validation fix (+80pp Datalabs)
3. **Post Title**: "4 Releases in 2 Weeks: Ask Inc42 v2.7.0 → v2.7.3 Journey"
4. **Time**: 45 min (pull from CHANGELOG, add narrative)

**From README Metrics:**

1. **Read**: Current metrics section
2. **Extract**:
   - Success rate: 39.2% baseline → 70-90% target
   - Response time: 31s average
   - Deployments: 15+ OPTs in 6 months
   - Infrastructure: Queue mode verified
3. **Post Title**: "Quality Baseline: 39.2% → 70-90% Improvement Roadmap"
4. **Time**: 30 min (metrics already documented)

**From Scripts:**

1. **Read**: `scripts/version-bump.sh`, `scripts/testing-lib.sh`, `scripts/n8n-lib.sh`
2. **Extract**:
   - Developer Productivity Toolkit (3 phases)
   - Time savings: 5-7 hours/week
   - Real scripts with usage examples
3. **Post Title**: "Developer Productivity Toolkit: 5-7 Hours/Week Saved"
4. **Time**: 45 min (add narrative to existing scripts)

### Ask Inc42 Content Ideas (20+ posts)

**Optimization Cycle Series** (15 posts):
- OPT-060: Time Filtering
- OPT-061: Hallucination Prevention (2-phase)
- OPT-062: Investor Query Investigation (deferred, why?)
- OPT-065: Tool Timeout Alignment (+10.7pp)
- OPT-068: Validation Fix (0% → 80%)
- OPT-066: Regression Investigation (upcoming)
- OPT-067: API Rate Limit Optimization (upcoming)
- ...and 8 more from backlog

**Architecture & Methodology** (10+ posts):
- Quality Baseline Establishment
- Infrastructure Verification (queue mode)
- Root Cause Analysis (API limits vs infrastructure)
- Developer Productivity Toolkit
- Testing Automation (smoke tests, ICP tests)
- Deployment Workflows (atomic, with testing)
- MCP Integrations (n8n-mcp, PostHog, Notion)
- n8n + LangChain Architecture
- RAG System Optimization
- Sequential vs Parallel Execution Trade-offs

**Quick Content** (extract in <15 min):
- Git commit message → Twitter micro-update
- OPT completion → "Shipped today" post
- Metric improvement → Before/after comparison
- Bug fix → "Here's what I learned" post

---

## Datalabs GTM Content Mine (30% of content)

### Where to Look
- `datalabs-gtm/final/strategy/gtm-framework-v2.md` - 5-pillar GTM strategy
- `datalabs-gtm/final/positioning/brand-positioning-v2.md` - Multi-ICP positioning
- `datalabs-gtm/analytics/*.md` - Metrics baselines and analyses
- `datalabs-gtm/drafts/seo/` - SEO playbooks and audits
- `datalabs-gtm/campaigns/active/` - Live campaigns
- `datalabs-gtm/memory/session-*.md` - Session learnings

### Content Extraction Formula

**From GTM Framework:**

1. **Read**: `final/strategy/gtm-framework-v2.md`
2. **Extract**:
   - 5 pillars: Outbound, Inbound, PLG, Lifecycle, Partnerships
   - Budget: $500-1K/month ($200-400 each for top 3 pillars)
   - Team: 2-3 people
   - Competing with Tracxn ($100M+ funded)
3. **Post Title**: "$500/Month GTM Stack to Compete with $100M+ Competitors"
4. **Time**: 30 min (framework already written)

**From Brand Positioning:**

1. **Read**: `final/positioning/brand-positioning-v2.md`
2. **Extract**:
   - Four-ICP model (Investors 11.4%, Founders 40.3%, Sales 14.3%, Consultants 8%)
   - Activation rates (Sales 77.6%, Students 79.4%, Founders 72.9%)
   - Revenue share modeling
   - Data quality crisis (96.5% NULL)
3. **Post Title**: "Four-ICP Strategy: Data-Driven Positioning with PostHog"
4. **Time**: 45 min (data already analyzed)

**From Analytics:**

1. **Read**: `analytics/onboarding-metrics-baseline.md` or `analytics/icp-demographic-insights.md`
2. **Extract**:
   - Baseline metrics (34.7% activation → 50% target)
   - ICP breakdown and insights
   - Cohort analysis and findings
3. **Post Title**: "34.7% → 50% Activation: Product-Led Growth Roadmap"
4. **Time**: 30 min (metrics documented)

**From SEO Drafts:**

1. **Read**: `drafts/seo/listicle-strategy.md` or `drafts/seo/programmatic-seo-plan.md`
2. **Extract**:
   - SEO learnings (technical SEO > engagement)
   - Programmatic SEO plan (500 pages in 3 months)
   - Listicle audit findings
3. **Post Title**: "Programmatic SEO: 500 Pages in 3 Months (B2B SaaS Playbook)"
4. **Time**: 45 min (playbook already written)

**From Session Memory:**

1. **Read**: Latest `memory/session-YYYY-MM-DD-*.md`
2. **Extract**:
   - Key findings and insights
   - Decisions made and rationale
   - Hypotheses tested
   - Next steps and open questions
3. **Post Title**: Varies based on session topic
4. **Time**: 20 min (session already documented)

### Datalabs GTM Content Ideas (15+ posts)

**GTM Strategy** (8 posts):
- $500/Month GTM Stack Breakdown
- 5-Pillar GTM Framework
- Four-ICP Positioning and Messaging
- Multi-ICP Activation Strategies
- Crisis Response Protocol
- Data Freshness Rules
- Budget Allocation Across Pillars
- Team Structure and Roles

**Growth & Activation** (7 posts):
- 34.7% → 50% Activation Roadmap
- PostHog-Driven Segmentation
- Product-Led Growth Tactics
- AI-Powered Outbound (Clay + Instantly)
- Programmatic SEO Strategy
- Lifecycle Marketing and Retention
- Partnership Strategy (VCs, Accelerators)

---

## Inc42 Media Content Mine (10% of content)

### Where to Look
- `inc42-media/brand-positioning/strategy/intelligence-engine-messaging-framework.md` - Messaging framework (2,274 lines)
- `inc42-media/tools/persona-tester/tests/` - Persona testing results
- `inc42-media/brand-positioning/campaigns/2025-01-launch/strategy.md` - Campaign strategy

### Content Extraction Formula

**From Messaging Framework:**

1. **Read**: `brand-positioning/strategy/intelligence-engine-messaging-framework.md`
2. **Extract**:
   - Intelligence Engine positioning (8.47/10 score)
   - 42 collateral variants (3 About, 4 Short, 3 Long, 10 One-liners, 19 Ads, 11 Newsletters)
   - Complete messaging hierarchy
3. **Post Title**: "Creating a Messaging Framework: 2,274 Lines, 42 Variants"
4. **Time**: 45 min (content exists, add narrative)

**From Persona Testing:**

1. **Read**: `tools/persona-tester/tests/2025-11-platform-variants/aggregated-results.yaml`
2. **Extract**:
   - 9 personas (3 Founders, 3 Investors, 3 Ecosystem)
   - Intelligence Engine wins 8.47/10 (8 of 9 personas)
   - All platform variants rejected (6.4-7.5/10)
   - Methodology: 5-criteria scoring, weighted
3. **Post Title**: "AI-Powered Persona Testing: Validating 'Intelligence Engine' Positioning"
4. **Time**: 45 min (results documented, add methodology)

**From Campaign Strategy:**

1. **Read**: `brand-positioning/campaigns/2025-01-launch/strategy.md`
2. **Extract**:
   - 8-week campaign plan
   - Multi-channel approach
   - Success metrics (2M+ reach, 15% traffic increase)
   - Segment-specific variants
3. **Post Title**: "Intelligence Engine Campaign: 8-Week Launch Strategy"
4. **Time**: 30 min (strategy exists)

### Inc42 Media Content Ideas (5+ posts)

- AI-Powered Persona Testing Framework
- Intelligence Engine Positioning (8.47/10 validation)
- Messaging Framework Creation
- Platform Variants Testing and Rejection
- Campaign Strategy and Execution

---

## Datalabs Product (V3) Content Mine (20% of content - upcoming)

### Where to Look (once V3 work starts)
- `datalabs-product/datalabs/final/strategy/v3-product-roadmap.md` - V3 roadmap
- `datalabs-product/datalabs/drafts/plans/agent-implementation-roadmap.md` - Agent specs
- `datalabs-product/datalabs/drafts/plans/agent-specs/*.md` - Individual agent designs
- Notion pages (Master Context, V3 Strategy)

### Content Extraction Formula

**From V3 Roadmap:**

1. **Read**: `final/strategy/v3-product-roadmap.md`
2. **Extract**:
   - Dual-mode platform (Ask Mode + Discover Mode)
   - Phase 1-4 timeline
   - AI Infrastructure setup
   - UX/UI design briefs
3. **Post Title**: "Datalabs V3: Dual-Mode Intelligence Co-Pilot Roadmap"
4. **Time**: 45 min (roadmap exists)

**From Agent Implementation:**

1. **Read**: `drafts/plans/agent-implementation-roadmap.md` and `agent-specs/`
2. **Extract**:
   - Tier 1 agents (Notion Sync, Draft Reviewer, Phase Tracker)
   - Implementation estimates (18-24 hours total)
   - Architecture and workflows
3. **Post Title**: "Building AI Agents for Product Development"
4. **Time**: 45 min (specs exist)

### Datalabs V3 Content Ideas (10+ posts - future)

- V3 Phase 1 Kickoff
- Dual-Mode Platform Design
- AI Infrastructure Setup
- Agent Implementation Journey
- UX/UI Design Briefs
- Notion Integration and Context Sync
- Building in Public: V3 Development

---

## Daily Content Capture Workflow

### Morning (5 minutes)
**Before starting work**, review yesterday:
- What did I ship?
- What metrics changed?
- What did I learn?
- Any surprising findings?

**Add to** `content/ideas/content-ideas.md`:
- "OPT-068 deployed - 0% → 80% validation success"
- "Learned: Sequential execution fixes parallel race conditions"
- "Quality baseline established - 39.2% starting point"

### During Work (0 minutes - passive capture)
**Claude Code does the work**, you capture the output:
- OPT documentation created → Content draft exists
- Git commits made → Progress logged
- Metrics analyzed → Data available
- Tests run → Results documented

**No extra work required** - just use what Claude Code already creates.

### End of Day (10 minutes)
**Review what was created today**:
- Check git log for commits
- Check CHANGELOG for version updates
- Check README for metric changes
- Check docs/ for new files

**Add 1-3 content ideas** to ideas file:
- Specific (not "wrote code")
- Metric-focused ("improved X from Y to Z")
- Story-driven ("why we chose A over B")

### Weekly (15 minutes - Friday)
**Review the week**, extract Building in Public update:
- What shipped (OPTs, features, deployments)
- Metrics table (before/after/change)
- Key learnings (3-5 specific insights)
- Next week focus (3-5 priorities)

**Time investment**: 30 min/week passive capture → 3-4 posts/week output

---

## Content Repurposing (1 → 6 pieces)

### Example: OPT-068 Case Study

**Single work session** (OPT-068 already completed):

1. **Monday LinkedIn Post** (60 min to draft):
   - Title: "OPT-068: Fixing Datalabs Validation (0% → 80%)"
   - Length: 1,200 words
   - Format: Problem → Investigation → Solution → Results → Learnings
   - Content source: `docs/fixes/OPT-068-IMPLEMENTATION.md`

2. **Tuesday Twitter Thread** (15 min to repurpose):
   - 10 tweets extracted from LinkedIn post
   - Tweet 1: Hook ("Datalabs validation was failing 100% of queries...")
   - Tweets 2-8: Key points from LinkedIn
   - Tweet 9: Results (0% → 80%)
   - Tweet 10: Learnings + CTA

3. **Wednesday Blog Post** (30 min to expand):
   - Same LinkedIn content + additional technical details
   - Code snippets from actual implementation
   - Architecture diagrams
   - Length: 2,000-2,500 words

4. **Thursday Twitter Micro-Update** (2 min):
   - "Shipped OPT-068 today: 0% → 80% Datalabs success rate. Sequential execution was the fix. #BuildInPublic"

5. **Friday Building in Public** (10 min):
   - Include OPT-068 in "What Shipped" section
   - Add to metrics table
   - Mention in key learnings

6. **Next Month Newsletter/Retrospective** (5 min):
   - OPT-068 as one of the month's highlights
   - Part of "15 Optimization Cycles" series

**Total time investment**: 2 hours → 6 content pieces → 3 weeks of social posts

---

## Quick Content Templates

### Micro-Update (Twitter - 2 min)
```
Shipped [feature/OPT] today:

[Metric before] → [Metric after]

[One-line learning]

#BuildInPublic
```

**Example**:
```
Shipped OPT-065 today:

46.4% → 57.1% success rate (+10.7pp)

Lesson: Tool timeout alignment matters more than I thought.

#BuildInPublic #AIProducts
```

### Metrics Comparison (Twitter/LinkedIn - 5 min)
```
[Metric Name] Progress:

Week 1: [Value]
Week 2: [Value]
Week 3: [Value]
Week 4: [Value]

[One-line insight about trend]
```

**Example**:
```
Ask Inc42 Success Rate Progress:

Week 1: 46.4%
Week 2: 57.1% (+10.7pp - OPT-065)
Week 3: 57.1% (stable)
Week 4: 80% Datalabs (+80pp - OPT-068)

Infrastructure wasn't the bottleneck. API rate limits were.
```

### Learning Nugget (Twitter - 2 min)
```
Learned today: [Specific learning]

[Why it matters or what changed]
```

**Example**:
```
Learned today: Sequential execution fixes parallel race conditions but adds +1-2s latency.

Worth it for 80pp improvement in success rate (OPT-068).
```

---

## Content Calendar Quick Fill

### Use This Formula Every Week

**Monday**: Pull from Ask Inc42 work (most recent OPT or optimization)
- Check: `ask-inc42/docs/fixes/` for latest OPT
- Time: 30-45 min to draft
- Format: Case study with metrics

**Wednesday**: Pull from Datalabs GTM work or business decisions
- Check: `datalabs-gtm/final/` or `datalabs-gtm/analytics/`
- Time: 30-45 min to draft
- Format: Strategy or framework

**Friday**: Building in Public (always fresh)
- Review week's git commits and metrics
- Time: 20-30 min to draft
- Format: Consistent weekly update template

**Sunday (Optional)**: Twitter thread repurposed from Monday post
- Extract 10 key points from Monday LinkedIn
- Time: 10-15 min to repurpose
- Format: Thread with hook + points + CTA

**Total time**: 2-3 hours/week → 12-16 posts/month

---

## Mining Checklist (Weekly)

### Ask Inc42
- [ ] Check `docs/fixes/` for new OPT documentation
- [ ] Review `CHANGELOG.md` for version updates
- [ ] Check `README.md` for metric changes
- [ ] Review git commits for progress
- [ ] Check `docs/benchmarks/` for new baselines

### Datalabs GTM
- [ ] Check `analytics/` for new metric baselines
- [ ] Review `memory/session-*.md` for learnings
- [ ] Check `campaigns/active/` for campaign updates
- [ ] Review `final/strategy/` for framework updates

### Inc42 Media
- [ ] Check `brand-positioning/strategy/` for new messaging
- [ ] Review `tools/persona-tester/tests/` for test results

### Datalabs V3 (when active)
- [ ] Check `datalabs/final/strategy/` for roadmap updates
- [ ] Review `datalabs/drafts/plans/` for agent specs
- [ ] Check Notion pages for context updates

---

## What If I'm Stuck?

### No Idea What to Write?

**Option 1**: Review last week's work
1. Open git log: `git log --since="7 days ago" --oneline`
2. Pick any commit with substance
3. Expand into 1,200-word case study

**Option 2**: Check your ideas file
1. Open `content/ideas/content-ideas.md`
2. Pick easiest/quickest idea
3. Draft in 30-45 min

**Option 3**: Default to Building in Public
1. Review week's metrics
2. Use `templates/building-in-public.md`
3. Fill in template (always works)

### No Time This Week?

**Minimum Viable Content**:
- Friday Building in Public only (20-30 min)
- 3-5 Twitter micro-updates (10 min total)
- Total: 30-40 min/week minimum

### Quality Concerns?

**Remember**:
- Authenticity > Polish
- Metrics > Storytelling
- Specific > Generic
- Your work is already world-class - just document it

**Use templates** to reduce decision fatigue and speed up drafting.

---

## Summary: Content is Already Created

You're NOT creating content from scratch. You're **documenting work that already exists**.

**Every week you**:
- Ship OPTs (documented in `docs/fixes/`)
- Analyze metrics (documented in `analytics/` or `README.md`)
- Make strategic decisions (documented in `final/` or `memory/`)
- Build with Claude Code (documented in git commits and scripts)

**Content mining** = Copy existing docs → Add narrative → Publish

**Time required**: 2-3 hours/week (drafting + repurposing), not 10+ hours (research + writing)

**Your advantage**: Production systems + Real metrics + Transparent failures = Content gold

---

## Next Step

Open `content/ideas/content-ideas.md` right now.

Add 10 ideas from your last month's work.

Pick the easiest one.

Draft it in 30 minutes using a template.

Publish Monday.

You already did the hard work. Now ship the content.
