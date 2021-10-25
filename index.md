# Team Meeting Notes

This website will hold the notes from each meeting.


# Sprint 1 Plan Meeting Notes:

Meeting started September 10th, 2021 at 11:55 AM.

We have decided that unless we are on campus for class, we will meet remotely over Discord. This will allow us to more easily share our screens and talk about code, and also avoid unnecessary trips to and from campus.

* Our meeting times will be Tuesdays, Thursdays, and Fridays during the afternoon, after we have all completed our classes and tasks for the day. 

We will be using a Github workflow in which we make our changes on branches specific to the task we are making changes for, and once that task is complete, merge that branch into master. This way we can link that branch or pull request to our task management software for each task, making it easier to keep track of our workflow. This is also the workflow used in Aislinn's coop experience, and the general consensus is that using the same workflow in this project will be good practice for the future. Also, this way nothing gets committed directly to the master branch and breaks everything on accident.

Griffin did a large chunk of research into potential frameworks, and found that using Angular and Spring would be useful. Angular will make the website frontend much easier to manage, Spring will help with handling database requests, and the combination of the two is well documented in resources online, which allows for an easier time learning how to use them.

* We have decided that for the time being, Griffin and Aislinn will focus on the website and hosting situation while Sam and Evan focus on the android application. 

* We decided that before our first standup, we would each do research into aspects of this project such as frameworks, IDEs, hosting possibilities, and so on. 

* Note: hosting through UA will mean intranet hosting, not internet hosting. This means that if we host anything through UA, we will need to have a VPN or be on campus for testing purposes.

We populated our task management dashboard with some tasks: creating a blank website, creating a blank application, hosting the website somewhere, figuring out button mechanics on the android app, and learning how to set up a redirect if the link is opened on a device with the application installed. These are subject to change, and probably will not take up the entire sprint, so more tasks will be added as necessary.



# Standup Meeting Notes Sprint 1

## September 14th, 2021

### General Notes

* We have collectively decided that Spring/Angular framework is our best option. The learning curve is high, but once we work past that, it should be very useful in our situation.

* We will add another task to our task list in which a basic, empty database is created for testing purposes, since the tasks we decided on during our sprint planning will not take the entire sprint, and the database is the most crucial part of this system.

* We plan to do code reviews as they are needed, partially for sanity checks and partially to share the knowledge of various pieces of the system amongst all four members of the team.

* Github IO should be able to host our website(s) for the time being. 


### Griffin:
* **Has done:** Created the discord, posted some resources for spring, angular, and security related learning.  
* **Will do:** Explore options related to database and database communication.  
* **Challenges:** Nothing quite yet.  


### Sam:
* **Has done:** Research into the frameworks we plan to use.  
* **Will do:** Download and set up Android Studio, try to get a blank application created.  
* **Challenges:** Nothing quite yet, except general lack of knowledge about new frameworks and IDEs.  


### Evan:
* **Has done:** Research into android development and frameworks.  
* **Will do:** More research into android development, download and set up Android Studio.  
* **Challenges:** Nothing quite yet, but little experience with android development.  


### Aislinn:
* **Has done:** Research into web development and frameworks.  
* **Will do:** More research, set up the blank websites necessary for the project.  
* **Challenges:** Nothing quite yet, but little knowledge of web development and frameworks.  



## September 16th, 2021

### General Notes:

* In debating between types of databases, we decided we would prefer to use NoSQL. 

* It might be better to find an external database hosting service rather than try to host through campus and deal with vpns, so that option will be explored.

* We think incorporating Maven into our workflow would be beneficial, and will be exploring that option soon.


### Griffin:
* **Has done:** Researched using Maven to help with project development. Identified possible NoSQL database options.   
* **Will do:** Compile information on environment, framework, and any other necessary project information in a digestible format for other group members to have to reference.   * **Challenges:** hard to get a clear full picture of everything at this point - Working with android side to plan out what would work best with them to begin making decisions. 


### Sam:
* **Has done:** Downloaded android studio and researched android application frameworks.  
* **Will do:** Will connect android studio to our repository and upload a blank android studio project file. Will also research more into frameworks.  
* **Challenges:** Integrating any solutions/frameworks with android studio - very little experience with android studio.  


### Evan:
* **Has done:** Continued research in android frameworks.  
* **Will do:** Refresh on Java language and research how other users implemented Java into their apps.  
* **Challenges:** Still no experience in android frameworks and little knowledge of java.  


