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
- Simplified liquidity coverage metric (LCR-style)

## Assumptions & scope
- Liquidity runoff assumptions are **held constant across scenarios** to isolate interest rate sensitivity.  
- This file is designed as a **simplified analytical framework**, not a full Asset–Liability Management (ALM) system.

## How to use
1. Open the Excel file: `Interest_Rate_Sensitivity_and_Liquidity_Stress_Test.xlsx`
2. Go to the **Inputs** tab and adjust assumptions (rates, balances, stress parameters)
3. Review **Results** for scenario comparisons

## File structure
- `/Interest_Rate_Sensitivity_and_Liquidity_Stress_Test.xlsx` — main model

## Notes / future improvements (optional)
- Link liquidity assumptions to rate scenarios (rollover constraints, haircuts)
- Add model controls (balance checks, error flags)
- Extend shocks beyond ±100 bps (sensitivity table)

## Author
Rick Yang
