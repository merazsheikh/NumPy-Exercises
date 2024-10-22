
# NumPy Exercises

This repository contains a Jupyter notebook that demonstrates various operations using NumPy, a fundamental package for scientific computing with Python. The notebook provides hands-on examples of array manipulations, including creating arrays, reversing arrays, reshaping, and more.

## Features

 - Creating arrays using NumPy (np.array())
 - Reshaping arrays and changing dimensions
 - Reversing arrays (both 1D and 2D)
 - Flipping arrays along different axes
 - Flattening arrays

## Prerequisites

To run the notebook, you'll need the following:

 - Python 3.x installed
 - Jupyter Notebook or Jupyter Lab
 - The following Python packages:
     - NumPy

You can install the necessary packages using the following command:

```bash
pip install numpy jupyter
```

## Getting Started

1. Clone this repository:

```bash
git clone https://github.com/yourusername/numpy-exercises.git
cd numpy-exercises
```

2. Navigate to the directory:
        
```bash
cd numpy-exercises
```

3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the NumPy.ipynb file in your browser.

5. Run the cells to explore the NumPy exercises and examples.

## Example Operations

Here are some of the key operations demonstrated:

- Creating a 1D array:

```python
x = np.array([89, 34, 56, 87, 90])
x.size  # returns 5, as the array has 5 elements
```

- Flipping a 2D array vertically:

```python
sample_2darray = np.array([[1,2,3,4],[5,6,7,8],[9,10,11,12]])
np.flip(sample_2darray, axis=0)
```
License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support
If you have any questions or run into issues, please:

Check the FAQ section
Open an issue in the repository
Contact the maintainers

Happy coding! 🚀
