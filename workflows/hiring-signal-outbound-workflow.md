# Hiring Signal Outbound Workflow

- Goal: Use job postings as buying signals for B2B outreach.
- Who it is for: Recruiting agencies, consultants, SaaS companies, service providers.
- APIs used: [Advanced LinkedIn Job Search API](../apis/advanced-linkedin-job-search-api.md), [LinkedIn Jobs Scraper with Company Insights](../apis/linkedin-jobs-scraper-company-insights.md), [All Jobs Scraper](../apis/all-jobs-scraper.md), [AI Contact Details Scraper](../apis/ai-contact-details-scraper.md), [AI Lead Qualifier](../apis/ai-lead-qualifier.md).
- Inputs: Job titles, keywords, geography, industry, company size, posting freshness.
- Outputs: Hiring companies, job details, website, company size, industry, likely pain, suggested pitch.

## Steps

1. Search job postings that imply a specific need.
2. Normalize company names and domains across job sources.
3. Enrich company websites with contact fields.
4. Qualify the company based on the role, company website, and industry.
5. Score urgency by posting date, number of similar roles, and seniority.
6. Route high-fit accounts to sales or recruiting workflows.

## Why It Is Valuable

Hiring is one of the clearest public signals that a company has budget, growth, or operational pressure.

## Monetization Angle

Sell hiring-trigger alerts, recruiting lead feeds, or niche outbound campaign setup.

## Complexity

Intermediate.
