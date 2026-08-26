# Contributing a Resource

Thanks for helping grow this list! Adding a resource is simple — no build tools, no setup.

## How to add a resource

1. **Fork the repo** and open the main `.html` file.
2. Find the `DATA` array near the bottom of the `<script>` tag. Each resource is one entry:

   ```js
   { title: "Your Resource Title",
     blurb: "One short sentence on what it is and why it helps.",
     links: [ {l:"Link label", u:"https://example.com"} ] }
   ```

3. Add your entry inside the right **category**:
   - **Beginner** — Python/ML basics, classical ML (regression, trees, clustering), core data science
   - **Intermediate** — neural networks, deep learning fundamentals, training/optimization
   - **Advanced** — computer vision, NLP, audio, diffusion models, and other modern architectures
   - **Practice & Past Tasks** — contest platforms, past IOAI/national-olympiad tasks, datasets

   If you're unsure which category fits, just make your best guess and say so in the PR — we're happy to move it during review.

4. Open a pull request. In the PR description, include:
   - A **short description** of the resource (a sentence or two — what it teaches and who it's for)
   - The **category** you added it under
   - Why it's useful for IOAI prep specifically (if that's not obvious from the description)

## What makes a good submission

- The resource should be **free and openly accessible** (no paywalls, no signup-only content where possible).
- It should map to something on the [official IOAI syllabus](https://ioai-official.org/republic-of-kazakhstan/syllabus-2026/) — if it's outside the syllabus scope, explain why it's still worth including.
- One resource per entry. If you have a bundle (e.g. a full course), that's fine as a single entry — just describe it clearly.
- Keep the `blurb` to one short sentence. It's a signpost, not a summary.

## Review process

- PRs are reviewed within **2–3 days**.
- We may ask you to tweak the category, tighten the description, or split a submission into multiple entries.
- Once approved, it's merged and live on the site immediately — no build step required.

## Reporting a broken or outdated link

Open an issue (or a PR removing/fixing it directly) with the resource title and what's wrong. These get priority since a dead link actively hurts the resource.
