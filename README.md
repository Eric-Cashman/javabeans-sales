# JavaBeans Sales

A small Pandas project for a data science course. It builds a DataFrame of coffee sales for the fictional chain JavaBeans, then analyzes total volume, year-over-year growth, and best/least-selling drinks.

## What's inside

- `dataframe_creation.ipynb`: the notebook with the DataFrame, calculations, and written strategy analysis
- `pyproject.toml`: project manifest listing dependencies (pandas, notebook)
- `uv.lock`: lockfile with the exact package versions used
- `main.py`: default file created by `uv init` (not used)

## How to run it

1. Install [uv](https://docs.astral.sh/uv/).
2. Clone this repo and move into the folder:
   ```
   git clone https://github.com/Eric-Cashman/javabeans-sales.git
   cd javabeans-sales
   ```
3. Install the dependencies:
   ```
   uv sync
   ```
4. Open `dataframe_creation.ipynb` in VS Code, select the project's `.venv` as the kernel, and click **Run All**.

## Tools

Python, Pandas, Jupyter Notebook, uv