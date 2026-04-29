# Lead Scoring Model

A simple starter model for ranking leads from the APIs in this repo.

## Core Fields

| Field | Score Idea |
| --- | --- |
| Contact completeness | Email, phone, website, social links |
| Source fit | Maps, directory, job, funding, review, ecommerce, startup |
| ICP match | Industry, location, company size, technology, marketplace |
| Timing signal | Hiring, funding, reviews, recent project post, active marketplace listing |
| Data confidence | Validated email, fresh source, duplicate-free record |
| Offer relevance | Clear reason this prospect needs the offer |

## Example Score

- Contact completeness: 0-20
- ICP match: 0-25
- Timing signal: 0-25
- Data confidence: 0-15
- Offer relevance: 0-15

Total: 100 points.

Use the score to prioritize review and routing. Do not treat it as proof that a prospect wants outreach.
