# Paste into GitHub → Settings → General (org profile)

Open: https://github.com/organizations/aumlayer/settings/profile

Sources: [aumlayer.com](https://aumlayer.com) (footer/social links).  
After filling **Social accounts** and confirming **Profile picture**, scroll down and click **Update profile**.

---

## Social accounts (copy each line)

| # | URL |
|---|-----|
| 1 | `https://www.youtube.com/@aumlayer` |
| 2 | `https://www.linkedin.com/company/aumlayer/` |
| 3 | `https://x.com/aumLayer` |
| 4 | `https://www.instagram.com/aumlayer` |

Optional fifth (if you swap one slot): `https://github.com/aumlayer/security-labs`

**X (Twitter) handle** is also set via API: `@aumLayer`

---

## Profile picture not sticking?

GitHub only saves the avatar when you click **Update profile** (green button at the bottom).

Checklist:

1. **Gravatar email** — leave **empty** (Gravatar overrides uploaded picture).
2. Upload **`assets/aumlayer-logo.png`** (transparent PNG from this repo).
3. Click **Update profile** once (not only “Upload new picture”).
4. Verify (owners):  
   `gh api orgs/aumlayer -q .avatar_url`  
   After save, open that URL in a private window — it should show the red **A**, not the pink identicon pattern.
5. Hard-refresh the org page (Ctrl+Shift+R). Top-left nav can lag behind the preview box by a few minutes.

If preview shows your logo but the **top-left** org menu is still pink squares **after** step 3, sign out/in or try another browser — that is usually stale session cache.

---

## Already set via API

| Field | Value |
|-------|--------|
| Display name | AUMLayer |
| Public email | info@aumlayer.com |
| URL | https://aumlayer.com |
| Location | India |
| Description | Engineering, security research, and operator education. Open CVE labs & IR tools: github.com/aumlayer/security-labs |
| X username | aumLayer |
