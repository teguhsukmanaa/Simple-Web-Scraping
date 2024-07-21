# Simple Web Scraping on E-commerce Website
Web scraping is the automated process of extracting data from websites. It involves using software to visit web pages, download their contents, and extract specific information. This data can then be saved locally for analysis or used in various applications. Web scraping is widely used for tasks such as market research, competitive analysis, content aggregation, and more. However, it requires careful attention to legal and ethical considerations, as scraping practices can vary in legality depending on how and what data is accessed from websites.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Explanation](#explanation)
- [Installation](#installation)
- [Results](#results)
- [Dashboard](#dashboard)
- [Contributing](#contributing)

## Introduction
This project will demonstrate how to use a simple web scraping method to collect data from an e-commerce website. The data collected will be in the form of product information displayed on the e-commerce webpage when a keyword search is performed for the related product. The main objective of this project is to conduct market research on seblak products by utilizing web scraping to gather data. The results of this market research analysis will serve as a basis for decision-making, strategy formulation, or trend analysis in starting a seblak product dropshipping business. The output of this project will include a compilation of product data obtained through web scraping, data analysis results, and conclusions drawn from the conducted market research.

## Dataset
The retrieved data consists of product information displayed on the e-commerce webpage following a keyword search for related products. This includes details such as product name, store location, product rating, total product sales, and product price. Approximately 380 rows of data were successfully scraped.

## Explanation
The first stage of this project involves web scraping to gather product data from web pages. This begins with selecting the appropriate web driver; for this project, I have opted to use Google Chrome as the driver. Subsequently, the chosen driver plugin can be installed using the Selenium library, as outlined below:
```
from selenium.webdriver.chrome.service import Service as ChromeService
from webdriver_manager.chrome import ChromeDriverManager
driver = webdriver.Chrome(service=ChromeService(ChromeDriverManager().install()))
```
Next, open the e-commerce website and perform a product search by entering the product keyword in the search field. Inspect the page carefully to identify elements that contain product information, such as the following:
![Screenshot 2024-07-21 220156](https://github.com/user-attachments/assets/d333b80e-9ced-4f88-9848-f3f6cae09fdb)

After gathering the required elements, proceed with the scraping as demonstrated in the notebook file in this repository. Once the necessary product information data has been obtained, we can then move on to subsequent stages such as data analysis, product trends, and market research.

## Installation
To run or get this project locally, please follow these steps:
1. Clone this repository: `git clone git@github.com:teguhsukmanaa/Simple-Data-Pipeline-For-App-Trend-Analysis.git`
2. Or download the files manually.

## Results
- Successfully obtained a compilation of data tables containing product information, including product name, store location, product rating, total product sales, and product price.
- In market research conclusion, there is a great public interest in seblak products based on sales data on the e-commerce website. This can be seen from the large number of existing sales, both within the scope of Jabodetabek and outside Jabodetabek. From a business perspective, seblak products appear suitable as a trade commodity for the dropshipping business that being considered. There is a promising potential income margin, and the selling prices do not vary significantly between Jabodetabek and other regions, thus minimizing the risk of disrupting public interest in affordable products.

## Dashboard
I have created a dashboard to summarize the analysis and insights from this project. You can check it out at the following link:
https://public.tableau.com/app/profile/teguh.sukmanaputra/viz/Hacktiv8WebScrapingProject-Teguh/Dashboard1?publish=yes 

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Let's collaborate and make this project even better!.

Thank you for visiting this repository! If you have any questions or feedback, please don't hesitate to reach me out.


[teguhsukmanaa](https://github.com/teguhsukmanaa)
