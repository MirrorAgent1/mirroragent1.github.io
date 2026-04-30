# ToadAid Contributor Website Template

A reusable GitHub Pages template for Toadgang contributors who have forged their Agent Identity.

This template creates a simple public doorway for each contributor, including:

- Contributor identity
- Forged Agent ID
- Public-good contribution message
- ToadAid links
- Toadgod X link
- Toadgang Telegram link
- GitHub / social links

## Pages

- `index.html` — contributor doorway
- `about.html` — contributor identity and vow
- `toadaid.html` — what ToadAid is
- `agent.html` — forged Agent ID / onchain identity
- `links.html` — important links
- `style.css` — shared blue pond / lotus theme
- `script.js` — mobile navigation and navbar behavior

## Replace These Placeholders

```text
{{CONTRIBUTOR_NAME}}
{{CONTRIBUTOR_HANDLE}}
{{CONTRIBUTOR_GITHUB_URL}}
{{CONTRIBUTOR_X_URL}}
{{AGENT_ID}}
{{AGENT_PAGE_URL}}
{{WALLET_ADDRESS}}
{{BASESCAN_URL}}
{{TOADAID_URL}}
{{TOADAID_EXPLORER_URL}}
{{TOADGOD_X_URL}}
{{TOADGANG_TELEGRAM_URL}}
```

## Suggested Default Links

```text
{{TOADAID_URL}} = https://toadaid.github.io/
{{TOADAID_EXPLORER_URL}} = https://toadaid.github.io/explorer/
{{TOADGOD_X_URL}} = https://x.com/toadgod1017
{{TOADGANG_TELEGRAM_URL}} = https://t.me/YOUR_TELEGRAM_GROUP_HERE
```

Update the Telegram link to the official/live Toadgang group invite link before publishing.

## Publish

```bash
git add index.html about.html toadaid.html agent.html links.html style.css script.js README.md
git commit -m "Build ToadAid contributor website"
git push origin main
```

## ToadAid

One toad, one light.  
One contribution, one ripple.
