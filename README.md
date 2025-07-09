# pytest-api-testing-framework
Educational API testing framework using Python &amp; Pytest, built from scratch following the TAU Pytest tutorial. Covers fixtures, assertions, parametrization, and reporting.

# 🧪 Pytest API Testing Framework

This repository is part of my QA Automation learning path and showcases key testing concepts using Python and Pytest. It’s based on the [Test Automation University Pytest Tutorial](https://testautomationu.applitools.com/pytest-tutorial/), and covers topics such as assertions, fixtures, test organization, parametrization, and test filtering.

All test cases are written against public APIs (e.g. JSONPlaceholder) using the `requests` library.

---

## 📚 Covered Topics

- Assertions and Pytest basics
- Fixtures (basic and scoped)
- Parametrized tests
- Skipping and marking tests
- Grouping tests by class and module
- Using `conftest.py` for shared logic

---

## 📂 Folder Structure

pytest-api-testing-framework/
├── tests/
│ ├── test_assertions.py
│ ├── test_fixtures_basic.py
│ ├── test_fixture_scope.py
│ ├── test_parametrize.py
│ ├── test_marks.py
│ ├── test_grouping.py
│ └── conftest.py
├── utils/
│ └── api_client.py
├── data/
│ └── test_payloads.json
├── reports/
├── requirements.txt
├── pytest.ini
└── README.md


---

## 🛠️ How to Use

1. Clone the repository  
2. Install dependencies:
```bash
pip install -r requirements.txt
```
Run tests and generate report:

```bash
pytest --html=reports/report.html
```

🔧 Tools Used
Python 3.11+

Pytest

Requests

Pytest-HTML
