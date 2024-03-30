## Music Dataset Analysis

In this project, I delve into the realm of unsupervised learning by analyzing a dataset comprising songs spanning from 1950 to 2011. This dataset, sourced from a research paper titled "Music Dataset: Lyrics and Metadata from 1950 to 2019," provides a rich collection of features including lyrical content and metadata associated with each song.

### Dataset Overview
The dataset consists of several columns, each providing valuable insights into the songs:

- **artist_name**: The name of the artist
- **track_name**: The title of the song
- **release_date**: The date when the song was released
- **genre**: The categorical genre of the song

Lyrical Features:

- **lyrics**: The pre-tokenized lyrics of the song
- **len**: The number of words in the lyrics
- **dating**, **violence**, **world/life**, **night/time**, **shake the audience**, **family/gospel**, **romantic**, **communication**, **obscene**, **music**, **movement/places**, **light/visual perceptions**, **family/spiritual**, **sadness**, **feelings**: Scores from 0 to 1 indicating the likelihood of the song's lyrics being associated with various themes or topics
- **topic**: The categorical label of lyrical content
- **age**: A score from 0 to 1 representing the "oldness" of the song, where 1 indicates the oldest and 0 the newest.

### Objectives
My main goal was to apply unsupervised learning techniques to cluster the songs based on their lyrical features and explore any underlying patterns or themes. Additionally, I aimed to identify insights from the clustering results and potentially recommend songs to users based on their preferences.

### Methodology
I started by conducting exploratory data analysis (EDA) to gain insights into the dataset, including identifying correlations between variables. I then preprocessed the data as needed and apply clustering algorithms to group the songs into clusters based on their lyrical content. After that, I interpreted the clusters to understand the themes represented by each cluster and make recommendations accordingly.

### Technologies
Here is a list of technologies I used in this project:

- Python
- Pandas and Numpy for data manipulation and analysis
- Scikit learn linear model, pre processing, model selections, metrics, and many more for machine learning tasks
- Matplotlib and Seaborn for data visualization
- Jupyter Notebook for interactive development and analysis

### Conclusion
By analyzing this music dataset using unsupervised learning techniques, I aimed to uncover hidden patterns and themes within the songs' lyrical content. Through clustering analysis, I provided a ton of valuable insights into the diverse landscape of music genres and themes across different time periods.
