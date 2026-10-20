# With Nate Media — Consulting Website

Responsive, static consulting website using With Nate Media brand colors: evergreen **#108E52**, deep violet **#25033D**, navy **#000080**, and near-black surfaces.

## Pages

- `index.html` — consulting-led homepage, services overview, industries, client outcomes, how we work, and About
- `services.html` — strategy and transformation, product engineering, AI/data, fractional leadership, engineering augmentation, and executive advisory
- `industries.html` — health and wellness, technology and SaaS, professional services, commerce, sports/entertainment, and regulated operations
- `case-studies.html` — four engagement summaries, with confidential client names withheld
- `styles.css` — shared responsive design system
- `logo-mark.svg` — brand mark derived from the user-supplied Illustrator file (SVG vector paths)

## How to publish

1. Visit https://vercel.com/new and import `nd-wnatemedia/with-nate-media-website`.
2. Choose **Other** for the framework preset. Static HTML does not require a build. Set output directory to `.` if Vercel asks.
3. Deploy and check the generated preview URL.
4. In Vercel Project Settings > Domains, add `wnatemedia.com` and `www.wnatemedia.com`.
5. Set the exact DNS records Vercel provides at your registrar. **Do not replace MX, SPF, DKIM, or other existing email-related DNS records.**

The website has no database and no runtime API requirements. Commits to the production branch will redeploy when the Vercel project is connected.

## Launch checklist

- [ ] Review the design on the live preview on desktop and mobile.
- [ ] Approve case-study client names and result figures before publishing; do not publicly identify the two confidential clients.
- [ ] Replace the temporary `mailto:nd@wnatemedia.com` contact CTA with the real GHL booking URL, or confirm that mailbox exists. **This email address has not been verified.**
- [ ] Add the final full horizontal logo lockup to the brand assets if desired; the current site incorporates the original vector brand mark.
- [ ] Review privacy requirements if forms, analytics, pixels, or cookies are added.

Client stories are summaries rather than direct testimonial quotes. Results are specific to each engagement and not promises of future performance. The estimated $3M Lava.ai opportunity is **not** booked/realized revenue.

No client-owned partnership badges or designations have been attributed to With Nate Media.
