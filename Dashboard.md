# Hoverboard Store Content System

Last exported: 2026-06-07 13:20:03

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

- **draft_created**: 10
- **needs_human_review**: 1
- **planned**: 18
- **published_live**: 1

## Next Planned Jobs

- **Job 13** — 2026-06-24 — Safety / Support — Hoverboard Helmet and Safety Gear Guide for Kids
- **Job 14** — 2026-06-27 — Hoverkart — Hoverkart vs Hoverboard: Which Is Better for Kids?
- **Job 15** — 2026-06-30 — Maintenance — How to Store a Hoverboard Battery Safely
- **Job 16** — 2026-07-03 — Product / Collection Support — 6.5 Inch vs 8.5 Inch Hoverboards for Kids: Simple Buying Guide
- **Job 17** — 2026-07-06 — Troubleshooting — Hoverboard Won’t Turn On: Safe Checks Before You Replace It
- **Job 18** — 2026-07-09 — Buyer Guide — Hoverboard Weight Limit Guide for Parents
- **Job 19** — 2026-07-12 — Seasonal / Gift Content — Christmas Hoverboard Gift Guide for Kids UK
- **Job 20** — 2026-07-15 — Accessories / Support — Best Hoverboard Accessories for Safer Riding

## Latest Cron Snapshot

```text
# Latest Cron Run Status

- **Last run:** Sunday, June 7th, 2026 - 12:26 PM (Europe/London)
- **Job:** 12
- **Topic:** Best Hoverboards for Beginners UK: What to Look For
- **Target file:** clients/hoverboard_store/content_engine/drafts/best-hoverboards-for-beginners-uk.html
- **Result:** created
- **Reason:** file created successfully
- **Shopify API called:** No
- **Next run:** Wednesday, June 10th, 2026 - 12:26 PM (Europe/London)
```

## Operating Rules

- OpenClaw cron creates local HTML only.
- Manual terminal workflow creates hidden Shopify drafts.
- Human review is required before live publishing.
- Existing published Shopify articles are read-only unless explicitly approved.
- Cron jobs must not call Shopify API.
- Compliance warnings must be reviewed before live publishing.