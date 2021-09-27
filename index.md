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



# Standup Meeting Notes

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


