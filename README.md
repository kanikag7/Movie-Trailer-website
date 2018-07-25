# Movie-Trailer-Website
My project 1 under Udacity Naodegree Program of Full Stack Web Developer I.
A simple movie trailer website project for Udacity's full-stack [nanodegree program](https://in.udacity.com/nanodegree). The project demonstrates the use of a Movie object class in Python to generate a static webpage, which displays a listing of favorite movies and links each movie to its trailers video on YouTube. The project also includes some CSS and jQuery involved in the display of the webpage.

##Table of contents
*Demo
*Quick Start
*Documentation
*Copyright and Licence

##Demo
For a demo, check out [https://github.com/kanikag7/Movie-Trailer-website/blob/master/movie/fresh_tomatoes.html](https://github.com/kanikag7/Movie-Trailer-website/blob/master/movie/fresh_tomatoes.html) !

##Quick Start
After downloading the project files, a movie trailer page can be created by importing media.py and fresh_tomatoes.py at the start of your Python script. Then create idividual Movie objects by calling media.Movie() and supplying it with four arguments -- title,storyline, poster_url, and trailer_url. Lastly, to generate the movie trailers page, call fresh_tomatoes.open_movies_page() and supply it with a list of the movie objects you created.

`import media
import fresh_tomatoes

#information for object arguments
title=Toy Story
storyline=A story of a boy and his toys that come to life
poster_image_URL=http://upload.wikimedia.org/wikipedia/en/1/13/Toy_Story.jpg
movie_trailer_URL=https://www.youtube.com/watch?v=KYz2wyBy3kc

# Create Movie object
 toy_story= media.Movie(title,Storyline, poster_url, trailer_url)

# Create movie trailer page with array of one movie
fresh_tomatoes.open_movies_page([toy_story])`

A more detailed example with multiple movie objects, which is used for the demo, can be found in entertainment_center.py

##Documentation
###Movie Object Class