### Aislinn:
* **Has done:** Set up project website, meeting notes website, and temporary web app website through Github IO, and populated the meeting notes website with all the meetings to date.  
* **Will do:** Research into database hosting options, since some companies do free hosting of small databases. Research into website hosting for web app, potentially using the same service but unsure of that yet. Install and set up android studio in case needed later.   
* **Challenges:** No experience with database hosting or website hosting, research needed.  



## September 17th, 2021

### General Notes: 

* We have decided to move our scrums from T,Th,F to M,W,F due to the fact that the time between our Thurday and Friday meetings was usually not enough to get much done and having meetings so close together seemed redundant, and having to wait until Tuesday to have a meeting for anything done over the weekend seemed less efficient. We will meet in person on Tuesday and Thursday when necessary for class or for collaboration, but official scrum meetings will be MWF. 


### Griffin: 
* **Has done:**  Created project environment using Spring Initializr utilizing Maven along with other dependencies to aid in development inside the Eclipse IDE with the Spring Tools Suite. Created a sample "Hello World" RESTful service with Spring.  
* **Will do:** Continue to play around with the project to become more familiar with how everything works together, as well as learn about how we will utilize the dev tools to our advantage.  
* **Challenges:** Finding the best way to distribute everything to teammates to get them setup to develop.  


### Sam: 
* **Has done:** Created a skeleton of the android RCV app and uploaded it to the Github repository.  
* **Will do:** Become much more familiar with Android Studio and the languages associated.  
* **Challenges:** Lots of unfamiliar jargon.   


### Evan: 
* **Has done:** Started to refresh Java background knowledge through tutorial online.  
* **Will do:** Work with Sam on figuring out how to implement button functions on his newly created android RCV app.   
* **Challenges:**  Java syntax can be confusing sometimes. Still need to follow along with an Android Studio tutorial, which is unfamilar.


### Aislinn: 
* **Has done:** Looked into database hosting options, found that AWS has a free option up to 20 GB for a year, and MongoDB has a free option up to 5 GB for an unknown amount of time: https://aws.amazon.com/rds/free/, https://www.mongodb.com/pricing. Also made potential (editable) mockups of how the database would look: https://docs.google.com/spreadsheets/d/1NizAbImWRdRm1RSx5LG8OXS0Z7zdzUtlD6RPF9buYmQ/edit?usp=sharing, 
https://docs.google.com/spreadsheets/d/1OJUGnvzLy9wOtFwZa0xpIyH7UvgxE63HRWSI5mbsPNs/edit?usp=sharing. Also updated project website with some basic info and updated scrum notes website to look better.
* **Will do:** Further research into database hosting and general database information, as well as catch up on information about Spring, Maven, REST, and other pieces of the framework.
* **Challenges:** General lack of knowledge about frameworks due to inexperience.



## September 20th, 2021 not finished

### General Notes: 

* We have decided that our meeting times will specifically be 4pm on Mondays and Wednesdays, and 1pm on Fridays. 


### Griffin: 
* **Has done:** Sent out development environment for web application, explored linking ide to github and using AWS to host for production.  
* **Will do:** Add the angular layer to the application, work with Aislinn on integrating AWS into our simple Hello world application  
* **Challenges:** Still looking for a simple solution to incorporate/setup the Github to work with everyone's local development so we can begin posting/pulling etc  

### Sam: 
* **Has done:** Installed the skeleton .apk on my phone and became more familiar with Android Studio and Java.  
* **Will do:** Get button to do something other than default functionality - if server is up then get it to ping the server.  
* **Challenges:** Communication between the app and the server.  


### Evan: 
* **Has done:** Nothing outside of documentation readings and videos for Android Studio.  
* **Will do:** Sit down have a discussion with Sam over the Android app functions and see if I can emulate the app through my computer.  
* **Challenges:** Waiting until the address for the website is set up so that I can begin linking it to the Android app.  


### Aislinn: 
* **Has done:** Added notes to page for last meeting, fixed some formatting errors, did more research into database hosting options and think that AWS is our best option for hosting, partially due to more space, the fact that we wont even need a full year of hosting, and AWS offers more support and has more information for how to run their Db's online.  
* **Will do:** Get my personal environment set up with the new framework and whatnot, set up AWS hosting so that we have a database (if everyones okay with that).  
* **Challenges:** I have never set up a database before, only messed with preexisting things so this will be a learning experience.  


