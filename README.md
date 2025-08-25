# Book Recommendation System

This project is an advanced **content-based book recommendation system** built using Python, pandas, and a pre-trained NLP model. The system provides book recommendations by analyzing the content of the books themselves, rather than relying on user behavior.

## Technologies Used

* **Python**: The core programming language for the project.
* **Pandas**: Used for efficient data manipulation and cleaning.
* **Sentence-BERT**: A powerful pre-trained NLP model for converting text into meaningful numerical representations (embeddings).
* **Scikit-learn**: Used for the machine learning components, specifically the `NearestNeighbors` algorithm.
* **PyTorch**: The deep learning framework that powers the Sentence-BERT model.

## Key Features

* **Advanced Feature Engineering**: The system combines numerical features (ratings, ratings count) with dense, high-dimensional text embeddings to create a comprehensive profile for each book.
* **Semantic Search**: Utilizes the NLP model to perform a semantic search, enabling recommendations for books with similar themes, genres, or writing styles.
* **Interactive Tool**: The script includes a continuous loop that prompts the user for a book title, providing a real-time, interactive experience.
* **Robust Input Handling**: The search function is robust and forgiving, allowing for case-insensitive and partial-title searches.

## How to Run

1.  Ensure you have the `books.csv` dataset in the same directory as the script.
2.  Install the necessary Python libraries by running:
    `pip install pandas scikit-learn sentence-transformers torch`
3.  Execute the Python script from your terminal or a Jupyter notebook.
4.  Follow the on-screen prompts to enter a book title and receive recommendations.
