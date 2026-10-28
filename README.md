# Sanca Crimes Data Warehouse

A study project that builds a data warehouse of street crime in
São Carlos, SP, Brazil, from public data.

**Status:** work in progress

## Questions

- Does street crime in São Carlos follow the
  [law of crime concentration](https://en.wikipedia.org/wiki/Law_of_Crime_Concentration)?
- Does the concentration change across spatial scales
  (street segment, street, neighborhood, census tract)?
- Do hotspots of vehicle and cell phone theft and robbery persist over the years?
- What sets hotspots apart: crime generators such as bars, shops and squares?

## Data sources

| Source | Content | Years |
|---|---|---|
| [SSP-SP](https://www.ssp.sp.gov.br/estatistica/consultas) | Police reports (all crime types) | 2022– |
| [SPSafe](https://zenodo.org/records/16739645) | Police reports (vehicles, cell phones, lethal crimes) | 2003–2022 |
| [Receita Federal – CNPJ](https://www.gov.br/receitafederal/dados/cnpj-metadados.pdf) | Business establishments | current |
| [IBGE – CNEFE 2022 and Census 2022](https://www.ibge.gov.br/) | Geocoded addresses, census tracts | 2022 |
| OpenStreetMap | Street network, squares, bus stops | snapshot |
