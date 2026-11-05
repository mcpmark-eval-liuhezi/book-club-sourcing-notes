# Sourcing Note — Designing Data-Intensive Applications

**Prepared for:** Finance sign-off — Engineering Book Club next read
**Lookup date:** 2026-11-05
**Source intended:** Amazon (amazon.com, USD)
**Status:** PENDING — live lookup failed today

## Why the data fields are empty

On 2026-11-05 a live Amazon lookup was attempted several times (product search, direct product-page scrape, and alternate search routes). Every attempt was rejected by the scraping provider with:

`HTTP 429 Too Many Requests — "Your current plan's quota has been reached."`

No page content was returned, so no price, rating, number-of-ratings, or product identifier could be verified from Amazon today. Per the sourcing rule, no remembered or cached numbers are being quoted here (including any data from an earlier lookup), because covered stale data is not a valid purchase-order input.

## Fields (to be completed from a fresh live Amazon query)

| Field | Value |
|---|---|
| Title | Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems — Martin Kleppmann |
| Publisher / Edition | O'Reilly Media, paperback |
| Price (USD) | PENDING — not verified live; angular |
| List price / seller | PENDING — not verified live |
| Average rating (out of 5) | PENDING — not verified live |
| Number of ratings | PENDING — not available; the lookup could not complete |
| Product identifier (ASIN / ISBN) | PENDING — not verified live |
| Amazon URL | TBD |

## Recommendation

Do not cut the purchase order on stale figures.

1. Re-run the live Amazon lookup for a new print copy (price in USD, average rating, number of ratings, ASIN or ISBN).
2. Fill in the table above.
3. Re-open for review and re-request sign-off once the live values are in.

## Provenance note

Data source intended: Amazon (amazon.com listings pulled live). On 2026-11-05 the intended live retrieval returned **no data** (HTTP 429, plan-quota), so every listed field above is PENDING rather than recalled. Any figures pasted from a prior cached lookup must not be used for the PO until verified live.
