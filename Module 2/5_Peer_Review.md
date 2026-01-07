# Part 5: Peer Review - Help Your Teammate Succeed

![Hero Image](assets/part5-hero.png)

## Why Peer Review Matters

**The Reality**: The best engineers give and receive feedback constantly.

**In This Course**: Peer review isn't optional. It's how you:
- Catch problems before you build
- Learn from others' approaches
- Practice professional communication
- Build your network

*Not doing peer review = -2 points. Don't skip this.*

## Finding Your Review Partner

**Timeline**:
- By September 24: Connect with ONE person on your team
- By September 26: Complete reviews

**How to Connect**:
- Check Canvas for your assigned team
- Reach out via Slack or email
- Exchange Figma board links
- Schedule time to review (don't wait until last minute)

## What to Review

![Review Process Image](assets/part5-review.png)

Leave THREE comments on their Figma board:

### 1. One Strength

What's working well in their PRD or architecture?

❌ **Generic**: "Looks good!"  
✅ **Specific**: "Your problem statement is strong—the quantified time savings (10-15 hours/week) immediately shows business value. The HubSpot research citation adds credibility."

### 2. One Technical Suggestion

How could their agent design or n8n flow improve?  

❌ **Vague**: "Maybe add more features?"  
✅ **Specific**: "Your agent architecture could benefit from error handling. What happens if the Twitter API rate limit hits? Consider adding a retry queue agent that stores failed requests and processes them when the rate limit resets."

**Another Example**: "Your Content Adapter has three separate OpenAI calls (one per platform). That's expensive and slow. Consider batching—send one request asking for all three versions in a single JSON response. Cuts cost by 66% and makes it 3x faster."

### 3. One Scope Check

Is their Week 3 build realistic?

❌ **Generic**: "Seems fine"  
✅ **Honest**: "You have 5 different API integrations in your MVP (Twitter, LinkedIn, Instagram, Facebook, TikTok). That's ambitious for Week 3. Consider starting with just Twitter + LinkedIn (easiest APIs, best documentation), then adding the others in Assignment 4 after you have the core working."

**Another Example**: "Your synthetic persona generator plans to process interview transcripts, surveys, AND support tickets. For Week 3 MVP, pick ONE data source (surveys are easiest—structured data). Add the others in Week 4 once you've proven the concept."

## Comment Format

![Comment Format Image](assets/part5-comments.png)

Start with your name:

`"[Your Name] - Your agent architecture is clear, but consider batching the OpenAI calls to reduce cost and latency."`

**Why**: Makes it easy to track who said what, professional habit.

## Completion Proof

![Completion Proof Image](assets/part5-proof.png)

**Required**: Screenshot your comments on their board.
**Include in Canvas submission**: Show you actually did this.

**What to capture**:
- Your comments visible
- Your name in comments
- The Figma board they're on
- Timestamp/date
---

| [← Part 4: Technical Architecture](./4_Technical_Architecture.md) | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |  |
|:---|:---:|---:|