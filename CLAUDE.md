# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

**Personal Branding** - Content creation & publishing workspace for building a personal brand as an AI Product Builder.

This is a standalone git repository within the parent `aiworkspace` workspace. All commits here go to the `personal-branding` repository, not the parent workspace.

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

## Quick Commands

### Create New Content
```bash
# LinkedIn post (use YYYY-MM-DD-topic-name.md naming convention)
cp templates/linkedin-post.md content/linkedin/drafts/2025-12-12-rag-systems.md

# Twitter thread
cp templates/twitter-thread.md content/twitter/threads/2025-12-12-llm-lessons.md

# LinkedIn carousel
cp templates/linkedin-carousel.md content/linkedin/drafts/2025-12-12-gtm-stack.md

# Weekly building-in-public update (use week number)
cp templates/building-in-public.md content/linkedin/drafts/2025-12-12-bip-week-1.md
```

### Move Content Through Workflow
```bash
# Schedule content (ready to publish)
mv content/linkedin/drafts/2025-12-12-rag-systems.md content/linkedin/scheduled/

# Archive after publishing
mv content/linkedin/scheduled/2025-12-12-rag-systems.md content/linkedin/published/

# Commit and push
git add content/ && git commit -m "publish: LinkedIn post - Building RAG systems" && git push
```

### Review Content
```bash
# Check what's drafted
ls -lt content/linkedin/drafts/

# Check what's scheduled
ls -lt content/linkedin/scheduled/

# Check monthly calendar
cat calendar/content-calendar.md

# Check content ideas
cat content/ideas/content-ideas.md
```

## Content Workflow

### Creating New Content

1. **Generate idea** → Add to `content/ideas/content-ideas.md`
2. **Plan in calendar** → Update `calendar/content-calendar.md`
3. **Draft** → Copy template from `templates/`, save to `content/{platform}/drafts/` with date prefix
4. **Review** → Edit, refine, run through quality checklist
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

## Repository Architecture

