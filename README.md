# WebDataScrape

![web-scraping-diagram](https://github.com/ANSHPG/WebDataScrape/assets/132222062/4f4d8751-738a-41d4-a6b8-ba66db144ab9)


The web scraping project was conducted using Google Colab, utilizing libraries such as Pandas, Requests, and BeautifulSoup. The objective was to extract data from an internship website for educational purposes.

2. The project began by utilizing the Requests library to simulate a browser's behavior, enabling access to the website's data. This step was crucial for mimicking human interaction and avoiding potential blocks from the website's security measures.

3. After establishing access to the website, a list of required data was identified. This included key information such as job profiles, company names, locations, compensation (CTC), experience requirements, and logos.

4. The BeautifulSoup library was employed to parse the HTML content of the website. Through methods like `find()` and `find_all()`, specific elements containing the desired data were located.

5. The extracted data was then processed using techniques such as `text()` and `strip()` to clean and format it appropriately. This ensured that the data was in a suitable format for storage and analysis.

6. To facilitate data analysis and manipulation, Series objects were created to store each category of information. Efforts were made to ensure that all Series were of the same length, preventing complications during DataFrame creation.

7. The collected data was then organized into a DataFrame, utilizing the Pandas library. This allowed for efficient storage and manipulation of the extracted information.

8. To capture data from multiple pages of the website, a loop was implemented. The URL was dynamically formatted to navigate through each page, and the scraping process was repeated for each page. Challenges were encountered in maintaining consistency, particularly in handling the varying lengths of data on different pages.

9. Despite encountering hurdles, such as adjusting the data length to match the consistent format, the project successfully consolidated all scraped data into a single DataFrame.

10. Finally, the extracted data was exported to a CSV file using the `to_csv()` function. This file served as a tangible output of the web scraping process, allowing for further analysis and exploration.

It's essential to note that this project was conducted solely for educational purposes and adhered to ethical standards. The repository is managed by Anshuman Pattnaik and is publicly available for personal use and research purposes.

In summary, this web scraping project demonstrated the practical application of Python libraries for extracting and organizing data from online sources, contributing to the researcher's understanding of data acquisition and analysis techniques.
