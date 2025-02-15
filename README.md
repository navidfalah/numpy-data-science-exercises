# 🐍 NumPy Data Science Handbook

## 📝 Description
This Python script demonstrates **numerical computing** and **data manipulation** using **NumPy**. It covers key concepts such as array creation, indexing, slicing, vectorized operations, and handling structured arrays. The script also includes examples of data aggregation, masking, and visualization.

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/navidfalah/numpy-data-science.git
   cd numpy-data-science
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Install additional libraries:
   ```bash
   pip install numpy matplotlib vega_datasets
   ```

## 🚀 Usage
1. Run the script:
   ```bash
   python numpy_data_science.py
   ```
2. The script will:
   - Create and manipulate NumPy arrays.
   - Perform indexing, slicing, and vectorized operations.
   - Handle structured arrays and perform data aggregation.
   - Visualize data using Matplotlib.

## 📂 File Structure
```
numpy-data-science/
├── numpy_data_science.py  # Main script
├── README.md              # This file
├── requirements.txt       # Dependencies
└── data/                  # (Optional) Data folder for local inputs
```

## 🧩 Key Features
- **Array Creation**:
  - Create arrays using `np.array`, `np.linspace`, `np.arange`, and `np.random`.
- **Indexing and Slicing**:
  - Access and modify array elements using indexing and slicing.
- **Vectorized Operations**:
  - Perform element-wise operations on arrays.
- **Structured Arrays**:
  - Create and manipulate structured arrays with named fields.
- **Data Aggregation**:
  - Aggregate data using masks and boolean operations.
- **Visualization**:
  - Plot data using Matplotlib.

## 📊 Example Outputs
1. **Array Creation**:
   - `x1 = rng.integers(10, size=6)`.
2. **Indexing and Slicing**:
   - `x1[0]`, `x1[:3]`, `x1[::-1]`.
3. **Vectorized Operations**:
   - `1.0 / values` for element-wise division.
4. **Structured Arrays**:
   - `x = np.zeros(4, dtype={'names':('name','age', 'weight'),'formats':('U10', 'i4', 'f8')})`.
5. **Data Aggregation**:
   - `np.sum(rainfall_mm == 0)` to count days without rain.
6. **Visualization**:
   - Plot rainfall data using Matplotlib.

## 🤖 Libraries Used
- **NumPy**: For numerical computing and array manipulation.
- **Matplotlib**: For data visualization.
- **vega_datasets**: For loading example datasets.

## 📈 Performance Metrics
- **Efficiency**: Optimized for numerical computations.
- **Flexibility**: Supports a wide range of array operations.

## 🛠️ Dependencies
- Python 3.x
- Libraries:
  - `numpy`, `matplotlib`
  - `vega_datasets`

## 🤝 Contributing
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Open a pull request.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 👤 Author
- **Name**: Navid Falah
- **GitHub**: [navidfalah](https://github.com/navidfalah)
- **Email**: navid.falah7@gmail.com
