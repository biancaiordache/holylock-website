# holylock.com

Marketing + legal pages for HolyLock. Static HTML, no build step.

## Structure

```
/
├── index.html       # Landing page (holylock.com)
├── support.html     # /support — FAQ + contact
├── privacy.html     # /privacy — privacy policy
├── terms.html       # /terms — terms of service
├── styles.css       # Shared styles
└── vercel.json      # Clean URLs (/support instead of /support.html)
```

## Deploying

1. Push this folder to a new GitHub repo.
2. In Vercel: New Project → import the repo → framework preset "Other" → leave build/output settings default (root = `/`).
3. Point `holylock.com` at Vercel via the DNS records Vercel provides on the domain settings page.

## Email

Set up `support@holylock.com`, `privacy@holylock.com`, `hello@holylock.com` as aliases in Google Workspace, or use a free MX forwarder like [ImprovMX](https://improvmx.com) pointing to your primary inbox.

## Editing

Just edit the HTML or CSS and push. No build. Fonts (EB Garamond + Inter) load from Google Fonts.

## Branding notes

- Palette mirrors the iOS app's design system (cream, rose, burgundy)
- Voice follows the guardrails in `V2_IDEAS.md` — soft, aspirational, no masculine "conquer/crush" vocabulary
- Effective date on legal pages: 24 April 2026 — bump when materially changed
