# Welcome to the Corona Survey ReadMe

## Tech

We are going to need the following:

* React
* Redux
* Express
* Knex.js (SQL)
* React-Router
* Send-Grid

We will create database migrations through knex to create a database. We will use seed files to insert test data into our database.

## User Stories

### Minimum Viable Product

* App needs to be able to show questions
* User should be able to answer questions
* User should be able to see a page that shows all of the results demonstrated in various charts.
* Should be a page with helpful information 

### Stretch and other goals

* Create a user profile
* Repeat survey and see a tracking trend in data
* Sort data by various metrics (such as location, symptom severity)
* **Double Stretch, Hard:** Create a new question and be able to select the way in which it is displayed without code.

## Views 

**base** | description
---|:-:
survey | collects responses and saves them
data | displays data in many different charts (*made of many components*)
info | helpful blurb page
**stretch** | **description**
login | a login page, logins the user in and provides json token
register | creates and stores user profile
profile | shows user data compared over time, can see data by dates and general trends

## Reducers

**name** | **description**
---|:-:
questions | 
results | 

## Actions

**name** | **reducer** | **description**
---|--|:-:
get_questions | question | get all questions (question, answers)
save_answer | answer | save an answer to a question
get_answers | answer |  get all answers to all questions
**stretch** | --- | 
sort_answers | answer | sort all the answers to the questions

## API

Method | Route | Usage | Response 
---|---|---|---
Get | api/v1/questions | Gets all the questions | Gets an array of objects
Get | api/v1/results | Gets ..
**stretch** | --- | --- | ---

## DB



