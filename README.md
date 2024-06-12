# Internship Project
# Towards an urban water balance twin
## Problem Statement:
### Overview:

As London grows, its water balance is increasingly disrupted by urbanization and climate change, leading to degraded groundwater quality and fluctuating water levels. These changes not only threaten the city's water supply but also incur substantial costs in water treatment and penalties for pollution incidents.

### Core Features:

  1.Predictive Analytics: Utilize historical data and real-time inputs to predict changes in groundwater levels.
  
  2.Optimal Pumping Recommendations: Based on predicted data, suggest whether to pump more or less water to maintain quality.
  
  3.Cost Reduction Strategies: Identify measures to minimize costs associated with water decontamination and penalties due to poor water quality.
  
  4.Environmental Compliance: Help Thames Water adhere to environmental regulations and prevent potential fines.

  
### Data:

To simulate the urban water balance, we employed a comprehensive data analysis approach. The data collection process began by identifying essential features and potential sources, including websites, databases, and APIs, with a specific focus on the Hydrology Data Explorer API, which provided London city data in CSV format. The acquired dataset encompasses rainfall data, water quality, river levels, flow, groundwater, land use, evapotranspiration, and surface runoff.

During preprocessing, our team conducted thorough data cleaning operations, addressing missing values, converting data types, and aggregating temporal intervals. Columns with high percentages of null values were removed, and missing values were imputed using central tendency measures such as the mean or median. We resolved data duplication issues and standardized datetime values into separate date and time components, ensuring dataset accuracy and consistency.

Exploratory data analysis (EDA) involved aggregating values into a unified database, averaging 15-minute interval data into daily values, and conducting temporal analysis spanning from 2013 to 2023. Various visualization techniques were employed to identify patterns and facilitate interactive exploration of the dataset. Rainfall data served as the base for all calculations related to modeling other features such as evapotranspiration, surface runoff, and groundwater infiltration.

To gain a deeper understanding of the interactions between groundwater levels and water quality, we used our best-performing model (Weighted Voting Esemble) to experiment with increasing and decreasing water quality features and observing the effects on groundwater levels. This model allowed us to simulate different scenarios and determine whether higher or lower groundwater levels would be more beneficial for maintaining optimal water quality.

This rigorous data analysis and simulation methodology enabled us to create a robust framework for understanding and managing the complex interactions between groundwater levels and overall water quality in urban environments. The insights gained from this approach are crucial for developing effective strategies to enhance water safety and sustainability in the Thames River region and beyond. 


### The main features are:

Rainfall

River flow

River level

Groundwater level

Water quality: Ammonia (mg/L), Conductivity (mS/cm), Dissolved Oxygen (%), pH, Temperature (°C)

Land use: Impervious surfaces, buildings, forest, etc.

Surface runoff

Evapotranspiration



# Unsupervised predict
# The Movie Recommender Algorithm
## Overview
The film and entertainment industry has been growing and evolving vastly over the years, resulting in it being a multi-billion-dollar worth of an industry. From live theatre, to audioless black and white, to music and theatre, to television and big screens in cinema's, and now streaming. Film making and production has truly come a long way.

Streaming seems to be the big thing now, with organisations such as Amazon, Apple, Netflix, Disney, etc, taking advantage of the opportunities that have occured from this segment. These organisations have created apps where movies, series, documentaries, and other forms of entertainment in the film industry can be access anywhere, anytime, with only just a touch of a finger. These apps do not only give you access to the movies you want, but also learn more about which ones interests you best, and recommends them for you.

It is through algorithms that this is possible. Models are created and trained to learn what suits you through the use of algorithms. Therefore, the machine learning model learns your interests, such as the different genres you are into, the casts you watch the most, the years they were released, and more. Once it catches on all your interests, it recommends movies and series that meet your likeness. The purpose of this document serves to depict how models are created, trained, tested, and how they can recommend movies to your likeness so that binging is much easier.

## Project Description
As Phantom AI, we were approached by Tesla to work on a project that will assist them with one of their biggest innovations, and enabling to penetrate the film and entertainment industry. Tesla is one of the biggest companies in the world and was founded by the richest man alive. It's aim is to create highly innovative, sophisticated vehicles that are intelligent, safe, and have a less negative effect on the environment, as their vehicles release less carboon footprint compared to gasoline cars. However, their biggest innovation is the development of self driven cars. This innovation has given them the opportunity to penetrate certain market segments, allowing them to increase their reach and have a wider market. In a nutshell, they want to bring the cinema... to your vehicles.

They want to create a software that can be installed in their vehicles that will serve as a streaming platform for movies and series. This is convenient for the driver when he/she switches to auto-pilot so that the car drives itself, and the driver can relax and catch-up on his/her favourite shows. Therefore, Tesla has approached us to:

build, train, and test a machine learning model build an app using streamlit services deploy the model on the streamlit app to assess its effectiveness


# Advanced classification Predict
# Sentiment Analysis
## Overview
This project focuses on analysing public opinions about climate change expressed on Twitter. The dataset contains 43,943 tweets where each tweet is labelled into one of four classes:

2 News: The tweet links to factual news about climate change. 1 Pro: The tweet supports the belief of man-made climate change. 0 Neutral: The tweet neither supports nor refutes the belief of man-made climate change. -1 Anti: The tweet does not believe in man-made climate change. The aim is to develop a machine learning model capable of categorising tweets into these classes, aiding environmentally conscious companies in aligning their products or services with public sentiments and values.

## Problem Statement
The main challenge involves training a model to interpret tweets and accurately assign them to one of the predefined classes based on their content. This classification task is vital for companies seeking to understand public sentiments regarding climate change.


# Advanced Regression Predict
# Spain Demand Shortfall
## Overview
The supply of electricity plays a large role in the livelihood of citizens in a country. Electricity, amongst other things, helps us stay connected, keep warm, and feed our families. Therefore there's a need to keep the lights on in order to maintain and improve the standard of living by investing in electricity infrastructure. However, in recent years, there has been evidence that the use of purely non-renewable sources is not sustainable.

The government of Spain is considering an expansion of its renewable energy resource infrastructure investments. As such, they require information on the trends and patterns of the country's renewable sources and fossil fuel energy generation. For this very reason, the government of Spain has been tracking the different energy sources available within the country.

# SQL Predict
## Problem Statement
The Bhejane Trading store is an online retailer specializing in the sale of covid-related essential items.The obective is to normalise the database of the store's inventory management system.
