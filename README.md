# Artificial Neural Network Project

This repository contains an implementation of an Artificial Neural Network (ANN) using sample datasets for supervised learning.

## Repository Structure

- `main.ipynb`: Main notebook containing the neural network implementation.
- `diabetes.csv`: Dataset related to diabetes diagnosis.
- `housing.csv`: Dataset related to housing.
- `iris.csv`: Dataset for flower classification.
- `.gitignore`: File to ignore unnecessary files in version control.
- `requirements.txt`: File containing the necessary libraries for running the project.

## Prerequisites

Before getting started, make sure you have the necessary tools installed:

- Python 3.7 or higher
- Jupyter Notebook
- The libraries listed in `requirements.txt`

Install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## How to Run

Follow the steps below to set up and run the project:

1. **Clone the repository**  
   Download the source code from the repository to your computer:
   
   ```bash
   git clone https://github.com/miguelgrieder/artificial-neural-network.git
   ```

2. **Set up the environment**  
   Make sure you have Python 3.7 or higher installed.

3. **Install dependencies**  
   Install the necessary libraries listed in `requirements.txt`:
   
   ```bash
   pip install -r requirements.txt
   ```

   Or install the required libraries manually:
   
   ```bash
   pip install numpy pandas scikit-learn matplotlib tensorflow
   ```

4. **Prepare the data**  
   Ensure the data files (`diabetes.csv`, `housing.csv`, `iris.csv`) are in the same directory as the notebook, or update the paths in the code as needed.

5. **Run the notebook**  
   Launch Jupyter Notebook and open the `main.ipynb` file:
   
   ```bash
   jupyter notebook main.ipynb
   ```

6. **Execute the cells**  
   In Jupyter Notebook, run each cell in sequence. The code will load the data, train the models, and display the results.