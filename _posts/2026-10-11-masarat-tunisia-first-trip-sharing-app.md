---
title: "🇹🇳 Masarat — Tunisia's First Community Trip-Sharing Mobile App"
date: 2026-10-11 12:00:00 +0100
categories: [Projects, Mobile]
tags: [flutter, dart, supabase, clerk, tunisia, carpooling]
---

## Shared Journeys, Trusted Community

**Masarat** is my Flutter mobile app (iOS & Android + Web) — a community trip-sharing / carpooling platform focused on Tunisia. Coordinate trips with your community, not a taxi app.

🔗 **Repo:** [github.com/ahmeddhahri100/Masarat](https://github.com/ahmeddhahri100/Masarat)

## What it does

- Create trips — departure, destination, date/time, seats, price
- Search & discover — recent trips, featured/boosted trips
- Join flow — Join Trip / Request Seat / Available Seats
- Chat to coordinate — per-trip realtime messaging
- Profiles — view/edit profile, my trips
- Boost / Premium, notifications, onboarding

## Tech stack

Flutter 3.32 · Dart · Riverpod · Supabase (Postgres + Realtime) · Clerk auth · Google Fonts / Lucide

Secrets are passed via `--dart-define` (see `.env.example`) — no keys in the repo.

## Try it

```bash
git clone git@github.com:ahmeddhahri100/Masarat.git
cd Masarat/masarat
flutter pub get
flutter run -d chrome \
  --dart-define=SUPABASE_URL=... \
  --dart-define=SUPABASE_ANON_KEY=... \
  --dart-define=CLERK_PUBLISHABLE_KEY=...
```

More in the [Masarat README](https://github.com/ahmeddhahri100/Masarat).
