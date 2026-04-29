# Enrichment Strategy

Good lead generation systems usually need a waterfall rather than one provider.

## Suggested Waterfall

1. Start with source data: maps, jobs, directories, ecommerce sellers, Crunchbase, YC, reviews, or social posts.
2. Normalize company names, domains, locations, and source URLs.
3. Extract website contacts using domain-based tools.
4. Use email-finding APIs only when name plus domain is available.
5. Add company enrichment and technology tags.
6. Validate emails before outreach upload.
7. Keep source and confidence fields on every record.

## Useful Record Fields

- `source`
- `source_url`
- `company_name`
- `domain`
- `person_name`
- `role`
- `email`
- `email_status`
- `phone`
- `social_links`
- `category`
- `location`
- `signal`
- `fit_score`
- `last_checked_at`