### Content State Machine
Content flows through three states:
- **drafts/** - Work in progress, iterate freely
- **scheduled/** - Reviewed, ready to publish (final state before going live)
- **published/** - Archive of posted content with YYYY-MM-DD prefix

### File Naming Convention
Always use `YYYY-MM-DD-topic-name.md` format:
- `2025-12-12-rag-systems.md` - LinkedIn post about RAG systems
- `2025-12-12-bip-week-1.md` - Building in public week 1 update
- `2025-12-12-gtm-stack.md` - GTM strategy post

This allows chronological sorting and prevents filename conflicts.

### Templates as Starting Points
Templates in `templates/` are complete with:
- Structure and section headers
- Inline guidance comments
- Pre-publish checklist
- Example content

Always copy (not move) templates to preserve originals.

## File Organization

```
content/
├── linkedin/
│   ├── drafts/           # Work in progress
│   ├── scheduled/        # Ready to publish
│   └── published/        # Archive with YYYY-MM-DD-topic.md
├── twitter/
│   ├── threads/          # Full thread drafts
│   ├── daily/            # Quick daily insights
│   └── published/        # Archive with dates
└── ideas/
    └── content-ideas.md  # Running idea list (add ideas as you get them)

templates/                # Copy to drafts when starting new content
├── linkedin-post.md      # Standard LinkedIn post (1000-1500 words)
├── linkedin-carousel.md  # Multi-slide LinkedIn post
├── twitter-thread.md     # Twitter thread (8-10 tweets)
└── building-in-public.md # Weekly Friday update format

strategy/                 # Core positioning and messaging
├── positioning.md        # Bios, elevator pitches, differentiators
├── content-pillars.md    # 4 content themes with examples
└── target-audience.md    # ICP definitions

calendar/                 # Content planning and scheduling
├── content-calendar.md   # Monthly content plan
└── publishing-schedule.md # Posting cadence and best times

assets/                   # Supporting materials
├── images/              # Screenshots, diagrams, visuals
└── metrics/             # Performance tracking data
```

## Git Workflow

```bash
# Always start with pull
git pull

# Working on content (drafts and calendar updates)
git add content/ calendar/
git commit -m "content: draft LinkedIn post on RAG systems"
git push

# When publishing (move to published and commit)
git add content/
git commit -m "publish: LinkedIn post - Building RAG systems"
git push

# When updating strategy or templates
git add strategy/ templates/
git commit -m "docs: update content pillars with new examples"
git push
```

**Commit Message Conventions**:
- `content:` - Drafting or editing content
- `publish:` - Publishing content to platform
- `docs:` - Updates to strategy, templates, or documentation
- `calendar:` - Content calendar updates

## Quality Checklist

Before moving to `scheduled/` or publishing, verify:

**Content Quality**:
- [ ] Aligns with one of the 4 content pillars (AI Product, GTM, Building in Public, Startup Intelligence)
- [ ] Reinforces positioning as "AI Product Builder in the Trenches"
- [ ] Includes concrete examples or metrics from your work (not vague statements)
- [ ] Shows, doesn't just tell (code snippets, screenshots, actual workflows)
- [ ] Stay authentic - real challenges, not just successes

**Structure & Engagement**:
- [ ] Strong hook (first 1-2 lines stop scrolling)
- [ ] Clear narrative arc (problem → solution → learning)
- [ ] 3-5 specific, actionable insights
- [ ] Clear call-to-action that encourages engagement
- [ ] Appropriate length (LinkedIn: 1000-1500 words; Twitter: 8-10 tweets)

**Technical Details**:
- [ ] Grammar and formatting are clean
- [ ] Links work and are relevant
- [ ] Hashtags are specific, not generic (max 5)
- [ ] File named with YYYY-MM-DD-topic format
- [ ] Targets the right audience (check strategy/target-audience.md)

## Metrics to Track

In `assets/metrics/`:
- LinkedIn: Views, engagement rate, comments, shares
- Twitter: Impressions, engagement rate, profile visits, followers
- Monthly: Best performing posts, topics, formats
- Quarterly: Follower growth, content pillar distribution

## Publishing Cadence & Best Times

### LinkedIn
- **Frequency**: 3-4x per week (Monday, Wednesday, Friday, Sunday)
- **Building in Public**: Every Friday
- **Best times**:
  - Morning: 9-11 AM IST (office start)
  - Evening: 6 PM IST (optimal - commute/evening scroll)

### Twitter/X
- **Threads**: 2-3x per week (Monday mornings at 10 AM IST)
- **Daily insights**: 1-2x per day
  - Morning: 8-9 AM IST
  - Afternoon: 1-2 PM IST
  - Evening: 6-7 PM IST

See `calendar/publishing-schedule.md` for detailed schedule.

## Common Workflows

### Start New Week
```bash
# Review calendar for the week
cat calendar/content-calendar.md

# Check what's in drafts
ls -lt content/linkedin/drafts/

# Create this week's building-in-public update (every Friday)
cp templates/building-in-public.md content/linkedin/drafts/$(date +%Y-%m-%d)-bip-week-X.md
```

### Daily Content Creation Session
```bash
# Check ideas for inspiration
cat content/ideas/content-ideas.md

# Create new draft from template
cp templates/linkedin-post.md content/linkedin/drafts/$(date +%Y-%m-%d)-topic-name.md

# Edit the draft
# Run through quality checklist when done
# Move to scheduled/ when ready
```

### Publishing Day
```bash
# Review what's scheduled
ls -lt content/linkedin/scheduled/

# After posting to LinkedIn/Twitter, archive it
mv content/linkedin/scheduled/2025-12-12-topic.md content/linkedin/published/

# Commit
git add content/ && git commit -m "publish: LinkedIn post - Topic name" && git push
```

### Monthly Planning
```bash
# Review last month's calendar
cat calendar/content-calendar.md

# Check which pillars need more coverage
# - AI Product Building: 37%
# - Scrappy GTM: 31%
# - Building in Public: 25%
# - Startup Intelligence: 19%

# Update calendar for next month
# Add new ideas to content-ideas.md
```

## Critical Rules

1. **Stay authentic** - Share real metrics, real challenges, real learnings (not just wins)
2. **Be specific** - "100% success rate" not "very successful"
3. **Show, don't tell** - Code snippets, screenshots, actual workflows, real examples
4. **Build in public** - Transparent about V3 journey, optimizations, failures, constraints
5. **Respect positioning** - Every post should reinforce "AI Product Builder in the Trenches"
6. **File naming** - Always use YYYY-MM-DD-topic-name.md format
7. **Template preservation** - Copy templates, never move them
8. **Check before scheduling** - Run through quality checklist before moving to scheduled/
