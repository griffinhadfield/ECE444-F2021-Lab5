# Griffin Hadfield ECE444 Lab 5
This repo is a clone of https://github.com/nelaturuk/education_pathways

## Activity 1 

Image showing the repo was cloned to my github account:
![image](https://user-images.githubusercontent.com/38739044/137636538-be1c5683-df35-4439-841f-cfdd17e5d0d1.png)

## Activity 2-5
Home page:
<img width="1920" alt="Screen Shot 2021-10-17 at 4 22 37 PM" src="https://user-images.githubusercontent.com/38739044/137643634-b3a4bd61-d4eb-44ed-baad-1691a7940960.png">


Results Pages:
<img width="1918" alt="Screen Shot 2021-10-17 at 4 23 17 PM" src="https://user-images.githubusercontent.com/38739044/137643636-b3912a58-6483-46f4-a5b7-fde2c776a13c.png">
<img width="1920" alt="Screen Shot 2021-10-17 at 4 23 21 PM" src="https://user-images.githubusercontent.com/38739044/137643637-9ab43b03-56bc-4473-9b70-86f616d9e6c4.png">

## Activity 6

The main change between the old UI and the updated UI shown above is the improvement in the distinction between elements. The better seperation between elements is especially clear in the "results" section. The addition of row and column lines to the table, as well as improved text alignment, makes it much more easy to tell which information pertains to which coloumn/row heading. Even the sepearation between the search controls and the results improves usability. 

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
