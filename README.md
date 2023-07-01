### Rainbow: Racial Diversity of People Referred to in the News and the Newsroom

We use the [Top News Data](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/ZNAKK6) that collates news articles from news feeds from ABC, CBS, CNN, NBC, LA Times, NBC, NYT, Politico, USAT, and WaPo, and [ethnicolr](https://github.com/appeler/ethnicolr) to estimate the racial diversity of the people cited in the news and the newsroom.


Race/ethnicity of authors across all outlets.

| Race/Ethnicity | Percentage |
|--------------|----------|
| nh_white     | 50%   |
| nh_black     | 28%   |
| asian        | 14%   |
| hispanic     | 8%   |
| other        | 2%   |


Race/ethnicity of people referred to across all outlets.

| Race/Ethnicity | Percentage |
|--------------|----------|
| nh_white     | 49%   |
| nh_black     | 29%   |
| asian        | 13%   |
| hispanic     | 7%    |
| other        | 1%   |

For channel wise breakdown, please refer to the notebooks.

### Notebooks

* [Get News Data](notebooks/01_news_grabber.ipynb)
* [Extract Names](noteooks/02_extract_names_from_news.ipynb)
* [Analyze Authors](notebooks/03_news_authors_lstm_infer.ipynb)
* [Analyze People Referred to](notebooks/04_news_mentioned_names_lstm_infer.ipynb)

### Authors

Rajashekar Chintalapati and Gaurav Sood
