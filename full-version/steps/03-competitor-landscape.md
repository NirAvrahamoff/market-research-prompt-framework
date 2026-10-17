# Step 3: Competitor Landscape

Maps the alternatives your customer actually chooses today, including doing nothing, and finds the gaps no one covers well.

| | |
|---|---|
| **Time** | 30 min |
| **Web browsing** | Yes |
| **You paste in** | Research Brief, Frustrations and Obstacles from Step 2, known competitors |
| **You get** | Competitor table, review complaints, positioning gaps |

## How to run it

Paste in the Frustrations and Obstacles sections from Step 2, plus any competitors you already know. Save the output as **Competitors**.

## Prompt

Copy everything in the block below. Replace every `[BRACKET]` with your own content.

```text
# Role
You are a competitive intelligence analyst.

# Goal
Map the alternatives our ideal customer uses today and find the gaps we can win on.

# Research Brief
[PASTE RESEARCH BRIEF]

# Voice of Customer (Frustrations and Obstacles only)
[PASTE FROM STEP 2]

# Known competitors
[LIST, or "find them"]

# Task
1. Identify up to 8 alternatives in three groups: direct competitors, indirect substitutes (a different kind of solution to the same problem), and the do-nothing or DIY option.
2. For each alternative, read its website, pricing page and public reviews.
3. Fill the table below. Every price needs a link and the date you saw it.
4. From reviews, collect up to 3 complaints per competitor, quoted exactly, with links.
5. Compare these complaints with our customers' frustrations and name the gaps no competitor covers well.

# Rules
- If pricing is not public, write "Not public". Do not estimate.
- Mark any judgement that is not a direct fact as [Inference].

# Output
COMPETITOR TABLE:
| Name | Type (direct / substitute / DIY) | Target customer | Core promise (their words) | Pricing (link, date) | Main strength | Main complaint |

REVIEW COMPLAINTS: per competitor, quotes with links.
POSITIONING GAPS: three to five gaps, each with its evidence and a confidence of High, Medium or Low.
GAPS IN THIS RESEARCH: what you could not find.
```

## Tip

The most dangerous competitor is often the spreadsheet, the agency or the habit your customer already has. Do not skip the DIY row.

---

[← Step 2: Voice of Customer](02-voice-of-customer.md) · [Step 4: Awareness Levels and Desires →](04-awareness-levels-and-desires.md)
