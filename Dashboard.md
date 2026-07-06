# Hoverboard Store Content System

Last exported: 2026-07-06 12:00:04

## Quick Links

- [[Content Queue]]
- [[Draft Inventory]]
- [[Published Inventory]]
- [[Latest Cron Status]]
- [[Cron Runs]]
- [[Publishing Rules]]
- [[Cluster Map]]
- [[Cluster Rules]]
- [[Safe Topic Rules]]
- [[Topic Opportunities]]
- [[UK Product Compliance Rules]]
- [[GSC Topic Opportunities]]

## Queue Status Summary

- **draft_created**: 18
- **needs_human_review**: 1
- **planned**: 10
- **published_live**: 1

## Next Planned Jobs

- **Job 21** — 2026-07-18 — Hoverkart — Hoverkart Compatibility Checklist Before You Buy
- **Job 22** — 2026-07-21 — Troubleshooting — Hoverboard Lights Flashing: What It Usually Means
- **Job 23** — 2026-07-24 — Buyer Guide — Are Hoverboards Good Gifts for 8 to 12 Year Olds?
- **Job 24** — 2026-07-27 — Safety / Support — Hoverboard Safety Checklist Before Every Ride
- **Job 25** — 2026-07-30 — Product / Collection Support — How to Choose a Hoverboard for a Beginner Child
- **Job 26** — 2026-08-02 — Maintenance — How to Keep a Hoverboard Clean Without Damaging It
- **Job 27** — 2026-08-05 — Hoverkart — Hoverkart Safety Tips for First-Time Riders
- **Job 28** — 2026-08-08 — Troubleshooting — Hoverboard Charger Not Working: Checks Before Buying a New One

## Latest Cron Snapshot

```text
# Latest Cron Run Status

- **Last run:** Tuesday, June 30th, 2026 - 10:19 AM (Europe/London)
- **Job:** 20
- **Topic:** Best Hoverboard Accessories for Safer Riding
- **Target file:** clients/hoverboard_store/content_engine/drafts/best-hoverboard-accessories-safer-riding.html
- **Result:** created
- **Reason:** file created successfully
- **Shopify API called:** Yes
- **Shopify Article ID:** 1006842446172
- **Next run:** Friday, July 3rd, 2026 (3 days from anchor)
```

## Operating Rules

- OpenClaw cron creates local HTML only.
- Manual terminal workflow creates hidden Shopify drafts.
- Human review is required before live publishing.
- Existing published Shopify articles are read-only unless explicitly approved.
- Cron jobs must not call Shopify API.
- Compliance warnings must be reviewed before live publishing.