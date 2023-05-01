# London Airbnb: data visualization

## Introduction

The project we worked on is based on data relating to the AirBnb service, a portal that connects people looking for accommodation in a specific city for short periods of time, with other people who have accommodation to rent. We will specifically focus on the AirBnb service in the city of London, United Kingdom, a very visited place internationally, for vacation, work commitments and commitments due to study or university.
The following project aims to analyze this service, through visualizations, to identify the best neighborhoods to stay in the city of London taking into account various factors including: the time of year, the price, user ratings, the type of apartment and the number of guests, thus making it possible to understand many of the characteristics that make up the AirBnb service. Furthermore, the consequences of using the service caused by the restrictions given by the Covid-19 pandemic are analysed, highlighting the changes that have taken place.

## Dataset 
The data used concern all the listings on the Airbnb site from September 2021 to December 2021, and come from publicly available information on the site. Specifically, all the ads present, the reviews of these ads and the calendar relating to future availability until December 2022 were scraped.
The dataset can be downloaded from the link (*http://insideairbnb.com/get-the-data.html) via a collection of three Csv files, which respectively include the listings, the reviews and the calendar.
The tool used to produce the visualizations is Tableau.

## Main features selection
Each file in .csv format contained in the collection represents a relational database table, with the related primary keys, foreign keys and association relationships.
There are 74 different attributes in the original dataset, most of which are unnecessary and not significant for the purpose of this case study, and which would make processing the file computationally expensive. A selection process of the significant attributes was therefore carried out, creating three new files in .csv format which contained only the fields strictly necessary for the purpose of the various visualisations.

## Data Understanding
Below are the tables, in Figure 1, deriving from the files after having carried out the selection process, with a detailed description of all the selected fields. Each of these tables represents an entity within the relational type diagram.

![alt text](https://github.com/nicoladisabato/london-airbnb-data-visualization/blob/figures/dataset_scheme.png?raw=true)
