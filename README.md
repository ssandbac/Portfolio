# 02 Advanced CSS: Portfolio

## Your Task

Welcome to this week's Challenge! This is an even-numbered week, so you won't be given any starter code. Instead, you'll create a web application from scratch! This week, you'll build a portfolio page, which you can add to as the course progresses. 

A portfolio of work can showcase your skills and talents to employers looking to fill a part-time or full-time position. An effective portfolio highlights your strongest work as well as the thought processes behind it. Students who have portfolios with deployed web applications (meaning they are live on the web) are typically very successful in their career search after the boot camp. This last point can’t be stressed enough: having several deployed projects is a minimum requirement to receive an initial interview at many companies. 

With these points in mind, in this Challenge you’ll set yourself up for future success by applying the core skills you've recently learned: flexbox, media queries, and CSS variables. You'll get to practice your new skills while creating something that you will use during your job search. It’s a win-win that you'll likely be grateful for in the future!

**Note:** If you don't have enough web applications to showcase at this point, use placeholder images and names. You can change them to real applications as you create them later in the course. However, at least one application should be live. So you can add on Challenge 1's deployed application or Module's 1 Mini Project's deployed application.

Let’s take a look at what a user story written from the perspective of a hiring manager might look like. As you might remember from your first Challenge, we follow the AS AN / I WANT / SO THAT format. 


## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```


## Acceptance Criteria

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

## Acceptance Criteria Simplified

In this project you are tasked with creating a portfolio of your work. It should match the mockup given as close as possible (though some leeway is given for your own creativity).

The following subtasks must be done:

* You should have your name, recent photo, and a nav section in the header (which should be at the top of the page)
* The nav section should have sections for About Me, Work, and Contact, and Resume
* When any of these nav sections is clicked, the page should scroll to the appropriate section further down on the page (You can do this without JavaScript-google can help you, or the instructional staff during office hours).
* Add an About Me section that has some info about yourself.
* You should create a section with images of your applications. You might not have any to start off with. In that case just put placeholder links and update the portfolio as we build out more challenge homeworks (you can link to these!)
* The sections should also have a description of your project
* Add a contact section that has ways to get ahold of you (email, phone, github page, whatever you feel comfortable with). If you're not comfortable putting your real phone, put a fake one for the graders.
* Your page should be responsive. What does this mean? It means when viewed on a mobile browser, it adjusts itself to conform to the smaller width. You can use the Chrome inspector to go into mobile view and set different widths to see how your page reacts. My recommendation here is to make sure you have the appropriate viewport meta tag (`<meta name="viewport" content="width=device-width, initial-scale=1" />`) then slowly shrink your page until something seems to break or look bad. Then use a media query to adjust, and continue.

## Mock-Up

The following animation shows the web application's appearance and functionality:

![portfolio demo](./Assets/02-advanced-css-homework-demo.gif)


## Grading Requirements

> **Note**: If a Challenge assignment submission is marked as “0”, it is considered incomplete and will not count towards your graduation requirements. Examples of incomplete submissions include the following:
>
> * A repository that has no code
>
> * A repository that includes a unique name but nothing else
>
> * A repository that includes only a README file but nothing else
>
> * A repository that only includes starter code

This Challenge is graded based on the following criteria: 

### Technical Acceptance Criteria: 40%

* Satisfies all of the above acceptance criteria.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository contains application code.

### Application Quality: 15%

* Application resembles the mock-up functionality provided in the Challenge instructions.

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality readme with description, screenshot, link to deployed application.

## Review

You are required to submit BOTH of the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository that contains your code. Give the repository a unique name and include a README file that describes the project.

- - -
© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
