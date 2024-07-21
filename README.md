# Simple Web Scraping on E-commerce Website
Web scraping is the automated process of extracting data from websites. It involves using software to visit web pages, download their contents, and extract specific information. This data can then be saved locally for analysis or used in various applications. Web scraping is widely used for tasks such as market research, competitive analysis, content aggregation, and more. However, it requires careful attention to legal and ethical considerations, as scraping practices can vary in legality depending on how and what data is accessed from websites.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Explanation](#explanation)
- [Installation](#installation)
- [Results](#results)
- [Contributing](#contributing)

## Introduction
This project will demonstrate how to use a simple web scraping method to collect data from an e-commerce website. The data collected will be in the form of product information displayed on the e-commerce webpage when a keyword search is performed for the related product. The main objective of this project is to conduct market research on seblak products by utilizing web scraping to gather data. The results of this market research analysis will serve as a basis for decision-making, strategy formulation, or trend analysis in starting a seblak product dropshipping business. The output of this project will include a compilation of product data obtained through web scraping, data analysis results, and conclusions drawn from the conducted market research.

## Dataset
The retrieved data consists of product information displayed on the e-commerce webpage following a keyword search for related products. This includes details such as product name, store location, product rating, total product sales, and product price. Approximately 380 rows of data were successfully scraped.

## Explanation
- step by step atau langkah-langkah dalam mengerjakan project
- mulai dari scraping hingga dapet output.

Tahap pertama dalam project ini yaitu melakukan web scraping untuk memperoleh data produk dari laman web. Hal ini dapat diawali dengan menentukan jenis web driver yang akan digunakan, yang mana pada project ini saya menggunakan Google Chrome sebagai drivernya. Dengan begitu kita dapat menginstal plugin driver yang kita pilih menggunakan library selenium seperti berikut: 
`from selenium.webdriver.chrome.service import Service as ChromeService
from webdriver_manager.chrome import ChromeDriverManager
driver = webdriver.Chrome(service=ChromeService(ChromeDriverManager().install()))`




## Installation
To run or get this project locally, please follow these steps:
1. Clone this repository: `git clone git@github.com:teguhsukmanaa/Simple-Data-Pipeline-For-App-Trend-Analysis.git`
2. Or download the files manually.

## Results
- berhasil dapet apa dari webscrap dan bentukan data yang didapet apa
- keismpulan hasil analisa untuk menjawab goals atau hasil analisa dari data webscrap.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Let's collaborate and make this project even better!.

Thank you for visiting this repository! If you have any questions or feedback, please don't hesitate to reach me out.


[teguhsukmanaa](https://github.com/teguhsukmanaa)
