# Position Management Skill

## Purpose
Standardize how positions are added, trimmed, held, or exited.

## Inputs
- Ticker
- Cost basis
- Current price
- Unrealized P&L
- Original thesis
- Current market condition
- Current position size
- Planned maximum size

## Workflow
1. Reassess whether the original thesis is still valid.
2. Determine whether price action confirms or weakens the thesis.
3. Decide among:
   - hold
   - add
   - trim
   - exit
4. If adding, define trigger and maximum additional size.
5. If trimming, define what risk is being reduced.
6. If exiting, define whether due to invalidation, target hit, or time-stop.

## Output Format
- Thesis status
- Position status
- Recommended action
- Trigger levels
- Risk note

## Guardrails
- Add only to strength or planned support, not emotional hope.
- Trim when asymmetry worsens.
- Exit immediately when thesis is invalidated.
