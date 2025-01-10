# Bank Marketing Project

## Overview

The Bank Marketing Project performs an analytical study to understand the factors influencing client subscriptions to term deposits by analyzing a marketing campaign dataset. This project aims to derive actionable insights that can enhance marketing strategies, improve client engagement, and ultimately lead to increased subscription rates for term deposits.

## Dataset

The dataset used in this project consists of **41,175 records** with the following key attributes:

- **Demographic Information:** Age, job type, marital status, education level
- **Financial Indicators:** Default status, housing loan status, personal loan status
- **Campaign Details:** Contact method, month and day of last contact, duration of calls, number of contacts made during the campaign, days since last contact from a previous campaign, previous campaign outcomes, and economic indicators (employment variation rate, consumer confidence index)

## Objectives

The primary objectives of the project are to:

1. Identify target demographics that are more likely to subscribe to term deposits.
2. Assess the effectiveness of various contact methods used during marketing campaigns.
3. Evaluate the performance of previous campaigns to inform future marketing strategies.

## Key Findings

- **Demographic Insights:** Increased subscription rates were found among blue-collar and administrative job roles, with married individuals leading in subscriptions.
- **Education Impact:** Higher education levels are positively correlated with subscription rates.
- **Effective Contact Methods:** Cellular communication is the most effective outreach method for driving subscriptions.
- **Seasonal Trends:** May is identified as the peak period for subscriptions.
- **Campaign Performance:** While subscription rates were consistent throughout the week, past campaigns showed a high number of failures necessitating strategy reassessment.
- **Model Performance:** Predictive models achieved approximately 91% accuracy in identifying potential subscribers, indicating strong predictive capability.

## Installation and Setup

To run the project:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ammaremad/bank-marketing-project.git
   cd bank-marketing-project
   ```

2. **Install the required packages:**  
   Make sure you have Python installed, then install the necessary libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Project Structure

- `data/` - Contains the dataset used for analysis
- `notebooks/` - Jupyter notebooks for exploration and analysis
- `scripts/` - Python scripts for data processing and modeling
- `requirements.txt` - Python dependencies required to run the project
- `results/` - Contains output files, figures, and visualizations

## Usage

To perform data analysis and model training, run the relevant Jupyter notebook files in the `notebooks/` directory or execute the scripts in the `scripts/` directory.

## Future Work

Potential future work could include:

- Refining marketing strategies based on new insights.
- Implementing more advanced machine learning techniques.
- Expanding the dataset to include additional features and analyzing their impact.


## Acknowledgments

Special thanks to the contributors and data scientists who provided valuable feedback and support for this project. 

---

Feel free to explore the code and analyses! If you have any questions or comments, please open an issue or submit a pull request. Happy coding! 
