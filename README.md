
# Call Center Optimization Analysis for United Airlines

## Project Overview
This project focuses on optimizing call center operations for United Airlines by analyzing key metrics such as Average Handle Time (AHT) and Average Speed to Answer (AST). The goal is to identify inefficiencies, streamline processes, and provide actionable recommendations to improve customer service and operational efficiency.



## Key Features

- **Data Preprocessing:** Cleaning and merging multiple datasets including call records, sentiment data, and primary call reasons.
- **Performance Metrics Analysis:** Detailed analysis of AHT and AST across various call reasons and agents.
- **Customer Sentiment Analysis:** Exploration of how customer and agent sentiment impacts call durations.
- **Agent Performance Evaluation:** Identification of top-performing and underperforming agents based on key metrics.
- **IVR Automation Insights:** Analysis of how self-service and IVR automation can reduce agent workload.
- **Visualizations:** Various charts and visualizations, including bar charts, pie charts, and a word cloud, to highlight key insights.


## Repository Contents
- **Python Scripts**:
  - **Data Cleaning:** `Data_Cleaning.ipynb` Python script to clean all the data sets which includes cleaning of call dataset, customer data, call reasons and sentiment datasets.
  - **Data Processing:** `Data_Processing.ipynb` Python script which include all the process of data analysis to drive insights from cleaned datasets.
  - **Data Prediction:** `Test_Pridiction.ipynb` Python script to generate predictions for the test CSV file based on historical data. 
- **Cleaned CSV folder:** It contains all the cleaned datasets.
- **Presentation:** This repository also contains a PowerPoint presentation that consolidates all the key insights and recommendations derived from the analysis of United Airlines' call center operations.
## Data Sources
The analysis is based on the following datasets:
- **Cleaned Calls Data:** Contains call details such as call start/end times, agent details, and call duration.
- **Cleaned Calls Reasons Data:** The primary reasons for calls and their associated escalation counts.
- **Cleaned Customer Data:** Contains customer details, including customer_id, customer_name, and elite_level_code, used to analyze how customer loyalty status impacts call handling and outcomes.
- **Cleaned Sentiment Data:** Captures agent and customer tones, sentiment scores, and silence percentage.
## Installation
To run this project locally, you'll need the following Python libraries:
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating visualizations. 
- `seaborn`: For advanced statistical plots.
- `numpy`: For numeric computations.
This project utilizes several Python libraries that are typically pre-installed in Jupyter Notebook environments. To get started, ensure the following libraries are available:


```import pandas as pd```

```import matplotlib.pyplot as plt```

```import seaborn as sns```

```import numpy as np```

If you are running this project in an environment where these libraries are not pre-installed, you can install them using:

```bash
pip install pandas numpy matplotlib seaborn 
```




## Running the Scripts 
To run the analysis, follow these steps:

1. **Clone the Repository**: Start by cloning the repository to your local machine.

   ```bash
   git clone https://github.com/yourusername/call-center-optimization.git
2. **Navigate to the Project Directory**: Move into the directory where the repository was cloned.

   ```bash
   cd call-center-optimization
3. **Open Jupyter Notebook**: Launch Jupyter Notebook in your preferred environment. Ensure that Jupyter is installed. If not, you can install it by running the following command:

   ```bash
   pip install notebook
4. **Open the Notebook File**: In the Jupyter interface, navigate to the project directory and open the `Data_Processing.ipynb` notebook file.

5. **Run the Notebook Cells**: Execute the cells in the notebook sequentially by clicking on each cell and pressing `Shift + Enter`. Alternatively, you can select "Run All" from the "Cell" menu to execute the entire notebook at once.
## Results
After running the notebook, the analysis will generate key results, including:
- **Average Handle Time (AHT) and Average Speed to Answer (AST)** for different primary call reasons:
   The notebook calculates the AHT and AST for each call reason to identify which types of calls take the longest to resolve and respond to.

- **Sentiment analysis** showing how customer and agent tones impact call handling:
   The sentiment analysis measures the impact of customer and agent emotions (e.g., frustrated, polite) on the duration of calls, helping to understand how sentiment affects call efficiency.

- **Agent performance analysis** to identify top-performing and underperforming agents:
   The performance analysis evaluates agents based on their AHT and AST metrics to determine which agents handle calls most efficiently and which ones may need further training.

- **Insights on IVR automation** and how self-service options can reduce agent workload:
   The project analyzes common call reasons that can be addressed through automation and IVR systems, potentially reducing agent workload by automating frequent and repetitive inquiries like seating and baggage issues.
## Visualizations
The notebook includes various visualizations such as:

- **Bar charts** for AHT and AST across primary call reasons:
   These charts provide a clear comparison of the average handle time and speed to answer for different call categories.

- **Stacked bar charts** for agent and customer tones:
   Visualizing agent and customer tones helps to understand the emotional dynamics during calls and their impact on call durations.

- **Pie charts** for keyword frequency in call transcripts:
   These charts illustrate the most common keywords used in call transcripts, highlighting the types of inquiries agents receive frequently.

These visualizations provide an easy-to-understand overview of the insights gained from the analysis, helping to identify areas for improvement in call center performance.
## Key Insights
Key findings from the analysis include:

- **Call reasons** such as **Checkout** and **Mileage Plus** have the longest **Average Handle Time (AHT)**, indicating areas where process improvements are needed to reduce resolution times.
  
- **Customer sentiment** (frustration or politeness) has a significant impact on call handling times. Frustrated customers lead to longer calls, while polite tones often result in quicker resolutions.

- **Automation through IVR systems** can significantly reduce agent workload for common queries like **Seating** and **Baggage**. By automating these frequent inquiries, agents can focus on more complex customer needs.
## Recommendations
Based on the analysis, the following recommendations are made to improve call center performance:

- **Reduce AHT** for high-volume call reasons such as **Checkout** and **Mileage Plus** by implementing process improvements and providing targeted agent training.

- **Implement IVR automation** for frequent inquiries like **Seating** and **Baggage** to reduce manual interventions, allowing agents to focus on more complex calls.

- **Provide targeted training** for agents with high **AHT** and **AST** to help improve their efficiency and overall performance in handling calls.

## Contributors
- **Md Rehaan** – Project Lead 
- **Rahul Gupta** – Project Lead
