# Hoverboard Store Content System

Last exported: 2026-06-10 13:20:04

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

- **Last run:** Wednesday, June 10th, 2026 - 12:26 PM (Europe/London)
- **Job:** 13
- **Topic:** Hoverboard Helmet and Safety Gear Guide for Kids
- **Target file:** clients/hoverboard_store/content_engine/drafts/hoverboard-helmet-safety-gear-kids.html
- **Result:** created
- **Reason:** file created successfully
- **Shopify API called:** No
- **Next run:** Saturday, June 13th, 2026 (3 days from now)

---

## Summary

Job 13 completed successfully.

**File created:** `clients/hoverboard_store/content_engine/drafts/hoverboard-helmet-safety-gear-kids.html`

**Meta title:** Hoverboard Helmet and Safety Gear Guide for Kids UK 2026
**Meta description:** A practical guide to choosing the right helmet and safety gear for kids on hoverboards. Includes sizing tips, gear checklist, and safety advice for UK parents.
**URL slug:** hoverboard-helmet-safety-gear-kids-uk-2026

**Guard check:**
- No unsupported public-road/pavement claims — safe wording used throughout
- No invented product specs, warranties, or certifications
- No fake safety guarantees
- FAQ format uses div.hs-faq-q and div.hs-faq-a correctly
- No manual FAQPage JSON-LD included
- Author: By Hoverboard Store ✓
- Authority section: Hoverboard Store Team ✓

**Compliance warnings:**
- Hoverboard legal use in UK is not confirmed in this article — riding location guidance uses "check current UK rules" phrasing only
- No specific product certifications or safety standards claimed for any particular brand of helmet or pads

**Verification needed before Shopify draft publishing:**
- Confirm all internal links point to existing published articles
- Review FAQ answers for accuracy against current UK guidance
- Verify the hoverboard accessories collection URL used in the CTA

**Reminder:** Run the terminal workflow manually to check and publish this draft to Shopify.
```

## Operating Rules

- OpenClaw cron creates local HTML only.
- Manual terminal workflow creates hidden Shopify drafts.
- Human review is required before live publishing.
- Existing published Shopify articles are read-only unless explicitly approved.
- Cron jobs must not call Shopify API.
- Compliance warnings must be reviewed before live publishing.