# Quick Version: One Prompt

A single prompt for a research agent that runs a condensed version of the framework in one session: brief, voice of customer, competitors, messaging and positioning.

| | |
|---|---|
| **Time** | 20 to 30 minutes |
| **Web browsing** | Yes (deep research or agent mode) |
| **You paste in** | Company website, competitors if known, where your customers talk |
| **You get** | A one-page report with quotes, a competitor table, desires matched to features, and a positioning draft |

## When to use it

- A first look at a market before deciding whether to invest more time.
- Preparing for a meeting with a founder or a prospect at short notice.
- Testing whether the sources you picked actually contain useful customer talk before running the full framework.

## Prompt

Copy everything in the block below. Replace every `[BRACKET]` with your own content.

```text
# Role
You are a market research analyst working for an early-stage startup. You find what real customers say and never write words for them.

# Goal
Produce a one-session market research report: who the customer is, what they say in their own words, who we compete with, and what we should lead with.

# Inputs
Company website: [URL]
Known competitors (optional): [NAMES OR URLs]
Target geography and language: [e.g. US English, Israel Hebrew]
Where our customers talk: [SOURCES, e.g. subreddits, G2 category, Amazon reviews, app store pages]
Today's date: [DATE]

# Task
Work through these stages in order and use what you learn in each one in the next.
1. Brief: from the website, describe the ideal customer, the product and the problems it solves.
2. Voice of customer: search the sources above and collect verbatim quotes in four categories: Fears, Frustrations, Desires, Obstacles. Aim for 5 to 8 per category.
3. Competitors: identify up to 5 alternatives, including the do-nothing option, with their core promise, pricing and main complaint from reviews.
4. Messaging: list the five strongest desires, ladder each one with "so I can..." twice, and match the product's top features to them.
5. Positioning: write one positioning statement and three homepage headline options.

# Rules
- Copy every quote exactly, with a direct link and date. Drop any quote you cannot link.
- Keep quotes in their original language and add an English translation in brackets if needed.
- No quotas. If evidence runs thin, write "Thin evidence" and move on.
- Never invent prices or product specs. Write "Not public" or "Unclear".
- Tag anything you conclude rather than find as [Inference].

# Output
BRIEF (one short paragraph per item)
VOICE OF CUSTOMER (quotes by category, each with source, date and link)
COMPETITOR TABLE: | Name | Type | Core promise | Pricing (link) | Main complaint |
DESIRES AND FEATURES TABLE: | Desire | So I can | So I can | Matching feature |
POSITIONING STATEMENT AND HEADLINES
GAPS: what this report could not verify, and what to check by hand before using it
```

## Strengths and limitations

**Where it is strong**

- Fast, with no copy-paste between steps.
- Keeps the same evidence rules as the full version: links, dates, original language and tagged inference.
- Good enough to shape a hypothesis or a first conversation.

**Where it falls short**

- Fewer quotes and two fewer categories (Identity and Beliefs), so the persona is thinner.
- No awareness-level tables, no market sizing and no validation layer.
- Long single prompts give you less control: if one stage goes wrong, everything after it inherits the mistake, and you only see it at the end.

Treat the quick report as a hypothesis. Before it goes into a deck or a product decision, open five of its links and run [Step 7: Validate](../full-version/steps/07-validate.md), or move to the [Full Version](../full-version/README.md).
