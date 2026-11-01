 
# NumPy Analyzer

A menu-driven Python application for performing NumPy array operations and statistical analysis. This project combines the power of **NumPy** with **Object-Oriented Programming (OOP)** principles to provide an interactive toolkit for working with 1D, 2D, and 3D arrays.

## 🚀 Features

### 1. Array Creation
- Create 1D, 2D, and 3D NumPy arrays.
- Accept numeric input from the user.
- Automatically reshape input elements based on the selected dimensions.
- Display the created array.

### 2. Array Indexing and Slicing
- Access individual elements using array indices.
- Slice 1D arrays using start and end positions.
- Slice rows and columns in 2D arrays.
- Perform slicing operations on 3D arrays.

### 3. Mathematical Operations
Perform mathematical operations between arrays:
- Element-wise addition
- Element-wise subtraction
- Element-wise multiplication
- Element-wise division
- Dot product for 1D arrays
- Matrix multiplication for 2D arrays

Includes validation for array dimensions, input size, and division by zero.

### 4. Combining and Splitting Arrays
- Concatenate 1D arrays.
- Vertically stack multidimensional arrays.
- Split 1D arrays into equal parts.
- Split multidimensional arrays along a selected axis.

### 5. Searching, Sorting, and Filtering
- Search for specific values using `np.where()`.
- Sort arrays in ascending or descending order.
- Filter elements using comparison conditions:
  - Greater than (`>`)
  - Less than (`<`)
  - Equal to (`==`)
  - Not equal to (`!=`)
  - Greater than or equal to (`>=`)
  - Less than or equal to (`<=`)

### 6. Aggregates and Statistics
Calculate useful statistical values:
- Sum
- Mean
- Median
- Standard deviation
- Variance
- Minimum
- Maximum
- Percentile
- Correlation coefficient

## 🛠️ Technologies Used

- **Python 3** – Core programming language
- **NumPy** – Numerical computing and array manipulation

### NumPy Functions Demonstrated

| Function | Purpose |
|---|---|
| `np.array()` | Create NumPy arrays |
| `np.reshape()` | Change array dimensions |
| `np.concatenate()` | Combine arrays |
| `np.vstack()` | Vertically stack arrays |
| `np.split()` | Split arrays into equal sections |
| `np.sort()` | Sort array elements |
| `np.where()` | Find matching elements |
| `np.dot()` | Calculate dot product |
| `np.matmul()` | Perform matrix multiplication |
| `np.sum()` | Calculate sum |
| `np.mean()` | Calculate mean |
| `np.median()` | Calculate median |
| `np.std()` | Calculate standard deviation |
| `np.var()` | Calculate variance |
| `np.percentile()` | Calculate percentile |
| `np.corrcoef()` | Calculate correlation coefficient |

## 🧠 Object-Oriented Programming Concepts

This project demonstrates several important OOP concepts through the `DataAnalytics` class.

- **Class and Object:** Encapsulates NumPy operations inside the `DataAnalytics` class.
- **Constructor (`__init__`):** Initializes the array attribute and tracks object creation.
- **Encapsulation:** Uses private helper methods such as `_ensure_array_exists()` and `_validate_same_shape()`.
- **Class Method (`@classmethod`):** Tracks the total number of created instances through `get_instance_count()`.
- **Static Method (`@staticmethod`):** Provides general array information through `array_info()`.
- **Instance Methods:** Perform array creation, mathematical operations, sorting, filtering, and statistical calculations.

## 📂 Project Structure

```text
NumPy-Analyzer/
│
├── main.py
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/NumPy-Analyzer.git
```

### 2. Navigate to the Project Directory

```bash
cd NumPy-Analyzer
```

### 3. Install NumPy

```bash
pip install numpy
```

### 4. Run the Application

```bash
python main.py
```

## 📋 Main Menu

When you run the application, the following menu is displayed:

```text
=======================================================
       Welcome to the NumPy Analyzer!
=======================================================
Choose an option:
1. Create a NumPy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit
=======================================================
```

Choose an option and follow the interactive prompts to perform the desired operation.

## 🎯 Learning Objectives

Through this project, you can practice:

- Creating and manipulating multidimensional NumPy arrays.
- Understanding array dimensions, shapes, and data types.
- Performing mathematical and matrix operations.
- Applying NumPy broadcasting-compatible operations.
- Searching, sorting, and filtering array elements.
- Computing descriptive statistics.
- Implementing OOP principles in a practical application.
- Handling invalid input and common runtime errors.
- Organizing code using reusable methods.

## 🔮 Future Improvements

- Add support for saving and loading arrays from files.
- Implement more advanced statistical operations.
- Add graphical visualization using Matplotlib.
- Support custom array operations and broadcasting.
- Add automated unit tests.
- Improve input validation and error handling.

## 👨‍💻 Author

**Your Name**

GitHub: [Your GitHub Profile](https://github.com/your-username)

## 📄 License

This project is open-source and available for educational and learning purposes. You can modify and improve it as needed.
