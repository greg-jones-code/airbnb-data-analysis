# airbnb-data-analysis
Analysis of AirBNB data for Edinburgh and Bristol

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in analyzing data from AirBnB homes located in Boston, MA and Oakland, CA. Specifically, I looked at the following questions:

1. How much do people charge to rent their homes (on average, minimum, maximum)? How does this compare from Boston to Oakland?
2. How many days a year do homeowners make their homes available to rent? How does this compare from Boston to Oakland?
3. Are there seasonality components or price spiking components for how hosts set their home prices? How does this compare from Boston to Oakland?
4. How many reviews do homes tend to get? How does this compare from Boston to Oakland?
5. What are the most common words used to describe a listing? Are the same words used for Oakland and Boston homes?

## File Descriptions <a name="files"></a>

The following are the files available in this repository:

- AirBnB_Project_1_Analysis.ipynb - a notebook of the analysis performed following the CRISP-DM process

- calendar_boston.csv and calendar_oakland.csv - csvs containing home_id, date, availability, and price for each home

- listings_boston.csv and listings_oakland.csv - these were not used for this particular analysis, but they were available from the original kaggle link

- reviews_boston.csv and reviews_oakland.csv - csvs containing the home_id, date of review, reviewer_id, reviewer_name, and reviewer comments for the reviewed stays.

It is worth noting that there were no numeric values associated with reviews.

## Results<a name="results"></a>

The main findings of the code can be found at the blog post available [here](https://medium.com/@josh_2774/how-do-you-become-a-developer-5ef1c1c68711).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to AirBnB and Kaggle for the data.  You can find the Licensing for the data and other descriptive information for the Boston and Oakland data on AirBnB [here](http://insideairbnb.com/get-the-data.html).