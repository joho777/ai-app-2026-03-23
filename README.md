# Bot-Friendly OSS — AI Bot Readiness Lab

A single-page, offline web app inspired by the trend: **How to attract AI bots to your open source project**.

This app helps you:
- Audit your repository for bot-first documentation, setup, and contribution guardrails
- Simulate an AI contributor attempting a first PR (with flakiness, context budget, and persona tuning)
- Generate ready-to-paste repo artifacts (README section, CONTRIBUTING.md, CODEBASE_MAP.md, templates)
- Export a ZIP starter pack (client-side) with your generated files + a manifest

## Run

Open `index.html` in your browser.

## Why this is interesting

Most AI coding agents behave like a very fast new contributor: they skim docs, try to run tests, then attempt a small patch.
Optimizing for that workflow improves onboarding for humans too.

## Notes

- No server; no data leaves your device.
- This does not scan live repositories; it is an interactive simulator and generator.

## Trend source

HN discussion: https://news.ycombinator.com/item?id=39835241
