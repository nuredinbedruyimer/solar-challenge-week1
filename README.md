# Project Setup

This repository includes the basic setup for the project environment, including a Python virtual environment, dependencies, and continuous integration using GitHub Actions.

## Branch

- All work is done on the `setup-task` branch.

## Files Added

- `.gitignore` — ignores `data/`, `.csv` files, and `.ipynb_checkpoints/`
- `requirements.txt` — lists Python dependencies
- `.github/workflows/ci.yml` — GitHub Actions workflow for basic CI

## Folder Structure

- `.vscode/`
  - `settings.json`
- `.github/`
  - `workflows/`
    - `unittests.yml`
- `.gitignore`
- `requirements.txt`
- `README.md`
- `src/`
- `notebooks/`
  - `__init__.py`
  - `README.md`
- `tests/`
  - `__init__.py`
- `scripts/`
  - `__init__.py`
  - `README.md`

## How to Reproduce the Environment

1. **Clone the repository**

   ```bash

   git clone <repository-url>
   cd <repository-folder>

   ```

2. **create and activate a virtual environment**

   ```bash

   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate

   ```

3. **install dependencies**

   ```bash

   pip install -r requirements.txt

   ```
