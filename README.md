# Hamoye-Internship-
Class codes and Project codes of Hamoye AI Lab internship programme 

# Description
Explore Electric Utility Data and Learn data science / Machine Learning technniques. The challenge is to make this data useful and derive/generate  actionable insights from it.

## Install
This project requires Python 3.7 and the following Python libraries installed:

* Numpy
* Pandas
* matplotlib
* scikit-learn

You will also need to have the software installed to run and execute a Jupyter Notebook

If you do not have Python installed yet, it is highly recommended that you install the `Anaconda distribution` of Python, which already has the above packages and more included. Make sure that you select the Python 3.7 installer and not the Python 2.x installer.


## Data Description

* **'Record_id'**: record id

* **'Utility_id_ferc1'**: Utility id assigned by the `FERC` (`FEDERAL ENERGY REGULATORY COMMISSION`)

* **'Report_year'**: year of report

* **'Plant_name_ferc1'**: the name of the plant

* **'Fuel_type_code_pudl'**: the type of fuel

* **'Fuel_unit'**: the unit of fuel

* **'Fuel_qty_burned'**: the quantity of fuel burned

* **'Fuel_mmbtu_per_unit'**: the measure of energy per unit

* **'fuel_cost_per_unit_burned'**: the fuel cost per unit burned

* **'Fuel_cost_per_unit_delivered'**: the cost of fuel delivered per unit

* **'fuel_cost_per_mmbtu'**: the cost of fuel per mmbtu

### DataFrame 

![dataset preview 1](https://user-images.githubusercontent.com/25388109/87964706-82764580-cab2-11ea-8e38-18c9bbf22736.png)

![dataset preview 1_1](https://user-images.githubusercontent.com/25388109/87964824-adf93000-cab2-11ea-87d7-d52bd4e165d9.png)


### Data types of the dataset


![dataframe data types](https://user-images.githubusercontent.com/25388109/87965483-bb62ea00-cab3-11ea-963a-f8ba37548530.png)


## Code

Template codde is provided in the `Hamoye_internship_stage_A_.ipynb` notebook file. You will also be required to use the `url=()` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. 

## Run

In a terminal or command window, navigate to the top-level project directory `Hamoye_internship_stage_A_.ipynb`/ (that contains this README) and run one of the following commands:

When you're ready, fire up the notebook.

```ipython notebook Hamoye_internship_stage_A_.ipynb```

or

```jupyter notebook Hamoye_internship_stage_A_.ipynb```

This will open the Jupyter Notebook software and project file in your browser.


### Visualize to check for features having missing values


![missing value graph ](https://user-images.githubusercontent.com/25388109/87965588-e9e0c500-cab3-11ea-84b5-3744a28c8fff.png)


### After filling missing values using mode imputation strategy


![missing value graph after filled](https://user-images.githubusercontent.com/25388109/87965684-0da40b00-cab4-11ea-9c9f-33333eeac48b.png)


### Pearson Correlation Graph

![Pearson correlation graph](https://user-images.githubusercontent.com/25388109/87965826-4a700200-cab4-11ea-9c22-0dbdc2ead895.png)


### Numerical data distribution

![data distribution](https://user-images.githubusercontent.com/25388109/87965939-6ffd0b80-cab4-11ea-86d3-07ea7833c437.png)


### Exploratory data Analysis

![fuel type code vs no of fuel type code](https://user-images.githubusercontent.com/25388109/87966026-958a1500-cab4-11ea-999e-05ffa5e67623.png)
![report year vs fuel mmbtu per unit](https://user-images.githubusercontent.com/25388109/87966041-98850580-cab4-11ea-99b2-626b513eff33.png)
![report year vs fuel type code vs fuel mmbtu per unit](https://user-images.githubusercontent.com/25388109/87966055-9b7ff600-cab4-11ea-9eff-e9ce0d3d4779.png)
