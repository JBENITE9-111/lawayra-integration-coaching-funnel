# Design Notes And Build Standards

## Project Template From GitHub

The `/Users/macmac/GitHub/10_landing_pages_websites/README.md` folder recommends this project shape:

- `brief.md`
- `copy.md`
- `design_notes.md`
- `source/`
- `assets/`
- `screenshots/`
- `versions/`

This AP project now follows that structure.

## Visual System Checklist

Before designing:
- Define purpose
- Define audience
- Define emotional tone
- Define visual direction
- Define the one thing the visitor should remember

Design tokens to create after final assets arrive:
- Colors
- Font stack
- Spacing scale
- Border radius
- Button styles
- Section backgrounds
- Breakpoints
- Shadows or no-shadow rule
- Image treatment
- Motion rules

## LaWayra Template Brand Specs

Use these only when the final page should follow LaWayra branding or when creating the sample/template page.

- Font: Poppins from Google Fonts.
- Heading weight: 700.
- Body weight: 400.
- Template import: `https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400&display=swap`
- Olive: `#3F4021`.
- Cream: `#FFF7E7`.
- Amber CTA: `#E4A017`.
- Charcoal: `#2B2728`.
- Logo asset: `lawayra-logo-new.png`, transparent outline flower.
- Voice: warm, authentic, compassion-first, grounded, clear.

The Integration Series template also uses supporting earth tones such as sage, beige, burnt orange, and brown. Keep amber as the primary CTA color so actions remain visually distinct.

## Landing Page Visual Requirements

- First viewport must show the offer/person/company clearly.
- Use real coach/customer imagery when available.
- Avoid generic centered hero over stock gradient.
- Avoid card piles with no hierarchy.
- Use enough whitespace for trust and readability.
- CTA must be visually distinct.
- Keep section rhythm predictable.
- Keep mobile layout simple and fast.

## Reusable Page Sections

- Header
- Hero
- Pain / problem
- Why now
- Who it is for
- Outcomes
- Method / framework
- What is included
- Coach bio
- Proof
- Pricing / booking
- FAQ
- Final CTA
- Footer

## Three-Coach Layout Requirements

- Design for three coach photos and three bios from the start.
- On desktop, use a three-column coach comparison section if bios are similar length.
- On tablet, use a two-column then one-column wrap.
- On mobile, stack coach cards with photo, name, role, short bio, and calendar CTA.
- Reserve stable image dimensions with `aspect-ratio` so card heights do not jump during image load.
- If each coach has a separate calendar, make the CTA label specific: `Book with [Name]`.
- If there is one shared team calendar, use one CTA repeated consistently and explain what happens after booking.
- Do not use the Monica image as final content unless explicitly approved; it is a sample asset from the template.

## Accessibility

- One H1.
- Use semantic sections.
- Every image needs meaningful alt text or empty alt if decorative.
- Buttons and links must have clear labels.
- Focus states must be visible.
- Text contrast should meet WCAG AA where possible.
- Mobile tap targets should be comfortable.

## Performance

- Compress and resize coach/hero images.
- Use explicit width/height or aspect-ratio on major media.
- Keep JavaScript minimal.
- Preload only the true hero asset.
- Avoid layout shifts around images, embeds, and forms.

## Browser QA Checklist

Test at:
- 375px mobile
- 768px tablet
- 1440px desktop

Check:
- Above-the-fold screenshot
- No horizontal overflow
- Nav links work
- CTA links work
- Calendar opens correctly
- Form valid/invalid states work
- No major console errors
- No failed local assets
- Hero image frames correctly
- Text does not overlap
- FAQ expands/collapses if interactive

## SEO Checklist

- Title tag: 50-60 characters
- Meta description: 120-160 characters
- One clear H1
- H2/H3 hierarchy matches content
- Descriptive image alt text
- Canonical URL when deployed
- FAQ schema only if FAQ is visible
- Person or Organization schema only after final details are confirmed

## Anti-Patterns To Avoid

- Generic AI-sounding copy
- Overpromising outcomes
- Too many competing CTAs
- Hero that does not say what the offer is
- Vague coach bio
- Testimonials with no specific transformation
- Hidden or unclear pricing when the flow needs clarity
- Booking buttons that do not explain what happens next
- Desktop-only design
