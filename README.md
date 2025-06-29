# Deep-Sum-Project
This project is a Python-based tool designed to compute the **deep (recursive) sum** of all numerical values within arbitrarily nested data structures. It supports lists, dictionaries, and JSON data containing numbers at any depth.
# 🧮 Deep Sum Project

This project is a Python-based tool designed to compute the **deep (recursive) sum** of all numerical values within arbitrarily nested data structures. It supports lists, dictionaries, and JSON data containing numbers at any depth.

The project includes a modular design with components such as `Header`, `Body`, and `Footer`, as well as test and example files. It can be used both programmatically and via command-line execution.

## Features

- Recursively sums integers and floats from deeply nested structures
- Accepts Python lists, dictionaries, or JSON files
- Modular code structure for maintainability
- Unit testing included

## Project Structure

- `main.py` – Entry point of the program
- `deep_sum.py` – Contains the recursive summation logic
- `test_deep_sum.py` – Unit tests for validation
- `requirements.txt` – Required Python packages
- `components/` – Optional UI modules:
  - `Header.py`
  - `Body.py`
  - `Footer.py`
- `examples/sample1.json` – Sample input data

## Example Input (sample1.json)

```json
{
  "a": 5,
  "b": [3, {"c": 7}, [1, 2]],
  "d": {"e": 10}
}
```

**Expected Output:**

```
Sum: 28
```


## Requirements

- Python 3.7+
- No external dependencies required unless added in `requirements.txt`



