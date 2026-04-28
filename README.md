# UX + Design System (for AI-built apps)

A rule-based UX and design system for AI-built apps, turning proven principles into enforceable constraints for better, simpler products.

---

## Table of Contents
- [What this is](#what-this-is)
- [What it’s based on](#what-its-based-on)
- [Why it matters](#why-it-matters)
- [Instructions](#instructions)
- [Goal](#goal)
- [License](#license)

---

## What this is
A rule-based UX + design system for AI.

It turns proven principles into strict rules the AI must follow when building.

---

## What it’s based on

- Hick’s Law → reduce choices  
- Cognitive Load → reduce thinking  
- Fitts’s Law → make actions easy  
- Jakob’s Law → use familiar patterns  
- Peak-End Rule → strong finish matters  
- Goal Gradient → show progress  
- Gestalt → clear structure  
- Signal vs Noise → remove clutter  
- Default Bias → guide decisions  

Most people know these.  
This system enforces them.

---

## Why it matters

AI builds for functionality, not usability.

So you get:

- messy UI  
- too many decisions  
- poor flows  

This system forces:

- clarity  
- speed  
- obvious next steps  

---

## Instructions

Use this system to design screens that are **fast, obvious, and require zero thinking**.

---

### Step 1 — Define the user and goal

Before designing anything, answer:

- Who is the user?
- What do they want right now?
- What is the ONE action they must take?

If you can’t answer this clearly → simplify first.

---

### Step 2 — Define the screen

Go to:

`/templates/screen.md`

Duplicate it and rename it:

```
/screens/home.md
/screens/onboarding.md
/screens/dashboard.md
```

Fill it in:

```
SCREEN NAME:
[USER INTENT]:
[PRIMARY GOAL]:
[PRIMARY ACTION]:
[SECONDARY ACTIONS]: (max 1–2)
[NEXT STEP]:
```

Rules:
- one primary action only  
- no competing actions  
- keep it minimal  

---

### Step 3 — Use the master prompt

Paste this into your AI tool:

```
Read UX.md and Design.md fully.

Treat them as strict rules, not suggestions.
Do not violate them.

Use /templates/screen.md to structure the screen.

[TASK]: Build this screen

[USER TYPE]: [Describe your user]

[CORE GOAL]: [What they want]

[PRIMARY ACTION]: [Main action]

PROCESS:

1. Define the screen
2. Build the UI/UX
3. Score it using UX.md
4. Fix weak areas
5. Repeat until score ≥ 85

RULES:

- one clear primary action
- minimise decisions
- remove unnecessary elements
- optimise for speed and clarity

OUTPUT:

- final improved version only
- include UX score (/100)

If the user has to think → it failed
```

---

### Step 4 — Provide your screen input

Paste your filled screen below the prompt.

Example:

```
[USER INTENT]: User wants to get started  
[PRIMARY GOAL]: Guide to first action  
[PRIMARY ACTION]: Get Started  
```

---

### Step 5 — Let AI build and refine

The AI will:

- build the screen  
- score it  
- identify problems  
- improve it  
- repeat until strong  

---

### Step 6 — Repeat for every screen

Use this process for:

- onboarding  
- dashboards  
- features  
- full flows  

---

## Goal

The user should:

- understand instantly  
- know what to do immediately  

If they have to think → it’s wrong  

---

## License

Free to use in personal and commercial projects.

Not allowed to resell or redistribute this as a standalone product.
