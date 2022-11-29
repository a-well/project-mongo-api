# Project Mongo API

Practicing RESTful routing and using MongoDB.

## The problem

Describe how you approached to problem, and what tools and techniques you used to solve it. How did you plan? What technologies did you use? If you had more time, what would be next?

## Endpoints

/songs to get a list of 10 songs, ranked by popularity. Results include track id, track name, artist name, genre, danceability and bpm.

/songs/:id to see a song with a specific id (e.g. songs/6384e9c585fc0c8b6190c7b2)

/songs?danceability=70 get songs with danceability rating of 70

/songs?popularity=89 get songs with popularity rating of 95

/songs?bpm=95 get songs with bpm of 95

/songs?genre=pop get songs with pop as genre

## View it live

https://project-mongo-api-jo5tvass7a-uc.a.run.app/