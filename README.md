Data Analysis: Video Game Success Factors (Metacritic)

This repository contains an Exploratory Data Analysis (EDA) developed in Python, focused on discovering what factors truly influence video game ratings (Metascores). Using a Metacritic dataset, the project poses and answers four key hypotheses regarding video game development and audience reception.

## Project Overview
The main objective of this analysis is to demystify common beliefs within the gaming community and developer industry using real data. Through data manipulation and visualization, this project evaluates the impact of game modes, release windows, user reviews, and platform performance.

## Technologies Used
* **Language:** Python 3
* **Environment:** Jupyter Notebook
* **Core Libraries:** * `pandas` (Data cleaning, manipulation, and structuring)
  * `numpy` (Numerical and conditional operations)

## Hypotheses Analyzed & Conclusions

**1. Does a game's rating depend on whether it is multiplayer or single-player?**
* **Result:** It was observed that the lack of an online mode does not penalize a game's score. Many of the highest-rated games rely heavily on their story mode. Even for titles that include online features, their high scores often depend more on the main narrative than the multiplayer component itself.

**2. Does the score show an increase depending on the release season?**
* **Result:** While the overall average score doesn't vary drastically between seasons, when analyzing the volume of games that **exceed the average score**, there is a slight positive trend for Autumn releases.

**3. Do more positive user reviews guarantee a better Metascore?**
* **Result:** There is no strict correlation. Data visualization shows that a high volume of positive user reviews does not guarantee a high Metascore; there are several titles with moderate critic scores that are highly beloved by the gaming community.

**4. Does a game's rating vary between Consoles and PC?**
* **Result:** Yes, score variations were identified for the exact same title depending on the platform. This suggests that technical factors (such as poor optimization, performance issues, or buggy ports) directly impact the user experience and, consequently, the final rating.

## 📂 Repository Contents
* [`Project.ipynb`](./Project.ipynb): The Jupyter Notebook containing all the source code, data cleaning (e.g., extracting months to define seasons), and the complete analysis.
* [`metacritic_games.csv`](./metacritic_games.csv): The original dataset used for the analysis.
