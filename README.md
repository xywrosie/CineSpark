# CineSpark — Website skeleton and Submission Form spec

This repo contains a minimal single-page site with three sections: Hero, Explain, and Project Submission. The submission uses an embedded form from Google Forms / Typeform / Tally.

How to embed your form

- Create the form in Google Forms, Typeform, or Tally.
- Copy the provider's embed URL or iframe code.
- Replace the `src` value inside the `<iframe id="formFrame">` in `index.html` with the provider's embed URL (or paste the full iframe markup).

Example embed snippets

- Google Forms: use the iframe `src` from the "Send" → "<>" embed code.

- Typeform (example):
  <iframe src="https://form.typeform.com/to/XXXX" width="100%" height="650" frameborder="0"></iframe>

- Tally (example):
  <iframe src="https://tally.so/embed/XXXXX" width="100%" height="650" frameborder="0"></iframe>

Submission form fields (design spec)

Basic Information

- Name (short answer)
- Email (email)
- University / Location (short answer)

Film Project Information

- Film title (or working title) (short answer)
- Logline — 1–2 sentence description (paragraph)
- Estimated budget (multiple choice)
  - Under $5K
  - $5K–$10K
  - $10K–$20K
  - $20K+
- Stage of project (multiple choice)
  - Idea
  - Script written
  - Pre-production
  - Currently filming

Funding Questions (Important for Learning)

- What is your biggest challenge right now? (multiple choice)
  - Raising money
  - Finding an audience
  - Distribution after the film is finished
  - Marketing / promotion

Interest Validation Question

- If CineSpark existed, would you submit your project? (multiple choice)
  - Yes
  - Maybe
  - No

Optional

- Would you be interested in being part of the CineSpark pilot program? (yes/no)

Next steps I can take for you

- I can create the form in Google Forms or Tally and paste the embed into `index.html` (tell me which service), or you can create the form and paste the embed URL here and I will update the iframe for you.
# CineSpark
