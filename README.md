# Veneto IVG Data Collection

Scripts to collect and analyze data about Voluntary Pregnancy Interruptions (IVG - Interruzioni Volontarie di Gravidanza) and conscientious objectors in the Veneto region healthcare system, using the hidden API from https://salute.regione.veneto.it/ivgStatistiche/.

## Data Sources

The scripts collect data from the main endpoint https://salute.regione.veneto.it/ivgStatistiche/api/grafico, and iterate throughs the different charts to retrieve the corresponding data.

Data is available from 2015 to 2022.

## Repository Structure

- `get_data.ipynb`: Notebook to collect data
- `clean_data.ipynb`: Notebook to clean data


## Disclaimer

This project processes and visualizes publicly available healthcare data from the Veneto Region's statistical portal. The data has been reorganized for research and transparency purposes.

Please note:
- All data comes from the official Veneto Region healthcare statistics portal
- Before drawing conclusions, verify against the original source 
- When using this data, please cite both the original source and this project

For questions or inquiries, contact:  
Marco Dalla Stella  
[m.dallastella@proton.me](mailto:m.dallastella@proton.me)
