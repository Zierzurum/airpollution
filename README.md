<img width="85" height="16" alt="image" src="https://github.com/user-attachments/assets/f28d602d-0109-4675-b362-7da0a7f4fe86" /># airpollution

This repository provides hourly air pollution datasets collected from five monitoring stations in Eskişehir, Türkiye, between 2024 and 2025.  
The data was obtained from the Turkish Ministry of Environment, Urbanization and Climate Change | National Air Quality Monitoring Network.

## Dateset Information
The features and their descriptions in the dataset are as follows:
Date: The date of observation (YYYY-MM-DD HH:MM:SS). 
PM 2.5 ( µg/m3 ): Particulate Matter 2.5 in µg/m3.  
PM 10 ( µg/m3 ): Particulate Matter 10 in µg/m3. 
The empty observations refer to missing data. 

The characteristics of the datasets are given in Table. 
We also provide modified datasets where 10%, 15%, 20%, and 25% of the values were artificially removed to simulate different missing data scenarios.


| Station            | Pollutant | Missing Rate (%) | Average | Standard Deviation|
|--------------------|-----------|-----------------|---------|-------------------|
| Vişne Park         | PM₁₀      | 6.410           | 38.455  | 30.992            |
| Metin Sönmez       | PM₂.₅     | 4.432           | 7.451   | 8.399             | 
| Cumhuriyet Bulvarı | PM₂.₅     | 0.886           | 22.644  | 17.266            | 
| Tepebaşı           | PM₁₀      | 4.534           | 46.356  | 19.324            | 
| Odunpazarı         | PM₂.₅     | 2.795           | 11.923  | 12.881            |

## License
The dataset is shared for research and educational purposes.

[![DOI](https://zenodo.org/badge/1064656015.svg)](https://doi.org/10.5281/zenodo.17259864)

