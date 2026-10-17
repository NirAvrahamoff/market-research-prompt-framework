# Step 1: Research Brief

Builds the one-page brief that every later step reads. It answers three questions: who we target, what we sell, and which problems we solve.

| | |
|---|---|
| **Time** | 15 min |
| **Web browsing** | Yes |
| **You paste in** | Company website, up to 3 competitor sites, what you already believe |
| **You get** | Research Brief (save it, you will paste it into every later step) |

## How to run it

Open a new chat in a tool with web browsing. Fill in the brackets and send the prompt. Save the output in your working document under the heading **Research Brief**. You will paste it into every later step.

## Prompt

Copy everything in the block below. Replace every `[BRACKET]` with your own content.

```text
# Role
You are a strategy analyst preparing a research brief for a market research project.

# Goal
Write a short brief that answers three questions: who we are targeting, what we are selling, and what problems we solve. Later research steps will use this brief as their only context, so it must be accurate and specific.

# Inputs
Company website: [URL]
Competitor websites (optional, up to 3): [URLs]
What I already believe (optional):
- Ideal customer: [TEXT or "unknown"]
- Product: [TEXT or "unknown"]
- Problems it solves: [TEXT or "unknown"]
Target geography and language: [e.g. US English, Israel Hebrew]

# Task
1. Read the company website and any competitor sites provided.
2. If something critical is missing and you cannot infer it from the sites, ask me up to 3 short questions before writing. Otherwise go straight to the brief.
3. Write the brief in plain language. Avoid marketing claims you cannot trace to the site.
4. Where my beliefs differ from what the website says, point out the difference rather than picking one.

# Output
Return exactly these sections:
IDEAL CUSTOMER: one paragraph on who they are, their situation, and what they want.
PRODUCT: one or two sentences on what it is and how it is positioned.
PROBLEMS: two to four problems the product solves, one sentence each.
COMPETITORS NAMED: the competitors you found or were given.
GEOGRAPHY AND LANGUAGE: as given.
OPEN QUESTIONS: anything unclear or contradictory.

Write in prose inside each section. Do not invent facts that are not on the sites or in my inputs.
```

## Tip

If you already know the answers, fill them in and let the model check them against the website. Disagreements between your view and the site are often the most useful finding of the whole project.

---

[← Framework overview](../README.md) · [Step 2: Voice of Customer →](02-voice-of-customer.md)
