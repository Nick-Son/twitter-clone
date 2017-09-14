# README

# Database(DB)
## ERD (Entity Relationship Diagram)
![erd diagram](/docs/images/erd.jpg)

# DB Tables
I made 3 tables for the app, User, Tweet and Profile. User stores the suer information like password etc. Tweet stores the information message that a user tweets and the Profile tables stores infomation about the user. Each user has one profile, and many tweets.

## User
- ID
- email
- password

## Profile
- ID
- user_id (belongs_to)
- first_name
- last_name
- avatar
- country

## Tweet
- ID
- user_id (belongs_to)
- message

# Pages
## homepage
- tweets on page
- log in/ log out

## tweet show page
- see tweet
- edit tweet (if logged in)

## profile page
- first_name, last_name
- tweet count
- avatar
- country
- ability to edit

