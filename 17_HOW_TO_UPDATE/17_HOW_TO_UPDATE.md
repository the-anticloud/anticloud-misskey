# How to Update — MISSKEY

**Project:** `MISSKEY`
**Category:** SOCIAL_MEDIA
**Domain:** social media
**Date:** 2026-10-08

---

## Update Procedure

### Checking for Updates
```bash
MISSKEY --version
MISSKEY check-update
```

### Applying Updates
```bash
pip install --upgrade MISSKEY
```

### Rolling Back
```bash
pip install MISSKEY==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

16/16 PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
