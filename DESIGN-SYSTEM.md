# Design System Methodology

This file defines how AI should make visual design decisions.

Design is not decoration.

Design must:
- improve clarity
- guide attention
- reduce visual effort
- increase trust
- make the product feel structured, calm, and premium

If the interface looks good but makes the user think harder, it failed.

---

## 1. Visual Hierarchy

### What
Visual hierarchy controls what the user sees first, second, and third.

### Why it matters
Users scan before they read. If hierarchy is weak, everything competes for attention.

### Rules
- one dominant focal point per screen
- primary action must be visually strongest
- secondary content must feel secondary
- use size, weight, spacing, and contrast to create order
- never rely on color alone

### Fail conditions
- everything looks equally important
- user does not know where to look first
- primary action is missed

### Enforcement rule
If the user cannot instantly identify the most important thing, redesign the hierarchy.

---

## 2. Color Theory

### What
Color controls attention, emotion, meaning, and state.

### Why it matters
Poor color use creates noise, weak contrast, and low trust.

### Rules
- primary color is for primary action only
- do not use primary color as decoration
- muted colors reduce attention
- high contrast increases attention
- success, warning, and error colors must be consistent
- background and surface colors must support readability
- all text must meet accessible contrast

### Suggested roles
- Background
- Surface
- Primary
- Secondary
- Text primary
- Text secondary
- Text muted
- Border
- Success
- Warning
- Error

### Fail conditions
- too many colors
- low contrast
- decorative gradients with no purpose
- multiple elements fighting for attention

### Enforcement rule
If color does not guide meaning or action, remove or reduce it.

---

## 3. Typography

### What
Typography controls readability, tone, and scanning speed.

### Why it matters
Users should understand content quickly without effort.

### Rules
- use maximum 2 fonts
- keep type scale consistent
- headings must create clear structure
- body text must be easy to read
- avoid dense paragraphs
- line height should support scanning
- do not use font size randomly

### Type scale
- Display: 56-80px
- H1: 36-48px
- H2: 28-32px
- H3: 20-24px
- Body: 14-18px
- Small: 12-13px

### Fail conditions
- too many text styles
- weak heading structure
- hard-to-read body copy
- inconsistent font sizes

### Enforcement rule
If text is not easy to scan, simplify the type hierarchy.

---

## 4. Spacing and Rhythm

### What
Spacing creates structure, grouping, and breathing room.

### Why it matters
Bad spacing makes interfaces feel messy, cheap, and hard to understand.

### Rules
Use a consistent spacing scale:

4 / 8 / 12 / 16 / 24 / 32 / 40 / 48 / 64 / 80 / 96 / 128

- related items should be closer together
- unrelated items should be farther apart
- cards and panels need enough internal padding
- sections need clear vertical rhythm
- avoid random spacing values

### Fail conditions
- crowded UI
- uneven gaps
- weak grouping
- inconsistent padding

### Enforcement rule
If spacing feels random, rebuild it on the spacing scale.

---

## 5. Alignment and Grid

### What
Alignment gives the interface structure and predictability.

### Why it matters
Misalignment creates visual friction and makes the product feel unfinished.

### Rules
- use consistent grid alignment
- align text and components intentionally
- avoid floating elements
- left-align body text by default
- keep repeated layouts consistent
- use columns and containers to control structure

### Fail conditions
- elements feel randomly placed
- sections do not line up
- layout feels unstable

### Enforcement rule
If the layout does not feel structured, fix alignment before adding more design.

---

## 6. Contrast and Emphasis

### What
Contrast controls what stands out.

### Why it matters
Without contrast, users cannot identify importance quickly.

### Rules
Use contrast through:
- size
- weight
- spacing
- opacity
- color
- position

Primary action should have the strongest contrast on the screen.

### Fail conditions
- too many high-contrast elements
- weak CTA visibility
- important content blends in
- low readability

### Enforcement rule
If everything stands out, nothing stands out.

---

## 7. Density Control

### What
Density is how much information appears in a given space.

### Why it matters
Too much density increases cognitive load and makes the UI feel heavy.

### Rules
- reduce visible information where possible
- separate dense areas with whitespace
- avoid large blocks of text
- use cards, sections, and groups to break complexity
- reveal detail progressively

### Fail conditions
- screen feels busy
- too much text at once
- too many controls visible
- user has to scan too much

### Enforcement rule
If the screen feels heavy, reduce density before changing style.

---

## 8. Component Consistency

### What
Components must look and behave the same everywhere.

### Why it matters
Consistency reduces learning effort and builds trust.

### Rules
Same component must have same:
- spacing
- radius
- typography
- states
- behaviour
- interaction pattern

Required states:
- default
- hover
- active
- disabled
- loading
- error
- success

### Fail conditions
- same button looks different in different places
- states are missing
- interactions behave inconsistently

### Enforcement rule
If a pattern appears once, reuse it consistently.

---

## 9. Motion and Transitions

### What
Motion explains change and provides feedback.

### Why it matters
Good motion makes interfaces feel responsive and understandable. Bad motion feels decorative or slow.

### Rules
- motion must guide attention
- motion must explain state change
- keep transitions fast
- avoid unnecessary animation
- do not animate everything

### Timing
- micro interaction: 100-200ms
- standard transition: 200-300ms
- complex transition: max 400ms

### Fail conditions
- animation slows the user
- motion feels decorative
- state changes happen with no feedback

### Enforcement rule
If motion does not improve clarity, remove it.

---

## 10. Accessibility

### What
Accessibility ensures the interface is usable by as many people as possible.

### Why it matters
Accessible design is clearer design.

### Rules
- body text contrast must meet 4.5:1 minimum
- large text contrast must meet 3:1 minimum
- do not use color alone to communicate meaning
- all interactive elements need visible focus states
- click targets should be at least 40x40px
- text must remain readable at small sizes

### Fail conditions
- low contrast
- missing focus states
- tiny click targets
- meaning depends only on color

### Enforcement rule
If it is not accessible, it is not finished.

---

## 11. Premium Feel

### What
Premium design is calm, intentional, consistent, and restrained.

### Why it matters
Users trust products that feel stable and considered.

### Rules
- remove visual noise
- use restraint with gradients and effects
- keep surfaces clean
- use subtle borders
- avoid heavy shadows
- avoid unnecessary decoration
- make every detail feel intentional

### Fail conditions
- UI feels noisy
- too many effects
- inconsistent styling
- cheap-looking gradients or shadows

### Enforcement rule
Premium design is not more design - it is less, done better.

---

## 12. Design Validation

For every screen, check:

1. Is the focal point obvious?
2. Is the primary action visually dominant?
3. Is the spacing consistent?
4. Is the type readable?
5. Is the color meaningful?
6. Is the layout aligned?
7. Is the density controlled?
8. Are components consistent?
9. Is accessibility covered?
10. Does it feel calm, premium, and trustworthy?

If any answer is no, redesign before shipping.

---

## Final Rule

Always choose:

- clarity over style
- restraint over decoration
- consistency over novelty
- readability over cleverness
- trust over visual noise

The interface should feel obvious before it feels impressive.
