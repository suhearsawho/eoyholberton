# Job Odyssey

<a href="https://jobodyssey.com">
    <img src="https://i.imgur.com/Z9dBwqq.png" alt="jobodyssey" title="JobOdyssey">
</a>

[Job Odyssey](https://jobodyssey.com) is a web application that is designed to gamify and organize your job search! Job Odyssey is specifically designed for
software engineers, with features to fit the software engineer job application process.
To achieve this goal, Job Odyssey provides a unique reward and currency system that is designed to re-energize your job 
search. Users can generate currency by performing certain actions - such as saving a job post, applying to jobs, and 
updating the status of previously applied jobs.

## Table of content

- [The Story](#the-story)
- [Getting Started](#getting-started)
- [Screenshots](#screenshots)
- [Features](#features)
    - [Github OAuth](#github-oauth)
    - [Job Search](#job-search)
    - [Add Applied](#add-applied)
    - [Applied Jobs](#applied-jobs)
    - [Rewards](#rewards)
- [Built With](#built-with)
- [Future](#future)
- [Authors](#authors)
    - [Christopher Choe](#christopher-choe)
    - [Susan Su](#susan-su)
- [Acknowledgments](#acknowledgements)

## The Story



## Getting Started

Access it on jobodyssey.com and create an account today!
* Must have a github account to use Job Odyssey
* To explore features with logging in, check out [Features](#features)

## Screenshots

<img width=50% src="https://i.imgur.com/i1Q9COP.png">

<img width=50% src="https://i.imgur.com/4xbKtA1.png">

<img width=50% src="https://i.imgur.com/6mkexPV.png">

## Features

Job Odyssey has features that can be found through our dropdown navigation bar menu.

<img width=50% src="https://i.imgur.com/h9BlAQx.png">

These features will be explored below!

<img width=50% src="https://i.imgur.com/SohetrC.png">

### **GitHub OAuth**

Job Odyssey handles user authorization through the Github OAuth. In order for
user data to be more secure, users are handled completely through authorization by Github. If you would like to logout, the authorization token will be erased but to have a completely separate user experience you will have to logout of Github as well.

<img width=50% src="https://i.imgur.com/4xbKtA1.png">

### **Job Search**

This job search feature used the Github Jobs API to search for a job based on user input parameters. The heart button on the left side will save the job as a job interested where pressed and delete it from jobs interested if pressed again.
The message icon on the right side of the listing is a link which will open a new window of the url to the actual job listing.

<img width=75% src="https://i.imgur.com/aTtDNRo.png">

### **Add Applied**

This form will allow a user to add an applied job to their list of applied jobs. The company, position, address, and date applied are mandatory fields while the drop down forms like language can be manipulated by clicking on one to add, and clicking again to remove the specific option (e.g. click on C and Python to add both, click again on C to remove). 

<img width=75% src="https://i.imgur.com/hwcvTMM.png">

### **Applied Jobs**

Jobs applied will be listed on this page with the ability to edit and delete the listing. This allows for updates on the status, notes, or any other information you would like to change later.

<img width=75% src="https://i.imgur.com/Hfftp3R.png">

This export to csv button allows you to see your applied jobs in a csv format. This can be saved and imported into excel or google sheets to have a better organized listing of all jobs applied.

<img width=75% src="https://i.imgur.com/tRFWRc2.png">

### **Rewards**

This rewards feature is a slot machine like spinner which will choose from a constructed group of ten possible rewards. The rewards are populated based on a rarity scale with each color representing a different rarity. The rewards are currently Holberton peers and staff but plans are to make them more general in the future. Each roll is 30 coins and repeats are not added to your total list of rewards. Check the home page to see which rewards you have won!

<img width=75% src="https://i.imgur.com/RRwTdoV.png">

## Built With
* [Python](http://www.python.org) - The Backend Language
* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - The Frontend Language
* [Flask](http://flask.pocoo.org/docs/1.0/) - The Web Development Framework
* [SQLAlchemy](https://www.sqlalchemy.org/) - Python SQL Toolkit and Object Relational Mapper
* [MySQL](https://mysql.com) - Relational Database Management System
* [React](https://reactjs.org) - Javascript Library
* [Material UI](https://material-ui.com) - Pre-Built React components

## Future

There are plenty of features that we would love to implement into Job Odyssey.
Adding more Job Search APIs (which mostly require approval) and allowing for the listing of those favorited jobs would be one towards the top of the list. Work is also being put into making
the view and formatting of the applied jobs easier to navigate and explore. Along with this, adding more features to keep users motivated and engaged such as alerts and notifications as well as more game features are currently being worked on. A community feature with a multiplayer aspect was also a consideration that we are looking into for the future.

If you have any suggestions or would like to contribute to Job Odyssey, please contact either of us.

## Authors
### **Christopher Choe** - [christopherchoe](https://github.com/christopherchoe)

    Chris hopes to be a backend software engineer, working on the database and REST API for the most part with some fingerprints in the frontend in order to better understand and integrate the backend into the whole picture.

### **Susan Su** - [suhearsawho](https://github.com/suhearsawho)
    
    Susan is an aspiring full stack software engineer who enjoys both backend work and frontend work, taking charge of the design and React portions of Job Odyssey while still being heavily involved in the backend database and API work as well. 
    
If you would like to contact [Susan](https://suhearsawho.github.io/) or [Chris](https://christopherchoe.github.io) about any opportunities, feel free to reach out!


## Acknowledgements
* Holberton School (Staff and Students)
* Cats
* Cafes
