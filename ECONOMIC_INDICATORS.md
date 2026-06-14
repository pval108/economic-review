# Crucial Economic Indicators

## Core Indicators

1. **Inflation Rate** (CPI) - Measures purchasing power and cost of living
2. **Unemployment Rate** - Labor market health
3. **Fed Funds Rate** - Benchmark interest rate affecting borrowing costs
4. **GDP Growth** - Overall economic expansion or contraction
5. **Wage Growth** - Real income and consumer spending power

## Leading Indicators (predict future conditions)

- Consumer Confidence Index
- Initial Jobless Claims
- Yield Curve (10-year vs 2-year Treasury spread)
- New Home Starts & Building Permits
- Manufacturing PMI

## Real Estate & Credit

- 30-Year Mortgage Rates - Housing affordability
- Delinquency Rates - Credit health and financial stress
- Housing Prices

## Market Indicators

- Stock Market indices (S&P 500, Nasdaq)
- Credit spreads - Risk appetite

## Current Context (June 2026)

Look at whether:
- Inflation is cooling or accelerating
- Unemployment is rising or stable
- Fed raising/holding/cutting rates
- Yield curve normal or inverted
- Delinquencies rising (recession signal)

## Notebook Status

**Currently Tracking:**
- ✅ Inflation
- ✅ Unemployment
- ✅ Mortgage rates
- ✅ Fed Funds
- ✅ Delinquencies

**Recommended Additions:**
- GDP
- Wage Growth
- Consumer Confidence
- Stock prices

## What to Do With This Data

### Analysis Approaches

1. **Trend Analysis** - Identify patterns and turning points in each indicator
2. **Correlation Analysis** - See which indicators move together
3. **Leading/Lagging Relationships** - Understand cause-and-effect timing
4. **Regime Detection** - Identify expansions vs recessions vs stagflation
5. **Forecasting** - Predict future economic conditions
6. **Risk Assessment** - Quantify economic uncertainty and downside risks

### Key Questions to Answer

- Is the economy accelerating or decelerating?
- Are we heading toward recession or continued growth?
- Is inflation under control?
- Is the Fed too tight or too loose?
- What is the health of credit markets?
- When will the next crisis occur?

## Financial Models to Include

1. **Recession Prediction Model**
   - Use yield curve inversion, unemployment, delinquencies
   - Binary classification: recession risk yes/no

2. **Stock Price Forecast**
   - Regression: Fed Funds, Inflation, Unemployment → S&P 500
   - Test predictive power of macro indicators

3. **Interest Rate Path Forecast**
   - Time series model for Fed Funds direction
   - ARIMA or LSTM for rate trajectory

4. **Credit Risk Model**
   - Predict delinquency rates from unemployment & inflation
   - Gauge financial system stability

5. **Real Estate Valuation**
   - Mortgage rates + Employment + Wages → Housing prices
   - Identify overvaluation/undervaluation

## Statistical Models to Include

1. **Time Series Analysis**
   - ARIMA/SARIMA for autocorrelated indicators
   - Detect trends, seasonality, stationarity

2. **Vector Autoregression (VAR)**
   - Model relationships between all indicators simultaneously
   - Impulse response analysis: what happens if Fed raises rates?

3. **Principal Component Analysis (PCA)**
   - Reduce dimensionality: summarize economy in 1-2 components
   - Identify common economic cycles

4. **Hidden Markov Model (HMM)**
   - Detect market regimes (bull, bear, volatile, crisis)
   - Probabilistic state identification

5. **Correlation & Causality**
   - Granger causality tests: does inflation cause unemployment?
   - Rolling correlations: do relationships shift over time?

6. **Clustering & Segmentation**
   - Group similar economic periods
   - Identify which historical periods resemble today

7. **Machine Learning Classification**
   - Logistic Regression / Random Forest / Gradient Boosting
   - Predict recession, bull market, or stagflation
   - Feature importance: which indicators matter most?

8. **Deep Learning (LSTM/GRU)**
   - Sequence modeling for multi-step forecasts
   - Capture nonlinear relationships

## Implementation Priority

**Quick Wins (Start Here):**
1. Correlation heatmap - see what's connected
2. Trend visualization - what's changing?
3. Recession prediction (logistic regression on yield curve + unemployment)

**Medium Effort:**
4. VAR model - systemic relationships
5. Rolling correlations - regime shifts
6. Stock price regression

**Advanced:**
7. Hidden Markov Model for market regimes
8. LSTM for multi-step forecasting
9. PCA for economy factor extraction

## Loan Origination Market: What to Understand

### 1. What you need to know about loan origination

To understand how loan origination works, you need to track the full pipeline from borrower demand to lender approval to funding. The main pieces are:

- borrower credit quality
- income and employment stability
- collateral value and housing affordability
- interest rates and lender cost of funds
- regulation and underwriting standards
- liquidity in the secondary market
- competition among lenders

