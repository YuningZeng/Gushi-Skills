# Earnings and Event Skill

## Purpose
Handle high-volatility periods around earnings, CPI, FOMC, jobs reports, and company-specific catalysts.

## Inputs
- Ticker
- Event type
- Event date
- Existing position size
- Implied volatility / expected move
- Conviction level
- Holding period intention

## Workflow
1. Identify whether the event is binary or directional.
2. Estimate whether the current position size is appropriate for gap risk.
3. Decide whether to:
   - reduce before event
   - hold through event
   - wait for reaction then trade
4. Define post-event scenarios:
   - beat and hold gains
   - beat but fade
   - miss and gap down
   - guidance-driven move
5. Record the reason for holding or not holding through the event.

## Output Format
- Event summary
- Gap-risk assessment
- Position decision
- Scenario map
- Post-event action plan

## Guardrails
- Respect gap risk.
- Size smaller into uncertainty.
- Do not confuse conviction with certainty.
