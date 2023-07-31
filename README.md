# Reviews_Data_Scraping
Scraped laptop brand reviews from Amazon with BeautifulSoup Python libraries and stored in MongoDB

The objective of this project was to identify highly rated laptops on Amazon and understand why these laptops were rated highly. To accomplish this, web scraping techniques were used to collect data on product information, ratings, and reviews for five laptops in the highly rated section of Amazon. A Firefox headless browser was used to search for laptops, and the main page URLs of the top five laptops were identified and downloaded locally. The product name, price, overall rating, and product information were then scraped from these pages.

Next, the URLs for the reviews of each laptop were identified, and the review pages were dynamically loaded and downloaded locally. The ratings and reviews were scraped from these pages and saved as review_1, review_2, etc. for each laptop, without capturing any personally identifiable information (PII) such as the actual user name. The primary keys such as laptop_1, laptop_2, etc. were created to join the product information and review information if required. Finally, the product and review information were saved in MongoDB.

MongoDB was chosen for its flexibility in storing varying data structures, scalability in handling large amounts of unstructured data like user reviews, and powerful querying capabilities for efficient data retrieval and analysis, enabling efficient storage and retrieval of data for business decision-making purposes.

This project aimed to support a company's business decisions by providing data on highly rated laptops and understanding why these laptops are rated highly. The web scraping techniques used in this project enabled the collection and preparation of data for use in business decision making.

## Tools & Libraries: Python, Gecko Driver, Selenium, requests, BeautifulSoup, Pandas, glob, and json.
## Database: MongoDB
