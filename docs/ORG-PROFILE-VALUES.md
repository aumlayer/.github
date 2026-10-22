# Organization profile — recommended values

Fields updated via GitHub API unless noted. Edit in  
**Settings → General → Profile**  
https://github.com/organizations/aumlayer/settings/profile

## Set automatically (API)

| Field | Value |
|-------|--------|
| **Organization display name** | `AUMLayer` |
| **Email (public)** | `info@aumlayer.com` |
| **Description** | Engineering, security research, and operator education. Open CVE labs & IR tools: github.com/aumlayer/security-labs |
| **URL** | https://aumlayer.com |
| **Location** | India |
| **Company** (metadata) | AUMLayer |

## Already in UI

| Field | Value |
|-------|--------|
| **Billing email (private)** | `info@aumlayer.com` |
| **Profile picture** | Transparent `assets/aumlayer-logo.png` (upload in UI) |

## Optional — set manually in UI

GitHub’s four **Social account** slots are UI-only (no stable public API). Suggested order:

| Slot | Suggestion |
|------|------------|
| 1 | https://github.com/aumlayer/security-labs |
| 2 | https://www.youtube.com/@… *(your channel)* |
| 3 | https://www.linkedin.com/company/… *(if applicable)* |
| 4 | https://aumlayer.com |

**Gravatar email:** leave empty if you use uploaded picture (not Gravatar).

After changes, click **Update profile** at the bottom of the General page.

## Re-apply via CLI (owners)

```bash
gh api -X PATCH orgs/aumlayer \
  -f name='AUMLayer' \
  -f email='info@aumlayer.com' \
  -f company='AUMLayer' \
  -f blog='https://aumlayer.com' \
  -f location='India' \
  -f description='Engineering, security research, and operator education. Open CVE labs & IR tools: github.com/aumlayer/security-labs'
```
