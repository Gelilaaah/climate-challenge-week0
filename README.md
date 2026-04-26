African Climate Trend Analysis — Week 0 Challenge



&#x20;📌 Project Overview



This project is part of the 10 Academy Week 0 Challenge, focused on analyzing historical climate data across five African countries:



* Ethiopia 🇪🇹
* Kenya 🇰🇪
* Sudan 🇸🇩
* Tanzania 🇹🇿
* Nigeria 🇳🇬



The objective is to explore climate trends, identify patterns and anomalies, and generate data-driven insights that could support Africa’s position in global climate negotiations (e.g., COP32).



&#x20; Objectives



&#x20;Set up a professional data project using Git and CI/CD

&#x20;Perform data cleaning, profiling, and exploratory data analysis (EDA)

&#x20;Compare climate patterns across countries

&#x20;Generate evidence-backed insights for climate policy



&#x20;🛠️ Tech Stack



* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Git \& GitHub (version control \& collaboration)
* GitHub Actions (CI/CD pipeline)



&#x20;📂 Project Structure



climate-challenge-week0/

│

├── .github/

│   └── workflows/

│       └── ci.yml          # CI/CD pipeline

│

├── notebooks/              # EDA notebooks per country

├── src/                    # Source code

├── scripts/                # Utility scripts

├── tests/                  # Unit tests

│

├── .gitignore

├── requirements.txt

├── README.md



⚙️ Setup Instructions



1️⃣ Clone the Repository



bash

git clone <your-repo-link>

cd climate-challenge-week0



2️⃣ Create Virtual Environment



bash

python -m venv venv

venv\\Scripts\\activate   # Windows



&#x20;3️⃣ Install Dependencies



bash

pip install -r requirements.txt



🔄 CI/CD Pipeline



This project uses GitHub Actions to ensure consistency and reproducibility.



&#x20;Workflow includes:



\* Installing dependencies

\* Verifying Python environment



Runs automatically on push to the `main` branch.



&#x20;📊 Analysis Workflow



1\. Data Cleaning



&#x20;  \* Handle missing values (`-999` → NaN)

&#x20;  \* Remove duplicates

&#x20;  \* Convert date fields



2\. Exploratory Data Analysis



&#x20;  \* Temperature trends

&#x20;  \* Rainfall patterns

&#x20;  \* Seasonal variations

&#x20;  \* Correlation analysis



3\. Cross-Country Comparison



&#x20;  \* Temperature variability

&#x20;  \* Precipitation distribution

&#x20;  \* Extreme weather events



4\. Insights Generation



&#x20;  \* Climate trends

&#x20;  \* Impact implications

&#x20;  \* Policy recommendations





