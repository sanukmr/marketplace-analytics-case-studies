# Trust-First Partner Optimisation

## Business Problem
Which partners should be promoted as "Top Picks" without
damaging customer trust?

## Common Approach
Promote partners with high revenue and high average ratings.

## Why This Fails
- Ratings with low sample sizes are unreliable
- High-revenue partners with declining quality increase churn
- Promotions amplify risk at scale

## My Approach
1. Quality Gate:
   - Minimum rating floor
   - Minimum rating count
   - Minimum order volume

2. Confidence-Based Scoring:
   Rating Strength = Avg Rating × Rating Count

3. Multi-Objective Ranking:
   - 40% Quality Strength
   - 30% Revenue Contribution
   - 20% Demand Reliability
   - 10% Review Depth

## Outcome
A scalable, explainable framework that prioritizes
trust, revenue, and long-term platform health.
