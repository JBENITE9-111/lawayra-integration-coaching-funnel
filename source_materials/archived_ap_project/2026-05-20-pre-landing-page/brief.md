# Landing Page Build Brief

Purpose: create a reusable landing page system for a future coaching offer. The LaWayra integration page is only a structural sample. Final offer details, coach photos, booking calendars, testimonials, dates, prices, and brand assets will be replaced with new uploaded customer information.

## Project Goal

Build a proper landing page that can convert visitors into booked calls or purchases once the final business/coach information is provided.

The page should be able to support either:
- A direct booking flow: landing page -> calendar -> booked call
- A direct purchase flow: landing page -> checkout -> thank-you page
- A warm-lead flow: landing page -> lead form / WhatsApp / email -> follow-up

## Required Inputs Before Final Build

Offer:
- Offer name
- One-sentence promise
- Who it is for
- Primary pain/problem
- Desired outcome
- Offer format: 1:1, group, cohort, course, workshop, retreat, subscription, or hybrid
- Duration and cadence
- Price or price placeholder
- Guarantees, refund policy, or eligibility notes
- What is included
- What is not included

Coach/company:
- Three coach names
- Three coach roles and credentials
- Short bio for each coach
- Coaching method/framework
- Why each coach is credible
- Three new coach photos
- Three booking calendar URLs, one per coach, unless the final flow uses one shared team calendar
- Brand logo
- Brand colors/fonts if different from sample

Conversion:
- Primary CTA
- Booking calendar URL
- Checkout URL, if any
- Thank-you page destination
- Contact fallback: WhatsApp, email, phone, or form
- Lead capture fields
- CRM / tracking requirements

Proof:
- Testimonials
- Case studies
- Screenshots or reviews
- Before/after stories
- Trust badges, certifications, press, client logos
- Results data, if legally safe to claim

Content/legal:
- Final copy claims that are allowed
- Claims to avoid
- Medical/therapeutic/legal/financial disclaimers if relevant
- Privacy policy URL
- Terms URL

## Recommended Landing Page Structure

1. Header
   - Logo
   - Minimal nav: Program, Coach, Details, FAQ
   - Persistent CTA

2. Hero
   - Specific offer label
   - Clear H1 with the offer or outcome
   - Human subhead
   - Primary CTA
   - Secondary CTA if useful
   - Real visual asset, ideally coach or domain-specific image

3. Problem / Pain
   - Mirror the visitor's current state
   - Use concrete symptoms, not generic anxiety
   - Avoid overclaiming or diagnosing

4. Why This Matters Now
   - Explain the cost of staying where they are
   - Explain why the offer exists
   - Bridge from pain to method

5. Who It Is For
   - Positive-fit bullets
   - Optional "not for you if" guardrails

6. Outcome / Transformation
   - What changes after the work
   - Practical, believable outcomes
   - Separate emotional outcomes from tactical deliverables

7. Method / Framework
   - The coach's process
   - Steps, pillars, modules, phases, or weekly path
   - This should become the page's central credibility section

8. What Is Included
   - Calls/sessions
   - Resources
   - Support channel
   - Community
   - Recordings
   - Worksheets/templates
   - Personal plan

9. Coach Bio
   - Support three coaches total
   - Real photo for each coach
   - Credentials for each coach
   - Relevant story for each coach
   - Why each coach's experience maps to the audience's problem
   - Individual booking CTA/calendar for each coach, if applicable

10. Social Proof
   - Testimonials
   - Outcomes
   - Screenshots
   - Review snippets
   - Client logos if available

11. Pricing / Booking
   - Price or call-to-apply framing
   - What happens after clicking
   - Calendar or checkout CTA
   - Friction reducers: limited spots, application criteria, support availability

12. FAQ
   - Who is this for?
   - What happens after I book?
   - Is this live or recorded?
   - How much time does it take?
   - What if I miss a session?
   - What results are realistic?
   - Is this a fit if I am new / advanced?

13. Final CTA
   - Restate the core outcome
   - Repeat primary CTA
   - Add contact fallback

14. Footer
   - Logo
   - Contact
   - Legal links
   - Copyright

## Page Strategy

The page should not begin by explaining every feature. It should start with:
- Who this is for
- What they are struggling with
- What the coaching helps them do
- Why this coach is credible
- What to do next

Primary conversion rule:
One page, one main action. If the final offer is call-based, the main CTA should be the calendar. If it is purchase-based, the main CTA should be checkout.

Secondary CTAs should support the main CTA, not compete with it.

## Copy Rules

- Start from source material, not generic formulas.
- Build a voice profile from real coach/company writing before drafting.
- Use short, direct sections.
- Avoid vague promises like "transform your life" unless backed by specifics.
- Use concrete mechanisms: calls, framework, exercises, support, feedback, accountability.
- Every CTA should tell the visitor exactly what happens next.
- Testimonials should support specific doubts: trust, safety, results, fit, process.

## Design Direction

The sample LaWayra structure uses a warm, grounded, coaching/wellness layout. For the final page, visual direction should be chosen after the new brand assets arrive.

Reusable design requirements:
- Strong first viewport with real brand/product/person signal
- Clear typography hierarchy
- Responsive mobile layout
- Real photos, not generic stock visuals
- CTA color must stand out from the base palette
- Consistent spacing scale
- No decorative clutter
- No nested card-heavy layout
- Accessibility: readable contrast, alt text, keyboard-visible focus states

## SEO Requirements

- One clear H1
- Page title around 50-60 characters
- Meta description around 120-160 characters
- Heading hierarchy must reflect the page structure
- Add FAQ schema only if FAQ content is visible on the page
- Add Organization / Person schema when final coach/company details are confirmed
- Optimize hero image size and reserve dimensions to avoid layout shift

## QA Requirements

Before final delivery:
- Test desktop, tablet, and mobile screenshots
- Check all nav links
- Check calendar/checkout/contact links
- Check form validation if a form exists
- Check no horizontal overflow on mobile
- Check console/network errors
- Check key accessibility issues: labels, alt text, contrast, focus order

## LaWayra Sample Usage

Use LaWayra only as a reference for structure:
- Hero -> pain -> why it matters -> who it is for -> outcomes -> program breakdown -> included -> facilitator -> pricing/booking -> FAQ -> final CTA.

Do not treat LaWayra dates, pricing, Monica bio, integration PDF, or retreat-specific claims as final content for the new landing page.

## TECH-MARKETING Source Findings

The TECH-MARKETING folder confirms the reusable structure and brand rules, but it does not contain enough final content for a complete 3-coach page.

Found:
- Template structure from `integration-series-landing-page.html`.
- Poppins font usage and LaWayra color system.
- Launch workflow for self-contained HTML pages hosted on GitHub Pages.
- One complete sample coach profile/photo from the Integration Series page: Monica Kronstain.
- Partial community/team references for possible additional facilitators, including Dan and Samuel Araya, but without complete landing-page bios, final photos, or individual booking calendar URLs.

Missing before final build:
- Coach 2 final name, role, bio, photo, and calendar URL.
- Coach 3 final name, role, bio, photo, and calendar URL.
- Final offer name, promise, pricing, schedule, checkout or booking flow, proof, and legal/disclaimer language.
- Final hero direction: one group hero image, three coach portraits, or a separate program image plus coach cards.
