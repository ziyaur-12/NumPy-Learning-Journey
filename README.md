# NumPy Learning Project

This repository contains a step-by-step collection of Jupyter notebooks for
learning NumPy arrays, array operations, vectorization, broadcasting, and
working with saved `.npy` files.

## Topics Covered

### Phase 1: NumPy Basics

[`phase-1.ipynb`](./phase-1.ipynb) introduces the fundamentals:

- Creating NumPy arrays
- Python lists vs NumPy arrays
- Creating arrays with `zeros`, `ones`, `full`, `random`, and `arange`
- Vectors, matrices, and tensors
- Array dimensions and reshaping
- Flattening, transposing, squeezing, and raveling arrays

### Phase 2: Array Operations

[`phase-2.ipynb`](./phase-2.ipynb) covers common array manipulation techniques:

- Arithmetic operations on arrays
- Sorting arrays
- Filtering values
- Boolean masks
- Fancy indexing and `np.where()`
- Adding and removing data
- Array compatibility
- Combining arrays with `vstack` and `hstack`
- Deleting rows and columns

### Phase 3: Advanced NumPy

[`phase-3.ipynb`](./phase-3.ipynb) demonstrates practical NumPy concepts:

- Business-style sales data analysis
- Yearly totals and averages
- Vector operations
- Vectorized calculations
- Broadcasting
- Dot products, norms, and angles between vectors

### Phase 4: Saving, Loading, and Visualization

[`phase-4.ipynb`](./phase-4.ipynb) explains how to:

- Save arrays using `np.save()`
- Load arrays using `np.load()`
- Work with `.npy` files
- Load and display a NumPy logo
- Create a dark version of an image using array operations
- Visualize arrays with Matplotlib

## Project Structure

```text
.
├── phase-1.ipynb       # NumPy basics
├── phase-2.ipynb       # Array operations
├── phase-3.ipynb       # Advanced operations and examples
├── phase-4.ipynb       # Saving, loading, and visualization
├── array1.npy          # Example saved integer array
├── array2.npy          # Example saved floating-point array
├── array3.npy          # Example zero-filled array
└── numpy-logo.npy      # NumPy logo image data
```

## Requirements

- Python 3
- NumPy
- Matplotlib
- Jupyter Notebook or JupyterLab

## Installation

Create and activate a virtual environment if needed:

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

Install the required packages:

```powershell
pip install numpy matplotlib jupyter
```

## Running the Notebooks

Open the project folder in a terminal and start Jupyter:

```powershell
jupyter notebook
```

Then open the notebooks in this order:

1. `phase-1.ipynb`
2. `phase-2.ipynb`
3. `phase-3.ipynb`
4. `phase-4.ipynb`

Run each cell from top to bottom. The notebooks in Phase 4 expect the `.npy`
files to be in the same folder as the notebook.

## Example

```python
import numpy as np

array = np.array([1, 2, 3, 4, 5])
print(array * 2)
```

## Learning Goals

After completing this project, you should be able to:

- Create and inspect NumPy arrays
- Perform fast numerical operations
- Select and filter array data
- Reshape and combine arrays
- Use vectorization and broadcasting
- Save and load NumPy data
- Visualize array data with Matplotlib

## GitHub Repository

View this project on GitHub:

https://github.com/ziyaur-12/NumPy-Learning-Journey
