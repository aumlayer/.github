<div align="center">

<!-- Header identicon: org owner must upload assets/aumlayer-logo.png in Settings → Profile (see docs/SET-ORG-AVATAR.md) -->
<img src="https://raw.githubusercontent.com/aumlayer/.github/main/assets/aumlayer-logo.png" width="140" alt="AUMLayer logo" />

# AUMLayer

**Engineering · Security research · Operator education**

[![security-labs](https://img.shields.io/badge/security--labs-public%20CVE%20catalog-020a10?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aumlayer/security-labs)

</div>

---

We ship product platforms internally and publish **defender-focused** open material under a single public catalog — reproducible labs, scanners, and IR notes for **authorized** testing only.

## Featured repository

| | |
|---|---|
| **[security-labs](https://github.com/aumlayer/security-labs)** | Umbrella repo for CVE entries by product/stack. Each entry may include a localhost Docker lab, optional PoC fetch scripts (pinned upstream), and read-only checkers. |
| **Latest entry** | [**PHP2Shell**](https://github.com/aumlayer/security-labs/tree/main/php/cve-2026-109618-php2shell) — CVE-2026-109618 & CVE-2026-109619 — mod_php lab + **PHP2Shell Checker** |

```bash
git clone https://github.com/aumlayer/security-labs.git
cd security-labs/php/cve-2026-109618-php2shell
# Lab
cd lab && ./scripts/up.sh
# Scanner (fixture demo)
cd ../checker && ./run_checker.sh --fixture
```

## Principles

| We publish | We keep private |
|------------|-----------------|
| `127.0.0.1` Docker labs & docs | Video / narration / marketing cuts |
| Log & artifact **scanners** | Customer evidence & host-specific dumps |
| Pinned third-party PoC **fetch** scripts | Unreviewed vendored exploit trees |

Full disclaimer: [security-labs/DISCLAIMER.md](https://github.com/aumlayer/security-labs/blob/main/DISCLAIMER.md)

## Contribute

New CVE folder + catalog row: [CONTRIBUTING.md](https://github.com/aumlayer/security-labs/blob/main/CONTRIBUTING.md)

Security issues in our lab/checker code: [GitHub Security Advisories](https://github.com/aumlayer/security-labs/security/advisories)

---

<div align="center">

**[Explore security-labs →](https://github.com/aumlayer/security-labs)**

Most product repositories remain private; subscribe to **security-labs** for public research updates.

</div>
