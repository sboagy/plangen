# plangen

A Python project that processes a JSON file and outputs a spreadsheet-compatible file (XLSX) for easy import into Google Sheets.

## Requirements
- Python 3.8+
- [pandas](https://pandas.pydata.org/) (for CSV/XLSX output)
- [openpyxl](https://openpyxl.readthedocs.io/) (for XLSX output)

## Setup
1. Install dependencies:
   ```sh
   pip install -r requirements.txt
   # or, using pyproject.toml (PEP 621):
   pip install .
   ```

## Usage
Run the main program with:
```sh
python main.py <input.json> <output.xlsx>
```
- `<input.json>`: Path to your input JSON file (should be a list of objects).
- `<output.xlsx>`: Path to the output XLSX file.

The resulting XLSX can be imported directly into Google Sheets and will support formulas if present in the data.
