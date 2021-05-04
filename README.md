# Budget-Records-anytime-anywhere
# Workout_Tracker - [workout-records](https://budget-anywhere-anytime.herokuapp.com/)

## Table of contents
- [Description](#Description)
- [User Story](#User/Story)
- [Usage](#Usage)
- [Framework HTML/JS](#Framework)
- [Credits](#Credits)

## Illustration

![sampleReadme](/public/pictures/app-Illustration.gif)

## Description

The user will be able to add expenses and deposits to their budget with or without a connection. 
   
## User/Story  
```md
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```

## Usage

* Visit [budget-anytime](https://budget-anywhere-anytime.herokuapp.com/)

* Offline Functionality:
    * Enter deposits offline

    * Enter expenses offline

* When brought back online:

  * Offline entries should be added to tracker.

## Framework

#### JavaScript(back-end) and public Html/CSS

  * MongoDB used to store data
    * IndexedDB used to store/cache data offline 
        ```
        once it's getting offline, data is going to be stored/cached into the browser memory

        ```
    * service-worker 
        ```
        service-worker.js file follows specific files to cache and event listeners/triggers that don't need user interaction
        * self.addEventListener

        ```

## Directory
* [GitHub Source](https://github.com/VictorCodrean/Budget-Records-anytime-anywhere)

## App link
Victor Codrean    
*  [workout-records/app link:](https://budget-anywhere-anytime.herokuapp.com/)


Asking me any questions:

<a href="mailto:codreanvictor@gmail.com" style="text-decoration:none"><img height="20" src = "https://img.shields.io/badge/Gmail-c14438?&style=for-the-badge&logo=gmail&logoColor=white&style=plastic"></a>

[<img height="20" src="https://img.shields.io/badge/-GitHub-black.svg?&style=for-the-badge&logo=github&logoColor=white&style=plastic"/>](https://github.com/VictorCodrean)


