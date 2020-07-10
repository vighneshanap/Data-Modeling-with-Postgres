# Data-Modeling-with-Postgres
In this project, we’ll model user activity data for a music streaming app called Sparkify. We’ll create a relational database and ETL pipeline designed to optimize queries for understanding what songs users are listening to. In PostgreSQL we will also define Fact and Dimension tables and insert data into your new tables.

songplay(this is fact_table) - songplay_id has songid as a primary key. songplay is a fact_table since it stores the metric for business processes. 

user(dim_user) - user_id as a primary key.

song(dim_song) - song_id is primary key since there should only one song must be present in the song table

artist_table_create(dim_artist) - artist_id is primary key since there should only one artist in the table

time(dim_time) - start_time is a primary key since its the timestamp which can let us query on time tabel
