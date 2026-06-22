# Just Us — Website

Single-page marketing site for Just Us, Charlotte's private dining experience.

## Before going live

In `index.html`, find the inquiry form and replace:

- `YOUR_EMAIL_HERE` with your real email address (the form uses [FormSubmit](https://formsubmit.co) — no backend needed, free, no signup)
- The placeholder phone number `(704) 555-0123`
- The placeholder Instagram handle `@justus.charlotte`

The first time someone submits the form, FormSubmit emails you a one-time confirmation link — click it once to activate. After that, every inquiry lands in your inbox automatically.

## Deployment

Static site — one HTML file, no build step. Deployed via GitHub + Vercel.

**Live domain:** justuscharlotte.com

To connect the domain in Vercel: Settings → Domains → Add → `justuscharlotte.com`. Add the two DNS records Vercel provides into Namecheap → Domain List → Manage → Advanced DNS. Propagates within a few hours.
