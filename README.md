# ROBUST V20 App Data (Latest Only)

This PUBLIC repository is a tiny stateless feed for the Android app.

- `latest.json`: only the latest ROBUST V20 strategy/market snapshot.
- No account balance, holdings, average prices, or order quantities are published.
- No history file, CSV, Excel, image archive, cache, or GitHub Artifact is stored.
- The private runner force-replaces `main` with a new root commit, so visible Git history remains a single latest snapshot.

The Android app should read `latest.json` from the raw GitHub URL.
