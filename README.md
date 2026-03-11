# NEXTIOM POS — Private Update Repository

⚠️ This is a **private** repository. Do not share the raw file URLs.

## How to push an update:

1. Replace `app.html` with the new version
2. Update `version.json` — change the version number (e.g. "2.0" → "2.1")
3. Commit and push to `main` branch
4. Customers will automatically see the update notification within 5 seconds of login

## version.json format:
```json
{
  "version": "2.1",
  "released": "2026-03-15",
  "notes": "Bug fixes and improvements"
}
```

## URL format (DO NOT SHARE):
- Version check: `https://raw.githubusercontent.com/nextiom-updates/nextiom-pos/main/version.json`
- App download:  `https://raw.githubusercontent.com/nextiom-updates/nextiom-pos/main/app.html`

© 2026 Nextiom (Pvt) Ltd
