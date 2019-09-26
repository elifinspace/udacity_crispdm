## UDACITY Data Scientist Nanodegree CRISP-DM PROJECT

This project is about:

*Coming up with three questions

*Extracting the necessary data to answer these questions.

*Performing necessary cleaning, analysis, and modeling.

*Evaluating results.

*Sharing insights with stakeholders.

I have used Seattle AirBnB dataset(https://www.kaggle.com/airbnb/seattle) to answer the following questions and find predictive variables for price.
  - What are the peak days in Seattle?
  - Which areas are more pricy than others?
  - What are the major factors that determine prices?

Medium Blog Post: https://medium.com/@elifsurmelif/seattle-airbnb-market-price-analytics-97196545da3a
If you have difficulty in displaying .ipynb files please go to  https://nbviewer.jupyter.org/ and paste the link that you're trying to display the notebook such as https://github.com/elifinspace/udacity_crispdm/blob/master/explore_raw.ipynb

## Getting Started

Instructions below will help you setup your local machine to run the copy of this project.

### Prerequisites

#### Software Requirements

  - Anaconda 3
  - Python 3.7.3
  
  - textblob (https://pypi.org/project/textblob/)
  - folium (https://pypi.org/project/folium/)
  - branca (https://pypi.org/project/branca/)
  - geopandas (https://pypi.org/project/geopandas/)

#### Running the notebooks

  - First install all the packages stated above.
  - Run the commands below in your working directory to open the project in jupyter lab:
    ```
    git clone https://github.com/elifinspace/udacity_crispdm.git
    
    jupyter lab
   
    ```
  - explore_raw.ipynb: This notebook includes the preliminary work, explorations.
  - map_visualisations.ipynb : This notebook includes map visualisations of some analysis on listings data.
  - main.ipynb :  This notebook makes use of the findings from the explore_raw.ipynb to cleanse and process the data. It is sufficient to run this notebook standalone to cleanse the data, generate predictions and evaluate the results.
  


## Authors

* **Elif Surmeli**