These elements determine whether origination volume rises or falls, how quickly loans close, and how profitable lending becomes.

### 2. Economic factors that drive loan origination

The most important macro factors are:

- inflation and expected inflation
- unemployment and wage growth
- Federal Reserve policy and short-term rates
- mortgage rates and long-term Treasury yields
- consumer confidence and spending
- housing inventory and home prices
- bank liquidity and credit spreads
- delinquency and default trends

These factors affect both borrower demand and lender willingness to lend.

### 3. What to expect at this point based on current data

Based on the indicators already in your notebook, the likely near-term picture is:

- loan demand will react to rate levels and affordability more than to broad economic optimism
- when rates are high, refinancing slows and purchase activity weakens
- if unemployment rises, borrower quality softens and delinquency risk increases
- if inflation cools, the Fed may ease policy later, which usually supports origination activity after a lag
- if housing prices continue to rise faster than wages, affordability becomes the main constraint

In other words, the market does not react instantly. It typically responds with a delay because loan production, underwriting, and borrower decision-making all take time.

### 4. How each factor impacts loan origination direction

#### Inflation
- Positive effect: moderate inflation can support nominal income growth and loan balances
- Negative effect: high inflation usually pushes rates higher, which suppresses refinance volume and slows new applications
- Reaction time: usually 1 to 6 months for borrower behavior, 6 to 12 months for lender pricing and underwriting changes

#### Unemployment
- Positive effect: low unemployment supports income stability and borrower quality
- Negative effect: rising unemployment reduces loan demand and increases defaults, especially in consumer and mortgage credit
- Reaction time: 3 to 9 months for origination volume changes, longer for credit performance deterioration

#### Federal Funds Rate / Monetary Policy
- Positive effect: lower rates reduce borrowing costs and support refinance and purchase activity
- Negative effect: higher rates raise funding costs and cool origination volume
- Reaction time: often 3 to 12 months, because lenders adjust pricing and borrowers respond after rate changes are visible

#### Mortgage Rates
- Positive effect: lower mortgage rates increase affordability and refinance activity
- Negative effect: higher mortgage rates reduce affordability and slow home buying
- Reaction time: immediate for pricing, 1 to 3 months for application volume, 3 to 6 months for funded volume

#### Wage Growth
- Positive effect: stronger wage growth improves affordability and credit quality
- Negative effect: weak wage growth limits purchasing power and increases stress in lower-income borrowers
- Reaction time: usually 2 to 6 months for borrower behavior

#### Housing Prices
- Positive effect: rising prices can increase home equity and support refinance and HELOC activity
- Negative effect: rapidly rising prices hurt affordability and reduce purchase activity
- Reaction time: 1 to 6 months for demand, longer for lender appetite in stressed markets

#### Delinquency Rates
- Positive effect: low delinquencies support lender confidence and easier credit standards
- Negative effect: rising delinquencies tighten underwriting and reduce loan availability
- Reaction time: 3 to 12 months, particularly after economic weakness becomes visible

#### Consumer Confidence
- Positive effect: higher confidence increases borrowing appetite and purchase sentiment
- Negative effect: low confidence reduces spending and borrowing activity
- Reaction time: usually 1 to 3 months for origination applications

### 5. Will origination increase or decrease over time?

The direction depends on the mix of these forces:

- If inflation falls, rates fall, and unemployment remains stable, loan origination usually increases over time
- If rates stay high, affordability remains weak, and unemployment rises, origination usually decreases over time
- If credit quality improves and lenders have sufficient liquidity, origination can increase even in a moderate-rate environment
- If lenders become more cautious due to defaults or market stress, origination can decline even when demand is present

In practical terms: expect slower market reaction to policy moves than to direct borrower affordability changes. Rate changes affect loan demand quickly, but funded volume and credit quality react more gradually.

### 6. How long does it take for the market to react?

Typical time horizons:

- immediate: mortgage pricing, lender rate sheets, borrower inquiries
- 1 to 3 months: application volume and pre-approval activity
- 3 to 6 months: funded loan volume and underwriting pipeline changes
- 6 to 12 months: broad market direction, lender standards, credit losses, and portfolio performance

This means the market often looks ahead, but actual origination results lag behind the latest economic news.

### 7. What to monitor for a practical view of the market

Track these in combination:

- mortgage rates
- inflation trend
- unemployment trend
- wage growth
- delinquency rates
- housing prices and inventory
- Fed commentary and policy expectations
- credit spreads and lender liquidity

If rates are falling and unemployment is stable, expect origination to improve over the next several quarters. If rates remain elevated and delinquencies rise, expect origination to weaken and underwriting standards to tighten.

### 8. Bottom line

Loan origination is not driven by one number. It is the result of borrower ability to qualify, lender willingness to fund, and economic conditions that change over time. The best signal is the combination of affordability, credit quality, and rate direction. If those three improve together, origination usually expands. If they worsen together, origination usually contracts.

