# Waterfall Enrichment Workflow

- Goal: Improve lead completeness by trying multiple enrichment methods in order.
- Who it is for: RevOps teams, lead sellers, enrichment product builders, agencies.
- APIs used: [AI Contact Details Scraper](../apis/ai-contact-details-scraper.md), [Hunter.io](../apis/hunter-io.md), [Clearbit Combined](../apis/clearbit-combined.md), [Smart Email Finder and Verifier](../apis/smart-email-finder-verifier.md), [Easy Bulk Email Validator](../apis/easy-bulk-email-validator.md).
- Inputs: Company name, domain, optional person name, optional existing email, source URL.
- Outputs: Best email, phone, social links, enrichment confidence, validation status, source trail.

## Steps

1. Start with the cheapest or most deterministic enrichment step.
2. Scrape the company website for generic and role-based contacts.
3. Search for person/company enrichment when identity clues exist.
4. Guess and verify emails only when name plus domain is available.
5. Validate final emails and keep source metadata.
6. Mark records as enriched, partial, or needs manual review.

## Why It Is Valuable

No single provider covers every record. A waterfall makes lead data more complete without wasting credits on every step.

## Monetization Angle

Offer CRM enrichment, build a data quality product, or sell verified lead list upgrades.

## Complexity

Intermediate.
