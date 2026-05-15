# Signal Festival

Signal Festival is an immersive event registration site for pass selection, attendee details, structured submissions, validation, and success routing.

This website is powered by Wix Headless and built using [wix-headless.dev](https://www.wix-headless.dev).

## Links

- Live site: [https://signalfestival.events/](https://signalfestival.events)
- Source: [https://github.com/wix-incubator/signalfestival](https://github.com/wix-incubator/signalfestival)
- Wix site ID: `e06b9151-2f47-469d-aee9-6b625cf8911d`

## What It Showcases

- A custom Astro festival registration flow backed by Wix Forms.
- Wix-hosted form schema loading with custom event UI rendering.
- Pass and attendee details submitted through Wix Headless APIs.
- Branded confirmation routing after submission.
- Public `robots.txt` and `llms.txt` configured through Wix SEO txt APIs.
- Deployment with `wix release`.

## Wix Solutions Used

- Wix Headless Site for the managed site/runtime foundation.
- Wix Forms for festival registration fields and submissions.

## Wix SDKs And Packages

- `@wix/astro`
- `@wix/astro-pages`
- `@wix/sdk`
- `@wix/forms`

## Local Development

Create a local env file from `.env.example` or run the Wix CLI env setup for the connected site.

```bash
npm install
npm run dev
```

## Build And Release

```bash
npm run build
npm run release
```
