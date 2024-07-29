# Public Funds Tracker

## Overview
The Public Funds repo aims to monitor and track the financial expenditures of various government bodies to ensure transparency and accountability. This repository collects, processes, and displays data related to budget allocations, expenditures, and potential discrepancies.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/public-funds.git
   ```
2. Follow the setup instructions in the [docs/setup](docs/setup) directory.

## Contributing
We welcome contributions from the community. Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute.

## Country-Specific Data Guidelines
This provides guidelines on how to find and add country-specific data to this repository. Follow these steps to ensure consistency and accuracy.

## Finding Country-Specific Information
1. **Official Government Portals**: Check the official government websites for open data portals, ministry reports, budget documents, and financial statements.
2. **International Organizations**: Refer to data from organizations like the World Bank, IMF, UN, and Transparency International.
3. **NGOs and Research Institutes**: Use reports and data from reputable non-governmental organizations and research institutions.

## Adding Country-Specific Data
1. **Create Directories**: Follow the structure `data/country/{country-name}` and create subdirectories as needed (e.g., budgets, expenditures, projects, reports).
```
├── data/
│   ├── country/
│   │   ├── nigeria/
│   │   │   ├── budgets/
│   │   │   ├── expenditures/
│   │   │   ├── projects/
│   │   │   └── reports/
│   │   ├── kenya/
│   │   │   ├── budgets/
│   │   │   ├── expenditures/
│   │   │   ├── projects/
│   │   │   └── reports/
│   │   ├── south-africa/
│   │   │   ├── budgets/
│   │   │   ├── expenditures/
│   │   │   ├── projects/
│   │   │   └── reports/
│   │   └── ...
```
2. **File Naming Convention**: Use clear and descriptive file names. Include the year and type of document (e.g., `2024-budget-summary.pdf`).
3. **Metadata**: Add a metadata file in each directory to describe the contents, source, and date of the data. Example:
   ```json
   {
       "source": "Ministry of Finance, Nigeria",
       "date": "2024-01-01",
       "description": "Budget summary for the fiscal year 2024."
   }

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Code of Conduct
Please note that this project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.
