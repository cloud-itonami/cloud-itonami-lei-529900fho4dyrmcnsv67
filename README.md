# cloud-itonami-lei-529900fho4dyrmcnsv67

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by Flix SE.**

This repository archives the publicly published General Terms and Conditions of
Carriage of **Flix SE** (the parent company of the FlixBus/FlixTrain intercity coach
and rail network), with source-url and retrieval-date provenance, per
[ADR-2607110300](https://github.com/com-junkawasaki/root/blob/main/90-docs/adr/2607110300-cloud-itonami-lei-corporate-tos-catalog.edn)
(`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`). It is a read-only
reference/archive repository — it does not act, propose, or execute anything on the
company's behalf, and is not a governed Advisor/Governor actor.

## Company identity

- **Legal name**: Flix SE
- **LEI (ISO 17442)**: [529900FHO4DYRMCNSV67](https://search.gleif.org/#/record/529900FHO4DYRMCNSV67) (GLEIF-verified, status ACTIVE, registration ISSUED)
- **Jurisdiction**: DE (Germany; legal form SGST — Societas Europaea)
- **Website**: https://www.flixbus.com
- **Ticker**: unlisted (privately held)

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of archived Terms and Conditions of Carriage documents.
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.

## Related cloud-itonami blueprint (passenger-road-transport vertical)

Flix SE operates one of the largest international intercity coach networks
(long-distance scheduled coach service across dozens of countries via a
franchise/partner-operator model). This vertical's *generic, forkable* Open
Business Blueprint counterpart in the `cloud-itonami` fleet is
[`cloud-itonami-isic-4922`](https://github.com/cloud-itonami/cloud-itonami-isic-4922)
(ISIC 4921/4922 sibling pair — urban/suburban vs. intercity/chartered coach
scheduling-and-dispatch coordination, Advisor⊣Governor actor pattern). This
LEI-catalog entry is a **read-only ToS reference only** — it is not a fork of, and
has no code dependency on, isic-4922; the cross-reference exists so a reader
researching real-world intercity-coach operators for market/competitive context can
find both the real company's published terms and the corresponding generic
governed-actor blueprint from one place. isic-4922's own `docs/business-model.md`
cites this catalog entry as a real-company reference point in its passenger-road-
transport landscape notes.

## Design rationale

See ADR-2607110300 in `com-junkawasaki/root` (`90-docs/adr/`).
