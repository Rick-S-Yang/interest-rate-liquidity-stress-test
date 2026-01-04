# Interest Rate Sensitivity & Liquidity Stress Test

- This project presents a simplified asset–liability and liquidity stress testing model designed to evaluate the impact of interest rate shocks on net interest income (NII) and short-term liquidity position.  
- The model is intended for educational and analytical demonstration purposes, aligned with entry-level risk, treasury, and financial analyst workflows.

---

## Overview

The model evaluates how interest rate shocks affect:
- Net Interest Income (NII)
- Cash position after liquidity stress
- A simplified Liquidity Coverage–style metric
  
---

## Model Structure

The Excel file is organized into three sections:

- **Inputs**
  - Simplified balance sheet (assets and liabilities)
  - Interest rate assumptions
  - Liquidity stress parameters
- **Model**
  - Interest income and expense calculations
  - Net interest income (NII)
  - Cash inflow and outflow under stress assumptions
- **Results**
  - Scenario comparison of NII
  - Cash position after stress
  - Simplified liquidity coverage metric

---

## Scenarios

The model evaluates three parallel interest rate scenarios:

- **Base Case**
- **+100 bps Rate Shock**
- **−100 bps Rate Shock**

All calculations are dynamically linked to the input assumptions, allowing users to easily modify scenarios and observe results.

---

## Key Outputs

- Net Interest Income by scenario
- Cash balance after liquidity stress
- Simplified liquidity coverage indicator
- Comparative scenario table for quick interpretation

---

## Quick Start (How to Use)

1. Open `Interest_Rate_Sensitivity_and_Liquidity_Stress_Test.xlsx`
2. Navigate to the **Inputs** sheet
3. Adjust key assumptions, including:
   - Asset and liability balances
   - Fixed vs. floating interest rates
   - Liquidity inflow and outflow assumptions
4. Review updated results in the **Results** sheet
5. Compare outcomes across interest rate scenarios

No macros or external dependencies are required.

---

## Key Assumptions & Scope

**In scope:**
- Parallel interest rate shocks
- Simplified repricing of fixed and floating instruments
- Basic liquidity stress logic using assumed inflows and outflows

**Out of scope:**
- Non-parallel yield curve movements
- Behavioral modeling of deposits
- Basis risk and optionality
- Second-round macroeconomic effects

The model is intentionally simplified to emphasize clarity, transparency, and analytical reasoning rather than full-scale ALM system complexity.

---

## Model Controls & Limitations

- The model relies on static assumptions and does not simulate dynamic balance sheet adjustments
- Liquidity metrics are simplified proxies and should not be interpreted as regulatory LCR
- Results are sensitive to input assumptions and intended for directional analysis only

---

## Preview

Screenshots of the Inputs, Model, and Results sheets are included above to illustrate structure and outputs.

---

## Future Improvements

Potential extensions include:
- Non-parallel interest rate scenarios
- Duration and economic value of equity (EVE) sensitivity
- More granular liquidity runoff assumptions
- Visualization enhancements and automated scenario tables

---

## Tools & Skills Demonstrated

- Excel-based financial modeling
- Scenario and sensitivity analysis
- Interest rate risk and liquidity risk concepts
- Structured model documentation and controls

---

## Disclaimer

This project is for educational and portfolio demonstration purposes only and does not represent a production-level risk management system.

