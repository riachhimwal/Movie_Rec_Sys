# Movie Recommendation System

## Overview
The **Movie Recommendation System** is a content-based filtering application that suggests movies similar to the one selected by the user. It utilizes **Scikit-learn**, **Pandas**, and **NumPy** for similarity calculations and **Streamlit** for the user interface.

## Features
- Search for a movie from a dropdown menu.
- Get five recommended movies based on similarity.
- Display posters of recommended movies.
- Interactive UI using **Streamlit**.

## Technologies Used
- **Python**
- **Streamlit** (for UI)
- **Scikit-learn** (for similarity calculation)
- **Pandas & NumPy** (for data handling)
- **Pickle** (for model storage)
- **Requests** (for fetching movie posters)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommender-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd movie-recommender-system
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```
2. Select a movie from the dropdown.
3. Click on **Show Recommendation** to get five similar movies with their posters.

## File Structure
```
movie-recommender-system/
│── model/
│   ├── movie_list.pkl      # Pickle file containing movie data
│   ├── similarity.pkl      # Pickle file storing similarity matrix
│── app.py                  # Main Streamlit app
│── requirements.txt        # Dependencies
│── README.md               # Project documentation
```



## Dependencies
The required Python libraries are listed in `requirements.txt`:
```
streamlit
pandas
numpy
scikit-learn
requests
pickle-mixin
```

## Future Enhancements
- Implement **collaborative filtering** for better recommendations.
- Add user authentication to save preferences.
- Improve UI with better visuals.
- Deploy on a cloud platform (Heroku, AWS, etc.).

## License
This project is open-source and available under the **MIT License**.

## Acknowledgments
- **Scikit-learn** for similarity computation.
- **Streamlit** for creating an interactive UI.

