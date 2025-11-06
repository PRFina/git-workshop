# Yet Another Git Resource

This repository contains the core materials for an interactive, in-person workshop on Git. The main artifact is a Jupyter Notebook that serves as a structured reference guide for the workshop's content.

> ⚠️ NOTE:
    This material is NOT a self-guided tutorial for learning Git. The Jupyter Notebook is designed to be used as a reference guide during or after attending the assisted, instructor-led workshop.

## Content Overview
The repository is structured around the `workshop.ipynb` notebook. This notebook lays out the conceptual flow and practical exercises of the workshop.

* It contains brief explanations of key Git concepts that were discussed live.

* It defines the practical scenarios and commands demonstrated by the instructor.

* The final section of provides a curated list of high-quality external resources to help users deepen their Git knowledge post-workshop.

## Installation & Setup
To run the Jupyter Notebook and view the content locally, you will need to set up the environment.

#### Prerequisites
* Ensure you have Python installed.

* Ensure you have Git (>=2.23) installed.

#### Environment Setup

1. Clone the Repository:
    ```Bash
    git clone https://github.com/PRFina/git-workshop
    cd git-workshop
    ```

2. Create a Virtual Environment (Recommended):

    ```Bash
    # For Linux/macOS
    python3 -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt
    ``` 

    If you prefer using `uv`
    
    ```bash
    uv sync
    ```

3. Launch Jupyter Notebook:

    ```Bash
    jupyter lab
    ```

    or use [vscode](https://code.visualstudio.com/docs/datascience/jupyter-notebooks) if you prefer. 