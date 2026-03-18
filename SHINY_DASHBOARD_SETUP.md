# Shiny Dashboard Setup — `src/dashboard.py`

## Using UV (recommended)

1. Install UV: https://docs.astral.sh/uv/getting-started/installation/

2. Sync dependencies:
   ```bash
   uv sync
   ```

3. Activate the virtual environment:
   ```bash
   .\.venv\Scripts\activate
   ```

4. Run the dashboard:
   ```bash
   uv run src/dashboard.py
   ```

> The dashboard may take a few moments to start up.

---

## Using pip

1. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   .\.venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the dashboard:
   ```bash
   python src/dashboard.py
   ```

It may seem idle for a bit as it build it.