# Violet-s-portfolio
##data analytics portfolio
> Dataset on South African Crime rates. Statistical summary on mean, median, min, and max. Handle missing values in the dataset, checking and removing duplicates and outliers.
`code`
> sa_crime_stats=pd.read_csv(r"C:\Users\user\Documents\TASKS\task_1\SouthAfricaCrimeStats_v2.csv")
print(sa_crime_stats['Station'].dtype)
print(sa_crime_stats.describe())
sa_crime_stats['Station']=sa_crime_stats['Station'].astype('string')
print(sa_crime_stats.info())
print(sa_crime_stats['Station'].dtype)

> Comparative Analysis to compare the crime rates across the five most frequent provinces. Province with the highest crime rates in the category of "All theft not mentioned elsewhere" over the entire period.
> Ranking the top 5 stations based on the average crime rate over the entire period and Identifying the top 5 stations with the highest and lowest crime rates over the entire period.
> The top 5 stations with a significant decrease in crime rates over consecutive years were identified and the percentage change in crime rates for Pretoria Central, Cape Town Central, Brooklyn, and Pretoria West stations over the years was plotted.
> Overall crime trends were analyzed by aggregating the data at the province level using the five most frequent provinces.
