---
name: laws-of-ux
description: "Use when building UI/UX components, landing pages, forms, navigation, or any interface work. Applies the 30 Laws of UX — from Fitts's Law to the Zeigarnik Effect — as actionable design rules. Also use when reviewing existing interfaces for UX problems, auditing accessibility/interaction patterns, or when the user asks to 'make it more usable', 'fix the UX', or references laws of UX, heuristic evaluation, or design principles."
---

# Laws of UX — Actionable Design Skill

A comprehensive UX design reference based on Jon Yablonski's Laws of UX (lawsofux.com) and the O'Reilly book. Use these laws as mental checklist items when building or reviewing any interface.

---

## QUICK REFERENCE — Decision Triggers

When you encounter these situations, immediately apply the corresponding law:

| Situation | Apply |
|-----------|-------|
| Buttons, CTAs, or interactive elements | **Fitts's Law** — size, spacing, positioning |
| Navigation structure, menu items | **Hick's Law** + **Miller's Law** |
| Onboarding or multi-step flows | **Hick's Law** + **Goal-Gradient Effect** + **Zeigarnik Effect** |
| Form design, text input | **Postel's Law** + **Fitts's Law** |
| Layout, visual grouping | **Law of Proximity** + **Law of Similarity** + **Law of Common Region** |
| Loading states, system response | **Doherty Threshold** |
| Content-heavy pages | **Chunking** + **Miller's Law** + **Cognitive Load** |
| Checkout, task completion flows | **Peak-End Rule** + **Goal-Gradient Effect** |
| Redesigns, feature changes | **Jakob's Law** + **Mental Model** |
| Making elements stand out | **Von Restorff Effect** + **Selective Attention** |
| Simplifying interfaces | **Occam's Razor** + **Tesler's Law** + **Hick's Law** |
| Progress indicators, menus, lists | **Serial Position Effect** |
| Delayed tasks, motivational UX | **Zeigarnik Effect** + **Goal-Gradient Effect** |

---

## THE 30 LAWS — Actionable Guidelines

### 1. Aesthetic-Usability Effect
> Users perceive aesthetically pleasing design as more usable.

**Apply:**
- Invest in visual polish — it directly improves perceived usability.
- Use consistent typography, spacing, and color to create a cohesive feel.
- **Caveat in usability tests:** Watch what users *do*, not just what they *say* — aesthetics can mask real issues.

---

### 2. Choice Overload
> Too many options overwhelm users.

**Apply:**
- Limit visible options at any given moment; highlight a recommended/default choice.
- Enable side-by-side comparison for decisions (e.g., pricing tables).
- Use search, filters, and progressive disclosure to narrow choices.

---

### 3. Chunking
> Group information into meaningful units.

**Apply:**
- Break content into visually distinct blocks with clear hierarchy.
- Use headings, subheadings, whitespace, and borders to create chunks.
- Group related form fields together; separate unrelated sections.

---

### 4. Cognitive Bias
> Mental shortcuts affect perception and decisions.

**Apply:**
- Be aware of confirmation bias — users look for what confirms their expectations.
- Use social proof (reviews, counts) and anchoring (original vs. sale price) ethically.
- Design for how people *actually* think, not how they *should* think.

---

### 5. Cognitive Load
> Mental effort has a hard limit.

**Apply:**
- Reduce extraneous cognitive load: remove unnecessary elements, decorations, and distractions.
- Intrinsic load is necessary — don't oversimplify to the point of uselessness.
- Show only what's needed at each step; hide complexity behind progressive disclosure.

---

### 6. Doherty Threshold
> Response under 400ms keeps users engaged.

**Apply:**
- Use optimistic UI updates (show the result immediately, sync in background).
- Add loading indicators for anything over 300ms.
- Use skeleton screens and animations to mask wait times.
- Progress bars make waits feel shorter regardless of accuracy.

---

### 7. Fitts's Law
> Target acquisition time = f(distance, size).

**Apply:**
- **Size:** Touch targets minimum 44x44px (iOS) or 48x48dp (Android). Larger is better.
- **Spacing:** At least 8dp between touch targets. Use 12-16dp for comfortable spacing.
- **Position:** Place primary actions in easy-to-reach areas (thumb zones on mobile — bottom half of screen).
- Label form inputs — clicking the label focuses the input, expanding the tap target.
- Edge and corner placement works well for frequently used targets on desktop (infinite cursor travel).
- Avoid placing critical actions in hard-to-reach corners on mobile (top corners require stretching).

---

### 8. Flow
> Balance challenge and skill for deep engagement.

**Apply:**
- Match task difficulty to user skill level — not too easy, not too hard.
- Provide clear feedback so users know what happened.
- Remove unnecessary friction (extra clicks, confusing navigation) to maintain flow.
- Make content and features discoverable to prevent disengagement.

---

### 9. Goal-Gradient Effect
> Motivation increases as you approach the goal.

