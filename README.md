# Datathon 2026 Participant Guide

Welcome to the AI Community's premier event of the year.

The Datathon is a data analysis competition where student teams work with real-world datasets across four tracks:

- Education
- Sustainability & Critical Infrastructure
- Health Care & Wellness
- Finance & Economics

Teams develop meaningful research questions, validate insights using data analysis and/or machine learning, and present their work to a panel of SBU professors from different departments.

## Why This Event Is Structured This Way

Learning data analysis is fundamental to understanding AI.

Your goal is not to build a model first. Your goal is to ask a strong question first, use data analysis to support your claim, and optionally strengthen your conclusions with machine learning.

## What You Get

- Sample datasets for each track
- Starter notebooks in `starter-notebooks/`
- A workflow you can adapt to your own question and method

Current starter notebook:

- `starter-notebooks/technology.ipynb`

Use the starter notebook as a template for exploratory data analysis, feature exploration, and optional model validation.

## Recommended Team Workflow

1. Choose one track.
2. Propose a specific, testable question.
3. Load and clean your dataset(s).
4. Perform exploratory data analysis (EDA).
5. Test your hypothesis with statistics/analysis.
6. Optionally build a machine learning model to validate or extend findings.
7. Present a clear, evidence-based story: question -> method -> evidence -> conclusion -> limitations.

## Track Datasets

Here are the dataset links provided for each track.

### Education

- Collegeboard trends in college pricing
- Collegeboard trends in financial aid
- Kaggle Education and Unemployment
- Kaggle Education in India
- [Potential data: NCES](https://nces.ed.gov/)
- [NCES ECLS](https://nces.ed.gov/ecls/)
- [NSSE BCSSE](https://nsse.indiana.edu/bcsse/index.html)

#### Sample Research Questions

- How do changes in financial aid patterns relate to shifts in college affordability trends over time?
- Which education indicators best predict unemployment patterns across student populations?

### Health Care & Wellness

- [Sleep Health and Wellness](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)
- [Lung Cancer / Smoking](https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link/data)
- [Obesity or Cardiovascular Disease Risk](https://www.kaggle.com/datasets/aravindpcoder/obesity-or-cvd-risk-classifyregressorcluster)
- [Leukemia Image Classification](https://www.kaggle.com/datasets/andrewmvd/leukemia-classification/data)
- [Heart Failure Prediction](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data)
- [COVID-19 Dataset(s)](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)
- [CORD-19 Research Challenge (Scuffed)](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge)

#### Sample Research Questions

- Which lifestyle and health indicators are most strongly associated with sleep quality outcomes?
- Can clinical features from heart failure data be used to build a reliable early-risk screening model?

### Finance & Economics

- [Coca-Cola Complete updated stocks Dataset](https://www.kaggle.com/datasets/matiflatif/coca-cola-complete-stocks-dataweekly-updated)
- [Bitcoin Historical Data](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data)
- [FRED Economic Data](https://fred.stlouisfed.org/series/UNRATE)
- [NVIDIA Stocks Data 2025](https://www.kaggle.com/datasets/meharshanali/nvidia-stocks-data-2025)
- [Company Bankruptcy Prediction](https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction)
- [Palantir - Stock Data - Latest and Updated](https://www.kaggle.com/datasets/kalilurrahman/palantir-stock-data-latest-and-updated)
- [U.S. Census Data](https://data.census.gov/all)

#### Sample Research Questions

- How does macroeconomic unemployment movement relate to volatility in selected equity sectors?
- Which financial indicators contribute most to bankruptcy risk prediction in firm-level data?

### Sustainability & Critical Infrastructure

- Mapping Your Infrastructure: Datasets for Infrastructure Identification | CISA
- [Data.gov electrical grid datasets](https://catalog.data.gov/dataset?q=electrical+grid)
- [Energy Demand for Buildings (BuildingsBench)](https://catalog.data.gov/dataset/buildingsbench-a-large-scale-dataset-of-900k-buildings-and-benchmark-for-short-term-load-f)
- [Hourly Energy Consumption](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)
- [Global Energy Stats (UN)](https://www.kaggle.com/datasets/unitednations/international-energy-statistics)
- [World Energy Consumption](https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption)
- [Global Water Consumption](https://www.kaggle.com/datasets/atharvasoundankar/global-water-consumption-dataset-2000-2024)
- [NOAA Water Model](https://registry.opendata.aws/noaa-nwm-pds/)

#### Sample Research Questions

- Which infrastructure and energy indicators best explain short-term changes in energy demand?
- Are patterns in water consumption and energy usage converging or diverging across regions over time?

## Research Quality Expectations

Strong projects usually include:

- A clear and scoped question
- Transparent data cleaning and assumptions
- Visual and statistical evidence supporting claims
- Honest discussion of limitations
- Reproducible workflow in a notebook

Keep in mind: correlation does not always imply causation.

## Suggested Notebook Structure

Use this outline in your starter notebook:

1. Problem statement and hypothesis
2. Dataset description
3. Data cleaning and preprocessing
4. Exploratory data analysis (charts + key patterns)
5. Statistical tests and/or model design
6. Results and interpretation
7. Limitations and next steps

## Exploratory Data Analysis Resources

EDA is one of the most important skills you will use in this Datathon. Before building any model or drawing any conclusions, you need to deeply understand your data — its shape, distributions, missing values, and relationships between variables. Skipping or rushing EDA is the most common reason teams produce weak or misleading results. Strong EDA is what separates a compelling story from a guess.

### Why EDA matters for this Datathon

- **You do not know your data yet.** Real-world datasets always contain surprises: mislabeled categories, unexpected skews, columns that seem useful but aren't, and correlations that only appear after visualizing the data. EDA is how you find these things before they silently break your analysis.
- **Your research question may need to evolve.** Often, EDA reveals that the question you started with is either unanswerable with the available data or less interesting than a pattern you discover along the way. Judges reward teams that show evidence of this kind of thoughtful iteration.
- **Visuals are your primary communication tool.** You will present your findings to professors who may not be domain experts. Clear, well-labeled charts from your EDA directly become your presentation evidence. A good chart is worth more than a complex model with a number attached.
- **Models built without EDA often fail silently.** If you don't understand your feature distributions and class balance before modeling, you risk building a model that looks accurate but is actually learning noise or data artifacts. EDA is your safety check.

### Helpful EDA Guides

- [A Beginner's Guide to Exploratory Data Analysis with Python (Deepnote)](https://deepnote.com/app/code-along-tutorials/A-Beginners-Guide-to-Exploratory-Data-Analysis-with-Python-f536530d-7195-4f68-ab5b-5dca4a4c3579?utm_content=f536530d-7195-4f68-ab5b-5dca4a4c3579)
- [Intro to Exploratory Data Analysis (EDA) in Python (Kaggle)](https://www.kaggle.com/code/imoore/intro-to-exploratory-data-analysis-eda-in-python)

## Final Reminder

This Datathon rewards rigorous thinking.

Ask a meaningful question. Support it with data. Use machine learning where it adds value.
