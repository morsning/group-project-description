# group-project-description

Projekt

The main purpose of this project is to make use of the concepts, techniques and frameworks covered throughout this course. Planning and developing an application that actually has some real world use is not only good practice for future employments but often much more rewarding than small coding exercises.

So what are we building?
As mentioned all the groups projects will have an expected common functionality that is required in order to get a passing grade. And I can’t emphasize this enough, if you are stuck in trying to understand any of the concepts we have covered and can not find your answer on google, ask me and I will explain it until you understand it :)

For the grade G

So the minimum functionality needed for a passing grade would be:

### A react application.
 
* Understand how we can separate our applications into components for cleaner structure and/or in order to re-use a component in several parts of our application. 
* How to create functional vs class-based components and their main differences. 
* Understanding how to send down props from a parent to a child component. 
* How to alter state in a parent through a child component.
* Basic event handling, (buttons and forms as a minimum)
* Basic understanding of how to avoid problems with the keyword this when working with class-based components. 
* Understanding of component level state, how to use component level state, and set component level state.
* Lifecycle methods, the two we have covered at least
* JSX Understanding the basics, sending down props, rendering lists through .map
* Routing (a couple of different pages should be present in your SPA, with some kind of navigation )
* Using axios to get and post data
* Handeling logins and restricted routes only visible for logged in users.
* State and lifecycle in functional components through the use of hooks.
* Controlled vs uncontrolled elements through the use of State rather than keeping a input fields value  only in the DOM. 
* Importing and exporting functions and components
* difference in syntax between named exports and default exports

### Node Express server.

* Basic understanding of how we create a server,
* create middleware functions, use third-party middleware functions,
* how we create routes,
* differences in HTTP methods for instance the difference of Post and Get.
* How to use mongoose in order to work with MongoDB.
* How to set up basic authentication and protect certain endpoints through the use of sessions and     JWT’s as well as how to store passwords (or not to store passwords…) 
* modeling messages in order to save messages/posts made by a specific user

### MongoDB.

* Basic understanding of how MongoDB works and how we can use a library available in Node to use MongoDB to store users and user related data.
Storing and being able to get messages/posts related to an logged registered user

### Amazon.

* This will be covered further down the course, there is not a single complicated concept related to this part of the course, there is a bunch of steps that you need to execute in order to deploy something but these are very basic and more or less a long todo-list anyone could follow. 

### TypeScript.

* Do not focus on this for now, this is a very small part of the course that will be a separate part than the main project, I will summarize the concepts you need to understand in a way I am confident everyone will understand within a couple of hours.
Describing the most basic concepts of typescript will be good enough for me.

**IMPORTANT – missing one or two of the above will not get you failed, the important part is that you understand most of it, and do not be afraid to ask If you want me to explain something again**

## For the grade VG

* All of the Above needed for G

* different levels of messages or posts being made or displayed depending on different types of users, in other words, an example could be to include a become friend functionality that connects you and a second user where you can send private messages to each other. 

* Having users with more functionality should not only be reflected in the REACT part, there needs to be some kind of separation in MongoDB as well. 

* Demonstrating an understanding of the basic concepts of Redux with react, creating reducers, action creators, and how to use the provider element to wrap your application as well as using the connect function.

* A somewhat clean separation of routes in your express-project

* **Having some additional functionality such as implementing Socket.IO for real-time chatting or painting our some weird game will give you some slack on one of the VG points above. In other words if you implement something more exciting than just messages you can skip one of the bullet-points above and still get your VG**
