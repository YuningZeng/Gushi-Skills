# Risk Control Skill

## Purpose
Prevent avoidable losses by forcing a risk review before and during trading.

## Inputs
- Total account size
- Current exposure
- Number of open positions
- Correlation across positions
- Max daily loss
- Max per-trade loss
- Upcoming macro or earnings events

## Workflow
1. Calculate total capital at risk.
2. Check whether multiple positions are effectively the same bet.
3. Verify that per-trade loss is within allowed tolerance.
4. Verify that total daily downside is acceptable.
5. Check liquidity and gap risk.
6. Check event risk.
7. Recommend reduce / hold / avoid.

## Output Format
- Account risk snapshot
- Per-trade risk check
- Portfolio correlation warning
- Event risk warning
- Action recommendation

## Guardrails
- Survival first, returns second.
- Never let one trade materially damage the account.
- Concentration risk must be explicit.
