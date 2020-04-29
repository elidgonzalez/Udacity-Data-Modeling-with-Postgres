# Udacity-Data-Modeling-with-Postgres

## Purpose 

In this first project the goal is to provide a database for library songs playing currently. From this Database, the users, songs, artist of song, and time played can be extracted. This allows for simple analysis of users using a music service to play. In addition to monitoring this information could be used to control or limit the amount of being played such as for free rather than paid user.

## Schema and ETL pipeline

The overall structure of this a star schema. In this case the songplays table was the fact table that all the dimension tables centered around. These tables were the users, songs, artists, and time tables. It was from the songplays table that all the data could be extracted from. For example to join all the tables and see all the columns you would join by song_id, user_id, artist_id, and start_time. With this the songplays table which contained songs that were played could be used to extract the particular. 

## Examples:
See **etl.ipynb**.
