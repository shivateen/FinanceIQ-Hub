# DAMAC FinIQ — Finance AI Platform Hub

The top-level console for the **DAMAC Finance AI Platform** (Powered by Tiger Analytics).
A single light-themed landing page that links all five standalone finance agents and shows
them in a right-hand **Agents** roster.

## The five agents

| Agent | Capability | Live app |
|-------|------------|----------|
| CloseIQ | Autonomous Month-End Close | https://shivateen.github.io/CloseIQ/ |
| ForecastIQ | AI Financial Forecasting | https://shivateen.github.io/ForecastIQ/ |
| PaymentsIQ | IPC Certificate Validation | https://shivateen.github.io/PaymentsIQ/ |
| ReconIQ | Intercompany Reconciliation | https://shivateen.github.io/ReconIQ/ |
| ValuationIQ | M&A Valuation Co-pilot | https://shivateen.github.io/ValuationIQ/ |

## Structure

```
index.html   The hub / landing page (self-contained, links to the five live apps)
```

## Run locally

```
python -m http.server 3000
```

Then open http://localhost:3000.

## Deploy

Static site — **GitHub Pages → Deploy from branch → `main` / root**. Published at
https://shivateen.github.io/FinanceIQ-Hub/.
