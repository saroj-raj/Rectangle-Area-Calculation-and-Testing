## Project Title
Rectangle Area Calculation and Testing

## Description
This project involves calculating the area of a rectangle given its length and width. It also includes unit tests to validate the function using different test cases. The project is implemented in Python, using unittest for testing.

## Getting Started

### Dependencies
- Python 3.x
- Jupyter Notebook (optional, if running the notebook version)
- Libraries: unittest, argparse (for running tests in the notebook)

### Installation
1. Install Python 3.x and Jupyter Notebook if not already installed.
2. Install required Python libraries:
    ```bash
    pip install unittest2
    ```

### Executing Program
#### Notebook Version
1. Open `A2_555.ipynb` in Jupyter Notebook and run the cells to execute the area calculation and tests.
2. Alternatively, run the Python script:
    ```bash
    python A2_555.py
    ```

### Problem Statement
The goal is to calculate the area of a rectangle given its length and width. The project also includes unit tests to validate the correctness of the calculation function using different scenarios:
1. Valid input
2. Zero length or width
3. Negative length or width

### Example Execution
- The program prompts the user to enter the length and width of the rectangle.
- It calculates the area and prints the result.
- The unit tests check for valid input, zero values, and negative values to ensure the function handles all cases correctly.

## Contents
- `A2_555.ipynb`: Jupyter Notebook for calculating rectangle area and running tests.
- `A2_555.py`: Python script for calculating rectangle area and running tests.

### Test Cases
1. **Valid Input**: 
    - Input: length = 5, width = 4
    - Expected Output: area = 20
    - Test Status: Passed
2. **Zero Length or Width**:
    - Input: length = 0, width = 8
    - Expected Output: area = 0
    - Test Status: Passed
3. **Negative Length or Width**:
    - Input: length = -3, width = 6
    - Expected Output: Raises ValueError
    - Test Status: Passed

## Output
The program will output the area of the rectangle based on user input and will display the results of the unit tests, indicating whether they passed or failed.

### Example Run
```python
Enter the length of the rectangle: 5
Enter the width of the rectangle: 4
The area of the rectangle with length 5.0 and width 4.0 is 20.0
```

## Authors
- Saroj Raj
- [LinkedIn Profile](https://www.linkedin.com/in/saroj-raj-22831198/)

## Version History
- 0.1
    - Initial Release
