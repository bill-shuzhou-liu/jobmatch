# jobmatch
The app to help find out a job by matching the job description and the resume. 

## Collect the job data
Use the scaper to download job description data from web,  [indeedscrapper](https://github.com/bill-shuzhou-liu/indeedscrapperlatest), the job summary is stored at the jobs_1.csv and details at data/ folder. 

## Preprocessing the data
Use the minhash to filer out duplicate jobs. 

Using the [NPL](https://resources.workable.com/natural-language-processing-engineer-job-description) to process the job data. 

Save the data into the sqllite

## Setup web app
Using the [pythonanywhere](https://www.pythonanywhere.com/) to host the django webapp. 

Paste the job description and your resume in the web page to get the score of the match. 

The app can also track what job you applied, and what resumse you used. For a new job, whether it is a duplicate jobs. 
