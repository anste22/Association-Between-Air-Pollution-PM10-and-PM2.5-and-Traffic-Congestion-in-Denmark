# Air Quality and Traffic Congestion Analysis in Denmark

This project focuses on analyzing air quality and traffic congestion data in Denmark between 2020 and 2022. The analysis includes the comparison of PM 10, PM 2.5, and traffic congestion values over specific time periods, as well as a spatial analysis using a shapefile of Denmark.

## Data Files

The following data files are used for the analysis:

- `1. Bøgehegnet, Greve Strand, Denmark PM2.5.txt`: Contains PM 2.5 data for Bøgehegnet, Greve Strand, Denmark.
- `1. Bøgehegnet, Greve Strand, Denmark PM10.txt`: Contains PM 10 data for Bøgehegnet, Greve Strand, Denmark.
- `3. Egelundsvej10, Aarhus, Denmark PM2.5.txt`: Contains PM 2.5 data for Egelundsvej10, Aarhus, Denmark.
- `4. Hillerød ab38, Denmark PM2.5.txt`: Contains PM 2.5 data for Hillerød ab38, Denmark.
- `5. Copenhagen, Denmark (PM2.5 + PM10).csv`: Contains PM 2.5 and PM 10 data for Copenhagen, Denmark.
- `6. Risø, Denmark (PM10).csv`: Contains PM 10 data for Risø, Denmark.
- `7. Traffic Congestion - 2020.xlsx`: Contains traffic congestion data for the year 2020.
- `8. Traffic Congestion - 2022.xlsx`: Contains traffic congestion data for the year 2022.

## Shapefile

The shapefile used for the spatial analysis is the following:

- `DNK_adm0.shp`: Shapefile of Denmark representing the administrative boundaries.

## Code Files

The code for analyzing and visualizing the data, including the spatial analysis, is provided in the following files:

- `FINAL PROJECT.ipynb`: A Jupyter Notebook file that performs data analysis, generates plots, and conducts spatial analysis using the shapefile.

The spatial analysis utilizes libraries such as GeoPandas and performs spatial operations to analyze the data within the context of the administrative boundaries of Denmark.

## Instructions

To run the code and generate the comparison plots and spatial analysis:

1. Ensure that Python 3 and the necessary libraries (e.g., pandas, matplotlib, GeoPandas) are installed.
2. Download the data files and the shapefile and place them in the appropriate directory.
3. Open the `FINAL PROJECT.ipynb` Jupyter Notebook.
4. Run the code cells in the notebook sequentially.
5. The comparison plots and spatial analysis results will be displayed in the notebook.

Note: The code assumes that the data files and shapefile are in the specified file paths. If you have placed them in different locations, update the file paths in the code accordingly.

## Results

The analysis produces comparison plots for the following scenarios*:

1. Comparison of PM 2.5 values in 2020 and 2022.
2. Comparison of PM 10 values in 2020 and 2022.
3. Comparison of traffic congestion values in 2020 and 2022.
4. Comparison of PM 10, PM 2.5, and traffic congestion values in 2020.
5. Comparison of PM 10, PM 2.5, and traffic congestion values in 2022.
6. Comparison of PM 10, PM 2.5, and traffic congestion values in 2020 (March-June).
7. Comparison of PM 10, PM 2.5, and traffic congestion values

*All the values are related to Denmark (whole country). Air quality values (for Denmark) were calculated as the average of individual stations located in different parts of the country (everyhing is described in the code).
