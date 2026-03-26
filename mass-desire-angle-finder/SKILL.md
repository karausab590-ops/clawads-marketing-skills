---
name: mass-desire-angle-finder
description: "Find untapped ad angles for any winning product using deep Reddit/forum research. Input your product + desire + avatar, get a full research report and 5+ battle-tested angles with hooks, outlines, and test priority."
metadata:
  author: Anthony Camacho
  version: "2.0"
  website: "https://clawads.io"
---

# Mass Desire Angle Finder

Turn one winning ad into 5+ new angles to scale from $300-500/day to $1K+/day. Based on Anthony Camacho's "Angle Loading" framework for direct response advertising and dropshipping.

## Required Input From User

You need exactly 3 things to start. Ask for any that are missing:

1. **Product** — what are you selling? (e.g., "posture corrector brace", "hair growth serum", "blue light glasses")
2. **Winning Desire** — what does your customer actually want? NOT the product, but the OUTCOME. (e.g., "I want to keep working without back pain ruining my life")
3. **Target Avatar** — who specifically? The more specific, the better angles you'll find. (e.g., "construction workers aged 35-55 with chronic lower back pain")

Optional but helpful:
- **Current winning angle** — what argument is your best ad making right now?
- **Niche/industry** — health, beauty, fitness, home, pet, etc.

Once you have all 3, run the full pipeline below. Do NOT skip steps.

---

## PHASE 1: Deep Avatar Research (This Is Where Angles Come From)

**Goal:** Find REAL words from REAL people who have this desire. You're looking for 6 specific things:

### What To Search For

| Category | What It Means | Example (Back Pain) |
|----------|--------------|-------------------|
| **Failed Solutions** | What they've already tried that didn't work | "I've been doing PT for 6 months and nothing changed" |
| **Limiting Beliefs** | What they believe about the problem that keeps them stuck | "I think I just have to live with it at my age" |
| **Hidden Frustrations** | Emotional pain beyond the surface problem | "My wife has to tie my shoes for me now. I feel useless." |
| **Things They Blame** | Who or what THEY think is responsible | "My doctor just keeps prescribing pills instead of fixing it" |
| **Knowledge Gaps** | What they don't know about their own problem | Doesn't know the pain is from hip tightness, not the spine |
| **Fear / Worst Case** | What they're terrified will happen if they don't fix it | "I'm scared I'll end up needing surgery" |

### Step 1.1 — Reddit Research (MOST IMPORTANT)

Search Reddit using `web_search` with these query patterns. Run ALL of them:

```
Query 1: site:reddit.com "[avatar]" "[problem]" "tried everything"
Query 2: site:reddit.com "[problem]" "nothing works" OR "still in pain" OR "gave up"
Query 3: site:reddit.com "[problem]" "doctor said" OR "doctor told me" OR "PT said"
Query 4: site:reddit.com "[problem]" "I've tried" OR "already tried" OR "doesn't work"
Query 5: site:reddit.com "[problem]" "scared" OR "afraid" OR "worried" OR "terrified"
Query 6: site:reddit.com "[problem]" "waste of money" OR "scam" OR "doesn't help"
```

Replace `[avatar]` with the target avatar description and `[problem]` with their core problem.

**Example for back pain product:**
```
site:reddit.com "back pain" "construction" "tried everything"
site:reddit.com "back pain" "nothing works" OR "still in pain"  
site:reddit.com "back pain" "doctor said" OR "doctor told me"
site:reddit.com "back pain" "I've tried" OR "already tried"
site:reddit.com "back pain" "scared" OR "afraid" "surgery"
site:reddit.com "back pain" "waste of money" OR "doesn't help"
```

For each search, open the top 3-5 Reddit threads using `web_fetch`. Read the FULL thread including comments.

