# Concur US2 Dark Mode TamperMonkey Script

A Tampermonkey/Violentmonkey userscript that applies an AWS Cloudscape-aligned dark theme to the SAP Concur expense portal at `https://us2.concursolutions.com`.

## What This Repository Contains

- `concur_us2_dark_mode.user.js` — the Tampermonkey userscript.
- `STANDARDS.md` — Cloudscape Dark Mode Standard v3.3.
- `SANITIZATION.md` — what was scrubbed before this repo was made public.
- `LICENSE` — MIT.

## Behavior Coverage

Follows the **Cloudscape Dark Mode Standard v3.3**. Forces a Cloudscape palette on the Concur shell, sign-in screen (the hero photo stays untouched as media), expense reports, travel itinerary, approvals queue, dashboard tiles, settings, and footer. Preserves SAP Concur brand blue logo and brand-color CTAs.

The match also covers `*.concursolutions.com` so future Concur subdomain rotations stay covered.

## Install on Chrome / Firefox

1. Install Tampermonkey: <https://www.tampermonkey.net>
2. Open: `https://raw.githubusercontent.com/BarnsAWS/Concur-US2-Dark-Mode-TamperMonkey-Script/main/concur_us2_dark_mode.user.js`
3. Click **Install**.
4. Visit `https://us2.concursolutions.com` and refresh.

## Bundle Alternative

Bundle: <https://github.com/BarnsAWS/AWS-DC-Full-Open-Source-Dark-Mode-Bundle> — install once, themes all 12+ sites.

## License

MIT.
