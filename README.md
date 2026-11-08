# Calculator CI Project

This project follows the Week 3 lab: **Automate build and testing processes using CI pipelines**.

## Project files (in execution order)

1. `calculator.py` — contains the calculator functions.
2. `test_calculator.py` — contains five Pytest unit tests.
3. `.github/workflows/ci.yml` — configures GitHub Actions to run the tests whenever code is pushed to the `main` branch.

## Run locally or in Google Colab

Install Pytest:

```bash
pip install pytest
```

Run the tests from the project root:

```bash
pytest -v
```

Expected result: all five tests pass.

## Run the CI pipeline on GitHub

1. Upload the complete project contents to a GitHub repository.
2. Ensure the workflow file is at exactly `.github/workflows/ci.yml`.
3. Commit and push the files to the `main` branch.
4. Open the repository's **Actions** tab and check the **Calculator CI Pipeline** workflow run.

Note: Running Pytest in Colab tests the application locally. The automated CI workflow itself runs on GitHub Actions after a push to GitHub.
