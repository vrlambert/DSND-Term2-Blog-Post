# Data Scientist Nanodegree Term 2 Blog Post
### Writing a blog post: Airbnb Data

In this repo you'll find the analysis I did for the data scientist nanodegree, in particular I dove into some publicly available data from Airbnb and tried to answer the following questions:

1. What is the distribution of Airbnb prices?
1. What are the top contributing features?
1. Does the set of high value features change looking at different cities?
1. Could we use this analysis to help people make their Airbnb rentals more attractive?

## Summary of Results
In general I found that the most important features were location and size of the Airbnb, and that didn't vary too much from city to city. Addressing each question in order:

- The prices are generally more expensive in Boston, with averages of ~$175 compared to averages of ~$125 in Seattle
- The top contributing features tend to be the number of bedrooms, the number of people accommodated, and the location of the apartment
- Bostonians seem to value renting the entire apartment more than Seattleites, who value the size of the place.
- No, we can't make too many recommendations other than to have a nicer and better located listing! Small things are to make sure they have smoke detectors and a TV.

## Requirements
`pandas`

`numpy`

`matplotlib`

`seaborn`

`scikit-learn`

`jupyter` if running locally

## Files in the repo
- `Airbnb Data Investigation.ipynb` - contains the analysis
- `boston-airbnb-open-data/calendar.csv` `listings.csv` `reviews.csv` - Boston data
- `seattle/calendar.csv listings.csv` `reviews.csv` - Seattle data

## Acknowledgements
I got the data from these two links on Kaggle
1. https://www.kaggle.com/airbnb/seattle/data
1. https://www.kaggle.com/airbnb/boston
