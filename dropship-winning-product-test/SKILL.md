---
name: dropship-winning-product-test
description: "Create systematic product testing frameworks for dropshipping. Use when evaluating potential winning products, planning ad tests, or analyzing product-market fit signals."
metadata:
  author: clawads
  version: "2.0"
  website: "https://clawads.io"
---

# Dropship Winning Product Ad Testing Framework

**Category:** Ads / Ecommerce  
**Works with:** OpenClaw, Claude Code, Cursor, any AI with file context  
**Purpose:** Validate winning dropship products with a $5-10/day ad test structure â€” know in 3 days whether to scale or kill

---

## What This Skill Does

Most dropshippers waste $200-500 testing products with no system. They either kill a winner too early (panic at day 1 numbers) or keep dumping money into a loser (hoping it turns around). This skill gives you a precise, data-driven framework for product testing: what to run, what metrics to watch, when to kill, and when to scale.

Built on frameworks used by 7-figure dropshippers who test 10+ products per week profitably.

---

## Why Most Product Tests Fail

1. **Wrong objective** â€” running Conversions before the pixel has data (use Add to Cart first)
2. **Testing too many variables at once** â€” different audiences AND different creatives AND different products
3. **Killing too early** â€” making decisions on day 1 data when Facebook needs 2-3 days to optimize
4. **Wrong success metrics** â€” looking at ROAS only, ignoring CPM, CTR, and CPC signals

---

## The 3-Day Test Protocol

### Day 0: Setup

**Campaign structure (one product):**
```
Campaign: [Product Name] â€” Test
  Ad Set 1: Broad (no interests, 18-45, your country)
  Ad Set 2: Interest A (most relevant single interest)
  Ad Set 3: Interest B (second most relevant interest)

Budget: $5-10/day per ad set ($15-30/day total)
Objective: Add to Cart (until 50 ATC, then switch to Purchase)
Ad format: Single image or video (test one creative per ad set)
```

**Pixel setup requirements:**
- ViewContent, AddToCart, InitiateCheckout, Purchase events all firing
- If pixel has < 50 purchases: use Add to Cart objective
- If pixel has 50+ purchases: use Purchase objective

---

## The Decision Matrix

### Check at End of Day 1:

| Metric | Kill Signal | Watch Signal | Green Light |
|--------|------------|--------------|-------------|
| CPM | > $30 | $15-30 | < $15 |
| CTR (Link) | < 0.8% | 0.8-1.5% | > 1.5% |
| CPC | > $2.00 | $1.00-2.00 | < $1.00 |
| Add to Cart | 0 with $10+ spent | 1-2 | 3+ |

**Day 1 rule:** Only kill if CPM > $40 AND CTR < 0.5% with $15+ spent. Otherwise let it run.

### Check at End of Day 2:

| Metric | Kill | Scale |
|--------|------|-------|
| Cost per ATC | > 3x your product cost | < 2x product cost |
| ATC rate (ATCs/sessions) | < 3% | > 5% |
| Checkout initiation | 0 | 2+ |

### Check at End of Day 3 â€” The Final Call:

**Kill the product if ANY of these are true:**
- 0 purchases with $50+ spent
- ROAS < 0.5x (spending $50, making back < $25)
- Cost per ATC > 4x product cost (no path to profitability)

**Scale the product if ALL of these are true:**
- 1+ purchases with ROAS > 1.5x, OR
- Cost per ATC < product cost AND 3+ checkout initiations

**Keep testing (extend 2 more days) if:**
- 1 purchase with ROAS > 1x but < 1.5x
- Good CTR (>1.5%) and CPC (<$1) but no sales yet (could be landing page issue, not product issue)

---

## The Profitability Math

Before you test, calculate your **break-even ROAS:**

