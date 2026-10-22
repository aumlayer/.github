# Set the AUMLayer logo on the org header (not just the README)

GitHub uses **two different images**:

| Place | What you see | How it is set |
|-------|----------------|---------------|
| **Org header** (circle/square next to “aumlayer”) | Pink **identicon** until you change it | **Settings → Profile → Upload new picture** |
| **Profile README** (center of Overview tab) | Logo above “AUMLayer” title | [`profile/README.md`](../profile/README.md) → `assets/aumlayer-logo.png` ✅ |

The README logo is already a **transparent PNG**. The header identicon only changes when an **org owner** uploads the same file in settings.

## Steps (org owner, ~1 minute)

1. Download the transparent logo:  
   **[assets/aumlayer-logo.png](https://github.com/aumlayer/.github/raw/main/assets/aumlayer-logo.png)**  
   (Right‑click → Save link as…)

2. Open org profile settings:  
   **https://github.com/organizations/aumlayer/settings/profile**

3. Under **Profile picture**, click **Upload new picture**.

4. Select `aumlayer-logo.png` → adjust crop → **Set new organization picture**.

5. Hard-refresh https://github.com/aumlayer (Ctrl+Shift+R). CDN cache can take 1–2 minutes.

## Local file (if you cloned this repo)

```text
assets/aumlayer-logo.png
```

1024×1024 RGBA, transparent background (no black box on dark theme).

## Link previews (ChatGPT, Slack, etc.)

Those previews use the **org header avatar**, not the README image — uploading in step 3 fixes them too.