## September 22nd, 2021

### General Notes: 

* We weren't able to get too much done because we were working on the writing assignment most of the last couple of days.


### Griffin: 
* **Has done:** read more advanced material on Spring Development, trying to climb the learning curve.   
* **Will do:** Work with Aislinn on database linking.  
* **Challenges:** I am in open waters at this point with the application, learning curve is high. Also, it is going to be a close call on time if integrating a basic Angular layer by the end of sprint1 is to be completed. Not sure how to approach.  


### Sam: 
* **Has done:** Changed button picture to a plus.  
* **Will do:** Have the button ping the server/Start looking into Spring.  
* **Challenges:** Not familiar with Java - having trouble navigating Android Studio.  


### Evan: 
* **Has done:** Research.
* **Will do:** Start looking over Spring material that had been previously sent over by Griffin. Also waiting to start more work on the Android app.  
* **Challenges:** Spring has a steep learning curve and will not be enjoyable to read over.  


### Aislinn: 
* **Has done:** Research into databases with AWS, set up aws account and began experimenting.  
* **Will do:** Spin up mongodb database with AWS and get credentials all sorted out so that we can link stuff to the database and use it.  
* **Challenges:** AWS is pretty finnicky with managing access to stuff so fighting with that will be fun.  



## September 24th, 2021

### General Notes: 

* We switched from AWS to MongoDB, which is, funnily enough, still hosted through AWS. But now we aren't the ones who have to deal with finnicky AWS stuff.


### Griffin: 
* **Has done:** Gotten everyone up and running with eclipse environment.   
* **Will do:**  Work through the udemy course to see if there’s any functionality we can quickly implement before Tuesday.  
* **Challenges:** Sorting out what we can reasonably accomplish by the end of sprint 1.  


### Sam: 
* **Has done:** Added dependencies for the android app.   
* **Will do:** Connect android app to Spring REST Web API.  
* **Challenges:** Need to learn Spring REST quickly.  


### Evan: 
* **Has done:** Setup Eclipse environment and bought the Spring Class so that research can begin with Spring Interface. Also got connected to MongoDB.
* **Will do:** Work with Sam on getting app connected Spring REST Web API and start reviewing Spring REST sections for the class as well as work on presentation.  
* **Challenges:** Trying to finish up everything before Tuesday.  


### Aislinn: 
* **Has done:** Updated website, added bios to website, updated meeting notes page, worked on presentation, spun up MongoDB database, got eclipse environment set up.  
* **Will do:** Continue to work on presentation, work on connecting mongodb to our setup.  
* **Challenges:** Connecting databases is annoying but shouldnt be too hard.  



## September 27th, 2021

### General Notes: 

* We didn't get as much done this weekend as we had hoped due to personal commitments. The presentation is tomorrow, so we're cutting it close for the demo.
* We decided the best idea would be to show off the fact that our android app can talk with the database. Not sure if our web-app will be able to, due to lack of angular layer as of yet.
* We plan to have a practice presentation either tonight or tomorrow before class in order to work out any problems prior to getting up in front of the class. 


### Griffin: 
* **Has done:**  Successfully connected the spring application to the MongoDb and entered and tested some sample data to confirm functionality. Researched how to get the android side involved for demo purposes.   
* **Will do:** Keep working on understanding how and implementing the method for communication with our spring boot app.  
* **Challenges:** Doesn't look like there's going to be time to get an angular layer done before the demo time.  


### Sam: 
* **Has done:** Helped Evan set up Android Studio and became more familar with Java and the source code.  
* **Will do:** Convert data into JSON, send request and JSON to database.  
* **Challenges:** Sending the request to the database will be a challenge. Not exactly sure how to do so.  


### Evan: 
* **Has done:** Got Android Studio connected to the git and researched into how JSON can connect to Database from app.
* **Will do:** Finish up demo with rest of team members and more specifically finishing up app implementation for demo.  
* **Challenges:** Less than one day to finish and still figuring out what need to be displayed for the demo.  


### Aislinn: 
* **Has done:** Fought with connecting database for way too long unsuccessfully (thanks for getting it working, Griffin).  
* **Will do:** Work on finishing up presentation, work with others on figuring out what exactly we're demoing.  
* **Challenges:** Not much experience with databases, and my personal environment isn't properly set up.  