**Apply:**
- Show progress bars, step indicators, or completion percentages.
- As users get closer to completion, reduce friction further.
- Provide artificial progress (e.g., "Step 2 of 3" even if real steps vary).
- Use milestones and rewards near the end of long flows.

---

### 10. Hick's Law
> Decision time increases with number and complexity of choices.

**Apply:**
- Minimize choices when speed matters (hero sections, CTAs).
- Break complex tasks into smaller, manageable steps.
- Use progressive onboarding — reveal features gradually, not all at once.
- **Do NOT oversimplify:** Always provide enough context (labels with icons, clear affordances).
- Highlight recommended or most popular options.

---

### 11. Jakob's Law
> Users prefer your site to work like sites they already know.

**Apply:**
- Follow established conventions for layout, navigation, and interactions.
- Place search in the expected location (top, center/right). Use standard nav patterns.
- Don't reinvent common patterns (hamburger menus, carousels, accordions) without strong reason.
- For redesigns: let users opt in gradually, allow reverting, and provide a transition period.
- **Depart from conventions only when you have a compelling UX improvement** and always test with users.

---

### 12. Law of Common Region
> Elements in a shared boundary are perceived as a group.

**Apply:**
- Use borders, backgrounds, or cards to group related elements.
- Visual containers create clear structure and help users understand relationships.
- Use padding and consistent background colors to create implicit boundaries.

---

### 13. Law of Proximity
> Nearby objects are perceived as related.

**Apply:**
- Place related items close together; separate unrelated items with space.
- Use consistent spacing to establish visual hierarchy and relationships.
- In lists, tighter spacing between items in a group, more space between groups.
- Example: Google Search results use spacing to group each result as a cluster.

---

### 14. Law of Prägnanz
> People perceive the simplest form of complex shapes.

**Apply:**
- Simplify complex visuals into clean, recognizable shapes.
- Use simple, clear icons — avoid complex illustrations for functional elements.
- The human eye seeks simplicity — help it by reducing visual complexity.

---

### 15. Law of Similarity
> Similar-looking elements are perceived as the same group.

**Apply:**
- Use consistent colors, shapes, and styles for elements with the same function.
- Links should look visually different from regular text (color, underline).
- Use consistent button styles for the same action type across the interface.

---

### 16. Law of Uniform Connectedness
> Visually connected elements are perceived as related.

**Apply:**
- Use lines, arrows, or borders to show connections between elements.
- Connect related items with visual connectors (e.g., flow diagrams, breadcrumbs).
- Use consistent visual treatments (borders, backgrounds) to connect related content.

---

### 17. Mental Model
> Users carry pre-existing beliefs about how systems work.

**Apply:**
- Match your design to users' existing mental models — research them.
- Use familiar patterns for e-commerce (product cards, cart, checkout).
- Test with real users to identify gaps between your mental model and theirs.
- User interviews, personas, journey maps, and empathy maps help bridge the gap.

---

### 18. Miller's Law
> Working memory holds ~7 (±2) chunks.

**Apply:**
- **Do NOT use "7 items max" as a hard rule** — Miller himself said it was rhetorical.
- The real lesson: use chunking to organize content into digestible groups.
- Break long lists, phone numbers, and data into logical groups.
- Short-term memory varies by individual — provide external memory aids (labels, breadcrumbs, history).

---

### 19. Occam's Razor
> The simplest explanation is usually correct.

**Apply:**
- Remove any element that doesn't contribute to the user's goal.
- Strive for simplicity in layout, copy, and interactions.
- Consider a design complete only when nothing more can be removed without breaking function.

---

### 20. Paradox of the Active User
> Users never read manuals — they start using immediately.

**Apply:**
- Don't front-load documentation or lengthy onboarding.
- Provide contextual help (tooltips, inline hints) throughout the experience.
- Design for learning-by-doing, not learning-by-reading.
- Make guidance accessible at the point of need, not before.

---

### 21. Pareto Principle
> 80% of effects come from 20% of causes.

**Apply:**
- Identify the 20% of features used by 80% of users — prioritize those.
- Focus design effort on the most impactful interactions.
- Use analytics to find the critical paths and optimize them ruthlessly.

---

### 22. Parkinson's Law
> Tasks expand to fill available time.

**Apply:**
- Set time limits for tasks and communicate them ("Takes 2 minutes").
- Use autofill, pre-population, and smart defaults to reduce completion time.
- Limit the perceived scope of a task to what users expect it to take.
- Reducing actual duration below expected duration improves perceived experience.

---

### 23. Peak-End Rule
> People remember the peak moment and the ending.