```
Break-even ROAS = Selling Price / (Selling Price - Product Cost - Shipping - Payment Fees)

Example:
Selling price: $39.99
Product cost: $8.00
Shipping: $3.00
Payment fees (3%): $1.20
Fixed costs: $1.00

Profit per unit = $39.99 - $8 - $3 - $1.20 - $1 = $26.79
Break-even ROAS = $39.99 / $26.79 = 1.49x

This means: for every $1 in ad spend, you need to make $1.49 back just to break even.
Target profitable ROAS = Break-even Ã— 1.5 = 2.24x
```

---

## How to Use This Skill

Paste this into your AI agent with your product details:

---

```
Use the dropship-winning-product-test skill.

MY PRODUCT TEST SETUP:
---
Product Name: [your product]
Selling Price: [e.g., $39.99]
Product Cost (from supplier): [e.g., $8.00]
Shipping Cost: [e.g., $3.00]
Target Country: [e.g., USA / Malaysia / UK]
Pixel Status: [new / has X purchases in last 30 days]
Ad Creative I Have: [image / video / UGC]
Test Budget Per Day: [e.g., $15/day]
---

DO THIS:
1. Calculate my break-even ROAS and target profitable ROAS
2. Give me the exact campaign structure (ad sets, audiences, budget split)
3. Set exact kill/scale thresholds for my specific numbers
4. Create a Day 1 / Day 2 / Day 3 decision checklist for this product
5. Tell me what to check first if I'm getting clicks but no purchases
```

---

## Troubleshooting Guide

### Getting impressions but no clicks (CTR < 0.5%)
- **Problem:** Ad creative is not stopping the scroll
- **Fix:** Change the first 3 seconds of video OR change the main image. The copy isn't the issue â€” the hook is.

### Getting clicks but no Add to Carts (ATC rate < 2%)
- **Problem:** Landing page / product page mismatch with ad promise
- **Fix:** Check if product page matches what the ad promised. Price shock? Lack of social proof? Poor mobile layout?

### Getting Add to Carts but no purchases (checkout rate < 30%)
- **Problem:** Checkout friction or trust issue
- **Fix:** Check: (1) are you requiring account creation? (2) Do you have a trust badge? (3) Is shipping cost shown early or only at checkout? (4) Is there a guarantee?

### Getting purchases but ROAS is bad (< break-even)
- **Problem:** Either price too low or product cost too high
- **Fix:** Test a higher price (often improves ROAS by filtering out non-buyers), OR find cheaper supplier, OR add an upsell to increase AOV

### Facebook says "Learning" for 3+ days
- **Problem:** Not enough conversion events for algorithm to learn
- **Fix:** Switch to a higher-funnel objective (ATC instead of Purchase) OR combine ad sets to consolidate budget

---

## Scale Protocol (When You Have a Winner)

**Week 1 winner detected (ROAS > 2x, 5+ purchases):**
1. Duplicate winning ad set at 2x budget
2. Keep original running â€” don't touch it
3. Test 2 new ad angles using the same audience

**Week 2 (ROAS still holding):**
1. Increase budget 20% every 3 days on winning sets
2. Launch lookalike audience (LAL 1-2% of purchasers)
3. Launch retargeting: ATC non-purchasers (last 7 days)

**Never:**
- Edit a winning ad set (resets learning phase)
- Scale more than 50% in a single increase
- Kill an ad set mid-day (always evaluate at same time each day)

---

## Quick Reference Cheat Sheet

```
DAY 1 ONLY KILL IF: CPM > $40 AND CTR < 0.5% with $15+ spent

DAY 2 KILL IF: Cost per ATC > 3x product cost with $30+ spent

DAY 3 SCALE IF: 1+ purchase AND ROAS > 1.5x break-even
DAY 3 KILL IF: 0 purchases with $50+ spent OR ROAS < 0.5x

BREAK-EVEN ROAS = Sell Price Ã· (Sell Price - All Costs)
TARGET ROAS = Break-even Ã— 1.5x

TESTING BUDGET: $5-10/day per ad set, 3 ad sets = $15-30/day total
```

---

**Skill maintained by:** ClawAds  
**Category:** Ads / Ecommerce  
**Platform:** Facebook, TikTok (same framework applies)  
**Use case:** Dropshipping product validation
