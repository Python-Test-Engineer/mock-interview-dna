Used Sonnet 4.6 not most advanced Opus 4.6

No info card was supplied - just the CSV.

I start with general ideas `kaggle_ideas.md` then use a command to create a detailed plan `kaggle_plan.md` and review that (I did not).

I then use the spec command to create a detailed technical specification which can be reviewed.

This spec is then executed and produces plots, charts, reports in the OUPUTS folder.

There is a `report.html` and plots and charts in `plots` folder.

I run a dashboard command to create a shiny dashboard.

Install UV `https://docs.astral.sh/uv/getting-started/installation/`or use `requirements.txt` with pip

- `uv sync` loads in all the libraries.
- ` .\.venv\Scripts\activate` to activate the virtual environment.
- `uv run src/dashboard.py` to run the Shiny dashboard.