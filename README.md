# MOVIE-RATING-PREDICTION
# Movie Rating Prediction - CODSOFT Internship Task 2

## Objective
Build a machine learning regression model that predicts the IMDb rating of a movie based on features such as genre, director, duration, and vote count.

## Dataset
- **Source**: IMDb Indian Movies Dataset
- **File**: `IMDB-Movie-Data.csv`
- **Size**: ~1.3 MB
- Contains metadata such as Genre, Director, Duration, Votes, and Ratings for Indian films.

## Technologies Used
- Python
- Google Colab
- pandas, numpy
- seaborn, matplotlib
- scikit-learn (LinearRegression, LabelEncoder, train_test_split, r2_score, mean_squared_error)

## Workflow
1. **Data Upload**: Dataset manually uploaded via Colab
2. **Cleaning**:
   - Converted `Duration` from text (`"123 min"`) to integer (`123`)
   - Removed commas from `Votes` (e.g., `"85,340"` → `85340`)
   - Dropped missing values
3. **Encoding**:
   - Converted categorical columns `Genre` and `Director` using `LabelEncoder`
4. **Modeling**:
   - Used Linear Regression from scikit-learn
   - Split data into training and testing sets
   - Evaluated with R² Score and Mean Squared Error (MSE)
5. **Visualization**:
   - Scatterplot of actual vs predicted ratings

## Model Results
- **R² Score**: ~`[your_r2_score]` (e.g., 0.64)
- **Mean Squared Error**: ~`[your_mse]` (e.g., 0.48)

## Folder Structure
task2_movie_rating_prediction/
├── movie_rating_prediction.ipynb
├── IMDB-Movie-Data.csv
└── README.md
Author
KAMALEESHWARI P  
CODSOFT Data Science Intern - 2025
Data Science Internship Tasks for CodSoft
