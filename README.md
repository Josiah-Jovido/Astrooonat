# Astrooonat
#### Music streaming and analysis app
Astrooonat is a music streaming and analysis app built on deezer api. The main function of the app is to analyze and display a user's listening data and generate song recommedations based off that.

#### [Notebook_1](https://github.com/Josiah-Jovido/Astrooonat/blob/main/Notebooks/Notebook_1.ipynb)
I trained a [model](https://github.com/Josiah-Jovido/Astrooonat/blob/main/Notebooks/model.pkl) using **DecisionTreeClassifier** on a dataset obtained from kaggle. The model is able to discern if a user likes or dislikes a song from the song attributes/features. This will help in the basic clustering of the songs into groups. From the positively liked group, we will build recommedations for the user off of that.

#### [Notebook_2](https://github.com/Josiah-Jovido/Astrooonat/blob/main/Notebooks/Notebook_2.ipynb)
I worked with a content-based recommendation system that leverages the features and attributes of a song. The Dataset used in the data preparation was gotten from Kaggle as i had no prior user data. I used **cosine similarity** for generating recommendations. Cosine similarity measures the similarity between two vectors of an inner product space. It is measured by the cosine of the angle between two vectors and determines whether two vectors are pointing in roughly the same direction. It is a metric used to measure how similar the documents are irrespective of their size, for this case i applied it to songs.
