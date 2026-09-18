# COSC 310 — Lecture 2

Python menu filtering, a shopping cart, business rules, and pytest tests.

## Setup and tests

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r starter/requirements.txt
pytest -v
```

Run the examples with `python starter/exercise1.py`,
`python starter/exercise2.py`, and `python starter/exercise3.py`.

The cart in `starter/exercise3.py` rejects quantities below one and unavailable
items in `add_item`, and rejects missing item IDs in `remove_item`.
Tests are in `starter/tests/test_cart.py`.
