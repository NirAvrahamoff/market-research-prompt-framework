# Step 5: Feature-to-Benefit Ladder

Translates every real product feature into benefits and ties each one to a proven customer desire. Shows which features to lead with and which ones the market does not care about.

| | |
|---|---|
| **Time** | 15 min |
| **Web browsing** | Yes |
| **You paste in** | Research Brief, product pages, desire ladder table from Step 4 |
| **You get** | Ranked feature table, lead features, orphan features |

## How to run it

Add the URLs of the product pages, docs or demo videos, and paste the desire ladder table from Step 4. Save the output as **Feature to Benefit**.

## Prompt

Copy everything in the block below. Replace every `[BRACKET]` with your own content.

```text
# Role
You are a product marketer who translates features into benefits customers care about.

# Goal
Build a table that runs from each real product feature to the customer desire it serves, and flag features that serve no proven desire.

# Research Brief
[PASTE RESEARCH BRIEF]

# Product sources
[URLs of product pages, docs, spec sheets, demo videos]

# Desires from Step 4
[PASTE DESIRE LADDER TABLE]

# Task
1. Read the product sources and list every concrete feature in the product's own wording. Add no benefit language yet.
2. For each feature, fill the ladder:
   a. Why it exists, in plain language
   b. Benefit: "so you can..."
   c. Benefit of the benefit: "so you can..." again
   d. Dominant emotion when that payoff is reached
   e. Matching desire from Step 4, or "None found"
3. Rank the features by how strongly they connect to desires with solid evidence.

# Rules
- Never invent specs. If a detail is unclear, write "Unclear" and link the page you checked.
- A feature that maps to "None found" is a finding, not a failure. Keep it in the table.

# Output
| Rank | Feature | Why it exists | Benefit (so you can...) | Benefit of the benefit | Dominant emotion | Matching desire | Source link |

LEAD FEATURES: the top three to lead messaging with, and why.
ORPHAN FEATURES: features with no matching desire.
```

## Tip

Orphan features are a gift for the product team. A feature nobody desires is either badly explained or not worth building further, and both are worth knowing.

---

[← Step 4: Awareness Levels and Desires](04-awareness-levels-and-desires.md) · [Step 6: Market Sizing Sanity Check →](06-market-sizing-sanity-check.md)