## September 29th, 2021

### General Notes: 

* We had our presentation yesterday. We feel like we are behind compared to the other teams, and really want to step it up in Sprint 2. 
* Will have planning on Thursday during class time. 


### Griffin: 
* **Has done:** Sprint 1 presentation.   
* **Will do:** Continue evaluating where we were successful and how we can readjust to do more in Sprint 2.  
* **Challenges:** Planning.  


### Sam: 
* **Has done:** Sprint 1 presentation and deliverables.  
* **Will do:** Sprint 1 retrospective and Sprint 2 meeting.  
* **Challenges:** Planning.  


### Evan: 
* **Has done:** Sprint 1 presentation.
* **Will do:** Need to have Sprint 1 retrospective and plan for Sprint 2.  
* **Challenges:** Sprint 2 planning.  


### Aislinn: 
* **Has done:** Did presentation yesterday, did some research into what data needs to be passed to and from database for poll stuff, but that will need to be finalized with a meeting specifically meant for that.  
* **Will do:** Start looking into angular to get that layer figured out, plan out meeting times for Sprint 1 retrospective, Sprint 2 planning, and data stuff.  
* **Challenges:** Planning.  



# Sprint 1 Retrospective: 

### Went Well
* We did a good job keeping up with housekeeping tasks and such
* We were able to hold each other accountable quite well
* We communicated well all thruought the sprint
* We did a good job ding independent research

### Didn’t go well
* We should not have split the team up between android and web app quite yet, since we had to focus on the backend and the android people ended up being left waiting a lot
* We should've decided sooner to tackle pieces of the backend like the database rather than put it off
* We didn't really keep up with our backlog well; we've decided to switch to a different tracker because the one we were using was kind of hard to use

### Challenges
* We weren't really using the backlog, so that led to some confusion on who was supposed to do what and when
* Getting everything connected to spring is a pain
* Spring in general is kind of a pain
* Our initial plan wasn't great in the first place, so working from that led to challenges
* We spent a lot of our time just doing research and figuring out how our backend would work in the first place



# Sprint 2 Plan Meeting Notes:

After doing our retrospective, we have decided to make a few changes to how our team would function:
* We will now use Trello as our task management app.
* We will not have the team arbitrarily split anymore.
* We want to avoid situations where one or more team members are waiting on others to finish work, and as such will organize our tasks so that side work can be done if certain tasks have to wait on completion of other tasks.
* We want to do more peer-programming and group programming, and will work together on tasks more often.

We have populated <a href="https://trello.com/b/aFmcoupn/rcv-app">this Trello board</a> with our backlog, which at this time includes these main objectives (that have been split into smaller tasks): 
* Hosting a website using Heroku with GitHub
* Deciding on exactly what data needs to be passed to and from database
* Adding testing using Postman
* Implementing voting and poll creation functionality in Android App
* Implementing voting functionality in Web App

We hope to have these done for the most part by the end of this Sprint. Thanks to having gotten most of our backend work done in Sprint 1, this should not take too long once we establish connectivity between our backend and our two front ends. 

We felt like we were behind the other teams in terms of functionality, and part of that was due to our planning problems with the first Sprint. This Sprint, we really want to catch up and get as much of the functionality for our applications in place so that during Sprint 3 we can focus on things like look and feel and accessibility. 



# Standup Meeting Notes Sprint 2

## October 1st, 2021

### General Notes: 

* Decided to have data details meeting next week to plan out specifics
* We are using Trello now, and that seems to be working better than PivotalTracker


### Griffin: 
* **Has done:** Worked with aislinn to try to deploy app to heroku, tried to adjust github repository to solve the issues.  
* **Will do:**  Try to recreate the project from local files into a new repository and deply to heroku from there over the weekend.  
* **Challenges:** Deciding to stick with heroku or consider other options.  


