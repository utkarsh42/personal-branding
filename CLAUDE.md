# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

**Personal Branding** - Content creation & publishing for building a personal brand as an AI Product Builder.

## Positioning

**Core Identity**: AI Product Builder in the Trenches
- Building production AI systems at Inc42 (Ask Inc42, Datalabs V3)
- Full-stack execution: Product + GTM + Business + Technical
- Constraint-driven innovation: Small team, tight budget, no ML expertise
- Focus: Indian startup intelligence ecosystem

**Target Audience**:
- AI/Product builders
- Startup founders
- GTM/Growth professionals
- Investors interested in AI products

## Content Workflow

### Creating New Content

1. **Generate idea** → Add to `content/ideas/content-ideas.md`
2. **Plan in calendar** → Update `calendar/content-calendar.md`
3. **Draft** → Use template from `templates/`, save to `content/{platform}/drafts/`
4. **Review** → Edit, refine, check positioning alignment
5. **Schedule** → Move to `content/{platform}/scheduled/`
6. **Publish** → Post to platform, move to `content/{platform}/published/`

### Using Templates

**LinkedIn Post**: `templates/linkedin-post.md`
- Hook, story, insights, CTA, hashtags
- Target: 1,000-1,500 words
- Cadence: 3-4x/week

**Twitter Thread**: `templates/twitter-thread.md`
- Hook tweet, main points (6-8 tweets), summary + CTA
- Target: 8-10 tweets
- Cadence: 2-3x/week

**Building in Public**: `templates/building-in-public.md`
- Weekly update format
- What shipped, metrics, learnings, next focus
- Cadence: Weekly on Fridays

## Content Pillars

1. **AI Product Building** - Technical deep-dives, RAG systems, LangChain, n8n
2. **Scrappy GTM Strategy** - $500/month stack, multi-ICP, PLG + AI outbound
3. **Building in Public** - Datalabs V3 journey, metrics, transparent learnings
4. **Startup Intelligence** - India ecosystem insights, funding data, market analysis

## File Organization

```
content/
├── linkedin/
│   ├── drafts/           # Work in progress
│   ├── scheduled/        # Ready to publish
│   └── published/        # Archive with dates
├── twitter/
│   ├── threads/          # Full thread drafts
│   ├── daily/            # Quick insights
│   └── published/        # Archive with dates
└── ideas/
    └── content-ideas.md  # Running idea list

templates/                # Copy to drafts when starting new content
strategy/                 # Positioning, pillars, audience definitions
calendar/                 # Monthly planning and scheduling
assets/                   # Images, screenshots, metrics
```

## Git Workflow

```bash
# Daily workflow
git pull                              # Get latest
# ... create/edit content ...
git add content/ calendar/
git commit -m "content: add LinkedIn post on RAG systems"
git push

# When publishing
git add content/{platform}/published/
git commit -m "publish: LinkedIn post - Building RAG systems"
git push
```

## Quality Checklist

Before publishing, verify:
- [ ] Aligns with one of the 4 content pillars
- [ ] Reinforces positioning as "AI Product Builder in the Trenches"
- [ ] Includes concrete examples or metrics from your work
- [ ] Has clear hook and call-to-action
- [ ] Targets the right audience (AI builders, founders, GTM professionals)
- [ ] Grammar and formatting are clean
- [ ] Links work and are relevant

## Metrics to Track

In `assets/metrics/`:
- LinkedIn: Views, engagement rate, comments, shares
- Twitter: Impressions, engagement rate, profile visits, followers
- Monthly: Best performing posts, topics, formats
- Quarterly: Follower growth, content pillar distribution

## Critical Rules

1. **Stay authentic** - Share real metrics, real challenges, real learnings
2. **Be specific** - "100% success rate" not "very successful"
3. **Show, don't tell** - Code snippets, screenshots, actual workflows
4. **Build in public** - Transparent about V3 journey, optimizations, failures
5. **Respect positioning** - Every post should reinforce "AI Product Builder in the Trenches"
