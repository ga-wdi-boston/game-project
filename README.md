# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project #1: The Game

### Overview

In our first project, let's start out with something fun - **a game**! Specifically, We'll be making **Tic Tac Toe**, a game that takes seconds to learn but minutes to master!

By the time you submit this project, you will have covered new ground in many of the big themes of the course:
- **Command Line**: Interacting with the computer and navigating the filesystem from the command line.
- **Source Control**: Managing and interacting with a git repository to store changes to code.
- **Programming Fundamentals**: Working with objects, constructors, and events, while learning how to strategically solve problems and resolve errors.
- **Web Fundamentals**:  Structuring, styling, and animating documents within a browser; responding to actions your users take and the data they input into the browser.
- **Browser Applications**: Using AJAX to connect to a back-end application.
- **Server Applications**:  We haven't covered a ton of server-side technologies yet (that's up next), but we learned a bit about how API endpoints work, and how to get data from them.
- **Security**: With JavaScript closures, scratching the surface of why security matters.
- **Deployment**: Host a static web site in a managed hosting environment (GitHub Pages)
- **Products and Teams**: Document your code and your code repository so others understand what you've built.


At a high level, here are our goals for you in this project:

* **Build a web application from scratch**, without a starter codebase
* Use your programming skills to **map out the game logic for a simple game like Tic Tac Toe**
* **Separate HTML, CSS, and JavaScript files** in your application
* Build an application **to a spec that someone else gives you**
* **Build a dynamic game that allows two players to compete** (bonus: compete from separate devices)
* **Craft a ``readme.md`` file that explains your app** to the world
* **Communicate with a back-end** (which we'll provide for you) to store the state of your game.

> **You will be working individually for this project**, but we'll be guiding you along the process and helping as you go. Everyone will get a chance to **be creative**, and work through some really **tough programming challenges** to get your feet wet in the world of web development. Those who dare will have the tools to make it **multi-player, and multi-device** – so you can say to someone, "hand me your phone," load up the game, and play a quick round!

---
## DELIVERABLES

When you present your project, you must hand in the following things

* A **working browser game, built by you**, hosted on GitHub Pages (or an alternative platform).
* A **git repository hosted on Github**, with a link to your hosted game, and frequent commits dating back to the very beginning of the project
* **A ``readme.md`` file** with explanations of the technologies used, the approach taken, unsolved problems, etc.
* A **link to your hosted working game** in the URL section of your Github repo
* Links to **wireframes and user stories**, preferably in the README of your repo.

In order to get a satisfactory score, your app must:

* **Be deployed online**, where the rest of the world can access it
* **Render a game board in the browser**
* **Switch turns** between X and O (or whichever markers you select)
* **Visually display which side won** if a player gets three in a row or show a draw/"cat’s game" if neither wins
* Use **jQuery** for **DOM manipulation** and **event handling**
* Use **AJAX** for data storage and retrieval

In addition, you must use separate files for your HTML, CSS, and JavaScript, and (where possible) use semantic markup for your HTML. And in general, try to stick with **KISS (Keep It Simple Stupid)** and **DRY (Don't Repeat Yourself)** principles

### Bonus
Once (and only once) you've satisfied the core requirements, here are some additional goals that you can shoot for:

* If allowing players to compete from separate devices, **display a "Waiting..." message** while users are waiting to be matched
* Keep track of **multiple game rounds** with a win counter
* Allow players to **customize their tokens** (X, O, name, picture, etc)
* **Get inventive with your styling**, e.g. use hover effects or animations to spiff things up
* Add **tableside chat** to your game
* **Use localStorage** to persist data locally, allowing games to continue after page refresh or loss of internet connectivity

---
## FEEDBACK

These are the things that instructors will be looking at, and giving you feedback on, after you've submitted your project.

#### Project Workflow
* __Planning__ : Did you complete user stories and wireframes before you started writing code? Did you create a schedule for yourself to keep your project on track?
* __Source Control__ : Did you use source control to keep track of changes in your project and make regular 'save points' for yourself?

#### Deliverables
* __Technical Requirements__ : Does your project meet all the technical requirements outlined above? Does it run?

* __Software Design/Problem Solving__ : How did you break up the functionality of your application? How did you solve the problems that you encountered along the way? Do the solutions you came up with make sense, from the perspective of industry best practices? How well can you defend the choices you've made?

* __Code Clarity__ : Did you follow code style guidance and best practices covered in class, such as spacing and semantic naming? Did you comment your code as your instructors as we have in class?

* __Creativity__ : Did you added a personal spin or creative element into your project submission? Is the finished product something of value to the end user, in addition to being functional (not just a login button and an index page)?


#### __Total__
Your instructors will give you a total score on your project as an aggregate across all the categories:

  Score | Expectations
  ----- | ------------
  **0** | _Does not meet expectations._
  **1** | _Meets expectactions, good job!_
  **2** | _Exceeds expectations, you magnificent creature, you!_

This will serve as a helpful overall gauge of whether you met the project goals. But more important than your overall score is your feedback, particularly in individual categories - this will help you identify where to focus your efforts for future projects.

---

## GETTING STARTED

Not sure where to get started? Here's a sample timeline that you can follow for this project, if you so choose.

##### Week 2
* __Day 1__ : After receiving the project prompt, begin sketching some rough wireframes for how the front end will look and act. Start thinking about what kind of data your front-end will need to store and manipulate in order to work correctly. Create a repo that your project will use, and add a README to it.
* __Day 2__ : Create a simple front-end with HTML and CSS, and host the front end on GitHub Pages.
* __Day 3__ : Write out some user stories for the app, and create the code to manage your game logic.
* __Day 4__ : Write jQuery code to handle browser interaction.
* __Day 5__ : Finess the jQuery code and link it up with your game logic.
* __Weekend__ : Test and debug your code.

##### Week 3
* __Day 1__ : Start communicating with the back-end using either `curl`, Postman, or simple browser requests. Use this to begin writing your AJAX code.
* __Day 2__ : Finish adding AJAX to your front-end app and link it into your back-end app.
* __Day 3__ : Add any additional features to your app. Test and debug. Clean up your documentation.
* __Day 4__ : Test and debug.
* __Day 5__ : Present!

Some other thoughts to meditate on:

* **Break the project down into different components** (data, presentation, style, DOM manipulation) and brainstorm each component individually. Use whiteboards!
* **Use your Development Tools** (console.log, debugger, alert statements, etc) to debug and solve problems
* Work through the lessons in class, **ask questions and come to office hours** when you need to. Think about adding relevant code to your Tic Tac Toe game each night, instead of, you know... _procrastinating_.
* **Commit early, commit often.** Don’t be afraid to break something because you can always go back in time to a previous version.
* **Read documentation** (jQuery especially) at home to better understand hwo the tools you're using work.
* **Don’t be afraid to write code that you know you will have to remove later.** Create temporary elements (buttons, links, etc) that trigger events if real data is not available. For example, if you’re trying to figure out how to change some text when the game is over but you haven’t solved the win/lose game logic, you can create a button to simulate that until then.

Finally, here are some resources that it might be good for you to look at/read about:

* **[MDN Javascript Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)** _(a great reference for all things Vanilla Javascript)_
* **[jQuery Docs](http://api.jquery.com)** _(jQuery API reference)_
* **[Writing Good User Stories](http://www.mariaemerson.com/user-stories/)** _(for a few user story tips)_
* **[Presenting Information Architecture](http://webstyleguide.com/wsg3/3-information-architecture/4-presenting-information.html)** _(for more insight into wireframing)_

**Good luck and happy hacking!**

[License](LICENSE)
------------------

Source code distributed under the MIT license. Text and other assets copyright
General Assembly, Inc., all rights reserved.
