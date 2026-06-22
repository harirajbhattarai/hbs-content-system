# Hoverboard Store Content System

Last exported: 2026-06-22 12:00:04

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

- **draft_created**: 11
- **needs_human_review**: 1
- **planned**: 17
- **published_live**: 1

## Next Planned Jobs

- **Job 14** — 2026-06-27 — Hoverkart — Hoverkart vs Hoverboard: Which Is Better for Kids?
- **Job 15** — 2026-06-30 — Maintenance — How to Store a Hoverboard Battery Safely
- **Job 16** — 2026-07-03 — Product / Collection Support — 6.5 Inch vs 8.5 Inch Hoverboards for Kids: Simple Buying Guide
- **Job 17** — 2026-07-06 — Troubleshooting — Hoverboard Won’t Turn On: Safe Checks Before You Replace It
- **Job 18** — 2026-07-09 — Buyer Guide — Hoverboard Weight Limit Guide for Parents
- **Job 19** — 2026-07-12 — Seasonal / Gift Content — Christmas Hoverboard Gift Guide for Kids UK
- **Job 20** — 2026-07-15 — Accessories / Support — Best Hoverboard Accessories for Safer Riding
- **Job 21** — 2026-07-18 — Hoverkart — Hoverkart Compatibility Checklist Before You Buy

## Latest Cron Snapshot

```text
# Latest Cron Run Status

- **Last run:** Sunday, June 21st, 2026 - 9:55 AM (Europe/London)
- **Job:** 14
- **Topic:** Hoverkart vs Hoverboard: Which Is Better for Kids?
- **Target file:** clients/hoverboard_store/content_engine/drafts/hoverkart-vs-hoverboard-for-kids.html
- **Result:** stopped
- **Reason:** file already exists
- **Shopify API called:** No
- **Shopify Article ID:** N/A
- **Next run:** Wednesday, June 24th, 2026 (3 days from now)
```

## Operating Rules

- OpenClaw cron creates local HTML only.
- Manual terminal workflow creates hidden Shopify drafts.
- Human review is required before live publishing.
- Existing published Shopify articles are read-only unless explicitly approved.
- Cron jobs must not call Shopify API.
- Compliance warnings must be reviewed before live publishing.