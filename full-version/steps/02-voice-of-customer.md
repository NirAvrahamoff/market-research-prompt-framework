# Step 2: Voice of Customer

Collects real quotes, with links, from people who match your ideal customer, and builds the persona only from what they said.

| | |
|---|---|
| **Time** | 30-60 min |
| **Web browsing** | Yes (deep research mode) |
| **You paste in** | Research Brief, list of sources where your customers talk |
| **You get** | Voice of Customer file: quotes by category and theme, persona sketch, gaps |

## How to run it

Switch to a deep research mode. Fill in the brackets, including the sources that fit your market (see [Choosing sources](../README.md#choosing-sources)). If some of your customers talk in private groups or on login-only sites, collect a few posts by hand and paste them into the optional slot. Save the output as **Voice of Customer**.

## Prompt

Copy everything in the block below. Replace every `[BRACKET]` with your own content.

```text
# Role
You are a voice-of-customer researcher. Your job is to find what real people say, in their own words, and never to write words for them.

# Goal
Collect verbatim quotes from people who match the ideal customer, grouped by theme, so that later messaging uses the market's own language.

# Research Brief
[PASTE RESEARCH BRIEF]

# Sources
Search these places first: [SOURCES, e.g. r/xyz, a G2 category page, Amazon reviews of competitor products, public forums]
You may add other public sources where this audience talks. Prefer posts from the last 12 months. Today's date is [DATE].

# Material I collected myself (optional)
[PASTE POSTS FROM PRIVATE GROUPS OR LOGIN-ONLY SITES, each with its link]

# Task
1. List the sources you searched and roughly how much relevant material each had.
2. Collect quotes in these six categories:
   Identity: how they describe themselves and their situation
   Fears: what they worry will happen
   Frustrations: what annoys them now, including current solutions
   Desires: what they want to have or become
   Beliefs: what they think is true about the problem or the market
   Obstacles: what stops them from getting what they want
3. Inside each category, group quotes into themes. Under each theme write one Note line that sums up the pattern.
4. Write a five-to-six sentence persona sketch built only from the quotes.

# Rules
- Copy every quote exactly as written, including slang, typos and punctuation.
- Keep quotes in their original language. If a quote is not in English, add an English translation in brackets after it.
- Every quote needs a direct link to the post or review, plus its date. Drop any quote without a link.
- Do not paraphrase, merge or tidy quotes. A summary is a Note, not a quote.
- There is no quota. Aim for 8 to 15 quotes per category, but stop when real material runs out and say so.
- If a category has fewer than 3 real quotes, write "Thin evidence" under it instead of filling it.

# Output
SOURCES SEARCHED: a short list.
Per category, each theme as: Theme: [name] / "Exact quote" (source, date, link) / Note: [pattern]
PERSONA SKETCH: five to six sentences.
GAPS: thin categories, sources you could not access, and audiences these sources may miss.
```

## Tip

Run it in two different research tools and merge the results. A quote both tools found is one you can trust.

---

[← Step 1: Research Brief](01-research-brief.md) · [Step 3: Competitor Landscape →](03-competitor-landscape.md)
