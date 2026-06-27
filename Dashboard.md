# Hoverboard Store Content System

Last exported: 2026-06-27 11:20:03

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

- **draft_created**: 14
- **needs_human_review**: 1
- **planned**: 14
- **published_live**: 1

## Next Planned Jobs

- **Job 17** — 2026-07-06 — Troubleshooting — Hoverboard Won’t Turn On: Safe Checks Before You Replace It
- **Job 18** — 2026-07-09 — Buyer Guide — Hoverboard Weight Limit Guide for Parents
- **Job 19** — 2026-07-12 — Seasonal / Gift Content — Christmas Hoverboard Gift Guide for Kids UK
- **Job 20** — 2026-07-15 — Accessories / Support — Best Hoverboard Accessories for Safer Riding
- **Job 21** — 2026-07-18 — Hoverkart — Hoverkart Compatibility Checklist Before You Buy
- **Job 22** — 2026-07-21 — Troubleshooting — Hoverboard Lights Flashing: What It Usually Means
- **Job 23** — 2026-07-24 — Buyer Guide — Are Hoverboards Good Gifts for 8 to 12 Year Olds?
- **Job 24** — 2026-07-27 — Safety / Support — Hoverboard Safety Checklist Before Every Ride

## Latest Cron Snapshot

```text
# Latest Cron Run Status

- **Last run:** Saturday, June 27th, 2026 - 10:19 AM (Europe/London)
- **Job:** 16
- **Topic:** 6.5 Inch vs 8.5 Inch Hoverboards for Kids: Simple Buying Guide
- **Target file:** clients/hoverboard_store/content_engine/drafts/65-vs-85-inch-hoverboards-kids-guide.html
- **Result:** stopped
- **Reason:** file already exists
- **Shopify API called:** No
- **Shopify Article ID:** none
- **Next run:** Tuesday, June 30th, 2026
```

## Operating Rules

- OpenClaw cron creates local HTML only.
- Manual terminal workflow creates hidden Shopify drafts.
- Human review is required before live publishing.
- Existing published Shopify articles are read-only unless explicitly approved.
- Cron jobs must not call Shopify API.
- Compliance warnings must be reviewed before live publishing.