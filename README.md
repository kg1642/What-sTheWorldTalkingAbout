

## About

What's the World Watching Right Now presents you with the current most popular movies of the world with corresponding reviews by New York Times. Two Web Apis were used for this project. Information about movies was collected from [MovieDB](https://developers.themoviedb.org/3) api while reviews were collected from [New York Times Api](https://developer.nytimes.com/movie_reviews_v2.json). The movies are represented by circles. The size of the circle represents the popularity of the movie. The bigger the size of the circle the more popular the movie is. If you hover on the circle it expands and displays the name of the movie. If you click on it, it expands further and shows you a short description of the movie with a link to its review in New York Times. 

The project is supposed to be interactive and you are encouraged to play around with the circles. The circles can also be dragged. Have fun!

![alt text](https://github.com/kg1642/WhatIsTheWorldWatchingRightNow/blob/master/public/images/Screen%20Shot%202018-10-07%20at%2011.37.40%20PM.png "WebApp at a Glance")
![alt text](https://github.com/kg1642/WhatIsTheWorldWatchingRightNow/blob/master/public/images/Screen%20Shot%202018-10-07%20at%2011.38.00%20PM.png "Hovering on a circle")
![alt text](https://github.com/kg1642/WhatIsTheWorldWatchingRightNow/blob/master/public/images/Screen%20Shot%202018-10-07%20at%2011.38.28%20PM.png "Clicking a circle")


## Motivation and Process
The first time I saw a bubble graph I was amazed by how great it is for data representation. Therefore, I wanted to use the bubbles in some form to represent some data. I love movies and try to find time to watch most of the latest popular movies. So, I decided to use bubbles to represent movies. A little bit reseach and I found the MovieDB database. I decided to use the circle size to represent the popularity of the movie. However, the users want to know more about the movie then just the name. So, adding the description and the reviews were the normal next steps. 


## Design Decisions

As mentioned earlier I am fascinated by bubbles. So, I always wanted to use bubbles to represent data and What's the World Watching Right Now was a perfect way to do so. Some of the other active design decisions took are background image and fonts. I wanted to go for a old filmy vibe. Therefore, I chose an backgroung image that has an old projector that projects light to the bubbles of movies. The font was is also stressed and I felt it looked antique and old. 

## Resources

1. [MovieDB Api](https://developers.themoviedb.org/3)
2. [New York Times Api](https://developer.nytimes.com/movie_reviews_v2.json)
3. [Nau Technologies] (https://naustud.io/tech-stack/) - The graph presented in this website provided me guidance. 
4. D3 

## Major Chanllenges
Most of the challenges I faced were learning the nuances of javascript and learning to work around its asynchronous nature. Similarly, I had to spent a lot of time understanding how to use D3. There were not any specific challenges but a lot of small ones which for most part were javascript nuances. 

## Next Steps:

The next steps for this project would be to include option for the user to choose a region and genre of the movie. This would give users options to get information about they care about. Also, the website is not well optimized for smaller screens. Making it well optimized it for all screen sizes is necessary before putting it online. 
