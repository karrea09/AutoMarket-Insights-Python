##### About the Project

This project digs into the Indian automotive market to answer questions like: Which brands dominate the mid-range segment? What cars offer the best value? Are high-performance models always expensive? I used Python to scrape data, clean it up, and create visualizations that reveal market patterns.

##### What’s Inside





Web Scraping: Collected car details (brand, model, price, mileage, BHP, etc.) from CarWale using Requests and BeautifulSoup.



Data Cleaning: Fixed missing values and standardized messy strings like "1997 cc, 22kmpl, 22bhp" with regex.



Analysis: Calculated metrics like a Value Score (Mileage × BHP / Price) and explored trends across brands and fuel types.



Visualizations: Created charts with Seaborn and Matplotlib to show fuel type distribution, price vs. mileage, and more.

The Jupyter notebook in the notebooks folder walks you through the code, and the presentation in the presentation folder summarizes the findings.

##### Key Insights





TATA leads the 8–12 lakh segment with a 31.2% share, followed by Hyundai at 25%.



Maruti Suzuki excels in petrol and CNG variants, ideal for fuel-conscious buyers.



MG and TATA are pushing electric vehicles, showing market adaptability.



Mahindra, TATA, and MG offer high-performance cars at competitive prices per BHP.



Maruti Suzuki, Toyota, and Skoda average over 20 kmpl, leading in efficiency.

##### Tools Used





Python: Core programming language.



Requests, BeautifulSoup: For web scraping.



Pandas, NumPy: For data manipulation.



Seaborn, Matplotlib: For visualizations.



Regex: For cleaning text data.

##### Challenges and Learnings

Working with real-world data was tricky. Some variants had missing mileage or BHP, and CarWale’s layout varied, requiring flexible scraping logic. Regex helped me clean up messy strings, and I learned to be patient while filling in missing data manually. This project sharpened my skills in data wrangling, EDA, and storytelling with data.

