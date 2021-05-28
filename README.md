# DataEngineering
This project fetches "Recently Played Tracks" from using Spotify API, cleanse, transform and Load the data to a database and schedule the pipeline to run once a day. 

API Link: 	https://developer.spotify.com/console/get-recently-played/?limit=50&after=0&before= \
Language: Python (pandas, requests, json, datatime, psycopg2, dag) \
Database: Postgres \
Orchestration: Airflow \
Dependency: Spotify premium account needed - API token will expire in a day hence need to refresh the token manually.
