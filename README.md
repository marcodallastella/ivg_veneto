# Veneto IVG Data Collection

Scripts to collect and analyze data about Voluntary Pregnancy Interruptions (IVG - Interruzioni Volontarie di Gravidanza) and conscientious objectors in the Veneto region healthcare system, using the hidden API from https://salute.regione.veneto.it/ivgStatistiche/.

## Data Sources

The scripts collect data from two main endpoints:
- IVG procedures performed in each hospital (`idTipoGrafico=8`)
- Number of conscientious objectors per facility (`idTipoGrafico=15`)

Data is available from 2015 to 2022.

## Repository Structure

- `ivg.ipynb`: Notebook to collect data about IVG procedures performed in each hospital
- `obiettori.ipynb`: Notebook to collect data about conscientious objectors in each facility
- `output/`: Directory containing the processed CSV files
  - `ivg_effettuate.csv`: Data about performed procedures
  - `obiettori.csv`: Data about conscientious objectors


## Disclaimer
This project is for research and transparency purposes. All data is publicly available through the Veneto Region's healthcare statistics portal. This is a project of Marco Dalla Stella ([email](mailto:m.dallastella@proton.me))