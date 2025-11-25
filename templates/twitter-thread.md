# Twitter Thread Template

---

## Thread Hook (Tweet 1/10)
<!-- Make them want to read the whole thread. Bold claim, surprising stat, or intriguing question -->

[Your hook tweet - max 280 chars]

Example: "We hit 100% success rate in our AI Q&A system with a 5-person team and no ML expertise. Here's the exact architecture we used (with code)🧵"

---

## Context Setup (Tweet 2/10)
<!-- Set the scene. What's the background? -->

[Context tweet - explain the situation]

Example: "6 months ago: 28.5% pass rate. Today: 100%. The difference? We stopped trying to make one LLM do everything."

---

## Main Point #1 (Tweet 3/10)
<!-- First key insight -->

[Main point with specifics]

Example: "Insight #1: Intelligent query routing. We built 3 specialized tools instead of one generic RAG:
- Inc42 Context (historical)
- Inc42 Updates (recent news)
- Datalabs (structured data)

Result: 60% improvement in relevance."

---

## Main Point #2 (Tweet 4/10)
<!-- Second key insight -->

[Main point with specifics]

Example: "Insight #2: Retry logic + fallbacks. Every query gets 3 attempts per tool. If all fail, we fall back to a backup tool.

This eliminated 90% of our 'I don't know' responses."

---

## Main Point #3 (Tweet 5/10)
<!-- Third key insight -->

[Main point with specifics]

Example: "Insight #3: Output validation before returning results. We enforce JSON schema validation + null handling + format checking.

Catches malformed responses before they reach users."

---

## Main Point #4 (Tweet 6/10)
<!-- Fourth key insight - optional depending on topic -->

[Main point with specifics]

Example: "The stack:
• n8n for workflow orchestration
• LangChain for agent logic
• OpenAI GPT-4o-mini
• Elasticsearch for structured queries
• Vector search for semantic matching

Total cost: ~$200/month"

---

## Main Point #5 (Tweet 7/10)
<!-- Fifth key insight - optional -->

[Main point with specifics]

Example: "What didn't work:
• Complex chains (too many failure points)
• Single prompt approach (couldn't handle variety)
• No retries (LLMs are probabilistic, one shot isn't enough)"

---

## Supporting Detail (Tweet 8/10)
<!-- Additional context, code snippet, or example -->

[Supporting detail or example]

Example: "Here's our query routing logic in pseudocode:

```
if (recent_news_query):
  tool = Inc42Updates
elif (company_data):
  tool = Datalabs
else:
  tool = Inc42Context

retry(tool, attempts=3, fallback=Inc42Context)
```"

---

## Key Takeaway (Tweet 9/10)
<!-- The main lesson or actionable insight -->

[What should readers remember?]

Example: "Key takeaway: Production LLM systems need specialization, not generalization.

3 specialized tools > 1 generic tool
Retry logic > hoping it works first time
Output validation > trusting LLM outputs blindly"

---

## Summary + CTA (Tweet 10/10)
<!-- Recap and call to action -->

[Summary in 1-2 lines + what you want them to do]

Example: "Recap: We went from 28.5% to 100% success rate with query routing, retries, and validation.

Building AI products with constraints? Follow @[username] for more production LLM lessons.

Questions? Drop a reply 👇"

---

## Pre-Publish Checklist

- [ ] Hook tweet is compelling (bold claim, stat, or question)
- [ ] Thread has clear structure (setup → insights → takeaway)
- [ ] Each tweet stands alone but flows to next
- [ ] Specific metrics or examples in each tweet
- [ ] Aligns with one of the 4 content pillars
- [ ] Under 280 characters per tweet
- [ ] CTA in final tweet (follow, reply, DM)
- [ ] Hashtags minimal (1-2 max, or none)
- [ ] Target audience will find valuable
- [ ] Grammar checked

---

## Content Pillar

Which pillar does this align with?
- [ ] AI Product Building
- [ ] Scrappy GTM Strategy
- [ ] Building in Public
- [ ] Startup Intelligence

---

## Target Audience

Who is this for?
- [ ] AI/Product Builders
- [ ] Startup Founders
- [ ] GTM/Growth Professionals
- [ ] Investors & VCs

---

## Thread Length Guide

- **Quick thread**: 5-6 tweets (single insight with examples)
- **Standard thread**: 8-10 tweets (multiple insights)
- **Deep dive**: 12-15 tweets (comprehensive tutorial)

---

## Threading Tips

1. **Numbering**: Use "1/10", "2/10" format for clarity
2. **One idea per tweet**: Don't cram multiple points
3. **Visual breaks**: Use bullet points, code blocks, emojis (sparingly)
4. **Hook diversity**: Stats, questions, bold statements
5. **CTA placement**: Always in final tweet
6. **Engagement**: Ask questions, invite replies
7. **Formatting**: Line breaks for readability

---

## Example Thread Structures

### Technical Deep-Dive
1. Hook (surprising result)
2. Context (the problem)
3. Solution part 1
4. Solution part 2
5. Solution part 3
6. Code example
7. What didn't work
8. Key metrics
9. Takeaway
10. CTA

### Scrappy Strategy
1. Hook (budget vs result contrast)
2. The constraint
3. Tactic 1 (with tool/cost)
4. Tactic 2 (with tool/cost)
5. Tactic 3 (with tool/cost)
6. Results (metrics)
7. What surprised us
8. Key lesson
9. Summary
10. CTA

### Building in Public
1. Hook (milestone or metric)
2. Where we started
3. What we shipped this week
4. Challenge we faced
5. How we solved it
6. Unexpected learning
7. Metrics/results
8. Next week's focus
9. Biggest takeaway
10. CTA

---

## Notes / Ideas

[Optional: Alternate angles, future threads, related topics]

---

**Last Updated**: November 25, 2025
