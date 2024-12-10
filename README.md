Sales Data Analysis
This project analyzes sales data from multiple months to uncover insights about sales performance, customer behavior, and product popularity. The dataset contains information such as order date, product details, purchase address, and more. The analysis aims to answer key business questions and visualize trends for better decision-making.

Project Features
Data Cleaning:

Combined multiple monthly sales files into a single dataset.
Removed missing values and invalid entries.
Extracted and transformed necessary columns (e.g., month, city, time).
Data Analysis & Insights:

Identified the best month for sales and quantified earnings during that period.
Determined which cities generated the highest sales revenue.
Analyzed sales trends by time to suggest optimal advertising schedules.
Discovered products frequently sold together.
Evaluated the most sold products and their relation to price.
Visualizations:

Sales trends over months and cities using bar charts.
Hourly sales trends using line plots.
Correlation between product quantity sold and price with dual-axis plots.
Key Insights
Best Month for Sales:

Found the highest-grossing month and calculated total sales for that month.
Top Cities for Sales:

Cities were ranked by total sales, and the top 10 cities were highlighted.
Optimal Advertising Hours:

Identified peak hours for sales to maximize advertisement impact.
Products Sold Together:

Highlighted combinations of products often purchased together.
Most Sold Product:

Analyzed which products sold the most and explored factors driving sales.
Technologies Used
Python: Data manipulation and analysis.
Pandas: Data cleaning, transformation, and aggregation.
Matplotlib & Seaborn: Data visualization.
OS Module: Directory and file handling.
Project Setup

Install the required libraries:


Copy code
pip install pandas matplotlib seaborn
Run the analysis script:

Copy code
python analysis_script.py
Ensure the sales data files are located in the Sales_Data folder.

File Structure

Copy code
├── Sales_Data/             # Folder containing monthly sales data
├── all_copy.csv            # Combined dataset
├── analysis_script.py      # Main analysis script
├── README.md               # Project documentation
Visualization Highlights
Monthly Sales Trends:

Top Cities by Sales:

Hourly Sales Trends:

References
Inspiration: Online tutorials and sales analysis examples.
Referenced code snippets: StackOverflow and ChatGPT.
License
This project is for educational purposes. You are welcome to use and modify the code for non-commercial purposes.
