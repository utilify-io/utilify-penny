# Utilify Penny

Penny is a free bot from [Utilify](https://utilify.io). She helps people moving to or within Texas analyze utility plans: electricity, internet, gas, water and trash.

Penny runs on Grok, xAI's assistant. Utilify is not affiliated with or endorsed by xAI.

## Use Penny

- Open Penny: https://x.ai/bot/gaFSyxjxWJNddVve3sy7o
- Meet Penny on the web: https://utilify.io

## Support Penny

Penny is free. If she helped you, you can [tip Penny](https://buy.stripe.com/9B67sLeBGfzbd0gcM38g004) (you choose the amount; $5 suggested). Tips go to Utilify LLC and are not tax-deductible.

## Current version

Penny checks for updates at https://utilify.io/penny/version.json, which is public and allows cross-origin requests.

| Field | Meaning |
| --- | --- |
| `latest_version` | Current template version |
| `released` | Release date (YYYY-MM-DD) |
| `template_url` | Where to get the current version |
| `repo_url` | This repository |
| `donation_url` | Tip link (Stripe) |
| `feedback_url` | `null` until set |
| `notes` | What changed |

The current version is **18** (2026-11-19).

## What Penny does not do

- Penny does not enroll anyone in an electricity plan and does not take payment.
- Penny never asks for a Social Security number, date of birth or driver's license number.
- For official Texas electricity plan listings, see [Power to Choose](https://www.powertochoose.org), the Public Utility Commission of Texas site.

## Data for AI agents

Penny uses the same Texas utility data as Utilify's public MCP server: https://github.com/utilify-io/utilify-mcp

## Disclosure

Utilify LLC is registered with the Public Utility Commission of Texas as a broker (registration BR260291). Utilify may receive compensation from providers. Plans are ranked by estimated annual cost, not by compensation. Full disclosure: https://utilify.io/broker-disclosure

## Contact

hello@utilify.io
