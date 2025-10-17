# Insurance Claims Dashboard

A data analysis project using insurance claim data to analyze performance trends and visualize insights that could help identify risk or opportunity areas.

## Goal

Use insurance claim data to analyze performance trends and visualize insights that could help identify risk or opportunity areas.

## Stack

- **Python**: Data Analysis and Cleaning (pandas, numpy)
- **Jupyter Notebooks**: Exploratory Data Analysis
- **Power BI**: Data Visualization and Dashboard
- **Kaggle API**: Dataset sourcing and version control
- **Dataset**: https://www.kaggle.com/datasets/litvinenko630/insurance-claims

## Scope

- Clean and explore 5k rows of data
- Perform 3-5 analyses (e.g., average claim cost by region, claim type frequency, customer age vs cost)
- Build a Power BI dashboard with filters and visuals
- Summarize 2-3 key findings that "tell a story" (e.g., "Older policyholders have higher claim severity in urban areas")

## Project Structure

```
insurance-dashboard/
|-- notebooks/          # Jupyter notebooks for exploration and analysis
|-- data/               # Raw data from Kaggle (not committed to GitHub)
|-- .gitignore
|-- pyproject.toml      # Python dependencies
|-- README.md
```

## Setup

This project uses [uv](https://github.com/astral-sh/uv) for dependency management.

```bash
# Install dependencies
uv sync

# Start Jupyter
uv run jupyter notebook
```

## Kaggle API Setup
Docs: https://www.kaggle.com/docs/api#authentication

This project uses the Kaggle API to download datasets. To set up authentication:

1. Go to your Kaggle account settings: https://www.kaggle.com/settings
2. Click "Create New Token" under the API section
3. Move the downloaded `kaggle.json` to `~/.kaggle/kaggle.json`:

## Workflow

1. **Data Acquisition**: Download dataset via Kaggle API in Jupyter notebook
2. **Exploration & Cleaning**: Analyze and prepare data using pandas
3. **Analysis**: Perform 3-5 targeted analyses on key metrics
4. **Visualization**: Export cleaned data and build Power BI dashboard
5. **Insights**: Document 2-3 key findings with narrative

## Dataset

We found our dataset on [Kaggle](https://www.kaggle.com/) by searching for "insurance claims dataset" in our browser. It provides a realistic and well-structured sample of insurance claim records suitable for analysis and visualization. The dataset contains over 5,000 entries, offering enough data to uncover meaningful trends while remaining lightweight and easy to work with.
