# Electric load forecasting: Data Sources Overview

This repo provides an overview of the three datasets used for electric load forecasting. Each dataset is briefly described.

---

## 1. Electricity Load Diagrams (2011-2014)

- **Donated On**: 03/12/2015  
- **Number of Clients**: 370  

### Dataset Description
This dataset captures the electricity consumption of 370 clients in Portugal between 2011 and 2014. The data consists of 15-minute interval readings recorded in kilowatts (kW).   The dataset is complete, with no missing values. Some clients joined after 2011, so their earlier consumption values are marked as zero.

### Reference
[source](https://archive.ics.uci.edu/dataset/321/electricityloaddiagrams20112014)

---

## 2. SmartMeter Energy Consumption Data in London Households

- **Source**: UK Power Networks  
- **Created**: 9 years ago, last updated 2 years ago  
- **Number of Households**: 5,567  
- **Time Period**: November 2011 to February 2014  
- **Data Intervals**: Half-hourly readings  


### Dataset Description
This dataset represents the energy consumption of 5,567 households in London, measured at half-hour intervals. It was collected as part of the Low Carbon London project, which tested dynamic Time of Use (dToU) pricing for a subset of 1,100 households. These households received high, low, or normal price signals to encourage energy conservation during peak demand. The remaining 4,500 households were on a flat-rate tariff. The dataset includes unique household identifiers, energy consumption data in kWh, and pricing information.

### Reference
[source](https://data.london.gov.uk/dataset/smartmeter-energy-use-data-in-london-households)

---

## 3. Residential Data from Pecan Street

- **Source**: Pecan Street Dataport  
- **Regions Covered**: New York, California, Austin  
- **Number of Homes**: 25 per region  
- **Time Period**: 6 months for New York, varying for other regions  
- **Data Intervals**: 1-second, 1-minute, and 15-minute intervals  
- **Dataset Type**: Time-series  


### Dataset Description
This dataset provides granular residential energy consumption data from 25 homes in New York, California, and Austin. The New York data covers six months of complete records, while California and Austin have 99% completeness. The data includes 1-second, 1-minute, and 15-minute intervals, offering a detailed view of energy usage in different regions. 

### Reference
[source](https://dataport.pecanstreet.org/academic)

---

