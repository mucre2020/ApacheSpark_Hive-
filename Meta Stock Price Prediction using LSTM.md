# Meta Stock Price Prediction using LSTM and Big Data Technologies

## Overview
This project implements a stock price prediction model for Meta Platforms, Inc. (formerly Facebook) using Long Short-Term Memory (LSTM) networks and big data technologies. The project demonstrates the integration of Hadoop, Hive, Apache Spark, and PySpark for processing and analyzing large-scale financial data.

## Technologies Used
- Hadoop Distributed File System (HDFS)
- Apache Hive
- Apache Spark
- PySpark
- LSTM (implemented using TensorFlow and Keras)

## Dataset
The dataset comprises historical stock prices of Meta Platforms, Inc. from 2012 to 2023, obtained from Yahoo Finance. It includes features such as Open Price, High Price, Low Price, Close Price, Adjusted Close Price, and Volume.

## Project Structure
1. Data Acquisition and Preparation
2. Dataset Upload to HDFS
3. Hive Table Creation and Data Loading
4. Data Exploration using Hive
5. Data Processing with Spark and PySpark
6. LSTM Model Implementation
7. Results Analysis and Visualization

## Key Results
- Mean Squared Error: 638.1364529778022
- Mean Absolute Error: 16.005507104082028
- R-squared Score: 0.8761447493230506

## How to Run
1. Ensure Hadoop, Hive, and Spark are installed and configured.
2. Upload the dataset to HDFS.
3. Create and load data into the Hive table.
4. Run the PySpark scripts for data processing and LSTM model implementation.

## Future Improvements
- Incorporate additional data sources (e.g., sentiment analysis)
- Experiment with ensemble methods
- Develop a real-time prediction system

## Contributors
- Mupenzi Clement
- Iransubije Philemon

## Acknowledgements
Special thanks to Dr. Kundan Kumar for guidance throughout the project.

## License
[Include your chosen license here]