**What to extract from each thread:**
- Copy exact quotes (verbatim language) that show pain, frustration, failed solutions, or beliefs
- Note the username context (age, job, how long they've had the problem)
- Look at COMMENTS too — often the most revealing stuff is in replies, not the original post
- Look for comments where multiple people agree on the same thing (corroboration = strong angle)

### Step 1.2 — Niche Forum / Community Research

Beyond Reddit, search for niche-specific forums:

```
Query: "[problem]" forum OR community OR "support group" -reddit
Query: "[problem]" "[avatar]" site:quora.com
```

### Step 1.3 — Amazon Review Mining

Search for competing products on Amazon and read the 1-3 star reviews:

```
Query: site:amazon.com "[competing product type]" reviews
```

**What to look for in bad reviews:**
- "This didn't work because..." — reveals what people expect
- "I returned it after..." — reveals the failure point
- "I wish it had..." — reveals unmet needs
- "The problem is actually..." — reveals their understanding of root cause

### Step 1.4 — Scientific / Authority Research

For health, beauty, and wellness niches, search for studies that could support angles:

```
Query: site:pubmed.gov "[problem]" "[common solution]" ineffective OR limitations
Query: site:pubmed.gov "[problem]" "root cause" OR "underlying mechanism"
Query: "[problem]" Harvard OR Mayo Clinic OR "medical study" new findings
```

**Why this matters:** If you can find a real study saying "painkillers don't actually help chronic back pain" or "most people stretch the wrong muscles," that becomes POWERFUL angle ammunition. Real data = real credibility in your copy.

### Step 1.5 — Compile the Research Report

After all research is done, organize everything into this format:

```
## RESEARCH REPORT: [Product] — [Avatar]

### Avatar Profile
- Who: [specific description]
- Core desire: [what they actually want]
- Current emotional state: [frustrated/desperate/hopeful/resigned]
- How long they've been dealing with this: [timeframe from research]

### Failed Solutions (What They've Already Tried)
1. [Solution] — "[exact quote from research]" (source: r/[subreddit])
2. [Solution] — "[exact quote]" (source: ...)
3. ...

### Limiting Beliefs (What They Think Is True)
1. "[belief in their own words]" — [how many people expressed this]
2. ...

### Hidden Frustrations (The Emotional Layer)
1. "[quote showing emotional pain]" — [context]
2. ...

### Things They Blame
1. [Who/what] — "[how they express this blame]"
2. ...

### Knowledge Gaps (What They Don't Know)
1. [What they're missing] — [evidence from research/studies]
2. ...

### Fears / Worst Case Scenarios
1. "[fear in their words]"
2. ...

### Key Verbatim Language (Use These In Copy)
- "[powerful phrase 1]"
- "[powerful phrase 2]"
- ...
```

**IMPORTANT:** Every single item must have a real source. No making things up. If you can't find enough data, tell the user and suggest adjusting the avatar or broadening the search.

---

## PHASE 2: Angle Extraction

Now you have the research. Here's how to turn it into angles.

### Core Principle: An Angle = Who/What You Blame

> Same person + same desire + **different blame** = different angle

An angle is NOT a hook. A hook is one line that grabs attention. An angle is the **entire persuasive argument** that runs through a piece of copy from start to finish. The hook CARRIES the angle, but the angle is bigger.

### The 7 Angle Types (Check Each One Against Your Research)

Go through each of these 7 types and ask: "Does my research support this?"

**Type 1: The Wrong Treatment Angle**
- Blame: The solution they've been using is actually making it worse
- Research signal: People saying "[solution] didn't work" or "[solution] made it worse"
- Example: "Painkillers mask the pain but make the real problem worse — here's what's actually happening to your spine every time you pop a Tylenol"
- Power level: ★★★★★ (very strong because it invalidates competitors AND creates urgency)

**Type 2: The Bigger Enemy Angle**
- Blame: An industry, system, or establishment that profits from keeping them stuck
- Research signal: People expressing distrust of industry, feeling like they're being milked for money
- Example: "The back pain industry is designed to keep you coming back, not actually fix you. Here's what they don't want you to know."
- Power level: ★★★★★ (triggers anger + positions you as the truth-teller)
- Credit: Stefan Georgi uses this heavily in his sales letters

**Type 3: The Closing Window Angle**
- Blame: Time itself — there's a point of no return and they're approaching it
- Research signal: People worried about it getting worse, fear of surgery, "what if it's too late"
- Example: "There's a 6-month window where back pain is still correctable. After that, you're looking at surgery. Most people blow right past it."
- Power level: ★★★★☆ (creates massive urgency but needs credible backing)

**Type 4: The Authority Failure Angle**
- Blame: Doctors, trainers, therapists, or other trusted authorities who failed them
- Research signal: People saying "my doctor told me it's just age" or "PT didn't help"
- Example: "Your doctor told you it's normal for your age. It's not. Here's what they missed in your diagnosis."
- Power level: ★★★★☆ (works when research shows widespread disappointment with authorities)

**Type 5: The Wrong Diagnosis Angle**
- Blame: A fundamental misunderstanding of what's actually causing the problem
- Research signal: Studies showing common misconceptions, people treating symptoms not root cause
- Example: "You've been stretching your back for months. But your pain isn't coming from your back — it's coming from your hips. Here's why that changes everything."
- Power level: ★★★★★ (creates an "aha moment" — the belief shift Anthony talks about)

**Type 6: The Hidden Saboteur Angle**
- Blame: Something in their daily routine that's secretly making it worse
- Research signal: People not connecting their habits to the problem
- Example: "The 8 hours you spend sitting at your desk isn't just uncomfortable — it's actively compressing your discs. By Friday, you've lost 3mm of spine height."
- Power level: ★★★★☆ (makes the problem feel immediate and personal)

**Type 7: The Trusted-Thing-Is-Poison Angle**
- Blame: Something they currently trust or rely on that's actually the problem
- Research signal: People using a common product/method religiously without results
- Example: "That memory foam mattress you spent $2,000 on? It's the reason you wake up stiff every morning. Here's what sleep researchers found."
- Power level: ★★★★☆ (shock value + invalidates a "safe" choice they made)

### How To Build Each Angle

For every angle type where your research has supporting evidence, build the full angle:

**1. Name it** — give it a short memorable label (e.g., "The Wrong Diagnosis Angle")

**2. Define the blame** — one sentence. Who/what are we blaming?

**3. Write the reframe** — 2-3 sentences. How does this angle make the avatar see their problem in a completely new way? This is the "belief shift." After reading this, they should think: "Wait... I never thought about it that way."

**4. The logical bridge to the product** — How does this reframe naturally lead to YOUR product as the answer? Write it out:
- "If [blame] is the real problem..."
- "Then [common solutions] can't work because..."
- "What you actually need is [category your product fits]..."
- "Which is exactly what [product] does by..."

The reader should feel like they DISCOVERED the product as the logical conclusion, not like you pitched them.

**5. Research evidence** — Paste the specific quotes, studies, or data that backs this angle. Every angle MUST have real evidence. No evidence = cut the angle.

**6. Three hook variations** — Write 3 different first lines that carry this angle:
- Hook A: Question format ("Did you know [reframe]?")
- Hook B: Statement format ("[Shocking claim from the angle]")  
- Hook C: Story format ("I spent [time] doing [wrong thing] before I realized...")

**7. Mini sales letter outline** — Show how this angle flows through an entire ad (not just the headline):

```
OPEN: [Hook carrying the angle — grab attention with the reframe]
   ↓
PROBLEM AMPLIFICATION: [Deepen the reframe. Show them HOW the thing we're 
blaming is hurting them. Use specific data/quotes. Make it visceral.]
   ↓
FAILED SOLUTIONS: [List 2-3 things they've tried. Explain WHY those didn't 
work through the lens of our angle. "Of course [solution] didn't work, 
because [angle reframe]..."]
   ↓
THE MECHANISM: [Introduce the unique mechanism — the new understanding that 
bridges to your product. This is the "aha moment." Don't name the product 
yet. Just explain the mechanism/principle.]
   ↓
THE PRODUCT REVEAL: [NOW introduce the product as the thing that applies 
this mechanism. It should feel obvious at this point. "That's exactly why 
[product] was designed to..."]
   ↓
PROOF: [Social proof, study references, before/after, testimonials — 
anything that reinforces the angle's argument]
   ↓
CTA: [Urgency tied specifically to THIS angle. Not generic urgency. 
e.g., for "closing window" angle: "Every day you wait, [consequence]."]
```

---

## PHASE 3: Prioritize & Final Output

### Scoring Each Angle

Rate every angle on 3 criteria (1-5 each):

| Criteria | What It Means | How To Score |
|----------|--------------|-------------|
| **Research Backing** | How many real people expressed this pain/belief? | 5 = multiple threads with dozens agreeing. 1 = only found 1 vague mention |
| **Emotional Weight** | How strong is the emotional trigger? (fear, anger, shame, hope) | 5 = "my wife ties my shoes, I feel useless." 1 = mild inconvenience |
| **Uniqueness** | Is anyone else running this angle in ads right now? | 5 = never seen this angle anywhere. 1 = every competitor runs this |

**Total score = Research + Emotion + Uniqueness (out of 15)**

### Final Ranking

Sort all angles by total score. Recommend:
- **Test First:** Highest scoring angle (explain why in 2-3 sentences)
- **Test Second:** Second highest (explain why)
- **Test Third:** Third highest (explain why)
- **Hold:** Any angles that scored well but need more research before testing

### Complete Output Format

Deliver everything in this structure:

```
# ANGLE LOADING REPORT: [Product Name]

## INPUT
- Product: [what they're selling]
- Desire: [the winning desire]  
- Avatar: [who we're targeting]
- Current winning angle: [if provided]

## RESEARCH REPORT
[Full Phase 1 report — every finding with sources and verbatim quotes]

## ANGLE 1: [Name] — Score: [X]/15
- **The Blame:** [1 sentence]
- **The Reframe:** [2-3 sentences — the belief shift]
- **Logical Bridge to Product:** [How this leads to buying]
- **Research Evidence:** [Specific quotes/data with sources]
- **Scoring:**
  - Research Backing: [X]/5 — [why]
  - Emotional Weight: [X]/5 — [why]  
  - Uniqueness: [X]/5 — [why]
- **Hook Variations:**
  1. [Question hook]
  2. [Statement hook]
  3. [Story hook]
- **Mini Sales Letter Outline:**
  1. OPEN: ...
  2. PROBLEM AMPLIFICATION: ...
  3. FAILED SOLUTIONS: ...
  4. THE MECHANISM: ...
  5. PRODUCT REVEAL: ...
  6. PROOF: ...
  7. CTA: ...

## ANGLE 2: [Name] — Score: [X]/15
[Same structure]

## ANGLE 3-5+: ...

## RECOMMENDED TEST ORDER
1. **Test First: [Angle Name]** — [Why this is the strongest bet. What makes it compelling.]
2. **Test Second: [Angle Name]** — [Why.]
3. **Test Third: [Angle Name]** — [Why.]

## VERBATIM LANGUAGE BANK
[List of 15-20 exact phrases from research that should be used in ad copy.
These are the words your avatar actually uses — not marketing language.]

## NEXT STEPS
- Write full ad copy for top 3 angles (or use a copywriting skill like perry-belcher-21-step-sales-letter or frank-kern-story-selling)
- Create advertorials for angles that test well on short-form ads
- Scale winning angles into listicles, VSLs, or landing pages
```

---

## Key Principles (Non-Negotiable)

1. **Research first, angles second.** Never generate angles without doing the research. The research IS the angle discovery process. No research = garbage angles.

2. **Verbatim language > marketing language.** The exact words real people use are 10x more powerful than anything you can write. "I feel like a burden to my family" hits harder than "chronic pain affects quality of life."

3. **Every angle needs evidence.** If you can't point to a real Reddit thread, Amazon review, or study that supports the angle, cut it. Three researched angles beat ten invented ones.

4. **Angles are arguments, not headlines.** A hook is one line. An angle is the entire logical argument: reframe → why old solutions failed → why this new understanding changes everything → why the product is the logical answer. It runs through the WHOLE piece of copy.

5. **Deeper research = more unique angles.** Surface-level research gives you the same angles every competitor already runs. Going deep into niche subreddits, reading 50+ comments, finding that one buried post with 3 upvotes where someone pours their heart out — THAT'S where the gold is.

6. **The desire stays constant.** You are NOT finding new desires. The desire is already validated by sales. You are finding new ARGUMENTS (angles) for why the avatar should act on that desire NOW, through THIS product.
