# MovieMania
A one stop application for searching movies of your interest. It includes features like recommendation implemented using cosine similarity algorithm, auto completion along with movie details including genre, release date, runtime, rating, cast, and reviews. 

# Data used
I have fetched data using TMDb api, IMDb dataset and wikipedia. 
I did web scrapping in the IMDb site using  beautifulsoup4 and performed sentiment analysis on those reviews.

# Link to the web app:
https://movie-mania-shruti.herokuapp.com/

# How to run this project:
1. Clone this repository in your local system.
2. Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt.
3. Replace YOUR_API_KEY in both the places (line no. 23 and 43) of static/recommend.js file.
4. Open your terminal/command prompt from your project directory and run the main.py file by executing the command python main.py.
5. Go to your browser and type http://127.0.0.1:5000/ in the address bar.
6. Now you can easily access this website

# How to get the API key
Create an account in https://www.themoviedb.org/ and request for the API key over there

