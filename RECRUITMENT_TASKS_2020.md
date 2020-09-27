# Tasks

* It is perfectly fine if you have no experience in the field and trying it out for the first time. Please put in sincere efforts!
* Each Task has a ID, tags, mentor, description, tips and useful resources
* Mention the Task ID(s) of all task(s) attempted in the README of your private GitHub repository.
* Read the instructions, evaluation criteria and submission details [here](https://github.com/WebClub-NITK/DSC-NITK-Recruitments-2020/blob/master/README.md)


## Task ID: NITK_Winter_Of_Code_Homepage
#### `web development` `frontend develoment`

Mentors: [@Sriram Rao](https://github.com/Sriram2001) (+91 7975610644), [@Madhumitha Nara](https://github.com/madhumithanara) (+91 7981819450), [@Harsh Prakash Gupta](https://github.com/harshnitk17) (+91 7898578609)

Tag: `Easy`

### Description
NITK Winter of Code is an initiative by NITK to promote Open Source culture among the students and also to give a feel of similar events like GSoC.
Your task is to design and develop an attractive homepage for the NITK Winter of Code portal. You can take inspiration from websites of similar events such as [Google Summer of Code](https://summerofcode.withgoogle.com/) or [Kharagpur Winter of Code](https://kwoc-19-archive.herokuapp.com/).
The website should have:
* A landing section with call to action
* Useful information about the event like registration dates, benefits etc. (You can make up the details like the timeline and such)
* A timeline section
* Anything you feel the wewbsite can use and will look good
* You can use any kind of effects or animations to make the website attractive

### Useful resources:
* HTML, CSS, JavaScript tutorials: https://www.w3schools.com/
* React JS docs: https://reactjs.org/tutorial/tutorial.html
* Current portal source code: https://github.com/woc-nitk/Project-Management-Portal
* [Current portal website](https://woc-portal-demo.herokuapp.com/)

### Tips
1. Design your website on a design tool like [Figma](https://www.figma.com/)(free) or [Adobe XD](https://www.adobe.com/in/products/xd.html)(also free!) before coding the website.
2. Try setting up the repository and use your homepage instead of the one currently in the codebase.

## Task ID: MicroKart

#### `Web Development`, `Microservices`
Mentor: [@abhishekkumar2718](https://github.com/abhishekkumar2718) (+91 7587730714), [@namanmanish](https://github.com/namanmanish) (+91 9429504960), [@Varun Pattar](https://github.com/varunpattar) (+91 97400 52012)

Tag: `Easy`

### Description

Microservice Architectural style is an approach to developing a single application as a suite of small services, each running its own processes and communicating with lightweight mechanisms. The services are:
- Highly maintainable and testable
- Loosely coupled
- Independently deployable
- Organized around business capabilities
- Owned by a small team.

Microservice architecture enables rapid, frequent and reliable delivery of large, complex applications.

Let's explore micorservice architecture by implementing an e-commerce website, comprised of at least three services. It should have the following features:
- Authentication: Ability to register, log in and reset lost passwords.
- Product catalog: Ability to browse, buy and sell products.
- Shopping Cart: Ability to manage a shopping cart.
- Adminstration: Ability to manage above features through authorized user roles.

### Useful resources:
- [Microservices.io](https://microservices.io/index.html)
- [Microservices architecture for E-commerce](https://medium.com/@dearsikandarkhan/microservices-architecture-for-e-commerce-f8b49270e72f): An article detailing advantages of migrating from an monolithic e-commerce website to microservices architecture.
- Refer to related resources for the backend framework of your choice.

### Tips

1. Document *at least* the following in your README - Description, Tech Stack, Installation instructions, Use instructions, API endpoints (if exposed), Screenshots (if any).
2. The choice of programming language is crucial - conventional backend frameworks like Django, Ruby on Rails might obstruct the process. Go is recommmended.
3. The emphasis of the task is to understand and build services: prioritise on backend and interservice communication rather than building user interface.

## Task ID: EMAIL_NOTIFICATION
#### `web developement`
Mentor:  [@mananpoddar](https://github.com/mananpoddarm) (+91 9113536695), [@Vivesh Yadav]() (+91 74629 42781), [@Dhanasekhar](https://github.com/DhanaSekharM) (+91 9538512471)

Tag: `Easy`

### Description
Create an authenticated platform where admin can send message to registered users via email.
Collect relevant infomation from users so that admin can notify user based on certain criteria(eg location).The user data can be stored in a database of your choice.
Admin can either choose to notify everyone at once or based on certain filters on user data.

### Useful resources:
 - [Sending emails in django](https://docs.djangoproject.com/en/3.1/topics/email/) (Using Django is not mandatory, feel free to use any framework)


## Task ID: Web_Club_Chat_Bot
#### `dialogflow` `chat bots`

Mentors: [@AdarshNaidu](https://github.com/AdarshNaidu) (+91 8618773543), [@madhumithanara](https://github.com/madhumithanara) (+91 7981819450)

Tag: `Medium`

### Description
A chatbot is an program that can simulate a conversation (or a chat) with a user in natural language through messaging applications.   
To keep track of all the events conducted by the club, we maintain a spreadsheet that contains all the details related to upcoming and past events. You can find a sample of the sheet [here](https://docs.google.com/spreadsheets/d/1GRv7jN_AeL81XR2H620Bsin8EL3kcz3ZE71LvteDJ1Y/edit?usp=sharing).     
Your task is to build a chatbot that can answer various queries that a user will have related to the Web Enthusiast's Club and the events conducted by it.     
Some example queries are:
* Tell me about all the upcoming events.
* What is the last event conducted by web club.
* How many events did web club conduct in the month of November.
* Who is the convener of Web Club.*
* When was web club established.*   
and so on...   
**Note: Use dummy data wherever applicable*   

### Useful resources:
* Dialogflow Documentation: https://cloud.google.com/dialogflow/es/docs/basics
* Adding Fulfillment: https://cloud.google.com/dialogflow/es/docs/fulfillment-overview
* Sample guilde on building chatbot: https://marutitech.com/build-a-chatbot-using-dialogflow/

### Tips
1. Some of the queries based on club events will require you to fetch the results from the spreadsheet in realtime.
2. Bonus points will be provided depending on the multitude of queries that the chat bot will support.
3. Create a simple website and integrate this chatbot to the site. If executed well, this chatbot will be integrated with the new web club website.

## Task ID: NITK_Virtual_Guide
#### `app development`

Mentors: , [@Prajwal S](https://github.com/prajwal27) (+91 9632721417), [@AdarshNaidu](https://github.com/AdarshNaidu) (+91 8618773543)

Tag: `Medium`

### Description
Build a mobile application that will act as a guide for students or any guest visiting NITK. Some example sections/modules that the app can contain.  
**Module 1: News** - This section should inform the users about the latest news related to NITK.   
**Module 2: Events** - Should tell about the ongoing or upcoming events in NITK.  
**Module 3: Mess Menu** - Should allow the users to choose and view menu for different mess in NITK for that particular day.  
**Module 4: Map** - This section should contain a 2D or 3D map of NITK. It should help the user navigate to any of the locations within NITK.  

### Note:  
1. It's not necessary to implement all the modules listed above, implement as many as possible.  
2. Feel free to add your own modules or make changes to any of the modules listed above.  

### Tips:  
1. Bonus points if the values used by various modules instead of hardcoding, are loaded dynamically from a backend service/spread sheet/any other online storage.  
2. Give more importance to UI/UX.  


## Task ID: Reddit_Client
#### `api` `app development` `web development`

Mentors: [@Dhanasekhar](https://github.com/DhanaSekharM) (+91 9538512471), [@Varun Pattar](https://github.com/varunpattar) (+91 97400 52012)

Tag: `Medium`

### Description
Reddit is a website comprising user-generated content—including photos, videos, links, and text-based posts—and discussions of this content in what is essentially a bulletin board system.
Your task is to build a frontend client(web or app or cli) using the Reddit API which is openly available.
Basic features such as
* Viewing posts(text, images, videos or link previews) from the front page of Reddit
* Sorting posts according to Hot, New, Top, etc.
* Upvotes, awards and comments
should be implemented. Feel free add additional features such as authentication, allowing upvotes/downvotes etc.

### Useful resources:
* Reddit API - https://www.reddit.com/dev/api
* What are REST APIs: https://restfulapi.net/
* Official Reddit clients: [Web](https://www.reddit.com), [Android](https://play.google.com/store/apps/details?id=com.reddit.frontpage&hl=en_IN)

### Tips
1. Give more importance to UI/UX.



## Task ID: Video Chat Application
#### `WebRtc` `WebSockets` `web development`

Mentors: [@Naman Trivedi](https://github.com/namanmanish) (+91 9429504960), [@Sriram Rao](https://github.com/Sriram2001) (+91 7975610644), [@Harsh Prakash Gupta](https://github.com/harshnitk17) (+91 7898578609)

Tag: `Medium`

### Description
Develop a website which facilitates video conferencing by implementing WebRtc architecture(Peer to Peer) <br/>
Some necessary features are:-
* When a user visits the home page he/she should get two options, to create a room or to join a room (similar to Zoom)
* Once he/she joins the created room he/she should get the room_id to share with people who can than join the room using this room_id
* The room should also provide a feature for text chat messages
* This text chat should be dynamic(We need not refresh page for updating with new chats)
* The space of chat room should be on left/right side of the web page and preferably there should be a option to hide it (similar to Google meets)
### Useful resources:
* Django Tutorials - https://www.youtube.com/watch?v=Fc2O3_2kax8&list=PLw02n0FEB3E3VSHjyYMcFadtQORvl1Ssj
* Django channels: https://channels.readthedocs.io/en/latest/
* WebRtc tutorial: https://www.youtube.com/watch?v=2Z2PDsqgJP8
* Express JS tutorial: https://youtu.be/L72fhGm1tfE
* Peer JS docs: https://peerjs.com/
* Socket IO docs: https://socket.io/docs/

### Tips
1. Bonus points for good UI/UX across differnt devices and screen sizes.

## Task ID: Lazy_Loading
#### `web development` `frontend develoment`

Mentors: [@Harsh Agarwal](https://github.com/harshagrwl) (+91 9582885426), [@Apoorva MK](https://github.com/apoorva-mk) (+91 9902921511)

Tag: `Medium`

### Description
Create a Web Application which should implement lazy loading and display only a few records on the screen at a time. For the demonstration purpose, you can use any dataset having more than 1000 records. The number of records per scroll event must be decided based on User Experience.
**Note: You are free to use any Dataset and any framework of your choice*

### Useful resources:
* Example of a Lazy Loading Website: https://scrollmagic.io/examples/advanced/infinite_scrolling.html
* Dataset which can be used for implementation: http://downloads.majestic.com/majestic_million.csv 
* Lazy Loading tutorial in Angular: https://angular.io/guide/lazy-loading-ngmodules

### Tips:
1. Bonus points will be given for implementing lazy loading for images.
2. Bonus points will be given for deploying the Web App to the cloud.

## Task ID: Alarming_System_Mobile_App
#### `app development`

Mentors: [@Harsh Agarwal](https://github.com/harshagrwl) (+91 9582885426), [@Apoorva MK](https://github.com/apoorva-mk) (+91 9902921511)

Tag: `Medium`

### Description
Build a mobile application that will act as an emergency alarming system for the friends and acquaintances whenever a person needs help. Some example functionalities that the app can contain.  
1. User should be able to Sign In the application using thier Mobile Number or Email Id (OAuth).
2. User should be able to select Emergenecy Contacts out of his/her saved contacts.
3. In case of any emergency, user should be able to just press a button to send the Help SMS to all the emergency contacts.
4. A common template can be used for the SMS to be sent.

### Note:  
1. It's not necessary to implement all the modules listed above, implement as many as possible.  
2. Feel free to add your own modules or make changes to any of the modules listed above.  

### Useful resources:
* Android tutorials: https://developer.android.com/training/basics/firstapp
* Tutorial for integrating SMS API: https://www.twilio.com/blog/2016/05/how-to-send-an-sms-from-android.html
* Firebase Phone Auth: https://firebase.google.com/docs/auth/web/phone-auth

### Tips:  
1. Bonus points if the data is loaded dynamically from a backend service/spread sheet/any other online storage instead of hardcoding.  
2. Bonus points for Good UI/UX.  


## Task ID: Multiplatform_App
####  `multiplatform development` `android` `iOS` `web development` `desktop application`

Mentors: [@mananpoddar](https://github.com/mananpoddarm) (+91 9113536695)

Tag: `Hard`

### Description
* As we get aware of more and more clients like mobile(android or iOS), web and desktop appliations, we should realise that if we want to develop an application supporting these many clients, we have to write the same logic for a feature over and over again right? Because every client have a different tech stack like web has javascript frontend frameworks, android has react-native etc which can develop package that can run over JVM, or windows desktop application can be developed using Microsoft's windows universal tool in c# or c++?
* I don't want to overwhelm you with loads of information, but believe me this task is doable and to explain it in the simple english at the risk of sounding technically disabled or ignorant(who cares xD), you should be able to write code once, and run that code over all these multiple clients without worrying about different tech stacks.
* There are multiple tools for developing such pipelines, like react or kotlin multiplatform plugin. you have to read the documentation carefully and try to develop such a pipeline and it can be for a very simple feature, as simple as a textbox which can just display the number of characters a user has inputted.


### Useful resources:
* kotlin multiplatform plugin - https://kotlinlang.org/docs/reference/mpp-intro.html
* comparison between different tools: https://steelkiwi.com/blog/flutter-vs-react-native-vs-xamarin-for-cross-platform-development/
### Tips
1. web and android or android and iOS can be an easy combination to start with.

## Task ID: Winter_of_Code_Server
#### `MySQL`  `GraphQL`  `Node.js` 
Mentor: [@adharshkamath]() (+91 8296678775), [@SaurabhAgarwala]() (+91 8415859101)

Tag: `Hard`

### Description
The Winter of Code portal's backend currently uses MySQL queries to get data from the database, and then sends these objects directly to the client. The task is to replace these queries using an ORM. The database schema can be found in the Wiki of the repo. 
Link to the GitHub repo - [https://github.com/woc-nitk/Project-Management-Portal](https://github.com/woc-nitk/Project-Management-Portal)

### Useful resources:
 - [What is an ORM](https://blog.bitsrc.io/what-is-an-orm-and-why-you-should-use-it-b2b6f75f5e2a)
 - [GraphQL tutorial](https://www.howtographql.com/graphql-js/0-introduction/)
 - [Using sequelize with Express](https://sequelize.readthedocs.io/en/1.7.0/articles/express/)
 - [TypeORM docs](https://typeorm.io/#/connection)

### Tips
1. Once you understand the basics of how raw SQL queries work, the task becomes pretty simple


## Task ID: HTML5_Game
#### `Game Development`  `Web Games`
Mentor: [@adharshkamath]() (+91 8296678775), [@SaurabhAgarwala]() (+91 8415859101)

Tag: `Hard`

### Description
Develop a multiplayer HTML5 game. The game need not have a very complex story/narrative. You're free to use any web game framework, any freely available sprites, sounds, fonts, etc. Use Socket.io or WebRTC for communication between the server and clients.
Get creative with the theme and other details.

### Useful resources:
 - [Javascript Game Engines](https://github.com/collections/javascript-game-engines)
 - [Socket.io](https://socket.io/docs/)
 - [Peer JS](https://peerjs.com/docs.html#start)

### Tips
1. Try to make a single player web game and then add the communication part with other players


## Task ID: Stock_Price_Tracker

#### `Web Development`, `Websockets`
Mentor: [@abhishekkumar2718](https://github.com/abhishekkumar2718) (+91 7587730714), [@Prajwal S](https://github.com/prajwal27) (+91 9632721417)

Tag: `Hard`

### Description

You are an up and coming developer for a stock trading company. The stock traders bring the following complaint to you:

> All stock prices are listed on a page and change second to second. However, the page does not update dynamically and we are tired of manually refreshing the page all time.

After doing some research, you figure out there are three possible solutions: Long Polling, Server Side Events and Websockets. Before commiting to an implementation, you would like to compare between the options by building a prototype and make a "Request for Comments" to your fellow developers.

For the prototype, you decide on the following constraints:
- The page contains 1000 stocks, with three columns - name, current price, most recent change.
- Prices are updated each second, with the following rules: A stock has a 50% chance to change, with the change in range of -5% to +5% of the original price.
- There will be 50 concurrent users (representing the size of the company's stock trading team).
- No new stocks are added during runtime.

### Useful resources:

- [Polling vs SSE vs WebSockets](https://codeburst.io/polling-vs-sse-vs-websocket-how-to-choose-the-right-one-1859e4e13bd9) 
- [RFC Style Guide](https://tools.ietf.org/html/rfc7322) - You don't need to follow this rigorously but stick to the spirit.
- Refer to related resources for the backend framework of your choice.

### Tips

1. Document *at least* the following in your README - Description, Tech Stack, Installation instructions, Use instructions, Screenshots.
2. The task emphasises building a prototype and writing a performance report - be sure to explain the different solutions, pros, cons and your conclusion.
3. If possible, measure the performance characteristics at different levels of load.
