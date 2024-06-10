#Towards an urban water balance twin

##Problem Statement:

###Project overview:

As London grows, its water balance is increasingly disrupted by urbanization and climate change, leading to degraded groundwater quality and fluctuating water levels. These changes not only threaten the city's water supply but also incur substantial costs in water treatment and penalties for pollution incidents.

###Core Features:

  1.Predictive Analytics: Utilize historical data and real-time inputs to predict changes in groundwater levels.
  
  2.Optimal Pumping Recommendations: Based on predicted data, suggest whether to pump more or less water to maintain quality.
  
  3.Cost Reduction Strategies: Identify measures to minimize costs associated with water decontamination and penalties due to poor water quality.
  
  4.Environmental Compliance: Help Thames Water adhere to environmental regulations and prevent potential fines.

  
###Data:

To simulate the urban water balance, we employed a comprehensive data analysis approach. The data collection process began by identifying essential features and potential sources, including websites, databases, and APIs, with a specific focus on the Hydrology Data Explorer API, which provided London city data in CSV format. The acquired dataset encompasses rainfall data, water quality, river levels, flow, groundwater, land use, evapotranspiration, and surface runoff.

During preprocessing, our team conducted thorough data cleaning operations, addressing missing values, converting data types, and aggregating temporal intervals. Columns with high percentages of null values were removed, and missing values were imputed using central tendency measures such as the mean or median. We resolved data duplication issues and standardized datetime values into separate date and time components, ensuring dataset accuracy and consistency.

Exploratory data analysis (EDA) involved aggregating values into a unified database, averaging 15-minute interval data into daily values, and conducting temporal analysis spanning from 2013 to 2023. Various visualization techniques were employed to identify patterns and facilitate interactive exploration of the dataset. Rainfall data served as the base for all calculations related to modeling other features such as evapotranspiration, surface runoff, and groundwater infiltration.

To gain a deeper understanding of the interactions between groundwater levels and water quality, we used our best-performing model (Weighted Voting Esemble) to experiment with increasing and decreasing water quality features and observing the effects on groundwater levels. This model allowed us to simulate different scenarios and determine whether higher or lower groundwater levels would be more beneficial for maintaining optimal water quality.

This rigorous data analysis and simulation methodology enabled us to create a robust framework for understanding and managing the complex interactions between groundwater levels and overall water quality in urban environments. The insights gained from this approach are crucial for developing effective strategies to enhance water safety and sustainability in the Thames River region and beyond. 


###The main features are:

Rainfall

River flow

River level

Groundwater level

Water quality: Ammonia (mg/L), Conductivity (mS/cm), Dissolved Oxygen (%), pH, Temperature (°C)

Land use: Impervious surfaces, buildings, forest, etc.

Surface runoff

Evapotranspiration
