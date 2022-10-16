---
layout: essay
type: essay
title: Design Patterns Lead the Way
published: true
# All dates must be YYYY-MM-DD format!
date: 2021-12-02
labels:
  - Meteor
  - React
---

## Introduction

Imagine waking up in the dead of night, thinking to yourself "I want a midnight snack." You stumble out of bed and reach for the light. Nothing happens. It seems the power is out in your house. Nevertheless, this doesn't deter you from your goal. You manage to get out of your room and tiptoe your way to the kitchen. All seems to be going well. Then, out of nowhere, you smack right into a wall. Ouch. It seems you didn't know your way around the house after all...

<img class="ui image" src="../img/essays/flashlight.png" height="200" width="800">

This incident is but one of many that could have easily had been prevented given the right guidance. Depending on the situation, there are endless different sources of guidance, whether it be a flashlight, a map, a teacher, blueprints for a building, instructions on an exam, or, in the world of software engineering, design patterns.

## Design Patterns

Design patterns are templates providing solutions for common problems in software engineering. They can be integrated into programming projects to ensure the quality of systems, make it quicker and easier for programmers to write correct code, and prevent problems from unexpectedly arising.  

There are a plethora of design patterns in existence. In fact, the book *Design Patterns: Elements of Reusable Object-Oriented Software*, made by four programmers known as the "Gang of Four," covers 23 of these, including the factory, adapter, singleton, and observer design patterns.

I've actually been implementing several of these design patterns with a team on a project called Bridging the Gap.

### Bridging the Gap
Bridging the Gap is a website my team and I are building as a final project for our software engineering class. The aim of Bridging the Gap is to connect University of Hawaii students with companies, allowing students more opportunities to find jobs and employers more candidates to hire. As of now, we are building our web app using [Meteor](https://www.meteor.com/), a JavaScript web framework, and [React](https://reactjs.org/), a JavaScript UI library, and we are making use of several design patterns, notably the front-controller, observer, singleton, and MVC. These patterns have been a great resource for our project, akin to a set of tools in a toolbox, helping us complete tasks so we do not have to brute force a solution like cavemen. Let's dive right into these design patterns!

<img class="ui image" src="../img/essays/toolbox.png" height="300" width="300">

#### Our design pattern tools:
##### Front-Controller
The front-controller design pattern is the first design pattern that my team and I have used. This design pattern describes the use of a single centralized handler that takes requests from clients. My team and I are implementing this pattern through the front-controller ReactRouter, which has enabled us to send clients to different pages based on their authorization. For instance, on the [Bridging the gap website](https://bridging-the-gap.xyz/#/), an unregistered user is only be able to view the landing page and sign-in/sign-up pages. Upon registration or logging in, however, a user will be able to see more pages on protected routes because they have been authenticated. As a result, ReactRouter has been a useful tool for Bridging the Gap. And this front-controller is actually part of another design pattern relative to our project, model view controller (MVC).
##### Model View Controller
The MVC design pattern specifies a model, which is a database; a view, which is the user interface; and the controller, the intermediary between the model and view, which decides what view is presented to the user as well as how the state of the model will change. Regarding the model, my team is using a database called MongoDB as a way to store our collections. As for the view, our web app is using [Semantic UI React](https://react.semantic-ui.com/) to present our user interface. And finally, we are using React Router as our controller. This MVC design controller has enabled us to structure our code efficiently and effectively.
##### Singleton
Alongside the MVC design pattern, my team and I are also incorporating the singleton design pattern into our project. In this design pattern, we provide a global variable and/or state by creating a single instance of a class. Our project's code makes use of this through our singleton collection classes. Within the files for these classes, we export a variable representing an instance of the collection and make it available to the rest of our code. In turn, we never have more than one instance of a collection class, nor do we need one, because we can simply import the class into whatever file we need, which is very convenient!
##### Observer
Not to mention, my team and I have also been utilizing the observer design pattern. This pattern states that you have a object as the "subject" and whenever its state changes you want to be able to inform other objects, the "observers," so that they can react. The publish-subscribe pattern is one example of the observer design pattern and Meteor directly implements it. As a result, this pattern has been utilized in our code. We publish our collections so that we have all the data available and we subscribe to them in different classes whenever we want to retrieve information pertaining to specific collections. It's like checking out books at the library, except with data! 

We can see that these patterns are incredibly helpful. Without them, I'm not sure how my team and I would have approached our project.

## Conclusion
All in all, design patterns play a big part in the field of software engineering. They structure our code, keep errors at bay, and give us peace of mind. It is important to make use of the direction they provide or we may be led astray, wanderers without so much as a compass to guide our way through the unknown.

### Find Bridging the Gap on github:
- [repo for our code](https://github.com/bridging-the-gap/bridging-the-gap)
- [project homepage](https://bridging-the-gap.github.io/)

### Image sources:
- [Toolbox](https://pixabay.com/illustrations/toolbox-tool-box-construction-work-2727391/)
- [Flashlight](https://boxofcrayons.com/boc/wp-content/uploads/2011/11/torch-light2.jpg)
