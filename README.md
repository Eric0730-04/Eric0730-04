# Hi, I'm Eric Sun 👋

**Data Analytics · Financial Analytics · Applied Machine Learning · AI Agents**

I'm pursuing a **Master of Management in Analytics at McGill University**, with a B.A. in **Economics and Data Science from UW–Madison**. I'm also a **CFA Level I candidate**, based in Montréal.

I build analytical tools that connect financial data and business questions to clear decisions—from checking investment ideas and interpreting corporate filings to investigating retail returns. My projects combine statistical analysis, machine learning, and AI agents with traceable evidence.

A few fun facts about me:

- 📈 I'm a retail investor.
- 📷 I'm an amateur photographer — [Photo selection](https://reflective-produce-ddd.notion.site/Eric-s-Photo-Selection-Space-1f163511629c4b07ad1135ddd88369e0).
- 🚴 I've completed a 100 km bike ride in 6 hours.
- 🏓 I'm a National Level 2 table tennis athlete (China).

[Portfolio](https://Eric0730-04.github.io) · [LinkedIn](https://www.linkedin.com/in/chang-sun-730841255/) · [Email](mailto:csun236@outlook.com)

## Featured Datathon & Hackathon Projects

### [SecondLook — PolyFinances Datathon 2026](https://github.com/Eric0730-04/polyfinances-datathon-2026)

**AlphaForge AI · Team 10 · Investment Decision Support**

A multi-agent prototype that gives self-directed investors a second look at an investment idea before they act.

- Checks proposed portfolio changes against an investor's goals, time horizon, risk capacity, concentration limits, and ESG preferences across a **50-asset universe**.
- Combines specialised agents on Amazon Bedrock with deterministic portfolio calculations, a rules engine, Guardrails, and S3 audit traces; includes a what-if simulator and explanations of what would change the verdict.
- Matched the expected rule-based verdicts in **36/36 prototype evaluation runs** across 18 scenarios, each repeated twice. See the [evaluation and scope](https://github.com/Eric0730-04/polyfinances-datathon-2026/blob/main/docs/evaluation.md).

**Built with:** Python · FastAPI · Amazon Bedrock · AWS Lambda · Amazon S3

**[Watch / download the full SecondLook demo — 4:52](https://github.com/Eric0730-04/polyfinances-datathon-2026/releases/download/demo-video/secondlook-demo.mp4)** · [Video guide](https://github.com/Eric0730-04/polyfinances-datathon-2026/blob/main/docs/demo_video.md)

[![SecondLook in action: investment checks, follow-up questions, and investor comparison](https://raw.githubusercontent.com/Eric0730-04/polyfinances-datathon-2026/main/docs/media/secondlook-preview.gif)](https://github.com/Eric0730-04/polyfinances-datathon-2026/releases/download/demo-video/secondlook-demo.mp4)

*Short silent preview; the complete MP4 includes audio.*

### [8-K Revision Agent — Asset Management Datathon](https://github.com/Eric0730-04/8k-revision-agent)

**McGill–FIAM Asset Management Hackathon 2026 · AI Agent Developer**

My AI-agent contribution to a team project combining quantitative equity strategies with financial disclosure analysis, now available as a standalone public demo.

- Built a Claude-powered research assistant to help portfolio managers assess whether SEC 8-K filings are likely to trigger **EPS estimate or price-target revisions within five trading days**.
- Integrated teammates' predictive models with Python tools for historical filing comparisons and analyst revision timelines, presented through a Streamlit interface.
- Enforced historical data cutoffs and clearly distinguished model predictions, historical evidence, and the agent's interpretation of filing text.

**Built with:** Python · Claude API · Streamlit · pandas · scikit-learn · LightGBM

**[Explore the public demo & source](https://github.com/Eric0730-04/8k-revision-agent)** · [How to use the agent](https://github.com/Eric0730-04/8k-revision-agent/blob/main/docs/WALKTHROUGH.md)

[![8-K agent walkthrough: submit a filing, run the tools, and inspect the research note](https://raw.githubusercontent.com/Eric0730-04/8k-revision-agent/main/docs/assets/walkthrough.gif)](https://github.com/Eric0730-04/8k-revision-agent#watch-the-workflow)

*The public edition includes a no-key offline walkthrough and optional live Claude tool use with synthetic data and illustrative scores. The team's licensed data and trained models remain private.*

### [Return Detective — Return Agent Hackathon](https://github.com/Eric0730-04/Return_Agent_Hackathon)

**ALDO / BSRM RetailGen AI Hackathon · Team Lead · 4th Place out of 42 Teams**

A prototype that turns unusual retail return patterns into evidence-based investigations and proposed responses for human review.

- Led a **five-person team** to deliver a working prototype in **42 hours** and presented a live demo to judges from AWS and ALDO Group.
- Designed a three-agent workflow—**Triage, Investigator, and Response**—using Strands Agents and Amazon Bedrock to investigate potential product and operational issues.
- Connected SQL screening, dated evidence, human approval gates, persistent case records, and historical follow-up checks in a Streamlit workspace.

**Built with:** Python · SQL · Strands Agents · Amazon Bedrock · Streamlit · Athena · DynamoDB

## Financial Due Diligence Work Samples

Selected financial writing, from public-market equity research to private-company due diligence.

| Work sample | Analysis | Read the report |
| --- | --- | --- |
| **UnitedHealth Group (UNH)** | Business model, industry positioning, financial analysis, scenario valuation, and investment risks. Research dated September 30, 2026. | [Equity research PDF](https://eric0730-04.github.io/financial-due-diligence-work-samples/unh-equity-research-eric-sun.pdf) |
| **Sereniby** | Product differentiation, market positioning, channel economics, and the investment case. June 29, 2025; public edition with sensitive company and personal information redacted. | [Redacted diligence PDF](https://eric0730-04.github.io/financial-due-diligence-work-samples/sereniby-due-diligence-eric-sun-redacted.pdf) |

[Browse the work samples on my portfolio](https://eric0730-04.github.io/#financial-due-diligence) · [Files and publication notes](https://github.com/Eric0730-04/Eric0730-04.github.io/tree/main/financial-due-diligence-work-samples)

## Analytics Project Experience

### Academic Analytics Consulting Projects with Propel Holdings

**Risk Division Data Engineer / Modeler – Customer Lifetime Value (CLV)**

Toronto, Canada · Sep 2026 – Present

- Developing component models in Python on a customer-month panel built from Snowflake and MySQL, benchmarking LightGBM and XGBoost against logistic regression, and integrating the existing default score into a probabilistic decomposition of future behavior.
- Partnering with finance team to define key profitability and credit utilization metrics, translating financial business logic into predictive modeling specifications.

## Academic Projects

Coursework projects in predictive modelling, classification, and operations research.

| Project | Focus & Contribution | Tools |
| --- | --- | --- |
| [Predicting Online Purchase Intention](https://github.com/Eric0730-04/Predicting-Online-Purchase-Intention) | Developed the **KNN and Random Forest** models for a team study of purchase behaviour; contributed to an offline classification benchmark with cross-validation and feature-leakage analysis. | Python, scikit-learn, Jupyter |
| [Fake News Detection](https://github.com/Eric0730-04/Fake_News_Detection_ML) | Analysed **4,000 news articles**, compared four classifiers, and selected a tuned RBF SVM; examined the precision–recall trade-off and limits of using non-text features. | Python, pandas, scikit-learn |
| [Production Line Optimization](https://github.com/Eric0730-04/Production-Line-Optimization) | Modelled a truck manufacturer's product mix with linear programming; used shadow prices and sensitivity analysis to evaluate capacity bottlenecks and management constraints. | Excel Solver, Linear Programming |

## Technical Skills

| Area | Tools & Methods |
| --- | --- |
| **Programming & Data** | Python, SQL, pandas, NumPy, MySQL, Excel |
| **Machine Learning** | scikit-learn, LightGBM, XGBoost, Regression, Random Forest, KNN, SVM, Clustering, PCA |
| **AI & Applications** | Amazon Bedrock, Strands Agents, Claude API, Tool Calling, Streamlit, FastAPI |
| **Cloud & Analytics** | AWS Lambda, S3, Athena, DynamoDB, Databricks, Power BI, Git/GitHub |
| **Analytical Methods** | Cross-Validation, Time-Series Evaluation, Portfolio Risk Analysis, A/B Testing, Linear Programming, Sensitivity Analysis |

## Education

**McGill University** — Master of Management in Analytics  
Current GPA: **4.00/4.00** · **$16,000 Entrance Scholarship**

**University of Wisconsin–Madison** — B.A. in Economics and Data Science  
GPA: **3.78/4.00** · Dean's List: Fall 2024 and Spring 2025
