# Hoverboard Store Content System

Last exported: 2026-05-30 19:20:30

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

- **draft_created**: 7
- **needs_human_review**: 1
- **planned**: 21
- **published_live**: 1

## Next Planned Jobs

- **Job 10** — 2026-06-15 — Hoverkart — Hoverkart Setup Guide for Beginners
- **Job 11** — 2026-06-18 — Troubleshooting — Hoverboard Beeping: Common Reasons and Safe Fixes
- **Job 12** — 2026-06-21 — Buyer Guide — Best Hoverboards for Beginners UK: What to Look For
- **Job 13** — 2026-06-24 — Safety / Support — Hoverboard Helmet and Safety Gear Guide for Kids
- **Job 14** — 2026-06-27 — Hoverkart — Hoverkart vs Hoverboard: Which Is Better for Kids?
- **Job 15** — 2026-06-30 — Maintenance — How to Store a Hoverboard Battery Safely
- **Job 16** — 2026-07-03 — Product / Collection Support — 6.5 Inch vs 8.5 Inch Hoverboards for Kids: Simple Buying Guide
- **Job 17** — 2026-07-06 — Troubleshooting — Hoverboard Won’t Turn On: Safe Checks Before You Replace It

## Latest Cron Snapshot

```text
# Latest Cron Run Status

- **Last run:** Friday, May 29th, 2026 - 12:26 PM (Europe/London)
- **Job:** 09
- **Topic:** How to Clean a Hoverboard Safely
- **Target file:** clients/hoverboard_store/content_engine/drafts/how-to-clean-a-hoverboard-safely.html
- **Result:** created
- **Reason:** file created successfully
- **Shopify API called:** No
- **Next run:** Monday, June 1st, 2026 (3 days from anchor)
```

## Operating Rules

- OpenClaw cron creates local HTML only.
- Manual terminal workflow creates hidden Shopify drafts.
- Human review is required before live publishing.
- Existing published Shopify articles are read-only unless explicitly approved.
- Cron jobs must not call Shopify API.
- Compliance warnings must be reviewed before live publishing.