### Sam: 
* **Has done:** Setup new project backlog on Trello with Evan.  
* **Will do:** Begin thinking about API.  
* **Challenges:** Not exactly sure how designing the API needs to be approached (Do we need to store local id's for polls? etc.)  


### Evan: 
* **Has done:** Helped Sam set up our new project backlog using Trello. Doing this will help production flow smoother than last sprint.   
* **Will do:** Start working on some of the activities from the project backlog, particularly android tasks or others that I will sign up for.  
* **Challenges:** Need to work sooner rather than later so we get more accomplished this sprint.


### Aislinn: 
* **Has done:** Tried to figure out heroku problems for a while, was unsuccessful. Updated notes page.  
* **Will do:** Continue working to figure out heroku or see if theres another option for hosting, coordinate a time for data meeting because might as well get that out of the way.
* **Challenges:** For some reason Eclipse automatically packages stuff into folders weirdly and heroku doesn't like that.  



## October 4th, 2021

### General Notes: 

* Data meeting is tomorrow (October 5th)


### Griffin: 
* **Has done:** Worked on possible fixes for the heroku deploy issues.  
* **Will do:** Implement Start-from-scratch option to fix heroku before looking for a new hosting solution.  
* **Challenges:** Bit of a hassle to redo everything to get what we have now to work with heroku.  


### Sam: 
* **Has done:** Updated a few Trello cards and designed some API.  
* **Will do:** Get android app to handle example data from https://jsonplaceholder.typicode.com/  
* **Challenges:** Very new to object-oriented code design.  


### Evan: 
* **Has done:** Researching into how controllers work, that might be my task that I pick up along with helping Sam with Android tasks.  
* **Will do:** Do more research into how to implement controller and prepare for data meeting.  
* **Challenges:** Pretty sure we have to figure out other tasks before implementing controllers.  


### Aislinn: 
* **Has done:** Tried to figure out heroku again, failed. Did some learning on how to use angular since I need to know that after we get website hosted anyway.  
* **Will do:** Look at alternatives to heroku if Griffin can't get it to work for website hosting, learn more about angular, prepare for data meeting tomorrow after class.  
* **Challenges:** All of these pieces together make trying to figure out how to put a new piece in kind of annoying.  



## October 6th, 2021

### General Notes: 

* Data meeting was successful; we now have outlines for exactly what data needs to be sent where in calls to and from the database. This will help with implementing the models/controllers/repositories to be used in our applications.
* Griffin and Aislinn both have major exams on Friday, so have to shift focus away from this project for a couple of days.


### Griffin: 
* **Has done:** Got everyone on the same page with what we have to accomplish with the spring app, and how we're going to organize the development.  
* **Will do:** Work on spring app controllers and other related files to be able to start postman'ing and implementing functionality to begin building unit tests.  
* **Challenges:** Busy second half of the week with 2 tests on friday, time has been devoted to other classes.  


### Sam: 
* **Has done:** Attended the data meeting and created the basic outline for our database organization.  
* **Will do:** Continue to work on the android app.  
* **Challenges:** Still unfamiliar with object-oriented code design.  


### Evan: 
* **Has done:** Attended our data meeting and joined new repository, but wasn’t able to get much accomplished after because of a test and lab that I had to finish.  
* **Will do:** Continue to work on controllers and working with Aislinn and or Griffin on how to implement controllers.  
* **Challenges:** Not sure if I need to wait to implement controllers so that they can work with another task, but need to work before other classes take up my free time.  


### Aislinn: 
* **Has done:** Worked on adding angular into framework, god a repo with the website hosted from angular in existence and added angular project to our main repo, but havent connected it to springboot app yet via dependencies and stuff.  
* **Will do:** Continue work on angular stuff, but wont be able to do a whole lot because exam on friday and I plan to pivot to focus on that for the next couple days, but by Friday afternoon I can pivot back to this.  
* **Challenges:** Lots of pieces that interact strangely with each other.  



## October 8th, 2021

### General Notes: 

* Short meeting; not much was done since the last one. 


### Griffin: 
* **Has done:** Studied the sample repository to begin working on spring app services and modelling.  
* **Will do:** Get enough laid out to begin postman'ing.  
* **Challenges:** Time constraints.  


### Sam: 
* **Has done:** Researched object-oriented code design by downloading and examining example projects.  
* **Will do:** Work on the android app.  
* **Challenges:** Same challenges.  


### Evan: 
* **Has done:** Researched structure and function of controllers and how to use them in our system.  
* **Will do:** Start implementing controllers into Eclipse.  
* **Challenges:** Still confused on controller syntax and where to implement.  


### Aislinn: 
* **Has done:** Researched angular, had to pause to study for exam.  
* **Will do:** More angular stuff for web frontend stuff and getting that connected to backend.  
* **Challenges:** Same old, same old.  



## October 11th, 2021

### General Notes: 

* There are some nasty sicknesses going around school right now; affecting productivity. 
* We decided that instead of having one person focus on all of the controllers, another on all the models, etc. we will split it up so that each person working on this area has their own whole pipeline to follow through on (ie. someone works on the user controller, model, and repository; someone else works on the creator controller, model, and repository, etc.) to avoid having hangups waiting on others to complete sections of work so much.


### Griffin: 
* **Has done:** Skeleton'd and stubbed out my local version for most of the services and models.  
* **Will do:** Get a test case dreamt up as a goal to achieve as functionality checkpoint.  
* **Challenges:** Will have to study between now and the next meeting for a test on that day.  


### Sam: 
* **Has done:**  Located an android studio tutorial that I'm going to go through.  
* **Will do:** Do the tutorial and see if I can make good progress on the app.  
* **Challenges:** Tutorial is long.  


### Evan: 
* **Has done:** Started implementing in Eclipse functionality for controllers.  
* **Will do:** Finish controller modules.  
* **Challenges:** Syntax still catching me off guard, need to look more into syntax.  


### Aislinn: 
* **Has done:** Researched a little bit of angular, was sick so slept most of the weekend and wasn't able to do much.  
* **Will do:** Get front end fully integrated and some sort of functionality in place to prove connectivity to database.  
* **Challenges:** Same old challenges.  



## October 13th, 2021

### General Notes: 

* We decided to set a hard deadline for end to end connectivity to be October 15th at 1pm, in order to spend next week knocking out as much functionality as possible before the end of the Sprint.
* We are going to have a peer-programming session tomorrow during class-time.


### Griffin: 
* **Has done:** Continued work on spring boot from last week.  
* **Will do:** Peer coding session tomorrow for team meeting - must prepare for that.  
* **Challenges:** Had to reconsider the development approach and adopt a new one other than how we initially had assigned the tasks.  


### Sam: 
* **Has done:** Worked through some of the android studio tutorial.  
* **Will do:** Demonstrate basic connectivity from the android app all the way to the database.  
* **Challenges:** XML is a harder language than anticipated.  


### Evan: 
* **Has done:** Worked on User pathway (Controller, Repository, Model, etc.)  
* **Will do:** Continue working on that pathway.  
* **Challenges:** Need to review tutorials on how Springboot works with angular and mongodb api.  


### Aislinn: 
* **Has done:** Worked on angular, got snagged on our current project structure but should be able to fix that now that I've touched base with Griffin on it.  
* **Will do:** Finish this tutorial and hopefully have connectivity through from database to angular app.  
* **Challenges:** There are a lot of little pieces that are annoying.  



## October 15th, 2021

### General Notes: 

* Aislinn was able to display end to end connectivity between an angular frontend and the database, so now the rest of the team can move forward with various pieces such as the user pipeline, voter pipeline, poll pipeline, android app, and angular app. 


### Griffin: 
* **Has done:** Had to fight dependency bugs which took up so much time in order to get the mapstruct dependency working for DTO implementations.  
* **Will do:** Continue to try to tackle the problems in the code that are preventing my poll DTO from being filled correctly.  
* **Challenges:** Had to fight dependency bugs which took up so much time in order to get the mapstruct dependency working for DTO implementations.  


### Sam: 
* **Has done:** Got android app to work with example code from https://jsonplaceholder.typicode.com/posts.  
* **Will do:** Get android app to work with local instance of Spring and work on UI.  
* **Challenges:** Android Studio UI has not been cooperating.  


### Evan: 
* **Has done:** Created user repository, model, and little of controller, service and implementation.   
* **Will do:** Finish tasks listed as halfway done and compile them so that they are ready for testing.  
* **Challenges:** Have to overcome some maven issues that are similar to what Griffin had to deal with.  


### Aislinn: 
* **Has done:** Followed tutorial, got end to end connectivity but its only locally hosted as of right now, will have to research how to host a whole springboot app somewhere (the angular gets hosted just fine, but without the rest of the springboot app it doesn’t actually do anything) but now we can run and test end to end stuff locally, so we can work on controllers/models/repositories and stuff as well as angular UI and stuff for the webapp. Also updated project notes website.    
* **Will do:** Work on making an angular frontend that is actually applicable to our app using this as a reference; look into hosting options for full springboot apps.  
* **Challenges:** We previously already had a lot of problems with Heroku, but it still seems like the best option unfortunately.    



## October 18th, 2021

### General Notes: 

* Going to have a peer programming session on Thursday to work through some of these pieces.


### Griffin: 
* **Has done:** Implemented vote pipeline, started to begin testing.  
* **Will do:** Iron out any bugs that may pop up when i finish testing and begin creating test unit cases from the functionality we have.  
* **Challenges:** Have to get enough of this done in time for Aislinn to have enough time to work on Angular.  


### Sam: 
* **Has done:** Designed some of the UI.  
* **Will do:** Implement the design and get Spring working.  
* **Challenges:** Not very familiar with Spring yet.  


### Evan: 
* **Has done:** Finishing up on user pipeline  
* **Will do:** Commit changes and begin testing.  
* **Challenges:** Time management so that Aislinn has enough time to work with the results.  


### Aislinn: 
* **Has done:** Worked on frontend angular stuff, integrating a tool that'll make it easier to put modules in but running into some versioning issues.  
* **Will do:** Continue working on frontend, once I have some stuff to connect through to ill work on adding actual functionality.  
* **Challenges:** Angular is dumb.  



## October 20th, 2021

### General Notes: 

* The tool that would have been used for the Angular app is incompatible with Springboot, so that option is out the window and progress is lost on the angular frontend.


### Griffin: 
* **Has done:** Polished some vote and poll code to do more in depth testing.  
* **Will do:** Consider how much RCV-specific functionality can be implemented on top of our base polling system in time for the presentation.    
* **Challenges:** Creating full unit tests with sample data: not sure when to stop adding functionality and when to switch over to testing it.  


### Sam: 
* **Has done:** Updated dependencies and worked on the Android App.  
* **Will do:** Get basic functionality working - not worrying about looks yet.  
* **Challenges:** Lots of warnings.  


### Evan: 
* **Has done:** Prepared for Peer Programming session tomorrow.    
* **Will do:** Conduct session tomorrow and hopefully have everything needed for sprint 2 working by tomorrow or by the end of the weekend.  
* **Challenges:** Deadline for Sprint 2 closing in.  


### Aislinn: 
* **Has done:** Worked on angular.   
* **Will do:** Work on angular.  
* **Challenges:** Angular.  




## October 22th, 2021

### General Notes: 

* We have the weekend to work on the project, hopefully we can get a lot done during that time. 


### Griffin: 
* **Has done:** Continued working on integrating poll, vote, and user together. Added the RUD of crud for polls.  
* **Will do:** Edit models' structure to match what comes from the android app.  
* **Challenges:** Still haven't gotten to writing tests: concerned with getting angular connected.  


### Sam: 
* **Has done:** Got example POST request to work and added create poll page.  
* **Will do:** Get poll creation to work with the spring rest api.  
* **Challenges:** Still unfamiliar with Spring Rest.  


### Evan: 
* **Has done:** Pushed initial version of User Pipeline.    
* **Will do:** Test and complete pipeline.  
* **Challenges:** Eclipse is still really weird to work sometimes.  


### Aislinn: 
* **Has done:** Worked on angular.   
* **Will do:** Work on angular.  
* **Challenges:** Angular.  



## October 25th, 2021

### General Notes: 

* The presentation is tomorrow, and unfortunately we don't have as much functionality as we want. 
* We will all be working for a large portion of time to get this done tonight to be ready for the presentation tomorrow.


### Griffin: 
* **Has done:** Working on getting a valid build together with all the user stuff included. Working with Aislinn to get Angular connected.  
* **Will do:** Angular first, then unit tests.  
* **Challenges:**  running into what seems to be pure configuration issues where our Angular is not running with our server so our paths are only leading to 404's.  


### Sam: 
* **Has done:** Added error checking and flushed out create poll page.  
* **Will do:** Just need to get the POST request to work with the spring rest api - will also work on sprint 2 presentation.  
* **Challenges:** Still unfamiliar with Spring Rest.  


### Evan: 
* **Has done:** Finished User Pipeline.   
* **Will do:** Create and finish the Sprint 2 Presentation.  
* **Challenges:** Upcoming presentation tomorrow.  


### Aislinn: 
* **Has done:** Worked on angular.   
* **Will do:** Work on angular.  
* **Challenges:** Angular.  
