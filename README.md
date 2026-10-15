### Hi, I'm Neil (Thanapol Doungsaeng)

I'm a data scientist at KasikornBank, based in Los Angeles while I finish my MSBA at UCLA Anderson. Before that I was at KBTG, the bank's technology arm.

I build three kinds of things: forecasts that hold up when you test them on more than one window, AI agent systems where code does the math and people approve the decisions, and dashboards that turn raw data into something a manager can act on.

#### Projects

| Project | What it is | Built with |
| --- | --- | --- |
| [**LA home value forecast**](https://github.com/neiltd/la-housing-forecast) · [live map](https://neiltd.github.io/la-housing-forecast/) | 14 models across 18 rolling forecast origins. ARIMAX with mortgage rates had the lowest error (2.67%); LSTM, XGBoost and Amazon's Chronos never beat it. We also tested whether Claude, GPT and Gemini can forecast prices once you hide the dates. Team project, UCLA Anderson. | Python, statsmodels, LightGBM, LLM APIs |
| [**Procurement audit planner**](https://github.com/neiltd/procurement-audit-planner) | Plans an internal audit from a UK council's public spend data. Six agents read and judge, Python computes every number, and a human auditor approves the risk register before the plan gets written. | Claude Code skills, sub-agents, agent teams |
| [**Audit planner harness**](https://github.com/neiltd/audit-planner-harness) | The same pipeline running as a standalone web app on the Claude API, with no Claude Code underneath. About 2,100 lines of Python. | FastAPI, Anthropic SDK, SSE |
| [**World Intelligence**](https://github.com/neiltd/worldmaphistory_v2) · [live site](https://neiltd.github.io/worldmaphistory_v2/) | An interactive map for investment research covering 214 countries and 1,500+ infrastructure points (ports, power plants, cables, chokepoints), tied to sector exposure. | React, TypeScript, MapLibre GL |
| [**E-commerce operations dashboard**](https://github.com/neiltd/ecommercedashboards) · [live demo](https://neiltd.github.io/ecommercedashboards) | Late-delivery tracking, regional demand and order trends on the Olist dataset, all in the browser. | JavaScript, Chart.js, Tailwind |

#### What I'm good at

- **Forecasting and ML:** time series (ARIMA/ARIMAX, VAR), gradient boosting, deep learning, and honest evaluation with rolling backtests.
- **AI agents:** multi-agent pipelines, tool use, human-in-the-loop gates, and checks that catch a model making numbers up.
- **Analytics:** SQL, Python, dashboards, and turning results into a recommendation someone can use.

#### Reach me

[LinkedIn](https://www.linkedin.com/in/thanapol-ds) · open to data science and AI engineering roles in LA or remote.
