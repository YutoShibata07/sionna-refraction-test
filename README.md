# Sionna Refraction - Custom Indoor Setting Test

## Overview

This project aims to test and demonstrate the refraction capabilities of the [Sionna](https://nvlabs.github.io/sionna/) library within a custom indoor environment configuration. The specific scenario involves simulating wave propagation around a table object made of wood.

## Prerequisites

*   Python 3.11
*   [uv](https://github.com/astral-sh/uv) (as a replacement for pip)
*   Jupyter Notebook or JupyterLab

## Installation

1.  Clone this repository (if you haven't already):
    ```bash
    # git clone <your-repo-url>
    # cd <your-repo-directory>
    ```

2.  Install the required Python packages using `uv`:
    ```bash
    uv pip install requirements.txt
    ```

## How to Test

1.  Navigate to the `notebooks` directory.
2.  Launch Jupyter Notebook or JupyterLab:
    ```bash
    jupyter notebook
    # or
    # jupyter lab
    ```
3.  Open and run the `refraction_demo.ipynb` notebook.

4.  **Verification Steps:**
    *   **Check Table Material:** Examine the notebook's configuration section or relevant output cells. Confirm that the material property assigned to the table object is set to `'wood'`.
    *   **Check for Transmission:** Analyze the simulation results, particularly any visualizations or plots showing wave propagation paths. Verify that there are **no** transmitted waves (i.e., waves passing through the table) visible below the table surface. This indicates that the material interaction (absorption/reflection based on the 'wood' properties) is working as expected for this setup, preventing transmission.