# Heart Knows — legal & support pages

Public GitHub Pages site for App Store Connect and Google Play **Support** and
**Privacy Policy** URLs. Contains HTML only — no app source code.

**Do not edit the HTML here by hand.** It is synced from the private
`vibe_tracker` repository:

```bash
# From vibe_tracker repo root:
docs/store/tools/sync_legal_site.sh --push
```

## Live URLs

After Pages is enabled (**Settings → Pages → Source: GitHub Actions**):

| Page | URL |
|------|-----|
| Support | `https://rishabhds.github.io/heartsignals-legal/support.html` |
| Privacy | `https://rishabhds.github.io/heartsignals-legal/legal/privacy-policy.html` |
| Terms | `https://rishabhds.github.io/heartsignals-legal/legal/terms-of-service.html` |

GitHub lowercases the username in Pages URLs (`rishabhDS` → `rishabhds`).
