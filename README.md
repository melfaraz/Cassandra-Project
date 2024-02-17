# Cassandra-Project

This Udacity Data Engineering nanodegree project entails the creation of an Apache Cassandra database named sparkifyks tailored for Sparkify, a music app. 

## The primary objective of this NoSQL database is to facilitate queries related to song play data. The data model is structured to accommodate the following queries:

### 1. Give me the artist, song title and song's length in the music app history that was heard during sessionId = 338, and itemInSession = 4
   Faithless Music Matters (Mark Knight Dub) 495.30731201171875 <br>
   for sessionId=338 and itemInsession=4, the artist name is 'Faithless', and the song is 'Music Matters (Mark Knight Dub)' with a length of 495.307312 seconds.
### 2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182

for userId=10 and sessionId=182, Sylvie Cruz listened to 4 songs:<br>
- Keep on Keepin On by Down To The Bone <br>
- Greece 2000 by 'Three Drives<br>
- Kilometer by Sebastien Tellier<br>
- Catch You Baby (Steve Pitron & Max Sanna Radio Edit) by Lonnie Gordon.<br>
### 3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'
Following user names were listening to the All hands againt his own song:<br>
Jacqueline Lynch <br>
Tegan Levine <br>
Sara Johnson <br>

## Project Steps
- Modeling your NoSQL database or Apache Cassandra database<br>
- Build ETL Pipeline
