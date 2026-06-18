# Revenue Sol — Documentation

Official documentation for [Revenue Sol](https://www.revenuesol.com) — the all-in-one AI CRM for local service businesses. Built with [Mintlify](https://mintlify.com).

## Structure

- `mint.json` — site config (navigation, theme, branding)
- `introduction.mdx`, `quickstart.mdx` — getting started
- `guides/` — product/help-center guides (inbox, AI employee, voice agent, jobs, payments, reviews, knowledge hub, mobile app)
- `integrations/` — connecting Twilio, RingCentral, Stripe, QuickBooks, Google
- `developers/` — webhooks, embeddable widgets, and integration notes
- `logo/`, `favicon.svg` — brand assets (placeholders — replace with final art)

## Local development

Install the Mintlify CLI and run the dev server from the repo root:

```bash
npm i -g mintlify
mintlify dev
```

The site runs at `http://localhost:3000`. Edits to `.mdx` files hot-reload.

## Deploying

Connect this repo in the [Mintlify dashboard](https://dashboard.mintlify.com). On every push to the default branch, Mintlify rebuilds and deploys. Point `docs.revenuesol.com` at Mintlify via a CNAME record in your DNS.

## Notes

- Brand assets in `logo/` and `favicon.svg` are simple placeholders — swap in the final Revenue Sol artwork.
- Screenshots are marked with placeholders in the guides; drop real images into an `images/` folder and reference them with Mintlify's `<Frame>`.
