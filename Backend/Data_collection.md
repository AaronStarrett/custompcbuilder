# PC Part Dataset

We obtained our PC parts dataset from an open-source project called PC Part Dataset available on GitHub. The dataset contains various components scraped from PCPartPicker.

## Source Information

- **Repository:** [PC Part Dataset](https://github.com/docyx/pc-part-dataset)
- **Last Updated:** February 20, 2024
- **Part Count:** 59,544

## Data Format

The dataset is available in JSON, JSON Lines, and CSV formats, which can be found in the `./data` directory of the repository.

## Usage Instructions

To run the scraper and obtain the dataset, follow these steps:

1. Ensure you have Node.js installed on your system.
2. Clone the repository to your local machine.
3. Open a terminal and navigate to the cloned directory.
4. Run `npm install` to install dependencies.
5. Run `npm run start` to start the scraper.
6. Wait for 5-10 minutes for the scraper to finish its operation.
7. The scraped data will be available in a directory named `data-staging`.

If you only need specific parts, you can specify them as arguments when running the scraper. Refer to the repository's README for more details.

## Note

Ensure to turn on your VPN before running the scraper to avoid any potential issues.

