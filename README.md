#  Refurbished Phone Selling – Demo App

A Streamlit demo for managing refurbished phone inventory, computing platform-specific listing prices, and simulating marketplace listings.

---

## Features

* Secure login (mock, configurable via environment variables).
* Add, edit, delete, and bulk import/export inventory.
* Automatic and manual price computation with platform fee models.
* Profitability guard with configurable thresholds.
* Condition mapping per platform with validation.
* Listing simulator with stock and reservation safeguards.
* Activity log of all operations.

---

## Installation

```bash
git clone https://github.com/yourusername/refurbished-phone-demo.git
cd refurbished-phone-demo
pip install -r requirements.txt
```

Requirements: `streamlit`, `pandas`, `openpyxl`.

---

## Usage

```bash
streamlit run app.py
```

Default credentials:

* **Username:** `admin`
* **Password:** `admin123`

Environment overrides: `RPAPP_USER`, `RPAPP_PASS`.

---

## Notes

* Fee models and condition mappings are simplified for demo purposes.
* All listings are **simulated only** – no external integrations.

---

## License

MIT License

---

Do you want me to rename the script to **`app.py`** in the README (instead of that long filename) so it looks cleaner and more professional?