**Apply:**
- Identify the emotional peak of your user journey — make it positive.
- Design the ending (checkout confirmation, success screen, last impression) deliberately.
- Use personality, humor, or delight at key moments (e.g., Mailchimp's high-five).
- Handle errors gracefully — they create negative peaks. Use humor or helpfulness.
- Negative experiences are recalled more vividly than positive ones.

---

### 24. Postel's Law
> Be liberal in what you accept, conservative in what you send.

**Apply:**
- Accept variable input: different formats, spellings, capitalizations, file types.
- Normalize input internally rather than forcing users to conform.
- Design for internationalization: text can expand 300% in translation, directions vary.
- Account for user customization (font size, zoom) — don't break gracefully.
- Your output (system messages, responses) should be clear, consistent, and helpful.

---

### 25. Selective Attention
> Users focus on relevant stimuli and filter out the rest.

**Apply:**
- Guide attention with visual hierarchy (size, color, contrast, position).
- Avoid banner blindness: don't style content to look like ads.
- Avoid change blindness: make important changes visually prominent.
- Don't compete for attention with multiple simultaneous highlights.

---

### 26. Serial Position Effect
> First and last items are remembered best.

**Apply:**
- Place the most important items at the beginning and end of lists/navigation.
- Put least important items in the middle (they'll be forgotten anyway).
- Position primary actions on the far left/right of navigation bars.

---

### 27. Tesler's Law
> Every system has irreducible complexity — someone must handle it.

**Apply:**
- Move complexity from the user to the system wherever possible.
- Build smart defaults, auto-suggestions, and intelligent form validation.
- Don't build for an idealized rational user — real people are messy.
- Provide contextual help for the complexity that can't be eliminated.

---

### 28. Von Restorff Effect
> The distinctive item is remembered best.

**Apply:**
- Make key CTAs and important information visually distinctive.
- Use color, size, or contrast to make items stand out from their surroundings.
- Don't overdo emphasis — too many "highlighted" items means nothing is highlighted.
- Don't rely solely on color for contrast (accessibility).

---

### 29. Working Memory
> Temporary storage for task-relevant information (4-7 chunks, 20-30s fade).

**Apply:**
- Support recognition over recall: show visited links, breadcrumbs, recent searches.
- Carry context across screens (comparison data, form progress).
- Don't make users remember information from one screen to another — show it.
- Visually differentiate states (active, visited, selected) to reduce memory burden.

---

### 30. Zeigarnik Effect
> Incomplete tasks are remembered better than completed ones.

**Apply:**
- Use progress indicators to show incomplete tasks and motivate completion.
- Tease additional content ("3 more results...", "Swipe for next...").
- Save user progress in multi-step flows so they can return.
- Use "save for later" and reminders to re-engage users with unfinished tasks.

---

## DESIGN AUDIT CHECKLIST

When reviewing an existing interface, run through these checks:

### Layout & Visual Hierarchy
- [ ] Are related items grouped using Proximity, Similarity, and Common Region?
- [ ] Is the visual hierarchy clear (size, color, spacing guide the eye)?
- [ ] Are complex shapes simplified per Prägnanz?

### Navigation & Information Architecture
- [ ] Does the navigation follow Jakob's Law (familiar patterns)?
- [ ] Are menu items chunked per Miller's Law (not overwhelming)?
- [ ] Is the most important item at the start or end (Serial Position Effect)?

### Forms & Input
- [ ] Are touch targets ≥44px with adequate spacing (Fitts's Law)?
- [ ] Is the system liberal with input acceptance (Postel's Law)?
- [ ] Is complexity hidden behind smart defaults (Tesler's Law)?

### Task Flows & Completion
- [ ] Are choices minimized at each step (Hick's Law)?
- [ ] Is there clear progress indication (Goal-Gradient Effect)?
- [ ] Does the ending delight or reassure (Peak-End Rule)?
- [ ] Are incomplete tasks surfaced to motivate return (Zeigarnik Effect)?

### Performance & Responsiveness
- [ ] Does feedback happen within 400ms (Doherty Threshold)?
- [ ] Are loading states masked with animations/skeleton screens?
- [ ] Is cognitive load kept in check (remove unnecessary elements)?

### Emotional & Psychological
- [ ] Is the aesthetic polished to boost perceived usability?
- [ ] Are key moments designed for positive emotional peaks?
- [ ] Is distinctive styling used for important items (Von Restorff Effect)?
- [ ] Is contextual help available at the point of need (Active User)?

---

## KEY NUMBERS TO REMEMBER

| Metric | Value | Source |
|--------|-------|--------|
| Touch target minimum (iOS) | 44 × 44 px | Apple HIG |
| Touch target minimum (Android) | 48 × 48 dp | Material Design |
| Touch target spacing | ≥ 8dp (minimum), 12-16dp (comfortable) | Material Design |
| Average finger pad size | 10-14mm | MIT Touch Lab |
| System response time | < 400ms | Doherty Threshold |
| Working memory capacity | 7 ± 2 chunks | Miller's Law |
| Text expansion (English → other languages) | Up to 300% | W3C / Postel's Law |

---

## SOURCE

Based on [Laws of UX](https://lawsofux.com/) by Jon Yablonski and *Laws of UX: Design Principles for Persuasive and Ethical Products* (O'Reilly, 2020).

The compiled reference document with all 30 laws in full detail lives at: `C:\Users\Nithilan\laws-of-ux.md`
