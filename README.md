# Analyzing Fan Engagement and Ticket Pricing Trends Across U.S. Concert Venues

# Project Overview
This project explores how fan engagement trends and average ticket pricing vary by region, artist genre, and venue capacity. The goal is to generate actionable insights to inform smarter marketing and pricing strategies for live events companies like Ticketmaster. Using data pipelines, SQL transformations, and dynamic dashboards, this project creates clear and interactive visualizations tailored to client needs.
# Tech Stack
* Python: Data ingestion, API calls, web scraping, and preprocessing
* SQL (AWS RDS MySQL): Data cleaning, transformation, and aggregation
* Amazon QuickSight: Dashboard creation and visualization
* GitHub Actions: Automation of CI/CD processes
* BeautifulSoup: Web scraping of supplemental data
# Project Objective
* Who are you helping? Live event organizers and sales operations teams at Ticketmaster and similar organizations.
* What problem are you solving for them? Helping optimize marketing campaigns and ticket pricing strategies based on regional, genre, and venue-specific fan engagement trends.
* How will you solve their problem? By collecting, cleaning, and analyzing data from multiple sources, creating derived metrics using SQL, and visualizing key insights through intuitive Amazon QuickSight dashboards.
Job Description
The Data Visualization (LiveAnalytics) Intern at Ticketmaster supports the Global Sales Operations team by designing and building dynamic dashboards using Amazon QuickSight. The role focuses on transforming complex datasets into clear and insightful visualizations that support better business decision-making in the live event space. View full Job Description here
Relevance to the Project: This project directly relates to the internship role by emphasizing real-world data collection, cleaning, SQL data modeling, and the creation of user-centric visualizations—skills that are crucial for success in this internship.
Data Sources
* Ticketmaster Discovery API
    * Data Collected: Event listings, ticket pricing, venue details, artist genres
    * Collection Method: Python scripts using the requests library
    * Ticketmaster API Documentation
* Pollstar.com / Setlist.fm
    * Data Collected: Artist tour dates, setlists, venue capacity information
    * Collection Method: Python scripts using BeautifulSoup for web scraping
These datasets provide a comprehensive view of live events necessary to analyze and draw meaningful correlations between fan engagement and ticket pricing.
# Notebooks and Scripts
* Data_Collection_API.ipynb
    * Collects event data from Ticketmaster API.
* Web_Scraping_Venues.ipynb
    * Scrapes venue and setlist data from secondary sources.
* Data_Cleaning_and_Merging.ipynb
    * Cleans, merges, and prepares data for SQL ingestion.
* SQL_Transformations.sql
    * SQL scripts for generating derived tables and analytical views.
* Visualization_Dashboard_QuickSight.md
    * Documentation for dashboard setup and visualization strategy.
All scripts and notebooks are available in the GitHub Repository.
Future Improvements
* Expand Data Sources: Integrate social media engagement metrics (like Twitter sentiment) to enrich fan engagement analysis.
* Advanced Predictive Modeling: Develop a predictive model to forecast future ticket sales based on historical engagement trends.
