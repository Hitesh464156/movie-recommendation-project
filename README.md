# movie-recommender-system-tmdb-dataset
A content based movie recommender system using cosine similarity
# Movie Recommender System

This project is a movie recommender system built using cosine similarity.

## Project Structure

* `app.py`: The main application file that runs the Streamlit app.
* `model/`: Directory containing the pre-trained model and similarity matrix.
	+ `movie_list.pkl`: Pickled list of movie titles.
	+ `similarity.pkl`: Pickled similarity matrix.
* `requirements.txt`: List of dependencies required to run the project.

## Dependencies

* `streamlit`: Used to build the web app.
* `requests`: Used to fetch movie posters from The Movie Database API.
* `pickle`: Used to serialize and deserialize the model and similarity matrix.

## How to Run

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the application using `streamlit run app.py`.

## Note

This project uses the MovieLens dataset and The Movie Database API to fetch movie posters.
