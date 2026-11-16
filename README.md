# Forkline: public beta

A science-fiction space trading game for phone and desktop browsers. Buy where goods are made, sell where they are wanted, and clear your debt before the interest grows. Travel costs days, not fuel; every trade settles in dollars; price reports from the stars arrive days late because of light-lag.

**Play:** https://playforkline.com/play/ · **Website:** https://playforkline.com/

## What this repository is

This repository is the published site: the public website and the playable build, served by GitHub Pages from the `main` branch at https://playforkline.com/. The development source (game source, build scripts, tests, design docs) lives in a separate private repository; the files here are its build output and are not edited by hand.

Pages: `/` homepage · `/play/` the game · `/about/` how to play, for players, parents and teachers · `/fleet/` what is planned for the community · `/devlog/` · `/report/` tester report form · `/crew/` mailing-list confirmation.

Live build as of 16 November 2026: **v25.13** (the build tag is in the game's menu link "Send a tester report"). Preview builds for review are published separately at https://preview.playforkline.com/ and are not the released build.

## Status

Public beta. Progress saves in your browser; local records may restart when a build changes the economy, and the game says so when it happens. The production site is indexable (`robots.txt` allows all, with a sitemap); the tester report and crew pages carry `noindex`, and the preview site is excluded from indexing.

## Feedback

Play a mission, then use the [tester report page](https://playforkline.com/report/) and follow the instructions there (no code, name or email is needed; you pick a callsign). Include the build version and a screenshot when they help. Feedback that changes the game can earn a credit in the in-game Codex, by callsign, if you opt in.

## Publication

Changes arrive here by pull request from the development repository's build step and go live only when Jason merges them. Preview first, then production.

## Rights

© 2026 Jason Von Holmes. All rights reserved. This repository distributes the playable build and site for play in the browser; no license is granted to copy, modify or redistribute the code or its content.
