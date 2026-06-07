# SaaSify Amplitude Analytics Demo

This repository contains a landing-page analytics assignment built for a Data Analyst role requiring Amplitude Analytics knowledge.

## Live demo

After GitHub Pages deployment is enabled, the live page should be available at:

`https://kollasaivyshnavi.github.io/saasify-amplitude-analytics-demo/`

## What this project demonstrates

The page simulates a SaaS landing page and sends business-friendly analytics events to Amplitude.

### Events tracked

1. `Landing Page Viewed`
2. `CTA Clicked`
3. `Conversion Intent Captured`

### Traffic-source fields captured

- `utm_source`
- `utm_medium`
- `utm_campaign`
- `utm_term`
- `utm_content`
- `referrer`
- `landing_page_url`
- `page_path`

### Conversion fields captured

- `cta_name`
- `conversion_stage`
- `intent_type`
- `funnel_step`

## Test URLs

Use these URLs after deployment to validate traffic-source tracking inside Amplitude:

```text
https://kollasaivyshnavi.github.io/saasify-amplitude-analytics-demo/?utm_source=linkedin&utm_medium=paid_social&utm_campaign=founder_growth

https://kollasaivyshnavi.github.io/saasify-amplitude-analytics-demo/?utm_source=google&utm_medium=cpc&utm_campaign=saas_search

https://kollasaivyshnavi.github.io/saasify-amplitude-analytics-demo/?utm_source=email&utm_medium=newsletter&utm_campaign=demo_offer
```

## Suggested Amplitude dashboard

Create a dashboard with these views:

1. Page views by `utm_source`
2. CTA clicks by `utm_source`
3. Conversion intent by `utm_campaign`
4. Funnel: `Landing Page Viewed` → `CTA Clicked` → `Conversion Intent Captured`

## Assignment explanation

This project shows how a business can connect campaign traffic to customer behavior. Instead of only tracking a page visit, the implementation captures the source of traffic, the campaign context, the CTA selected by the user, and the resulting conversion intent. This helps a marketing or operations team understand which channels are driving the strongest intent and where users drop off in the funnel.
