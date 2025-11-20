Data Science Job Market Overview

📌 Project Overview

The Data Science Job Market Overview project is a comprehensive analytical repository designed to explore, track, and visualize the current landscape of Data Science employment.

Navigating the job market requires concrete data on compensation, required skills, and geographic hotspots. This project serves as a centralized hub for this data, offering a foundation for understanding market trends, differentiating between roles (e.g., Data Scientist vs. Data Analyst vs. Machine Learning Engineer), and identifying salary benchmarks across different regions and seniority levels.
[Download Excel Dataset](https://1drv.ms/x/c/0D7791385F2F33D6/IQCamcdUcy8iQLdRMDM1W1JPASadx_btuBbmCxUB8BUBvGs?e=5IZkBq)



📊 Key Features & Insights

This dataset and analysis framework aims to provide answers to critical career questions through the following metrics:

Salary Benchmarking: Analysis of average, median, and range of salaries broken down by job title and experience level.

Geographic Analysis: Identification of top hiring hubs and "remote-friendly" opportunities.

Skill Demand: (Proposed) Frequency analysis of required technical skills (Python, SQL, AWS, etc.) appearing in job descriptions.

Role Segmentation: Comparative analysis between various data-centric roles to understand market saturation and demand.

🛠 Tech Stack

The project currently utilizes the following tools for data management and analysis:

Microsoft Excel: Primary tool for data storage, preliminary cleaning, and quick-view visualizations (Pivot Tables/Charts).

Python (Proposed/Compatible): The dataset is structured for seamless integration with Python's data science stack:

pandas for data manipulation.

matplotlib / seaborn for advanced visualization.

scikit-learn for potential predictive modeling (e.g., salary prediction).

📂 Project Structure

The repository is organized as follows:

Data-Science-Job-Market-Overview/
├── README.md                               # Project documentation
└── Data Science Job Market Overview.xlsx   # Primary Dataset (Excel format)


🚀 Setup & Usage

1. Clone the Repository

To access the local data file, clone this repository to your local machine:

git clone [https://github.com/KiruruKamau/Data-Science-Job-Market-Overview.git](https://github.com/KiruruKamau/Data-Science-Job-Market-Overview.git)
cd Data-Science-Job-Market-Overview


2. Accessing the Data (Excel)

Simply open Data Science Job Market Overview.xlsx in Microsoft Excel, Google Sheets, or LibreOffice Calc to view the raw data and any embedded dashboard sheets.

3. Loading Data with Python (Quick Start)

For data scientists wishing to perform advanced analysis, the dataset can be easily loaded into a pandas DataFrame. Ensure you have pandas and openpyxl installed (pip install pandas openpyxl).

import pandas as pd

# Load the dataset
file_path = 'Data Science Job Market Overview.xlsx'
try:
    df = pd.read_excel(file_path)
    
    # Display the first 5 rows
    print("Dataset Head:")
    print(df.head())
    
    # Display basic info
    print("\nDataset Info:")
    print(df.info())
    
except FileNotFoundError:
    print("Error: File not found. Please ensure you are in the correct directory.")


🤝 Contributing

Contributions to the analysis or data updates are welcome!

Fork the repository.

Create a feature branch (git checkout -b feature/NewAnalysis).

Commit your changes (git commit -m 'Add new visualization script').

Push to the branch (git push origin feature/NewAnalysis).

Open a Pull Request.

📜 License

This project is available for open use. Please credit the original data source when sharing insights.
