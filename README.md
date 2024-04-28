# Markdown to Word 202404

## Usage

```bash
python docx-202404-from-md.py TEMPLATE.md TEMPLATE.docx
```

* For installation instructions, see the [Installation](#installation) section before reading following notes.
* If you use conda, you need to activate the environment before running the script.

    ```bash
    conda activate ./.conda
    ```

    * If you do not use conda, you do not need to activate the environment.
* You can invoke the script from any directory as long as you either activate the conda environment or have the required packages installed.

## Installation

### Prerequisites

* Git
* Miniconda
    * Alternatively, Python 3.12 or later with `python-docx`, `beautifulsoup4`, `requests`, and `ruff` installed.
* Pandoc

### Setup

* Clone the repository.

    ```bash
    git clone --recurse-submodules https://github.com/mehmetoguzderin/docx-202404-from-md
    cd docx-202404-from-md
    ```

* If you use conda, create the environment.

    ```bash
    conda env create --prefix ./.conda -f environment.yml --yes
    ```

    * If you do not use conda, install the required packages.

        ```bash
        pip install python-docx beautifulsoup4 requests ruff
        ```

* Install Pandoc.

    * On Ubuntu:

        ```bash
        sudo apt install pandoc
        ```

    * On macOS:

        ```bash
        brew install pandoc
        ```

    * On Windows:

        Download the installer from the [official website](https://pandoc.org/installing.html).

* If you use conda, activate the environment.

    ```bash
    conda activate ./.conda
    ```

    * If you do not use conda, you do not need to activate the environment.

* Run the script.

    ```bash
    python docx-202404-from-md.py TEMPLATE.md TEMPLATE.docx
    ```
