# Project-2

## Data Source
The data set was derived from https://hdr.undp.org/data-center/human-development-index#/indicies/HDI, United National Human Development Reports, a public website containing information about the HDI of various countries across the globe along with their respective factors, including their country name, mean/expected years of schooling, life expectancy, and GNI per capita. The data was collected on November 14, 2024.
## Analysis 
Analysis Methods
**Data Cleaning and Preprocessing:**
* Removed NA values and handled missing data appropriately.
* Reshaped variables for consistency and ease of analysis (e.g., creating new variables like schooling gap).
* Reformatted and parsed string variables for consistency, such as income categories.
  
**Descriptive Statistics:**
* Calculated summary statistics (mean, median, standard deviation) for key variables like HDI, life expectancy, GNI per capita, and mean years of schooling.
* Created visualizations to summarize the distribution of variables, such as histograms and boxplots.
  
**Bivariate Analysis:**
* Explored relationships between pairs of variables (e.g., HDI vs. life expectancy, mean years of schooling vs. GNI per capita) using scatter plots, boxplots, and correlation analysis.
  
**Multivariate Analysis:**
* Conducted multivariate analysis with three variables (e.g., schooling gap, HDI, GNI per capita) to examine the interactions between income, education, and development outcomes.
* Used ggplot models or visualizations (e.g., scatter plot ) to identify trends and relationships.
  
**Variable Creation:**
* Created new variables to analyze specific aspects of development, such as calculating the "schooling gap" (difference between mean years of schooling and expected years of schooling).
  
**Visualization:**
* Used various types of plots (e.g., bar charts, histograms, boxplots, scatter plots) to visually represent the data and the relationships between variables.
* Produced proportional bar charts to visualize the distribution of countries across income categories.

## How to Reproduce 
* Clone the repository and install the required R packages (e.g., dplyr, ggplot2, tidyr).
* Download the dataset from the provided source or use the included file in the repository.
* Load and clean the dataset by handling missing values, reshaping variables, and formatting strings as needed.
* Run the provided R script or R Markdown file to reproduce the analysis, visualizations, and final report.
