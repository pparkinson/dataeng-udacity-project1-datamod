# Project 1: Data Modelling with Postgres

Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. 
They are particularly interested in understanding what songs users are listening to.

In this project, the aim is to complete data modeling with Postgres by creating a Postgres database with tables to optimize queries on song play analysis, creating a database schema and building an ETL pipeline using Python.

# Project Datasets
The project uses the following datasets; song data set and log data set. The data is collected as JSON files.
## Song dataset

## Log dataset

# Database Schema
Using the song and log datasets a star schema is created to query song play analysis.

## Fact table
Table name:   songplays
Table fields: songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent

## Dimension tables
Table name:   users 
Table fields: user_id, first_name, last_name, gender, level

Table name:   songs
Table fields: song_id, title, artist_id, year, duration

Table name:   artists
Table fields: artist_id, name, location, latitude, longitude

Table name:   time
Table fields: start_time, hour, day, week, month, year, weekday
