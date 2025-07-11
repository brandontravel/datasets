# datasets

A community-driven, public open datasets project supporting solo travelers, digital nomads, and travel advocates. These structured JSON datasets help travelers plan smarter, safer, and more connected journeys.

## About This Project

This repository provides modular, structured data files useful for travel-related apps, websites, and research. Datasets include country information, safety tips, cultural notes, tech connectivity, visa requirements, and more.

## Repository Structure

```
datasets/
├── travel/
│ ├── travel-safety.json
│ ├── travel-healthcare.json
│ ├── travel-insurance.json
│ ├── travel-vaccinations.json
│ ├── emergency-numbers.json
│ ├── country-risk-ratings.json
│ ├── night-safety.json
│ ├── travel-advisories.json
│ └── border-crossing-info.json
│
├── culture/
│ ├── culture.json
│ ├── tipping-culture.json
│ ├── dress-code.json
│ ├── religious-customs.json
│ ├── public-etiquette.json
│ ├── languages.json
│ ├── festivals-and-holidays.json
│ ├── cultural-taboo-list.json
│ ├── gender-norms.json
│ └── lgbtq-travel-tips.json
│
├── connectivity/
│ ├── tech-connectivity.json
│ ├── wifi-hotspots.json
│ ├── sim-card-providers.json
│ ├── coworking-spaces.json
│ ├── transport-apps.json
│ ├── ridesharing-services.json
│ ├── country-specific-apps.json
│ ├── internet-censorship.json
│ ├── vpn-recommendations.json
│ └── power-plug-types.json
│
├── logistics/
│ ├── visa-requirements.json
│ ├── currency-info.json
│ ├── cost-of-living.json
│ ├── public-transport.json
│ ├── metro-maps.json
│ ├── airports.json
│ ├── airlines.json
│ ├── local-transport-options.json
│ ├── driving-regulations.json
│ └── left-right-driving.json
│
├── accommodations/
│ ├── airbnb-safety-tips.json
│ ├── camping-sites.json
│ ├── home-exchange-platforms.json
│ ├── emergency-housing-options.json
│ └── accommodation-scam-warnings.json
│
├── food-water/
│ ├── drinking-water-safety.json
│ ├── local-food-safety.json
│ ├── vegan-vegetarian-options.json
│ ├── local-grocery-options.json
│ ├── popular-dishes.json
│ ├── alcohol-laws.json
│ ├── tipping-restaurants.json
│ ├── street-food-guide.json
│ └── allergies-and-diet-info.json
│
├── finance-legal/
│ ├── currency-exchange.json
│ ├── credit-card-acceptance.json
│ ├── money-transfer-services.json
│ ├── travel-legal-notes.json
│ ├── embassy-contacts.json
│ ├── lost-passport-guidelines.json
│ ├── consular-services.json
│ ├── local-police-info.json
│ └── travel-permit-requirements.json
│
├── combined.json
├── README.md
├── CONTRIBUTING.md
├── LICENSE
```

## How to Use

- Clone or download the repository.
- Use the JSON files in your projects, apps, websites, or for research.
- Example fetch:
  ```bash
  curl https://raw.githubusercontent.com/brandontravel/datasets/main/travel/travel-safety.json
  ```

## Contributing

We welcome community contributions! Please read CONTRIBUTING.md for details on how to submit data improvements or new files.

## Suggestions

Only submit data verifiable through government sources, trusted platforms, or first-hand experience.

Use consistent formatting and keys as shown in existing JSON files.

## License

Creative Commons Zero v1.0 Universal (CC0 1.0) — public domain dedication.
