# dataWave: the data processing notebook

**Metousiosis** |
Transitioning from a raw Excel export to a refined synthesized dataset that powers the dataWave web app backend.

![Banner Image](</img/Turner_wave_Betty Saunders.jpg> "Surfing Teahupo'o.")
<br>Waves breaking on a Lee Shore at Margate (W. Turner, 1840). Tate Modern, London.*(Photography: Betty Saunders)*

> This notebook details the data-processing pipeline used to produce the data that powers [this](https://github.com/brooks-code/blue-pacific-dataviz) contribution to the pacific dataviz challenge 2025. If you're curious about the submission:
>
> - Live [demo](https://brooks-code.github.io/blue-pacific-dataviz/).

---

## Table of Contents

<details>
<summary>Contents - click to expand</summary>

- [dataWave: the data processing notebook](#datawave-the-data-processing-notebook)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Acknowledgements](#acknowledgements)
  - [License](#license)

</details>

## Features

- *Data structuring* with logical groups by using sentinel flags
- Multiple layers of *data cleaning*
- *Data reshaping*: convert wide-format data into a long-format
- *Reciprocal transformation*: apply reciprocal conversion to values exhibiting inverse relationships
- *Value scaling*: normalizes raw values for consistency and easy comparability across groups
- *Data quality* checks
- *Interactive analytics* visualization

## Requirements

- Python 3.10+
- jupyterlab/notebook or an IDE with the jupyter extension
- *Recommended:* virtual environment (venv or conda)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/brooks-code/dataWave-data-processing-notebook.git
cd dataWave-data-processing-notebook
```

- Create and activate a virtual environment (venv example):

```bash
python -m venv .venv
# macOS / Linux
source .venv/bin/activate
# Windows (PowerShell)
.venv\Scripts\Activate.ps1
```

Install dependencies:

```bash
pip install -r requirements.txt
```

or just run:

```bash
pip install jupyterlab notebook pandas numpy ipywidgets
```

I you have Jupyter notebooks already available on your system, you can also do it straight from the notebook by uncommenting and running this cell:

```python
# Uncomment this line
#%pip install pandas numpy ipywidgets
```

## Usage

- Start Jupyter, from the terminal:

```bash
# JupyterLab
jupyter lab

# or classic Notebook
jupyter notebook
```

- In the browser, open the notebook file (e.g., `dataWave_processing.ipynb`).

- Run cells in order:

Use Kernel -> Restart & Run All to execute the entire notebook from a clean state.

## Contributing

1) Fork the repository.
2) Create a feature branch (git checkout -b feature/your‑feature).
3) Commit your changes (git commit -m "Add …").
4) Push and open a Pull Request.

Please verify that:

- All new features are documented in this README.

## Acknowledgements

The [pacific dataviz](https://pacificdatavizchallenge.org/) team!  非常感谢你 (fēi cháng gǎn xiè nǐ).

## License

This project is released into the public domain under the [Unlicense](https://unlicense.org/). See the [LICENSE](/LICENSE) file for details. The source dataset remains the property and under the license provided by the original owner.
