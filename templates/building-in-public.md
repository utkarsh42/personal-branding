# Building in Public - Weekly Update Template

---

## Header

**Datalabs V3: Week [X] Update** 🚀

[Optional emoji that represents the week's theme]

---

## What Shipped This Week

<!-- Be specific about what was actually delivered, not just worked on -->

**Shipped**:
- [Feature/component 1] - [What it does, why it matters]
- [Feature/component 2] - [What it does, why it matters]
- [Infrastructure/setup 3] - [What it enables]

**Example**:
- ✅ Query routing system - Directs queries to the right tool (Inc42 Context vs Updates vs Datalabs)
- ✅ Retry logic with 3 fallbacks - Handles LLM failures gracefully
- ✅ Output validation layer - Enforces JSON schema before returning results

---

## Key Metrics

<!-- Real numbers. Be transparent. -->

**This Week**:
- [Metric 1]: [Current value] (↑/↓ [change] from last week)
- [Metric 2]: [Current value] (↑/↓ [change] from last week)
- [Metric 3]: [Current value] (target: [goal])

**Example**:
- Success rate: 100% (↑ from 85% last week)
- Avg response time: 31 seconds (↓ from 45s)
- Test pass rate: 60.7% (↑ from 28.5% in October)
- Users tested: 5 internal (targeting 10 external next week)

---

## What I Learned

<!-- Specific, actionable learnings. Not vague. -->

**3 key learnings**:

1. **[Learning #1 - Technical]**
   - What we discovered
   - Why it surprised us
   - What we'll do differently

2. **[Learning #2 - Process]**
   - What we discovered
   - Impact on the team/timeline
   - Adjustment we're making

3. **[Learning #3 - Strategic]**
   - What we discovered
   - How it changes our thinking
   - Next steps

**Example**:
1. **LLMs need specialization, not generalization**
   - One generic RAG = 40% success. Three specialized tools = 100%.
   - Surprised that narrower scope actually improved overall coverage.
   - Future: Build tools for specific query types vs one-size-fits-all.

2. **Retry logic is non-negotiable for production**
   - Single attempts failed 15% of the time (LLMs are probabilistic).
   - 3 retries + fallback brought that to <1%.
   - Every new tool we build will have retry logic from day one.

3. **5-person team needs extreme focus**
   - Tried to build too many features in parallel - nothing shipped.
   - Switched to one feature at a time - velocity 3x faster.
   - New rule: Max 1 in-progress feature per person.

---

## Challenges This Week

<!-- Be honest about what's hard. People connect with authenticity. -->

**Blockers/Challenges**:
- [Challenge 1] - [How it affected progress]
- [Challenge 2] - [Status: resolved/ongoing]
- [Challenge 3] - [What we're trying next]

**Example**:
- Datalabs tool returning null values for 30% of queries
  - Discovered field name mismatch (funding_type vs last_funding_type)
  - Fixed by updating field mapping
  - Testing fix this week

- Team capacity: Designer on leave, frontend blocked
  - Status: Ongoing
  - Mitigation: Focusing on backend/infrastructure this week

---

## Next Week's Focus

<!-- What are you committing to ship next week? -->

**Goals for Week [X+1]**:
- [ ] [Specific deliverable 1]
- [ ] [Specific deliverable 2]
- [ ] [Specific deliverable 3]
- [ ] [Metric target]

**Example**:
- [ ] Ship external beta to 10 users
- [ ] Add caching layer (target: <15s response time)
- [ ] Write V3 design brief for Ask Mode
- [ ] Test success rate target: Maintain 95%+ with real users

---

## Phase Progress

<!-- Where are you in the overall roadmap? -->

**Phase 1: AI Infrastructure Setup** (Current Phase)
- [X] OpenAI API integration
- [X] Query routing system
- [X] Retry logic and fallbacks
- [X] Output validation
- [ ] Caching layer (next week)
- [ ] Production deployment

Overall: [X/Y] milestones complete (Z% of Phase 1)

**Example**:
Overall: 4/6 milestones complete (67% of Phase 1)
Timeline: On track for end-of-December completion

---

## Behind the Scenes

<!-- Optional: Share something interesting that didn't fit elsewhere -->

**[Interesting insight, challenge, or moment from the week]**

**Example**:
"Realized our 5-person team is actually 1.5 FE, 1 BE, 1 Designer, 1 PM + me doing product/GTM/strategy. That's why we're so resource-constrained - we're effectively a 3.5 person product team. Leaning into this constraint by building maximum automation."

---

## Call to Action

<!-- What do you want readers to do? -->

[Invitation for engagement, feedback, or collaboration]

**Examples**:
- "Testing with real users next week. If you work in VC/startup data, DM me to get early access."
- "What's your experience with query routing in LLM systems? Drop a comment."
- "Follow along for weekly V3 updates. We're building in public all the way to launch."

---

## Hashtags

#BuildInPublic #AIProducts #DatalabsV3 #ProductManagement #[Weekly theme]

---

## Pre-Publish Checklist

- [ ] Specific metrics (not vague "good progress")
- [ ] Honest about challenges (not just wins)
- [ ] Learnings are actionable (not generic)
- [ ] Next week goals are concrete
- [ ] Phase progress updated accurately
- [ ] CTA encourages engagement
- [ ] Maintains "AI Product Builder in the Trenches" voice
- [ ] Valuable to readers (not just status update)
- [ ] Grammar and formatting clean

---

## Posting Cadence

**Day**: Every Friday
**Time**: 5-7 PM IST (after week wraps up)
**Platform**: LinkedIn (primary), Twitter thread (secondary)

---

## Format Variations

### Early Phase (Setup/Foundation)
Focus on: Infrastructure, architecture decisions, tool selection

### Mid Phase (Building Features)
Focus on: Feature shipped, UX decisions, technical challenges

### Late Phase (Testing/Launch Prep)
Focus on: User feedback, metrics, iteration learnings

### Post-Launch
Focus on: Usage metrics, feature adoption, roadmap

---

## Example Week 1 Update

**Datalabs V3: Week 1 Update** 🏗️

**Shipped**:
- ✅ OpenAI API integration + cost monitoring
- ✅ Query routing architecture (3 specialized tools)
- ✅ Test suite with 30 ICP-specific queries

**Metrics**:
- Test pass rate: 28.5% (baseline)
- Avg response time: 45s
- Cost per query: $0.12
- Target: 70%+ pass rate by Week 4

**What I learned**:
1. **Single RAG approach doesn't work for diverse queries** - News queries need different handling than company data
2. **5-person team = ruthless prioritization** - Dropped 3 "nice-to-have" features to focus on core AI quality
3. **Production LLM ≠ Demo** - Test suite revealed 12 edge cases we never saw in demos

**Challenges**:
- Datalabs tool null handling (30% of queries)
- No ML expertise on team (learning as we build)

**Next week**:
- [ ] Implement retry logic + fallbacks
- [ ] Add output validation layer
- [ ] Target: 50%+ test pass rate

**Phase 1 Progress**: 3/6 milestones (50%)

Building an AI product without ML expertise is humbling. Every percentage point improvement feels earned.

What's the hardest part of building production LLM systems for you?

#BuildInPublic #AIProducts #DatalabsV3 #ProductManagement #LangChain

---

## Notes / Ideas

[Optional: Themes to explore, metrics to track, formats to try]

---

**Last Updated**: November 25, 2025
