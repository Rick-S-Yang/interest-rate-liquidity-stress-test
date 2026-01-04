# Interest Rate Sensitivity & Liquidity Stress Test 

A simplified, input-driven Excel model that evaluates **interest rate shocks** on **Net Interest Income (NII)** and provides a **basic liquidity stress view** (e.g., simplified LCR-style coverage) under multiple scenarios.

## What’s included
- **Inputs**: key balance sheet items, rates, and stress assumptions  
- **Model**: interest income/expense logic and scenario calculations  
- **Results**: scenario comparison outputs (Base / Up / Down)

## Scenarios
- **Base**
- **Up**: +100 bps parallel rate shock
- **Down**: −100 bps parallel rate shock

## Key outputs
- Net Interest Income (NII) by scenario  
- Cash impact under stress assumptions  
- Simplified liquidity coverage metric (LCR)

## Assumptions & scope
- Liquidity runoff assumptions are **held constant across scenarios** to isolate interest rate sensitivity.  
- This file is designed as a **simplified analytical framework**, not a full Asset–Liability Management (ALM) system.

## Content Preview

![Inputs and assumptions](images/inputs.png)

![Model structure](images/model.png)

![Scenario results](images/results.png)


## Notes / future improvements (optional)
- Link liquidity assumptions to rate scenarios (rollover constraints, haircuts)
- Add model controls (balance checks, error flags)
- Extend shocks beyond ±100 bps (sensitivity table)

