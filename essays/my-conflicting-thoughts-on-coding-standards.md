---
layout: essay
type: essay
published: false
title: My Conflicting Thoughts on Coding Standards
# All dates must be YYYY-MM-DD format!
date: 2021-09-23
labels:
  - Java
  - JavaScript
  - Checkstyle
  - ESLint
---

## Introduction
Coding standards are the backbone of programming languages like Java and C++. These standards allow programmers to organize their code and write clearly and effectively, which is a great benefit, especially when working on big projects with others. However, some programmers may argue that coding standards are annoying and cumbersome, taking precious time away from working on the actual functionality of code. I personally share opinions from both sides of the coin; I understand the benefits of coding standards, but I also realize the inconveniences. My college programming experience has definitely shaped my perspectives into what they are today.

## My First Experience: Checkstyle and Java Coding Conventions
My first official experience with coding standards was in my second Java class, Intro to Computer Science II, or ICS 211 for short. In this class, I expected that I would just continue to write Java code and organize it mostly own way, including adding comments wherever I wanted, whenever I wanted. However, this would not be the case. I would need to start using a tool called Checkstyle in the Eclipse IDE to ensure my code conformed to a specific Java coding standard. Initially, I thought that incorporating Checkstyle into my programming assignments would be no big deal, but it did present a few difficulties. 

<img class="ui floated image" src="../img/other/checkstyle_logo.png" height="100" width="700">

My biggest issue was writing the comments. I had to write a specific type of comment, a JavaDoc comment, for all of my classes and methods. Writing comments for classes wasn't a big deal since I'd only deal with a handful of classes at a time, but writing comments for methods was a different story. Often, my ICS 211 assignments required I write comments for around 20 methods at a time, and they were quite lengthy. In each, I had to explain what the method was doing, list all of the method parameters and describe what they were, list what would be returned from the method, if anything, along with any other important information concerning the method; otherwise, Checkstyle would throw a fit. This was stressful, especially when I was stuck working on Java errors and had little time to allocate toward getting my comments done. In short, writing comments for each method in my programs was a hindrance in ICS 211. However, as I continued doing so I actually gained some key insight. In particular, while writing comments for methods, I remember asking myself, "what is my code actually doing?" Sometimes, I think I know what exactly my code does but have a hard time describing it in words. Writing comments, in turn, forced me to address this weakness, allowing me to gain a more comprehensive understanding of my code. But what about other Java coding rules?

Aside from Checkstyle, there were other Java coding conventions I was expected to follow in my code that Checkstyle couldn't detect. For instance, for my Java class, I needed to have two blank lines between each method and write lines of code no greater than 100 characters long each. My lack of compliance with the latter coding rule ended up taking 10 points off (out of 100) on one of my assignment grades. Being deducted that many points for the aesthetic of my code and not the way it functioned was the silliest thing to me, the equivalent of losing points for spelling errors on a math test. But I eventually realized why such a rule was important. Imagine a programmer consistently writing really long lines of code for a large 10,000 line program. Perhaps for the programmer, reading this code is no big deal. But to others who may be inspecting this code, they are not going to like the cluttered mess of mumbo jumbo they're going to see. So I did realize some benefits of coding conventions from ICS 211, and I am continuing to learn them now.

<img class="ui floated image" src="../img/essays/ESLint_logo.png" height="150" width="700">

## My Current Experience: ESLint and JavaScript Coding Conventions
In present times, I am learning JavaScript for my software engineering class. Instead of Checkstyle, I am using the tool ESLint in the IntelliJ IDEA IDE to enforce JavaScript coding rules and standards in my code, as well as detect possible errors. From my experience so far, ESLint is less exhausting but a bit more daunting than Checkstyle. ESLint doesn't require me to add comments for each of my functions like Checkstyle did, which is a big plus in my book. However, ESLint is very strict and has many rules. For instance, if you have even one empty line after your code, that is an error. Not to mention, ESLint is very stern with the use of spaces when writing expressions, parameter lists, and the like. I don't know a lot about ESLint or IntelliJ currently, so I always end up having to fix each and every ESLint error manually until I get a green checkmark at the top right of my IntelliJ window, which is quite frustrating. Nevertheless, I do see the reasons why ESLint is the way it is. EsLint is just trying to ensure my code is as safe, clean, and concise as possible. Even the rule preventing an extra blank lines from being added to the end of my code serves a purpose. If there were somehow hundreds of blank lines at the end of my JavaScript file, lines I didn't notice, this would waste a lot of space. Thankfully, ESLint ensures issues like this seldom occur and is therefore a pretty handy tool.

## Credit to Coding Standards
Overall, I will not go and say that I'm the biggest fan of coding standards or the tools that enforce them. However, they should be given credit where it's due. From my programming classes, I've learned a lot through following coding rules, knowledge that will help me take on programming jobs in the real world, where organization and clarity of code is extremely important. Therefore, I will try and develop a greater appreciation of coding standards and their purpose as I continue programming.

Image Sources:
- [Checkstyle_logo](https://en.m.wikipedia.org/wiki/File:Checkstyle_Logo.png)
- [ESLint_logo](https://dev.to/glocore/understanding-eslint-configuration-35di)
