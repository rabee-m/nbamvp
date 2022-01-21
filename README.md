<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://courtsidecritics.com/wp-content/uploads/2020/10/MVP.jpg">
    <img src="images/logo.png" alt="Logo" width="280" height="280">
  </a>

<h3 align="center">NBA MVP Predictor</h3>

  <p align="center">
    A machine learning model using RandomForest Regression that predicts NBA MVP's using player data.
    <br />
    <a href="https://github.com/github_username/repo_name"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Demo</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Report Bug</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Request Feature</a>
  </p>
</div>





<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

<p>This project utilizes RandomForest Regression ML model to predict the NBA MVP. Now you may think that this is not a regression problem, but more of a classification problem, however our approach to predicting MVP consists of predicting a numerical variable called MVP win share. From that prediction, the player in the season with the highest MVP win share is predicted to be the MVP. As you can see structuring the problem like this lends more towards a regression solution.</p>

<p> Our machine learning model is trained on data from 1980-2010, and then we use that to predict the MVP's for the 2011-2021 season.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [scikit-learn](https://scikit-learn.org/)
* [seaborn](https://seaborn.pydata.org/)
* [Matplotlib](https://matplotlib.org/)


<p align="right">(<a href="#top">back to top</a>)</p>

### Examples of Graphs Used
![Correlation Heatmap)](https://user-images.githubusercontent.com/62624592/150454517-dfe1383c-1416-49e1-9e83-c2e96ba94ba2.png)

![VIF Graph](https://user-images.githubusercontent.com/62624592/150454616-e78df7f0-9a81-4730-b799-d1fc116d5ff6.png)

### Usage
<p> To run this model, download the jupyter notebook, and data. Then within the file change the URL for the raw_mvp_data variable to the path wherethe data is located on your system.</p>

<!-- Results -->
## Results
![MVP Predictions](https://user-images.githubusercontent.com/62624592/150454335-fd0f689a-162a-4fb6-9ef4-f1bf16a7c7e5.png)
<p> The model achieved an R^2 value of 0.6127, guessing 8/10 of it's predictions correctly. </p>

<!-- Acknowledgements -->
## Acknowledgements
Inspiration from this article: (https://towardsdatascience.com/predicting-the-next-nba-mvp-using-machine-learning-62615bfcff75)
<!-- Acknowledgements -->
