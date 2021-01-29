# airbnb-data-analysis
Analysis of AirBNB data for Edinburgh and Bristol

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

In order to run the analysis code you will need the standard libraries included within the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

In order to run the analysis you will also need to download and install [nltk](https://www.nltk.org/data.html), [spacy](https://spacy.io/) (specifically module en_core_web_sm) and [TextBlob](https://textblob.readthedocs.io/en/dev/).

To visualise the analysis of words used the listings and reviews data you will need to download scattertext from [here](https://pypi.org/project/scattertext/0.0.2.6.0/) and install wordcloud (using pip install wordcloud).

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in analyzing data from AirBnB homes located in Boston, MA and Oakland, CA. Specifically, I looked at the following questions:

1. What are the most common words used to describe a listing? Are the same words used to describe Boston and Oakland homes?
2. How many days a year do homeowners make their homes available to rent? How does this compare between Boston and Oakland?
3. How much do people charge to rent their homes (on average, minimum, maximum)? How does this compare between Boston and Oakland?
4. Are there seasonality components or price spiking components for how hosts set their home prices? How does this compare between Boston and Oakland?
5. Are there any property-specific amenities (i.e. Wi-Fi, TV, kitchen) that can help predict price? Which of these have the strongest influence on price? How does this compare between Boston and Oakland?
6. How many reviews do homes tend to get? What are common words used in reviews and are they primarily positive or negative? How does this compare between Boston and Oakland?

## File Descriptions <a name="files"></a>

The following are the files available in this repository:

- AirBnB_Project_1_Analysis.ipynb - a notebook of the analysis performed following the CRISP-DM process

- calendar_boston.csv and calendar_oakland.csv - csvs containing home_id, date, availability, and price for each home

- listings_boston.csv and listings_oakland.csv - these were not used for this particular analysis, but they were available from the original kaggle link

- reviews_boston.csv and reviews_oakland.csv - csvs containing the home_id, date of review, reviewer_id, reviewer_name, and reviewer comments for the reviewed stays.

## Results<a name="results"></a>

The main findings of the code can be found at the blog post available [here]().

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to AirBnB and Kaggle for the data.  You can find the Licensing for the data and other descriptive information for the Boston and Oakland data on AirBnB [here](http://insideairbnb.com/get-the-data.html).