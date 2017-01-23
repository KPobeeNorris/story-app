## Story App

Background
-----

Whilst at Maker's Academy we were given the opportunity to have a practice project week ahead of the final project.  There was an initial idea session where everyone had the chance to throw out suggestions for projects, and 10 seconds to very briefly explain the idea.  At this point all the ideas were put into a form and we were able to vote/choose which projects we wanted to work on.  

My team (Contributors details are at the bottom of the page) were chosen to work on a web app that helped children develop skills around sentence construction.  The idea and project developed over the course of the week and resulted in a web app that presented the child with a short story with a number of gaps in it, for the child to chose from the word options provided, so they could create their own final version of the story.  

As it was aimed at younger children we wanted to make sure the design was simple, but interesting and eye catching.  The app incorporates the addition of cartoon animals that appear on the screen once the child had chosen these as part of the story.  In addition to this we plugged in a sketch pad at the bottom of the story so the child could have the option of drawing their own interpretation of the story as they went along.

Instructions
------
* Git clone https://github.com/KPobeeNorris/story-app.git
* Node - If not already installed, you will need to type 'brew install node' into the command line
* Once complete type 'npm install' to ensure all relevant dependencies are downloaded.

* To run the app from the command line type node ./bin/www and navigate to localhost:3000 in the browser of your choice

![story app screenshot](https://cloud.githubusercontent.com/assets/20423761/22204954/a918a72e-e16c-11e6-9f52-a9c3d5d58fa3.png)


Tests
-----
In a previous week of our Maker's course we had been challenged to write our own test suites.  As such the team decided that it would like to get a greater understanding of this concept and chose to write our own tests for this project.  The tests themselves can be viewed in spec/StorySpec.js.  Whilst there does not appear to be many tests we iterated over the process again and again as the project developed and as a result got rid of redundant tests as necessary.  

To see the tests run you simply need to navigate to your localhost:3000 page and choose to 'inspect' the page.  From the options that appear when the side panel opens select the 'console' tab and it will display the passing tests.

User Stories
------
```
As a child  
so I can complete a sentence,  
I can click and select a word.  

As a child  
so I can make a sentence from scratch,  
I can click and select a word at a time from an array of words.  

As a child  
so I can see the points I have scored,  
I can click the submit button when I have finished my sentence.
```

Contributors:
[Blanca Mendizabal Perello](https://github.com/groundberry) | [Katy McCann](https://github.com/Katy600) | [Akram Rasikh](https://github.com/AkramRasikh)
