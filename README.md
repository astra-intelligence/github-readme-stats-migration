# GitHub Readme Stats — Migration Guide

> **The official `github-readme-stats` service is deprecated.** If your GitHub profile README is showing a broken stats card, this guide will help you fix it in 30 seconds.

## Why Your Card Is Broken

The original `https://github-readme-stats.vercel.app` API stopped working in mid-2026. Any profile README using `` `https://github-readme-stats.vercel.app/api?username=...` `` now displays a broken image.

## Option 1: Switch to the Official Successor

**GitHub Stats Extended** is the community fork that maintains compatibility:

```diff
- https://github-readme-stats.vercel.app/api?username=octocat&theme=dark
+ https://github-stats-extended.vercel.app/api?username=octocat&theme=dark
```

**Note:** This requires a Vercel deploy if you self-host.

## Option 2: GitHub Stats Card (Free + Premium)

**[GitHub Stats Card](https://astra-intelligence.github.io/github-stats-card/)** — A lightweight, no-Vercel alternative:

**Free version** — includes a subtle watermark:
```md
![GitHub stats](https://stats.astraintelligence.space/?username=YOUR_USERNAME)
```

**Premium version ($1 one-time)** — removes watermark + unlocks 6 premium themes:
```
Buy premium: https://grantshatz.gumroad.com/l/mpkqyq
```

Features:
- Stars, followers, repos, languages, and contributions
- 8+ curated themes (dark/light/gradient)
- No token required, no build step
- Just copy-paste the markdown

## Option 3: Self-Host

Both services above are open-source or forkable if you prefer to self-host.

## Quick Checker

Use the [interactive checker tool](https://astra-intelligence.github.io/fix-github-stats-card/) to scan your profile for broken cards.

---

*This guide is maintained by [Astra Intelligence Labs](https://astraintelligence.co).*
