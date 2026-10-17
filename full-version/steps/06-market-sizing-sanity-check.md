# Step 6: Market Sizing Sanity Check (optional)

Builds a bottom-up TAM, SAM and SOM with every assumption visible, so a founder can defend the number in front of investors or replace weak inputs with better data.

| | |
|---|---|
| **Time** | 20 min |
| **Web browsing** | Yes |
| **You paste in** | Research Brief, competitor table from Step 3, your expected price |
| **You get** | Assumptions table, TAM / SAM / SOM with formulas, sensitivity check |

## How to run it

Optional. Run it before an investor deck or a pricing decision. Save the output as **Market Sizing**.

## Prompt

Copy everything in the block below. Replace every `[BRACKET]` with your own content.

```text
# Role
You are a startup analyst who builds bottom-up market estimates and shows every assumption.

# Goal
Estimate TAM, SAM and SOM for this product in [GEOGRAPHY], with every input sourced or clearly marked as an assumption.

# Research Brief
[PASTE RESEARCH BRIEF]

# Pricing context from Step 3
[PASTE COMPETITOR TABLE]

# Our expected price
[PRICE AND BILLING UNIT, or "use the competitor median"]

# Task
1. Define the countable customer unit (for example, companies with 10 to 200 employees in sector X, or households with children under 5).
2. Find how many such units exist, citing a source with a link and year.
3. Build the estimate bottom up:
   TAM = all units × annual price
   SAM = units we can realistically reach with our channel and geography × annual price
   SOM = SAM × a plausible 3-year share, justified by comparable companies
4. Find one published top-down figure for this market and compare it with your result.
5. Sensitivity: show SOM with the two weakest assumptions at half and at double their values.

# Rules
- Every number is either [Sourced] with a link and year, or [Assumption] with a one-line reason.
- If the top-down and bottom-up figures differ by more than 3x, explain the likely reason. Do not force them to match.

# Output
ASSUMPTIONS TABLE:
| Input | Value | Unit | Sourced or Assumption | Link or reason |

RESULT: TAM, SAM and SOM in [CURRENCY] per year, with formulas shown.
TOP-DOWN COMPARISON: the published figure, its link, and the gap.
SENSITIVITY: SOM in the low and high cases.
WEAKEST ASSUMPTIONS: the two inputs to verify first.
```

## Tip

Investors trust a small, well-argued bottom-up number far more than a huge top-down one from a market report. Lead with the bottom-up figure and use the report only as a cross-check.

---

[← Step 5: Feature-to-Benefit Ladder](05-feature-to-benefit-ladder.md) · [Step 7: Validate →](07-validate.md)
