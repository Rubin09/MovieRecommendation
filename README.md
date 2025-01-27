# Movie Recommendation System

This is a **Streamlit-based Movie Recommendation System** that suggests movies to users based on the selected title. The project uses a content-based filtering approach, leveraging movie metadata and cosine similarity to recommend similar movies.

---

## Features

- **Interactive User Interface**: Select movies from a dropdown menu and view recommendations instantly.
- **Content-Based Filtering**: Uses movie metadata like genres, cast, crew, and tags to find similar movies.
- **Efficient Recommendation Engine**: Powered by cosine similarity for fast and accurate recommendations.
- **Data Preprocessing**: Prepares and vectorizes movie data using Scikit-learn's `CountVectorizer`.
- **Saved Model**: Precomputed similarity matrix stored using `pickle` for quick retrieval.

---

## Technologies Used

- **Python**: Core language for implementation.
- **Streamlit**: Framework for building the web-based user interface.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For vectorization and cosine similarity calculations.
- **Pickle**: For model and data persistence.

---

## Installation and Setup

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- Streamlit
- Required Python libraries (`pandas`, `scikit-learn`, `pickle`, `numpy`, `requests`)

### Steps to Run Locally

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Rubin09/MovieRecommendation.git
   cd MovieRecommendation
