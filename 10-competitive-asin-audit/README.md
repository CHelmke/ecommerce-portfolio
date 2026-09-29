# Competitive ASIN Audit - Party Supply Bundles

## Objective
Compare two similar Amazon listings using customer-facing information, normalize differences that make a direct comparison misleading, and identify what should be validated in Seller Central before making larger changes.

## Public portfolio version
This is a recreated September 2026 public-listing case study. The original product identifiers are intentionally **sanitized** in the public repository; the analytical method and point-in-time metrics are preserved.

## Key finding
The bundles are not identical: **Party Kit A** serves 24 guests / 106 pieces, while **Party Kit B** serves 16 / 67 pieces. Normalizing price therefore matters.

At the observed snapshot prices, the cost was approximately:
- Party Kit A: **$2.85 per guest**
- Party Kit B: **$1.87 per guest**

That leaves Party Kit A roughly **52% more expensive per guest**, even after adjusting for the larger bundle.

## Other observations
- Party Kit B had a sharper, clearer main-image presentation.
- Both listings showed the same star rating in the reviewed snapshot, but Party Kit B had more accumulated ratings/reviews.
- The shopper-facing recent-activity signals differed. They are not equivalent metrics, so they are treated as directional evidence only.
- Party Kit B showed a substantially stronger Party Packs Best Sellers Rank in the snapshot.
- Party Kit A had a structured `Number of Items` inconsistency.
- Party Kit B had a `Material = Latex` attribute that did not align cleanly with the stated paper/plastic contents.
- Party Kit A sat in a variation family, making the price ladder across options important to conversion.

## First priorities
1. Improve the main-image presentation.
2. Make the 106-piece / serves-24 value proposition unmistakable.
3. Review the variation-family pricing ladder and option-level conversion.
4. Correct incomplete or inaccurate structured attributes.
5. Verify Featured Offer, inventory and delivery promises under the same ZIP code and time.

## What I would check with account access
- Impressions and sessions
- Click-through rate
- Unit session percentage / conversion
- Search-term performance
- Advertising traffic
- Featured Offer percentage
- Conversion by variation option
- Inventory and delivery promise

The purpose is to separate a **traffic problem** from a **click problem**, **conversion problem**, or **availability problem** before making broad changes.

## Files
- `competitive_asin_audit.xlsx` - structured comparison, normalized value calculations, priorities and methodology notes
- `competitive_asin_audit_preview.png` - visual preview of the comparison sheet

## Skills Demonstrated
Competitive Analysis | Amazon Merchandising | Value Analysis | PDP Audit | Structured Attributes | Variation Strategy | BSR Interpretation | Traffic vs. Conversion Diagnosis | Seller Central Investigation Planning
