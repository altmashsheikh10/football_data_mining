# Football Data mining
This repository contains various resources for the exploratory data analysis and implementation for the machine learning algorithms to rate football teams based on various factors.

## About the data
The dataset contains data about 99 top teams in the world, with a total of 10 features describing the teams:

<table>
    <tr>
        <th>
            Feature
        </th>
        <th>
            Remark
        </th>
    </tr>
    <tr>
        <td>
            Tournament
        </td>
        <td>
            The league the team participates in, and the data is from e.g. Premier League, Bundesliga etc.
        </td>
    </tr>
    <tr>
        <td>
            Goals
        </td>
        <td>
            Total number of goals scored in the year 2020-21
        </td>
    </tr>
    <tr>
        <td>
            Shots pg
        </td>
        <td>
            Number of shots on target per goal
        </td>
    </tr>
    <tr>
        <td>
            Yellow Cards
        </td>
        <td>
            Yellow cards accumulated over the season
        </td>
    </tr>
    <tr>
        <td>
            Red Cards
        </td>
        <td>
            Red cards awarded throughout the year
        </td>
    </tr>
    <tr>
        <td>
            Possession%
        </td>
        <td>
            Possession%(of the ball) averaged over all matches
        </td>
    </tr>
    <tr>
        <td>
            Pass%
        </td>
        <td>
            Percentage of successfully completed passes
        </td>
    </tr>
    <tr>
        <td>
            Aerials Won
        </td>
        <td>
            Average of number of aerial duels won per match
        </td>
    </tr>
    <tr>
        <td>
            Rating
        </td>
        <td>
            Rating assigned to team based on these features
        </td>
    </tr>
</table>

The Jupyter Notebook contains various visualizations of the data to understand the intricacies better. Following this, is the development of 3 Machine Learning models viz. Linear Regression, KNN, and Random Forest Regressor. The accuracy scores of the models are also tested. The model with the highest accuracy(KNN) is then saved as the pickel file `model.pkl

## References
<li><b>Kaggle</b> - <a href="https://www.kaggle.com/">kaggle.com</a>
