# UK Mounjaro Price Dataset

A comprehensive, regularly-updated dataset of Mounjaro (Tirzepatide) prices from GPhC-regulated UK pharmacies.

## About This Dataset

This dataset provides transparent pricing information for Mounjaro weight loss medication across licensed UK online pharmacies. All data is collected from registered, regulated providers and includes:

- Individual dose prices (2.5mg through 15mg)
- Average pricing across all doses
- Trustpilot review scores and review counts
- Delivery costs
- Last updated timestamp

## Data Source

Data is collected and verified by [Click Compare](https://click.compare/mounjaro/), a UK pharmacy comparison platform focused on transparency and helping consumers make informed healthcare decisions.

**Interactive version**: For the most up-to-date prices and a sortable comparison table, visit [click.compare/mounjaro](https://click.compare/mounjaro/)

## File Format

The dataset is provided in JSON format (`mounjaro-prices-uk.json`) with the following structure:

```json
{
  "metadata": {
    "last_updated": "YYYY-MM-DD",
    "source": "https://click.compare/mounjaro/",
    ...
  },
  "pharmacies": [
    {
      "name": "Pharmacy Name",
      "trustpilot_rating": 4.9,
      "trustpilot_reviews": 1234,
      "delivery_cost": "Free",
      "prices": {
        "2.5mg": 169.99,
        ...
      },
      "average_price": 179.99
    }
  ]
}
```

## Update Frequency

This dataset is updated monthly to reflect current market pricing. Check the `last_updated` field in the metadata for the date of the most recent update.

## Data Verification

- All pharmacies are verified as registered with the General Pharmaceutical Council (GPhC)
- Review scores are sourced directly from Trustpilot
- Prices are collected from pharmacy websites and verified regularly
- **All prices include delivery costs** - the medication prices listed already include any delivery charges where applicable

## Important Notes

- **Prices fluctuate**: Always verify current pricing directly with pharmacies before ordering
- **Prescription required**: Mounjaro is prescription-only medication requiring consultation with a UK healthcare professional
- **Regulated providers only**: All listed pharmacies are fully licensed and regulated

## Usage

This dataset is provided for:
- Consumer research and price comparison
- Market analysis and healthcare pricing research
- Transparency in pharmaceutical pricing
- Academic and journalistic purposes

## Regulatory Information

All listed pharmacies are regulated by the General Pharmaceutical Council (GPhC). You can verify pharmacy registration at: https://www.pharmacyregulation.org/

## Access the Data

**Interactive Dataset on Kaggle**: [View on Kaggle](https://www.kaggle.com/datasets/abbieclayton/uk-mounjaro-prices-pharmacy-comparison-dataset)

For data analysis, research, or to download the complete dataset with version history, visit our Kaggle page.

## License

This dataset is provided under Creative Commons Attribution 4.0 International (CC BY 4.0).

You are free to use, share, and adapt this data provided you give appropriate credit to [Click Compare](https://click.compare) as the source.

## Contact

For questions about this dataset or to report inaccuracies, please visit [Click Compare](https://click.compare) or use the contact information provided on the website.

---

**Live Comparison Tool**: Visit [click.compare/mounjaro](https://click.compare/mounjaro/) for an interactive, always-current price comparison with additional features including filtering, sorting, and direct links to pharmacy consultations.
