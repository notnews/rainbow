### Rainbow: Racial Diversity of People Referred to in the News and the Newsroom

We use the [Top News Data](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/ZNAKK6) that collates news articles from news feeds from ABC, CBS, CNN, NBC, LA Times, NBC, NYT, Politico, USAT, and WaPo, and [ethnicolr](https://github.com/appeler/ethnicolr) to estimate the racial diversity of the people mentioned in the news and the newsroom.

Data suggest that African Americans and Hispanics are grossly underrepresented in the newsroom. We see a more attenuated pattern for the mentions.

Race/ethnicity of authors across all outlets.

| Race/Ethnicity | Percentage |
|--------------|----------|
| nh_white     | 78%   |
| nh_black     | 5.7%   |
| asian        | 8.5%   |
| hispanic     | 7.3%   |
| other        | .4%   |


Race/ethnicity of people mentioned in the news across all outlets.

| Race/Ethnicity | Percentage |
|--------------|----------|
| nh_white     | 73.5%   |
| nh_black     | 9.5%   |
| asian        | 8.6%   |
| hispanic     | 8%    |
| other        | .4%   |

For channel-wise breakdown, please refer to the notebooks.

### Notebooks

* [Get News Data](notebooks/01_news_grabber.ipynb)
* [Extract Names](notebooks/02_extract_names_from_news.ipynb)
* [Analyze Authors](notebooks/03_news_authors_lstm_infer.ipynb)
* [Analyze People Mentioned](notebooks/04_news_mentioned_names_lstm_infer.ipynb)

### Authors

Rajashekar Chintalapati and Gaurav Sood
