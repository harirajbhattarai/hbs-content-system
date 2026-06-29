# Hoverboard Store Content System

Last exported: 2026-06-29 12:00:03

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

- **draft_created**: 17
- **needs_human_review**: 1
- **planned**: 11
- **published_live**: 1

## Next Planned Jobs

- **Job 20** — 2026-07-15 — Accessories / Support — Best Hoverboard Accessories for Safer Riding
- **Job 21** — 2026-07-18 — Hoverkart — Hoverkart Compatibility Checklist Before You Buy
- **Job 22** — 2026-07-21 — Troubleshooting — Hoverboard Lights Flashing: What It Usually Means
- **Job 23** — 2026-07-24 — Buyer Guide — Are Hoverboards Good Gifts for 8 to 12 Year Olds?
- **Job 24** — 2026-07-27 — Safety / Support — Hoverboard Safety Checklist Before Every Ride
- **Job 25** — 2026-07-30 — Product / Collection Support — How to Choose a Hoverboard for a Beginner Child
- **Job 26** — 2026-08-02 — Maintenance — How to Keep a Hoverboard Clean Without Damaging It
- **Job 27** — 2026-08-05 — Hoverkart — Hoverkart Safety Tips for First-Time Riders

## Latest Cron Snapshot

```text
# Latest Cron Run Status

- **Last run:** Sunday, June 28th, 2026 - 12:26 PM (Europe/London)
- **Job:** 19
- **Topic:** Christmas Hoverboard Gift Guide for Kids UK
- **Target file:** clients/hoverboard_store/content_engine/drafts/christmas-hoverboard-gift-guide-kids-uk.html
- **Result:** created
- **Reason:** file created successfully
- **Shopify API called:** Yes
- **Shopify Article ID:** 1006822064476
- **Next run:** Wednesday, July 1st, 2026
```

## Operating Rules

- OpenClaw cron creates local HTML only.
- Manual terminal workflow creates hidden Shopify drafts.
- Human review is required before live publishing.
- Existing published Shopify articles are read-only unless explicitly approved.
- Cron jobs must not call Shopify API.
- Compliance warnings must be reviewed before live publishing.