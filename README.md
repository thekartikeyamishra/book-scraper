# Web Scraper Project

A Python-based project that scrapes book details from the website [Books to Scrape](http://books.toscrape.com/) using Beautiful Soup and pandas. This project extracts book titles, prices, and availability statuses from the website and exports the data to a CSV file for further analysis or usage.

## Features

- Scrape book titles, prices, and availability status from a webpage.
- Use Beautiful Soup for parsing HTML content.
- Export the scraped data to a CSV file.
- Simple and efficient scraping workflow.

## Requirements

- Python 3.7 or higher
- Libraries:
  - `requests`
  - `beautifulsoup4`
  - `pandas`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/thekartikeyamishra/book-scraper.git
   cd book-scraper
   ```

2. Install the required dependencies:
   ```bash
   pip install beautifulsoup4 pandas
   ```

## Usage

1. Run the script in your Python environment (Google Colab is recommended for easy file downloads).

2. The script will scrape the following details from the [Books to Scrape](http://books.toscrape.com/) website:
   - Book Title
   - Price
   - Availability

3. The scraped data will be displayed as a DataFrame and saved as a CSV file named `books_data.csv`.

4. The CSV file can be downloaded directly to your local machine if using Google Colab.


## Example Output

**DataFrame Output:**

| Title                                      | Price  | Availability   |
|--------------------------------------------|--------|----------------|
| A Light in the Attic                       | £51.77 | In stock       |
| Tipping the Velvet                         | £53.74 | In stock       |
| Soumission                                 | £50.10 | In stock       |

**CSV File:**
The above data will be saved in a CSV file named `books_data.csv`.

## Troubleshooting

- **Requests Error**: Ensure that the website is accessible and that you have an active internet connection.
- **Empty Data**: Check if the website structure has changed, which may require updating the HTML parsing logic.
- **Dependency Issues**: Ensure all required libraries are installed using `pip install`.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request for improvements or new features.


## Contact

For questions or feedback, please contact:

- **Author**: Kartikeya Mishra
- **GitHub**: [thekartikeyamishra](https://github.com/thekartikeyamishra)


