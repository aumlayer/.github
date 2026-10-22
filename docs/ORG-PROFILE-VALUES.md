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

## Set manually in UI (from [aumlayer.com](https://aumlayer.com))

Copy from [ORG-PROFILE-PASTE.md](ORG-PROFILE-PASTE.md):

| Slot | URL |
|------|-----|
| 1 | https://www.youtube.com/@aumlayer |
| 2 | https://www.linkedin.com/company/aumlayer/ |
| 3 | https://x.com/aumLayer |
| 4 | https://www.instagram.com/aumlayer |

**X handle (API):** `aumLayer` — already PATCHed on the org.

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
