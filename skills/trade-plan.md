# Trade Plan Skill

## Purpose
Generate a structured trading plan before execution.

## Inputs
- Ticker
- Time horizon: intraday / swing / position
- Thesis
- Entry zone
- Invalidations
- Target zone
- Current position
- Maximum acceptable loss
- Upcoming events

## Workflow
1. Define the trade thesis in one sentence.
2. Identify the setup type:
   - breakout
   - pullback
   - trend continuation
   - reversal
   - earnings reaction
3. Define entry conditions.
4. Define stop-loss logic.
5. Define take-profit logic.
6. Define position size based on account risk.
7. List conditions that cancel the trade.

## Output Format
- Trade thesis
- Entry plan
- Stop-loss plan
- Take-profit plan
- Position sizing notes
- Disqualifying conditions
- Event risk warning

## Guardrails
- No trade without invalidation.
- No averaging down without a predefined plan.
- No oversized position relative to account risk.
