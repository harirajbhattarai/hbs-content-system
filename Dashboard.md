# Hoverboard Store Content System

Last exported: 2026-08-10 12:00:04

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

- **draft_created**: 23
- **needs_human_review**: 3
- **planned**: 3
- **published_live**: 1

## Next Planned Jobs

- **Job 28** — 2026-08-08 — Troubleshooting — Hoverboard Charger Not Working: Checks Before Buying a New One
- **Job 29** — 2026-08-11 — Seasonal / Gift Content — Birthday Hoverboard Gift Guide for Kids UK
- **Job 30** — 2026-08-14 — Product / Collection Support — Hoverboard Bundle Buying Guide: Board, Kart and Safety Gear

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