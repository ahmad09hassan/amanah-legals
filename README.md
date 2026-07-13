# Amanah Legal Solutions - LPO Landing Page

High-converting landing page for Amanah Legal Solutions, a Legal Process Outsourcing (LPO)
firm serving U.S. law firms from Sheridan, Wyoming.

## Stack

Zero-dependency static site: a single self-contained `index.html` (inline CSS/JS,
Google Fonts). No build step.

- `index.html` - the landing page
- `thanks.html` - form submission confirmation page

## Forms

The lead form uses [Netlify Forms](https://docs.netlify.com/forms/setup/)
(`data-netlify="true"`, form name `lead`, honeypot `bot-field`). Submissions appear in
the Netlify dashboard under **Forms  lead** once deployed. The form redirects to
`/thanks.html` on success.

## Deploy

Any static host works. For Netlify: connect the repo, no build command, publish
directory `/`.

## Conversion architecture (for future editors)

The page is structured as a legal brief - each section is an "exhibit" in the argument:

| Section | Job |
|---|---|
| Hero | Pain-led headline + risk reversal in the first screen |
| Facts bar | Trust proof (NDA, lawyer review, US registration, no retainer) |
| Exhibit A | Problem agitation + cost-of-inaction math |
| Exhibit B | Named mechanism: the Attorney-Ready Method (5 steps, 2 gates) |
| Exhibit C | Services + practice areas |
| Exhibit D | Confidentiality (top objection for law firms) |
| Exhibit E | Offer stack + Attorney-Ready Guarantee (risk reversal) |
| Exhibit F | FAQ (objection handling) |
| Contact | Lead form + direct booking path |

Keep every claim defensible. The guarantee ("if the first deliverable isn't
attorney-ready, you don't pay") is a real business commitment - don't ship copy the
firm can't honor.
