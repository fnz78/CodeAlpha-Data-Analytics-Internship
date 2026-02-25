# CodeAlpha-Data-Analytics-Internship
This repository contains all tasks completed during the CodeAlpha Data Analytics Internship.  
The project demonstrates the complete data workflow:

Web Scraping

Data Cleaning

Data Visualization

Data Storytelling

Insight Extraction

Each task builds on the previous one to create a structured and professional data analysis pipeline.


🧩 Task 1 – Web Scraping
🎯 Objective

Extract book data from an online bookstore website using Python.

🛠 Tools Used

Python

requests

BeautifulSoup

Pandas

📥 Data Collected

Book Title

Price

Rating

Availability

📌 Process

Sent HTTP request to the website.

Parsed HTML using BeautifulSoup.

Extracted required elements.

Structured the data into a Pandas DataFrame.

Saved the dataset as:

books_data.csv
✅ Outcome

Successfully scraped structured book data ready for preprocessing and analysis.

🧹 Task 2 – Data Cleaning & Preprocessing
🎯 Objective

Transform raw scraped data into clean, analysis-ready format.

🛠 Tools Used

Python

Pandas

🔄 Cleaning Steps
1️⃣ Price Cleaning

Removed currency symbols (£)

Converted values to float

2️⃣ Rating Conversion

Converted text ratings:

One → 1
Two → 2
Three → 3
Four → 4
Five → 5
3️⃣ Data Type Verification

Ensured:

Price → float

Rating → integer

4️⃣ Missing Values Check

Verified dataset completeness.

📁 Output

Saved cleaned dataset as:

cleaned_books_data.csv
✅ Outcome

Dataset prepared for visualization and analysis.

📊 Task 3 – Data Visualization & Storytelling
🎯 Objective

Transform cleaned data into meaningful visual insights.

🛠 Tools Used

Python

Pandas

Matplotlib

Seaborn

📈 Visualizations Created
1️⃣ Price Distribution (Histogram)

Shows clustering of book prices.

Insight:
Most books are priced between £40–£60.
Very few extreme price values observed.

2️⃣ Rating Distribution (Count Plot)

Displays frequency of each rating level.

Insight:
Rating 3 appears most frequently.
Very few 1-star books present.

3️⃣ Price vs Rating (Boxplot)

Shows price spread across rating categories.

Insight:
Prices overlap significantly across ratings.
Higher rating does not necessarily mean higher price.

4️⃣ Average Price by Rating (Bar Chart)

Clear comparison of mean price per rating.

Insight:
No strong upward price trend as rating increases.

5️⃣ Top 5 Most Expensive Books

Highlights highest-priced books.

Insight:
A small subset of books dominate the higher price range.

6️⃣ Correlation Heatmap

Analyzes numerical relationships.

Insight:
Weak correlation between price and rating.

📖 Final Data Story

From the visual exploration:

Book prices are concentrated in a mid-range cluster.

Rating 3 is the most common rating category.

There is no strong correlation between rating and price.

Higher-rated books are not significantly more expensive.

The dataset shows stable and moderate price variation.

Overall, pricing appears independent of rating quality in this dataset.

🚀 Skills Demonstrated

Web Scraping

HTML Parsing

Data Cleaning

Data Transformation

Data Visualization

Exploratory Data Analysis

Insight Communication

Project Structuring

🏁 Conclusion

This internship project provided hands-on experience across the full data analytics pipeline — from raw data extraction to structured storytelling through visualization.

Through this project, I strengthened my skills in Python-based data analysis, improved my understanding of data preprocessing, and developed the ability to communicate insights clearly through visual storytelling.

The project reflects practical application of data analytics concepts in a structured and professional workflow.

👨‍💻 Author

Kn Farhan nazim
Data Analytics Student
CodeAlpha Internship Participant
