# Hypertile — downloads

Release downloads and the Sparkle update feed for **Hypertile**, a tiling window manager for macOS.

- **Buy and learn more:** https://abanwar.com/hypertile/
- **Download:** see [Releases](../../releases)
- **Requires:** macOS 14 Sonoma or later, Intel or Apple Silicon

Every build here is signed with a Developer ID certificate and notarized by Apple, so it opens
without warnings, and each update is signed with Hypertile's own key — the app refuses any
update that doesn't match.

## Update feed

Hypertile checks for updates once a day through [Sparkle](https://sparkle-project.org). The
appcast is attached to each release, so the current feed is always at a stable URL:

```
https://github.com/bocciaman/hypertile-releases/releases/latest/download/appcast.xml
```

The feed used to be served from the website. Copies sold before it moved have the old address
compiled into them and check it every day, so `abanwar.com/hypertile/appcast.xml` permanently
redirects here. That redirect has to stay for as long as any of those copies are still running —
without it they would stop receiving updates, and it is the only channel left to reach them.

Downloads live on GitHub rather than behind the Gumroad purchase link because Sparkle needs a
URL it can fetch without credentials, and Gumroad's links are signed and expire.

## What is here

Only the built downloads and the update feed. The source is in a separate private repository.
