## Exploratory Data Analysis on Ultra-Marathon Dataset
### Author - Praneeth D
### About the Data
Dataset is a large collection of ultra-marathon race records registered between 1798 and 2022. All data was obtained from public websites.

The following columns (with data types) are included:
* Year of event (int64)
* Event dates (object)
* Event name (object)
* Event distance/length (object)
* Event number of finishers (int64)
* Athlete performance (object)
* Athlete club (object)
* Athlete country (object)
* Athlete year of birth (float64)
* Athlete gender (object)
* Athlete age category (object)
* Athlete average speed (object)
* Athlete ID (int64)

[Dataset Link](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running)

### Exploration and Analysis
I have processed the dataset by reading and converting it into a dataframe. Given the large size, I filtered the data to include only USA marathons conducted in 2020 with race lengths of 50 km and 50 mi. Subsequently, I eliminated unnecessary features and meticulously examined each column to address any inconsistencies. With the cleaned dataframe, I generated visualizations to conduct preliminary analysis. Finally, I utilized various pandas and Python functions to answer specific queries and address uncertainties.

### Conclusions and Future Work

I've gained significant insights into exploratory data analysis (EDA) through this project. While focusing on USA marathons in 2020, specifically those with race lengths of 50 km and 50 mi, I've applied filtering and analytical techniques. Considering the vast dataset, time constraints have limited me from delving deeper into similar analyses for other countries and their specific marathons. Nonetheless, this project has equipped me with valuable skills in dataset manipulation and EDA, providing a foundation for future in-depth analyses. 
