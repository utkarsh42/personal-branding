# Personal Branding

**Content creation & publishing for building a personal brand as an AI Product Builder**

---

## Quick Start

```bash
# Create new LinkedIn post
cp templates/linkedin-post.md content/linkedin/drafts/YYYY-MM-DD-topic-name.md

# Create new Twitter thread
cp templates/twitter-thread.md content/twitter/threads/YYYY-MM-DD-topic-name.md

# Create weekly building-in-public update
cp templates/building-in-public.md content/linkedin/drafts/YYYY-MM-DD-bip-week-X.md
```

---

## Positioning

> **AI Product Builder in the Trenches**
>
> Building production AI systems at Inc42 (Ask Inc42, Datalabs V3) with full-stack execution, constraint-driven innovation, and transparent building in public.

**For**: AI/Product builders, Startup founders, GTM professionals, Investors

---

## Active Priorities

| Priority | Task | Status |
|----------|------|--------|
| P0 | Weekly Building-in-Public posts (Fridays) | 🟢 Active |
| P1 | LinkedIn content: 3-4 posts/week | 🟢 Active |
| P1 | Twitter threads: 2-3/week | 🟡 Ramping |
| P2 | Content pillar distribution balance | 🟡 Monitoring |

---

## Key Milestones

| Milestone | Target | Status |
|-----------|--------|--------|
| **First 1,000 LinkedIn followers** | Q1 2026 | 🔴 Not started |
| **Building-in-Public streak** | 8 weeks consecutive | 🔴 Not started |
| **Twitter 500 followers** | Q2 2026 | 🔴 Not started |
| **First viral post (10K+ views)** | Q1 2026 | 🔴 Not started |

---

## Blockers & Risks

| Risk | Impact | Mitigation |
|------|--------|------------|
| **Consistency** | Content gaps hurt growth | Batch creation, content calendar |
| **Time constraints** | Product work takes priority | Protected content blocks |
| **Pillar imbalance** | Over-indexing on one topic | Monthly pillar audit |

---

## Folder Structure

```
personal-branding/
├── content/
│   ├── linkedin/          # LinkedIn posts
│   │   ├── drafts/        # Work in progress
│   │   ├── scheduled/     # Ready to publish
│   │   └── published/     # Archive with YYYY-MM-DD prefix
│   ├── twitter/           # Twitter/X content
│   │   ├── threads/       # Thread drafts
│   │   ├── daily/         # Daily insights
│   │   └── published/     # Archive
│   └── ideas/
│       └── content-ideas.md  # Running idea list
├── templates/             # Copy these when starting new content
│   ├── linkedin-post.md
│   ├── linkedin-carousel.md
│   ├── twitter-thread.md
│   └── building-in-public.md
├── strategy/              # Core positioning and themes
│   ├── positioning.md     # Bios, elevator pitch
│   ├── content-pillars.md # 4 core content themes
│   └── target-audience.md # ICP definitions
├── calendar/              # Content planning
│   ├── content-calendar.md      # Monthly calendar
│   └── publishing-schedule.md   # Posting cadence
└── assets/                # Supporting materials
    ├── images/            # Visuals, screenshots
    └── metrics/           # Performance tracking
```

---

## Content Workflow

### 1. Ideation
Add ideas to `content/ideas/content-ideas.md` as you encounter them

### 2. Planning
Update `calendar/content-calendar.md` with planned content for the month

### 3. Drafting
```bash
# Use template for the content type
cp templates/linkedin-post.md content/linkedin/drafts/2025-11-26-rag-systems.md

# Write content
# Save frequently
```

### 4. Review
- Check alignment with content pillars
- Verify positioning reinforcement
- Run through quality checklist (see CLAUDE.md)

### 5. Schedule
```bash
# Move to scheduled when ready
mv content/linkedin/drafts/2025-11-26-rag-systems.md \
   content/linkedin/scheduled/2025-11-26-rag-systems.md
```

### 6. Publish
```bash
# Post to platform
# Move to published archive
mv content/linkedin/scheduled/2025-11-26-rag-systems.md \
   content/linkedin/published/2025-11-26-rag-systems.md

# Commit
git add content/
git commit -m "publish: LinkedIn post - Building RAG systems with n8n"
git push
```

---

## Content Pillars

1. **AI Product Building** - RAG systems, LangChain, n8n, production LLM systems
2. **Scrappy GTM Strategy** - $500/month GTM stack, multi-ICP, PLG + AI outbound
3. **Building in Public** - Datalabs V3 journey, transparent metrics and learnings
4. **Startup Intelligence** - India ecosystem, funding data, market insights

---

## Publishing Cadence

### LinkedIn
- **Posts**: 3-4x/week (Mon, Wed, Fri, Sun)
- **Building in Public**: Every Friday
- **Best times**: 9-11 AM IST, 5-7 PM IST

### Twitter/X
- **Threads**: 2-3x/week
- **Daily insights**: 1-2x/day
- **Best times**: 8-10 AM IST, 1-3 PM IST, 6-8 PM IST

---

## Using Templates

### LinkedIn Post Template
- Hook (first line that stops scrolling)
- Story/Context (setup the situation)
- Key insights (3-5 bullets with specifics)
- Call to action (what do you want reader to do?)
- Hashtags (3-5 relevant tags)

### Twitter Thread Template
- Hook tweet (make them want to read more)
- Main points (6-8 tweets with one idea each)
- Summary + CTA (recap and call to action)

### Building in Public Template
- What shipped this week
- Key metrics (be specific)
- What I learned
- Next week's focus

---

## Examples from Your Work

**LinkedIn Post Ideas**:
- "How we achieved 100% success rate in our AI Q&A system"
- "Building a $500/month GTM stack that competes with $100M+ competitors"
- "30-second aha moment: Designing AI product onboarding that converts"

**Twitter Thread Ideas**:
- "5 lessons from shipping production LLM systems with a 5-person team"
- "Query routing in multi-tool AI systems: A thread"
- "How I sized the $39M Indian startup intelligence market (detailed methodology)"

**Building in Public Updates**:
- Weekly Datalabs V3 progress
- Ask Inc42 optimization results (OPT-025 → OPT-030)
- GTM experiment results

---

## Metrics to Track

**LinkedIn**:
- Views per post
- Engagement rate (likes + comments + shares / views)
- Profile visits
- Follower growth

**Twitter**:
- Impressions per tweet/thread
- Engagement rate
- Profile visits
- Follower growth

**Monthly Review**:
- Best performing posts by pillar
- Topics that resonated
- Follower growth trends
- Engagement trends

---

## Tips for Success

1. **Be specific with metrics** - "100% success rate" not "very successful"
2. **Show your work** - Code snippets, screenshots, actual workflows
3. **Stay authentic** - Real challenges, real learnings, real metrics
4. **Build in public** - Share the V3 transformation journey transparently
5. **Engage authentically** - Comment on 10 relevant posts daily
6. **Batch create** - Draft multiple posts at once, schedule throughout week
7. **Repurpose** - Twitter thread → LinkedIn post → Blog article

---

## Resources

- **Strategy**: See `strategy/` folder for positioning and content pillars
- **Calendar**: Check `calendar/content-calendar.md` for monthly plan
- **Ideas**: Browse `content/ideas/content-ideas.md` for inspiration
- **Templates**: All in `templates/` folder
- **Operating Guide**: See `CLAUDE.md` for detailed workflow

---

**Last Updated**: 2026-01-05
