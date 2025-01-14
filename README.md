# Traffic Flow Forecasting in San Francisco, California

This repository contains my thesis project focused on forecasting traffic flow in paths of San Francisco, California. The goal is to predict the number of taxis that will cross a specific path given historical data. The project utilizes machine learning and deep learning models such as XGBoost, LSTM, Encoder-Decoder, and Random Forest for making accurate forecasts.

## Repository Overview

- **Objective:** Forecast traffic flow in paths of San Francisco, California, using historical data.
- **Methodology:** Time series forecasting using machine and deep learning models. We use the Strict Path Queries paper to measure traffic flow in each path accurately. Read more about SPQ methodology [here](Related_Work/Strict_Path_Queries.pdf).
- **Data:** The dataset consists of paths, each comprising consecutive edges representing road segments between intersections.
- **Models Used:** XGBoost, LSTM, Encoder-Decoder, and Random Forest.
- **Number of Paths:** 1000 paths are used for making traffic forecasts.
- **Approach:** The problem is transformed into time series forecasting, with one time series for each path in the dataset.

## Dependencies

To run the code in this repository, ensure you have the latest version of Python installed. The required libraries are listed in the `Necessary Python Libraries.txt` file. You can install them using pip or conda commands.

## About Me
My name is Efstratios Karkanis, and I am a 4th-grade student at the University of Piraeus. For any inquiries or to establish contact, please feel free to reach out to me at stratoskarkanis2@gmail.com.

Feel free to explore the code and the insights gained from this project. Contributions and feedback are always welcome!



