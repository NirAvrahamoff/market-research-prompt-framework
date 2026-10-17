# Step 7: Validate Before You Use It

A second AI can catch weak reasoning, but it cannot confirm that a quote or a number is real. Validation therefore has three layers, and the first one is done by hand.

| | |
|---|---|
| **Time** | About 1 hour, plus customer calls |
| **Web browsing** | Partly (you open links yourself) |
| **You paste in** | The full research file from Steps 1 to 6 |
| **You get** | Evidence ratings, a list of weak claims, and corrections from real customers |

## 7a. Quote audit (by hand, about 20 minutes)

Open 10 random quote links from Step 2 and 5 from Step 3. For each one, check that the post exists, that the wording matches exactly, and that the author plausibly fits the persona.

| Link | Exists | Wording matches | Fits persona |
|---|---|---|---|
| | | | |

If more than 2 of the 15 fail, treat the whole quote set as unreliable and rerun Step 2 with a different tool or narrower sources.

## 7b. Cross-model critique

Open a fresh session in a **different** AI tool from the one you used for the research, paste the full file, and run:

```text
# Role
You are a skeptical research reviewer. Your job is to find what is wrong or unsupported, not to praise.

# Material
[PASTE FULL RESEARCH FILE]

# Task
1. List the five claims in this file that a decision would rest on most heavily.
2. For each, rate the evidence as Strong, Moderate or Weak, and say why.
3. Find contradictions between steps (for example, a desire in Step 4 that the Step 2 quotes do not support).
4. Name customer segments or sources the research likely missed, given the sources used.
5. Give one alternative interpretation of the customer's core problem that fits the same evidence.

# Rules
Be specific: name the step and the item. Skip generic advice such as "do more research".

# Output
KEY CLAIMS TABLE: | Claim | Step | Evidence rating | Reason |
CONTRADICTIONS
MISSING SEGMENTS OR SOURCES
ALTERNATIVE INTERPRETATION
```

## 7c. Five customer conversations

Take the claims rated Weak in 7b and the top three positioning gaps from Step 3. Turn them into open questions and talk to five people who match the persona. Where the conversations contradict the AI research, believe the conversations and update the file.

## Why this step matters

AI research tools are fast and confident, and both qualities hide mistakes. Most of the value of Steps 1 to 6 depends on the evidence being real, and this is the only step that checks it against the world rather than against another model.

---

[← Step 6: Market Sizing Sanity Check](06-market-sizing-sanity-check.md) · [Step 8: Build Assets →](08-build-assets.md)
