# README: Task-01 - Data Science Internship at Prodigy InfoTech

## Project Overview

Excited to announce the successful completion of Task-01 during my data science internship at Prodigy InfoTech 🚀. This project involved creating a bar chart or histogram to visualize the distribution of a categorical or continuous variable. Specifically, the project was focused on demonstrating proficiency in data visualization using Python and Jupyter Notebook.

## Table of Contents

1. [Project Description](#project-description)
2. [Technologies Used](#technologies-used)
3. [Setup and Installation](#setup-and-installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [License](#license)
7. [Contributors](#contributors)

## Project Description

Task-01 aimed to create visual representations of data distributions using bar charts or histograms. The focus was on understanding the spread and frequency of a categorical (e.g., gender) or continuous variable (e.g., age) within a given dataset. This project was executed in a Jupyter Notebook environment, utilizing Python libraries for data manipulation and visualization.

### Objectives

- Import and clean data.
- Visualize the distribution of a chosen variable using a bar chart or histogram.
- Interpret the visualized data to derive meaningful insights.

## Technologies Used

- **Python**: Programming language used for data manipulation and visualization.
- **Jupyter Notebook**: Interactive computing environment for writing and running code.
- **Pandas**: Data manipulation library.
- **Matplotlib**: Visualization library for creating static plots.
- **Seaborn**: Statistical data visualization library based on Matplotlib.

## Setup and Installation

### Prerequisites

Ensure you have the following software installed:

- Python (version 3.6 or higher)
- Jupyter Notebook

### Installation Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/username/prodigy-infotech-task-01.git
   cd prodigy-infotech-task-01
   ```

2. **Create a Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Required Packages**

   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebook

1. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open the notebook file `Task-01-Data-Visualization.ipynb` and run the cells sequentially.

## Usage

### Example Usage

The notebook provides a step-by-step guide on how to:

1. Load the dataset.
2. Clean and preprocess the data.
3. Create bar charts or histograms to visualize data distributions.
4. Customize plots with titles, labels, and colors.

### Visualizing a Categorical Variable

To visualize the distribution of genders in a dataset:

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# Load dataset
data = pd.read_csv('data/dataset.csv')

# Plot gender distribution
sns.countplot(x='gender', data=data)
plt.title('Gender Distribution')
plt.xlabel('Gender')
plt.ylabel('Count')
plt.show()
```

### Visualizing a Continuous Variable

To visualize the age distribution in a dataset:

```python
import pandas as pd
import matplotlib.pyplot as plt

# Load dataset
data = pd.read_csv('data/dataset.csv')

# Plot age distribution
plt.hist(data['age'], bins=10, edgecolor='black')
plt.title('Age Distribution')
plt.xlabel('Age')
plt.ylabel('Frequency')
plt.show()
```

## Project Structure

```
prodigy-infotech-task-01/
├── data/
│   └── dataset.csv  # Sample dataset
├── images/
│   └── example_plot.png  # Example of generated plot
├── prodigy_ds_01.ipynb  # Jupyter Notebook file
├── requirements.txt  # Required Python packages
└── README.md  # Project documentation
```

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contributors

- **Saumya Poojari** - [saumya.poojarii7@gmail.com]
- LinkedIn - https://www.linkedin.com/in/ssaumz/

Feel free to reach out with any questions or feedback!

---

Thank you for your interest in this project. Happy coding! 🚀
