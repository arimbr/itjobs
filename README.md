# Analyzing IT jobs data

I believe jobs data can be used to help students choose which technologies to learn.


## Dataset
* The data has been scraped from Stack Overflow Careers
* Tha data is saved in a file 'data.jl' with a job in JSON format for each line
* The data contains information about the job title, tags selected by the employer, date scraped, location, employer and job description

## Modelling
* The relationship between jobs and tags can be represented as a Python Pandas DataFrame 
* The data can be loaded into MySQL/PostgreSQL to build a job or tag recommendation system
* The data can also be loaded into MongoDB

## Analizing
* It is possible to study the similarity/correlation between different tags
* It is possible to extract the job requirements from the job description
* It is possible to run NMF algorithm on the job descriptions to identify topics
* It is possible to run KMeans or other clustering algorithms on the data to identify job clusters based on the tags

## Data product
* A web visualization of the relationships between tags
* A web visualization of the relationships between jobs
* A web application that allows students to interact with the data, selecting tags and showing them statistics about the jobs they would have access to, and recommending them which technologies to learn based on their past choices and the relationships between tags 
