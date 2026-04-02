# 100K AI Career Planner — Claude Code Skill

> A brutally honest, fully personalized 6-month plan to land a $100K AI job (or equivalent income through freelancing/consulting).

Built by **Ayush Singh** | [Second Brain Labs](https://secondbrainlabs.com)
From the video: *"If I Wanted a $100K AI Job in 6 Months, I'd Do This"*

---

## What Is This?

This is a Claude Code skill that turns Claude into a personal AI career coach. It collects 15 targeted questions across 3 rounds, then generates a fully personalized 6-month action plan — no generic advice, everything tied directly to your answers.

The plan is built on a 5-step framework:
1. **Architecture-Level AI Understanding** — System 1 vs System 2 thinking
2. **The Skill Value Formula** — `(Revenue + Time Saved) × Scarcity`
3. **Visibility > Ability** — LinkedIn presence strategy
4. **The Outreach Machine** — 800 contacts/month, 3-step DM framework
5. **Read Research Papers** — 1 paper/week, starting with what matters for your role

---

## Installation

### Option 1: One-liner (recommended)

```bash
mkdir -p ~/.claude/skills/ai-career-planner && \
  curl -fsSL https://raw.githubusercontent.com/ayush488-glitch/ai-career-planner-skill/main/SKILL.md \
  -o ~/.claude/skills/ai-career-planner/SKILL.md
```

### Option 2: Manual

1. Clone this repo:
   ```bash
   git clone https://github.com/ayush488-glitch/ai-career-planner-skill.git
   ```
2. Copy the skill file:
   ```bash
   mkdir -p ~/.claude/skills/ai-career-planner
   cp ai-career-planner-skill/SKILL.md ~/.claude/skills/ai-career-planner/
   ```

---

## Usage

Once installed, invoke the skill inside Claude Code:

```
/ai-career-planner
```

Claude will start the intake session immediately.

---

## What You'll Get

After answering 15 questions across 3 short rounds, Claude generates a **single personalized document** with 6 sections:

| Section | What's Inside |
|---------|---------------|
| **1. Architecture Learning Roadmap** | Week-by-week learning plan based on your current skill ratings and target role |
| **2. Skill Value Audit** | Brutally honest scoring of every skill on your resume using the `(Revenue + Time Saved) × Scarcity` formula |
| **3. Visibility Plan — 10 LinkedIn Posts** | A rewritten LinkedIn headline + 10 actual post drafts you can copy-paste and publish |
| **4. Outreach Machine** | Daily/monthly targets, target company criteria, and 3 personalized DM templates |
| **5. Research Paper Reading Plan** | 12-week reading list with paper titles, what to focus on, and career takeaways |
| **6. Week-by-Week 6-Month Timeline** | A master calendar merging all 5 tracks, scaled to your available hours/week |

---

## How It Works

**Phase 1 — 3 rounds of questions (15 total)**

- Round 1: Where you are right now (skills, experience, available hours)
- Round 2: Where you want to go (role, geography, salary target, interests)
- Round 3: Your story and constraints (projects, blockers, opinions, cold outreach comfort)

**Phase 2 — Plan generation**

Once all 15 answers are collected, Claude generates the full 6-section plan. Every sentence references something specific from your answers. No generic advice.

---

## The 5-Step Framework

### Step 1: Architecture-Level Understanding
Most engineers know Layer 3 (LLM execution). The $100K engineer builds all three:
- **Layer 1:** ML model predicts
- **Layer 2:** Decision logic verifies (business rules + expected value)
- **Layer 3:** LLM executes action

### Step 2: Skill Value Formula
```
Skill Value = (Revenue Generated + Time Saved) × Scarcity
```
If a skill doesn't generate revenue or save time, and a million people have it — it's worth nothing.

### Step 3: Visibility > Ability
Post on LinkedIn 3-4x/week. You need 50 decision-makers in your target space to know your name. AI can't automate your personal brand.

### Step 4: The Outreach Machine
25 LinkedIn connections/day. 800/month. 3-step DM framework: Callout → Value → Micro-commitment.

### Step 5: Read Research Papers
1 paper/week. The limitations section is a free roadmap of what gets built next.

---

## Author

**Ayush Singh**
Founder, [Second Brain Labs](https://secondbrainlabs.com)
7+ years building AI systems | Placed students at Google, Microsoft, Pipe, and more

---

## License

MIT — use it, fork it, share it.
