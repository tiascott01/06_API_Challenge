# 06_API_Challenge
## Overview

This repository contains a two correlating files with exported CSV files for analyzing and summarizing data into the Jupyter Notebook file. All data may not be available as there are specific API keys required for running all the data cells in these notebooks. The directions for the module were to use an API to pull data into a jupyter file, create data and charts against the imported data, and export the findings from the first notebook into the second. The second notebook continued to convert the data and then used another API to cross reference data into another set of dataframes and charts. Other exported items include resource files and supporting images from the data analysis which can be found in the output_data folder.

Additionally, the file also has several factors I wish to address here. First, I did not use the basic colors from the notebook when creating my graphs. I instead used specific tones of green, yellow, blue, pink, and red. This was intentional. These are the same hues from my previous homeworks and I believe it's a better representation of different datasets than plotting all the charts in the same original plot colors. I realize this is a full portfolio of work and I would like my portfolio to show a congruent use of colors and styles across each of my pieces where possible.

## Results

In the 06_API_Challenge, this dataset is an API pull of roughly 600 cities from a random city generator. The API then appends data from each city about data points such as temperature, humidity, and cloudiness. A further analysis compares several of these factors against latitude for correlation. The data chain continues by importing of the cities into another notebook which maps all the cities by the amount of humidity. After describing my ideal weather conditions, the data is futher narrowed down to cities which fit these conditios. This data is then used against another API which collects hotel data against the ideal city location. A final map shows hotel destinations which adhere to my ideal weather conditions and the location across the globe.

## Usage

You can use this file to analyze the data in the corresponding resource CSV's.

1. Open the respective file (`WeatherPy.ipynb) in Jupyter Notebook.

2. Make sure that the resource and analysis directories are congruent within their respective places as listed in the script, if not change the location.
   
3. Cells requiring the API key will not work without the key.

5. Run individual cells within the (`WeatherPy.ipynb) to see the calculations of breakdown by category.

6. Results will be exported from the notebook into another outbound folder.

7. After all the cells are run the notebook will be finished.

8. Open the respective file (`VacationPy.ipynb) in Jupyter Notebook.

9. Make sure that the resource and analysis directories are congruent within their respective places as listed in the script, if not change the location.

10. Cells requiring the API key will not work without the key.

11. Run individual cells within the (`VacationPy.ipynb) to see the calculations of breakdown by category.

## Resources and Citations

1. Office Help - Kristina D'Alessio

2. Linear Regression as a Function - Davin Frankosky

3. API Key Help and General Questions - BCS Assistant
   
4. General - ChatGpt.com

