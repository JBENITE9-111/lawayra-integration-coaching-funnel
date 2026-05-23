# How To Build And Launch A Funnel Page

When LaWayra launches a new program, workshop, or offer, it needs its own landing page. The build pattern is a branded, self-contained HTML page hosted on GitHub Pages, with no WordPress or external page builder required.

## Build Process

1. Gather content.
   Collect program name, headline/tagline, start date and schedule, price, checkout URL, program description, what's included, facilitator photo and bio, hero image, and 3-5 FAQ questions. The more complete the source material, the faster the build.

2. Place source files in the project folder.
   Put PDFs, proposals, mockups, promo slide PNGs, and photos in the project directory. Text should be extracted from these files before drafting the page.

3. Run the landing page build workflow.
   In Claude Code, run `/build-landing-page` and provide the offer details and file locations. Claude Code reads source files, extracts content, applies LaWayra branding, and generates a self-contained HTML page.

4. Review the page locally.
   Open the HTML file in a browser. Check content accuracy, mobile responsiveness, facilitator photos, CTA button links, logo rendering, and section flow. Request specific changes such as heading size, hero image swap, copy edits, or price changes.

5. Push to GitHub.
   Tell Claude Code to push. It should update `.gitignore` if needed, commit, and push to `origin main`. The page goes live on GitHub Pages within 1-2 minutes.

6. Share the viewable URL.
   Use this format: `https://marcuswest-lab.github.io/lawayra-content-strategy/[filename].html`.

## Brand Specs For Landing Pages

- Font: Poppins from Google Fonts.
- Headings: Poppins Bold, 700.
- Body: Poppins Regular, 400.
- Colors: Olive `#3F4021`, Cream `#FFF7E7`, Amber `#E4A017` for CTAs, Charcoal `#2B2728`.
- Logo: `lawayra-logo-new.png`, outline flower with transparent background.
- Voice: warm, authentic, compassion-first.
- Voice reference expected by the original SOP: `content-machine/lawayra-voice-guide.md`.
- Full SOP expected by the original workflow: `lawayra-landing-page-sop.md`.

## Template Reference

Template: `integration-series-landing-page.html`, the Integration Series page.

Available sections:
- Hero
- Pain Point
- Why It Matters
- Program Breakdown
- Outcomes
- What's Included
- Facilitator Bio
- Pricing
- FAQ
- Final CTA

Not every page needs every section. Adapt the structure based on offer complexity.

## AP Project Note

For this AP project, the Integration Series page is a structure and brand reference only. Do not include the integration PDF or PDF download section unless the user explicitly requests a downloadable resource later.
