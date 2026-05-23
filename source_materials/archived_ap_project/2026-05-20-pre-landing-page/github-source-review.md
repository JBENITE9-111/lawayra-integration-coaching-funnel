# GitHub Source Review For Landing Page Work

Reviewed root: `/Users/macmac/GitHub`

## High-Signal Sources Found

### 1. Landing page project template

Path:
`/Users/macmac/GitHub/10_landing_pages_websites/README.md`

Useful finding:
This folder is an index for landing pages, websites, web apps, reusable components, copywriting, design references, assets, experiments, and archived sites.

Recommended structure from the file:
- `brief.md`
- `copy.md`
- `design_notes.md`
- `source/`
- `assets/`
- `screenshots/`
- `versions/`

Applied to AP project.

### 2. Brand voice skill

Path:
`/Users/macmac/GitHub/02_skills_and_agents/claude_skills/everything_claude_main_skills/brand-voice/SKILL.md`

Useful workflow:
- Build voice from real source material, not generic examples.
- Gather 5-20 representative samples when possible.
- Prefer recent material.
- Extract rhythm, sentence length, claim style, capitalization, question usage, transitions, and words to avoid.
- Produce a reusable voice profile before drafting.

Landing page use:
When final coach/customer materials arrive, build a voice profile before writing page copy.

### 3. Content engine skill

Path:
`/Users/macmac/GitHub/02_skills_and_agents/claude_skills/everything_claude_main_skills/content-engine/SKILL.md`

Useful workflow:
- Start from source material.
- One section/output should carry one real claim.
- Specificity beats adjectives.
- Avoid hype language and platform filler.
- Repurpose source material by extracting 3-7 atomic claims, ranking them, and assigning one strong idea per output.

Landing page use:
Use uploaded docs, transcripts, testimonials, and social posts as the source set. Extract atomic claims for hero, proof, method, and FAQ.

### 4. Product lens skill

Path:
`/Users/macmac/GitHub/02_skills_and_agents/claude_skills/everything_claude_main_skills/product-lens/SKILL.md`

Useful diagnostic questions:
- Who is this for?
- What is the pain?
- Why now?
- What is the 10-star version?
- What is the MVP?
- What is the anti-goal?
- How do you know it is working?

Landing page use:
Use these questions as the intake layer before copy or design. They prevent a vague page.

### 5. Conversion engine

Path:
`/Users/macmac/GitHub/05_marketing_sales/lead_generation/AI-LEAD-OUTREACH-SYSTEM/06_conversion/outreach-engine.md`

Useful workflow:
- Choose strategy before writing.
- Choose hook before message.
- Use one clear ask.
- No generic language.
- Every line must connect to a real signal.

Landing page use:
The same logic applies to page CTAs:
- Decide the main conversion path first.
- Select the strongest hook.
- Make every section support one action.

### 6. Frontend design skill

Path:
`/Users/macmac/GitHub/02_skills_and_agents/claude_skills/everything_claude_main_skills/frontend-design/SKILL.md`

Useful workflow:
- Frame purpose, audience, emotional tone, visual direction, and one memorable idea before coding.
- Build type hierarchy, color variables, spacing rhythm, layout logic, motion rules, and surface treatment.
- Pick a direction and commit to it.
- Avoid generic SaaS hero sections and random card piles.

Landing page use:
When final assets arrive, choose the visual direction based on the offer and audience, not the LaWayra sample.

### 7. Design system skill

Path:
`/Users/macmac/GitHub/02_skills_and_agents/claude_skills/everything_claude_main_skills/design-system/SKILL.md`

Useful workflow:
- Extract colors, typography, spacing, radius, shadows, breakpoints.
- Score UI on color consistency, typography hierarchy, spacing rhythm, component consistency, responsiveness, accessibility, information density, and polish.
- Watch for AI-looking defaults: gratuitous gradients, glass cards, generic centered hero, bland font stack.

Landing page use:
Create design tokens once final brand assets arrive. Audit the final page against the listed dimensions.

### 8. Frontend patterns skill

Path:
`/Users/macmac/GitHub/02_skills_and_agents/claude_skills/everything_claude_main_skills/frontend-patterns/SKILL.md`

Useful workflow:
- Use component composition.
- Keep forms controlled and validated.
- Use accessible responsive UI patterns.
- Optimize performance.

Landing page use:
If building in React/Next later, split the page into semantic components: Header, Hero, Problem, Method, Proof, FAQ, CTA, Footer.

### 9. SEO skill

Path:
`/Users/macmac/GitHub/02_skills_and_agents/claude_skills/everything_claude_main_skills/seo/SKILL.md`

Useful checklist:
- Fix technical blockers before content optimization.
- One page should have one clear primary search intent.
- Mobile-first matters.
- One clear H1.
- Title tag around 50-60 characters.
- Meta description around 120-160 characters.
- FAQ schema only when matching content is visible.

Landing page use:
Add SEO metadata and schema after the final offer and brand details are confirmed.

### 10. Browser QA skill

Path:
`/Users/macmac/GitHub/02_skills_and_agents/claude_skills/everything_claude_main_skills/browser-qa/SKILL.md`

Useful checklist:
- Check console errors.
- Check failed network requests.
- Screenshot desktop and mobile.
- Test nav and CTAs.
- Test forms.
- Test 375px, 768px, 1440px.
- Check accessibility basics.

Landing page use:
Use before final handoff. Especially important for booking/calendar links and mobile hero layout.

## Low-Signal / Not Used

Most `/Users/macmac/GitHub` matches were unrelated automation, n8n internals, code examples, archived backups, or generic framework docs. I did not add those to the AP project because they do not materially help create a landing page.

## Current Project Decision

The AP project should be a reusable landing-page toolkit, not a LaWayra-specific page.

LaWayra sample assets and copy are only placeholders for structure. Replace them when final customer assets arrive.
