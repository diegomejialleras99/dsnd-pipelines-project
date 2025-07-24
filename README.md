# README

# Fashion Trend Prediction

This project contains a Jupyter notebook (`starter.ipynb`) that implements a data science pipeline to predict whether a customer would recommend a product or not. This model will analyze the text of a review, the customer's age, the product category, and other relevant information to predict whether the customer would recommend the product or not. 

### Getting Started

```
git clone https://github.com/diegomejialleras99/dsnd-pipelines-project.git

cd dsnd-pipelines-project

```

### Dependencies

```
pip install -r requirements.txt

```

### Installation

Step-by-step explanation of how to get a development environment running.

1. **Clone the repository**
   
   Download the project files to your local machine using Git:
   
   ```
   git clone https://github.com/diegomejialleras99/dsnd-pipelines-project.git
   
   cd dsnd-pipelines-project
   ```
   
3. **(Optional) Create a virtual environment**
   
   It's recommended to use a virtual environment to avoid conflicts:
   
   ```
   python -m venv venv
   
   source venv/bin/activate      # On macOS/Linux
   
   venv\Scripts\activate         # On Windows
   ```
   
5. **Install dependencies**
   
   Use the requirements.txt file to install all necessary libraries:
   
   ```
   pip install -r requirements.txt
   ```
   
7. **Execute the notebook**

   ```
   jupyter notebook starter.ipynb
   
   ```
   Run each cell sequentially to:

     Load and explore the dataset
  
     Train the model
  
     Evaluate results


### Testing

To evaluate model performance, run all the cells in starter.ipynb. The final section includes:

Accuracy

F1-score

Confusion matrix

ROC-AUC

These help verify that the classifier performs well on the test set.


### Project Instructions

The project is implemented in a single notebook starter.ipynb and includes the following student deliverables:

1. Load and explore the dataset.

2. Perform exploratory data analysis (EDA).

3. Preprocess data (e.g., encode categorical variables, normalize).

4. Train a classifier to predict the event label.

5. Evaluate the model using appropriate metrics.

6. Interpret the model results, including feature importance.

### Built With

Python

Jupyter Notebook

pandas

seaborn

matplotlib

scikit-learn


### License

[License](LICENSE.txt)
