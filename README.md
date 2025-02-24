# IPL Auction 2025

## Project Overview
The **IPL Auction 2025** project extracts, analyzes, and visualizes IPL player auction data to uncover trends and insights. The project integrates web scraping, data analysis, and dashboard visualization to provide a data-driven perspective on IPL auction strategies.

## Features
- **Web Scraping**: Extracts auction data using `requests` and `BeautifulSoup`.
- **Data Processing**: Structures the data into CSV format using `pandas`.
- **Data Analysis**: Identifies top purchases, spending patterns, and player trends using `pandas`, `numpy`, `matplotlib`, and `plotly`.
- **Interactive Dashboard**: Google Looker Studio visualizes key insights with dynamic charts and filters.
- **User Interactivity**: Provides interactive filtering and visualization options.

## Tools & Technologies
### Web Scraping:
- `requests`
- `BeautifulSoup`

### Data Processing & Analysis:
- `pandas`
- `numpy`
- `matplotlib`
- `plotly`

### Dashboard Visualization:
- **Google Looker Studio** (Interactive and dynamic visualization)

## Project Workflow
1. **Web Scraping**: Extract player names, base prices, sold prices, teams, and categories.
2. **Data Processing**: Convert data into structured CSV format.
3. **Data Analysis**: Explore price trends, team spending, and player demand.
4. **Dashboard Development**: Create interactive visualizations with user-driven filters.
5. **Insights & Conclusion**: Extract findings on IPL auction strategies.

## Future Scope
- **Real-Time Data Updates**: Automate data scraping and dashboard refresh.
- **Advanced Analytics**: Predict player auction prices using ML models.
- **Expanded Visualization**: Use Power BI/Tableau for deeper insights.
- **Comparative Analysis**: Compare IPL 2025 with past auctions.
- **Web Application**: Develop an interactive platform for user exploration.

## Learning Outcomes
- **Web Scraping**: Extracting data from live websites.
- **Data Processing**: Cleaning and structuring datasets.
- **Data Analysis**: Gaining insights from structured data.
- **Dashboard Development**: Creating interactive visual representations with user engagement.

## How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/ipl-auction-2025.git
   cd ipl-auction-2025
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the data extraction script:
   ```sh
   python scrape_ipl_data.py
   ```
4. Perform analysis:
   ```sh
   python analyze_data.py
   ```
5. Visualize data in Google Looker Studio by connecting to the generated CSV file and interacting with dynamic filters.

## Contributors
- **Your Name** – [GitHub Profile](https://github.com/your-profile)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
