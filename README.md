# Recipe Recommender System

## Project Overview
A sophisticated machine learning system that recommends recipes to users based on their preferences and past interactions. The system uses collaborative filtering and latent factor models to provide personalized recipe recommendations.

## Key Features
- **Personalized Recommendations**: Uses collaborative filtering to suggest recipes based on user preferences
- **Advanced Rating Prediction**: Implements a latent factor model using TensorFlow for accurate rating predictions
- **Comprehensive Data Analysis**: Includes extensive exploratory data analysis of recipe and user interaction data
- **Multiple Baseline Models**: Implements various baseline models for comparison:
  - Global Average Rating
  - User-Based Average Rating
  - Recipe-Based Average Rating
  - Matrix Factorization Model

## Technical Implementation
- **Model Architecture**: Latent factor model implemented using TensorFlow/Keras
- **Performance Metrics**: Uses Mean Squared Error (MSE) for model evaluation
- **Data Features**:
  - Recipe metadata (ingredients, cooking time, nutrition info)
  - User ratings and reviews
  - Temporal interaction data
  - Recipe characteristics and tags

## Project Structure
- `baseline_model.ipynb`: Implementation of baseline recommendation models
- `grid_search.ipynb`: Hyperparameter tuning for the recommendation system
- `EDA.ipynb`: Exploratory Data Analysis of the recipe dataset
- `EDA - Jack.ipynb`: Additional exploratory analysis and insights

## Model Performance
- Global Average Baseline MSE: ~1.58
- User Average Baseline MSE: ~1.57
- Recipe Average Baseline MSE: ~1.76
- Optimized Latent Factor Model MSE: ~1.54

## Technologies Used
- Python
- TensorFlow/Keras
- Pandas
- NumPy
- Jupyter Notebook

## Future Improvements
- Implementation of content-based filtering
- Integration of ingredient-based similarity metrics
- Addition of real-time recommendation updates
- Enhanced user preference learning

## Author
- jak-weston
- nathanielgberg
- chase-of-the-fjords

## License
This project is open source and available under the MIT License.
