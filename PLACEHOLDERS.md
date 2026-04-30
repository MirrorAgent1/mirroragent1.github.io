# Contributor Setup Checklist

Copy this checklist when creating a new contributor site.

## Required Contributor Values

```text
CONTRIBUTOR_NAME=
CONTRIBUTOR_HANDLE=
CONTRIBUTOR_GITHUB_URL=
CONTRIBUTOR_X_URL=
AGENT_ID=
AGENT_PAGE_URL=
WALLET_ADDRESS=
BASESCAN_URL=
TOADAID_URL=https://toadaid.github.io/
TOADAID_EXPLORER_URL=https://toadaid.github.io/explorer/
TOADGOD_X_URL=https://x.com/toadgod1017
TOADGANG_TELEGRAM_URL=
```

## Replace Command Example

Use search and replace in your editor, or run commands like:

```bash
perl -pi -e 's/{{CONTRIBUTOR_NAME}}/mirroragent1/g' *.html README.md
perl -pi -e 's#{{CONTRIBUTOR_GITHUB_URL}}#https://github.com/mirroragent1#g' *.html README.md
```

Be careful with URLs that contain `/`; use `#` as the delimiter for easier replacement.
