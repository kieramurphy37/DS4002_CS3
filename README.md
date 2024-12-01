# DS4002_CS3

## Software and Platform

- **Software**: Google Colab
- **Add-on package**: VADER, Pandas, Numpy, Matplotlib, Seaborn
- **Platform**: Mac

## Documentation Map

-**ProjectOverview Folder**: Contains information important to understanding the purpose and goal of the project.
  - `CS3 Blog Post.pdf`: contains informationd found online about the topic
  - article
  - hook document
  - rubric
- **Data Folder**: Contains all data
  - `Womens Clothing E-Commerce Reviews.csv`: Our original dataset, downloaded from Kaggle and uploaded to GitHub
  - `Cleaned_Data.csv`: Our cleaned data, created from the `MI3_Cleaning.ipynb` and used for the rest of the EDA and analysis
  - `DataAppendix.pdf`: Description of the data used
- **Scripts Folder**: Contains all source code and scripts
  - `MI2_Cleaning.ipynb`: Data cleaning script, creates `Cleaned_Data.csv`
  - `MI2_EDA`: Exploratory data analysis on our cleaned dataset
  - `MI3_Analysis_AllSentimentScores.ipynb`: Analysis of all sentiment score data points
  - `MI3_Analysis_Negative.ipynb`: Analysis of negative sentiment score data points
  - `MI3_Analysis_Positive.ipynb`: Analysis of positive sentiment score data points

## Reproduction Information

1. **Data Gathering**: We got our data from kaggle - [Women's E-Commerce Clothing Reviews Dataset](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews) . However, we have uploaded it to this GitHub repository under the _Data Folder_. The scripts include fetching the data from our GitHub repo.
2. **Data Cleaning**: To reproduce our cleaned dataset, run the `MI2_Cleaning.ipynb` script. We downloaded the final dataframe and uploaded it to GitHub. The future scripts will fetch the cleaned data set from the _Data Folder_.
3. **Exploratory Data Analysis**: To explore the data and gather initial insights to refine the analysis plan, run the `MI2_EDA.ipynb` script under the _Scripts Folder_.
4. **Analysis**: To conduct analysis on the data, there are 3 main files to run: `MI3_Analysis_AllSentimentScores.ipynb`, `MI3_Analysis_Negative.ipynb`, and `MI3_Analysis_Positive.ipynb`. You can find all of these files in the _Scripts Folder_. We decided to do analysis on the negative and positive subsets to account for most of the reviews being positive - we still wanted to explore negative sentiment scores without any skewing.

## References
1. “Welcome to Vadersentiment’s documentation!¶,” Welcome to VaderSentiment’s documentation! - VaderSentiment 3.3.1 documentation, https://vadersentiment.readthedocs.io/en/latest/ (accessed Sep. 11, 2024).
2. Nicapotato, “Women’s e-commerce clothing reviews,” Kaggle, https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews (accessed Sep. 11, 2024).

