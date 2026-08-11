# Market Price Forecasting System

A comprehensive Python-based market intelligence and price forecasting system designed to analyze commodity price trends across local and international markets. The system processes market data to deliver actionable trading insights and strategic recommendations for commodity traders, analysts, and business decision-makers.

---

## Market Coverage

The system performs comparative analysis across two distinct market environments:

- **Kano Central Market** – A representative local market capturing regional trade dynamics, supply chain constraints, and domestic pricing patterns
- **Makurdi International Market** – A global trading hub reflecting international price trends, cross-border demand, and foreign exchange influences

This dual-market approach enables traders to identify arbitrage opportunities, understand price differentials, and make informed cross-market decisions.

---

## Core Functionality

### 1. Price Increase Analysis
- Calculates percentage and absolute price changes for each commodity over the analysis period
- Identifies commodities with the largest price increases
- Ranks products by growth rate for investment prioritization
- Provides historical context for price movements

### 2. Current Selling Price Comparison
- Compares real-time current selling prices across both markets
- Determines which market offers premium pricing for each commodity
- Calculates price differentials and potential profit margins
- Highlights market inefficiencies and opportunities

### 3. Expected Market Price Validation
- Compares current prices against projected or expected price targets
- Identifies markets that have reached their forecasted price levels
- Evaluates forecasting accuracy and market performance
- Signals whether prices are aligning with predictions

### 4. Supply Sufficiency Assessment
- Evaluates current stock levels against demand projections
- Classifies markets as having sufficient supply for the forecast period
- Identifies potential stockout risks and supply shortages
- Provides inventory management recommendations

### 5. Market Momentum Evaluation
- Assesses market activity, turnover, and velocity
- Identifies markets requiring additional momentum or stimulation
- Suggests promotional strategies or marketing interventions
- Flags underperforming markets for strategic review

### 6. Commodity Trader Recommendation Engine
- Synthesizes all analysis outputs to generate trading recommendations
- Evaluates markets based on price, supply, growth potential, and risk
- Recommends optimal markets for bulk purchasing decisions
- Provides rationale and supporting data for each recommendation

---

## Commodities Analyzed

The system tracks multiple commodities to enable comprehensive market intelligence:

*(Replace with your actual commodities)*
- **Commodity A** – Staple food product with high local demand
- **Commodity B** – Export-oriented product with international price sensitivity
- **Commodity C** – Seasonal product with volatile pricing patterns
- **Commodity D** – Industrial raw material with strategic importance

---

## Technical Implementation

### Programming Concepts Applied

| Concept | Application in Project |
|---------|----------------------|
| **Variables & Data Types** | Storing commodity names, prices (integers/floats), market names (strings), and supply status (booleans) |
| **Arithmetic Operations** | Calculating price differences, percentage changes, averages, and profit margins |
| **Comparative Operators** | Comparing prices across markets, checking against expected targets, and evaluating supply thresholds |
| **Logical Operators** | Combining multiple conditions for complex decision-making (e.g., price above target AND supply sufficient) |
| **Conditional Statements** | Implementing if/elif/else logic for market classification, alert generation, and recommendations |
| **User Input Handling** | Accepting dynamic data entry for scenario testing and sensitivity analysis |
| **Type Conversion** | Converting string inputs to appropriate numeric types for accurate calculations |

### Data Processing Architecture

1. **Data Input Layer**
   - Accepts commodity details (names, prices, quantities)
   - Captures market-specific data for both locations
   - Handles multiple product entries simultaneously

2. **Processing Layer**
   - Performs price calculations and statistical comparisons
   - Evaluates conditions against business rules
   - Generates intermediate metrics and indicators

3. **Analysis Layer**
   - Answers specific business questions using processed data
   - Identifies patterns and outliers
   - Produces classification outputs (sufficient, high increase, etc.)

4. **Output Layer**
   - Presents results in clear, business-readable formats
   - Highlights key findings and recommendations
   - Provides supporting calculations for transparency

---

## Business Applications

### Strategic Planning
- Supports budget allocation and purchasing decisions
- Enables scenario planning for different market conditions
- Informs long-term investment strategies

### Trading Operations
- Identifies profitable trading opportunities
- Guides bulk purchasing decisions
- Optimizes portfolio diversification

### Inventory Management
- Prevents stockouts through supply forecasting
- Reduces holding costs through demand alignment
- Balances stock across markets

### Marketing Strategy
- Identifies markets needing promotional push
- Supports pricing strategy optimization
- Informs customer targeting decisions

### Risk Management
- Flags market volatility and price instability
- Identifies supply chain vulnerabilities
- Supports hedging and mitigation strategies


---

## Key Business Questions Answered

The system directly addresses six critical business questions:

| # | Question | Business Value |
|---|----------|----------------|
| 1 | Which commodity recorded the largest price increase? | Identifies high-growth investment opportunities |
| 2 | Which market has the highest current selling price? | Informs pricing strategy and market selection |
| 3 | Which market reached its expected market price? | Validates forecasts and signals saturation |
| 4 | Which market has sufficient supply after updates? | Guides restocking and supply chain decisions |
| 5 | Which market requires additional momentum? | Flags markets needing marketing intervention |
| 6 | Which markets would you choose for bulk purchasing? | Directs trading decisions with data-backed rationale |

---

## Sample Output Structure

### Price Analysis Report
<img width="1122" height="670" alt="N2" src="https://github.com/user-attachments/assets/44c32fd7-b2d1-4f85-8e28-1912c03d2e18" />
<img width="1156" height="676" alt="N5" src="https://github.com/user-attachments/assets/921af8c3-b706-4854-abb7-29605aefd131" />
<img width="1151" height="613" alt="N4" src="https://github.com/user-attachments/assets/1ed87464-dca0-41b4-a269-070bd744de3f" />
<img width="1131" height="602" alt="N3" src="https://github.com/user-attachments/assets/232cdd88-90a7-453c-afd3-1e3b0ba31795" />
