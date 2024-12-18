# Ferroalloy Optimization Model

## Introduction

The ferroalloy optimization model is designed to enhance the efficiency of alloy additions in the metallurgical process. This model leverages data on alloy compositions, costs, and desired properties of the final product to determine the most cost-effective and efficient alloying strategy. It analyzes the current composition of the molten metal and predicts the optimal amounts and types of ferroalloys to be added to achieve the desired chemical and physical properties.

By incorporating real-time data and predictive algorithms, the model can adjust to variations in raw material quality and operational conditions, ensuring consistent product quality. It minimizes waste and reduces costs by accurately calculating the necessary additions, avoiding excess use of expensive alloys. Additionally, the model can simulate different scenarios, helping metallurgists make informed decisions and adapt quickly to changing requirements.

Overall, this ferroalloy optimization model enhances the control and precision of the alloying process, leading to improved product quality, reduced costs, and increased operational efficiency.The Ferroalloy Optimization Model is designed to enhance the efficiency of alloy additions in the metallurgical process. This model leverages data on alloy compositions, costs, and desired properties of the final product to determine the most cost-effective and efficient alloying strategy. It analyzes the current composition of the molten metal and predicts the optimal amounts and types of ferroalloys to be added to achieve the desired chemical and physical properties.

- **Cost and Efficiency Optimization**: Analyzes the current composition of the molten metal and predicts the optimal amounts and types of ferroalloys to be added to achieve the desired chemical and physical properties.
- **Real-Time Data Integration**: Incorporates real-time data and predictive algorithms to adjust for variations in raw material quality and operational conditions, ensuring consistent product quality.
- **Waste Reduction**: Minimizes waste and reduces costs by accurately calculating necessary additions, avoiding excess use of expensive alloys.
- **Scenario Simulation**: Simulates different scenarios to help metallurgists make informed decisions and adapt quickly to changing requirements.

## Website and Lime Calculation

This project also includes a website that features a lime calculation tool, using machine learning models to enhance prediction accuracy. The website was developed with HTML, CSS, and JavaScript, and deployed using Vercel. The project utilizes Git and GitHub for version control and collaboration, along with Excel and Power BI for data analysis and visualization.

## Requirements

- **Python 3.x**
- **Required Python Libraries**:
  - `pandas`
  - `scipy`
  - `openpyxl`


## Usage

### 1. Prepare Input Files

Ensure the following Excel files are prepared and structured correctly:

- **`efficiency_cost.xlsx`**: Contains the efficiencies and costs of each alloy.
  - **Columns**: `Alloy`, `Cost`, `C Efficiency`, `Mn Efficiency`, `S Efficiency`, `P Efficiency`, `Si Efficiency`, `Al Efficiency`, `Nb Efficiency`.
  
- **`grade_chemistry.xlsx`**: Contains the target chemistry for elements (C, Mn, S, P, Si, Al, Nb) in terms of minimum and maximum allowable values.
  - **Columns**: `Element`, `Min Value`, `Max Value`.
  

- **`initial_weights.xlsx`**: Contains the initial weights of the alloys available for addition.
  - **Columns**: `Alloy`, `Weight (kg)`.
  

### 2. Run the Script

Execute the Python script `lrf_optimization.py`:


# Project: Linear Regression for Resource Optimization in Steel Production

This project implements a linear regression model to optimize the quantity of specific ores needed to achieve desired element compositions (grades) in steel production. The goal is to predict the amount of each ore to be added, based on the initial composition of raw steel, using historical data of past efficient calculations.

## Key Features:
- **Independent Models**: Each ore is modeled independently with its own linear regression, assuming no dependency between different ores.
- **Linear Relationship**: The model assumes a direct linear relationship between the ore amount and the target element's final composition.
- **Cost-Efficiency**: The model is trained on historical data that represents the most cost-efficient practices used by industry professionals.
- **Grade Flexibility**: The application can predict the necessary ore quantities for any steel grade.

## Usage:
- Input the initial composition and the target grade.
- The model will output the required quantities of each ore to achieve the desired composition.

This tool simplifies the optimization process, providing accurate, cost-effective solutions for real-world steel production.


## Requirements

To run this project, you need to have the following dependencies installed:

- `scikit-learn==1.3`
- `numpy==1.23`
- `pandas==1.4`

## Instructions:
1. Clone the repository using:
```
git clone https://github.com/prachi-pranesh/JSP-Optomisation-of-ferro-alloys.git
cd JSP-Optomisation-of-ferro-alloys/JSPL Internship project_model ml
```

2. Train the model using:
```
python main.py
```


### 3. Output

The script will output the optimal amounts of each alloy to be added to achieve the desired chemical composition at the lowest cost, along with the total cost.


## Project Deployment

The website is deployed using Vercel, and version control is managed via Git and GitHub. The project also includes analysis tools built with Excel and Power BI to further enhance decision-making processes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was developed to assist in the optimization of alloy additions in the metallurgical process, with a focus on cost-effectiveness, precision, and improving overall operational efficiency.


