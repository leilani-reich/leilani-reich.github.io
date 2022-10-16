---
layout: essay
type: essay
published: true
title: Smart Questions Can Do No Wrong
# All dates must be YYYY-MM-DD format!
date: 2021-09-09
labels:
  - Software Engineering
  - StackOverFlow
---

## Introduction

<img class="ui right circular floated rounded image" src="../img/essays/stack_overflow.png" height="160" width="200">
In the world of software engineering, both up-and-coming and experienced software engineers often find themselves asking questions, whether it be regarding errors in code, programming concepts, or software issues. As a result, it's only natural that these individuals would turn to sites like [StackOverFlow](https://stackoverflow.com/) for help. However, actually receiving help from others is not as simple as it may seem; software engineers need to be able to craft smart questions.


## What constitutes a smart question?
 A smart question has a lot of criteria, as discussed by Eric Steven Raymond and Rick Moen in their article "[How to Ask Questions the Smart Way](http://www.catb.org/esr/faqs/smart-questions.html)." First of all, a smart question should be something that cannot simply be answered using Google, a manual, or any other readily available source. For instance, it would be inappropriate to add a post on a Java forum asking what an array is when that information can be found quickly on [Oracle](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/arrays.html). Next, a smart question and the post surrounding it should reveal that the questioner actually took the time to try and solve the problem and is not just searching for an easy solution. Similarly, the question itself should be well-prepared, organized, and informative. As stated by Raymond and Moen, "*The more you do to demonstrate that having put thought and effort into solving your problem before seeking help, the more likely you are to actually get help.*" It is also important that smart questions be posted on appropriate web forums, which seems pretty obvious. I definitely wouldn't go around asking members of a Windows forum how to fix an issue with my MacBook, would you? Alongside the traits I've already listed, there are also many other qualities smart questions share: they are specific, concise, courteous, easily accessible, and free from spelling and grammar mistakes. Now that we get the gist of what smart questions are, let's examine two questions asked on StackOverFlow and determine whether they are smart or not.

## StackOverFlow: Smart vs Not So Smart Questions
### Why is processing a sorted array faster than processing an unsorted array?
In this [first question](https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array), user GManNickG asked about the difference between processing times in a sorted array and an unsorted array. He provided his C++ code, pointed out where he'd sorted an array, and stated the exact runtime values of his code when this array was sorted versus unsorted. In turn, he revealed that the runtime decreased immensely when he sorted the array as opposed to when he didn't, which he found confusing. GManNickG then elaborated on his thoughts behind the differences in runtime. Particularly, he showed how he replicated his C++ code in Java to check if C++ was the culprit behind the differing processing speeds of unsorted versus sorted arrays but soon discovered that this was not the case. After discussing his thoughts and code, GManNickG ended his post by asking for help to clear up his confusion.

This question is a prime example of a smart question! First off, GManNickG's question itself is clear and concise, and his post has Java, C++, performance, cpu-architecture, and branch-prediction tags so users can understand the context surrounding the question. In addition, GManNickG posted his question on StackOverFlow, an appropriate forum for programming questions. Moving on, the actual content of his post was well-crafted. GManNickG revealed that he spent time contemplating his question, and he provided his code in a clear, concise, and easy-to-read format convenient for StackOverFlow users. With the way GManNickG wrote his post, he garnered many in-depth answers discussing something called branch prediction. In fact, StackOverFlow users even provided diagrams, tables, and code to help GManNickG understand branch prediction and how it affected the runtime of his code. The volume and quality of responses was very likely due to the way GManNickG wrote his post. Looking back at what constitutes a smart question, it is clear that GManNickG's question definitely does! But what about the next question?

### How to change variables in my JavaScript code
In the [second question](https://stackoverflow.com/questions/60568186/how-to-change-variables-in-my-javascript-code), user Salome Sulaberidze asked about how she could change variables in her code in JavaScript. In her post, Salome provided code she made to represent the current date and time and described how she wanted to replace variable declarations she initialized with "var" with "const" or "let", but was having problems doing so. 

Unlike the last question, Salome's question is a prime example of a not-so-smart question. First of all, unlike smart questions, which are clear and precise, the question Salome asked was a little ambiguous. In the header of her StackOverFlow post, she asked how to change variables in her code, but she only stated that she was referring to variable declarations specifically in the body of her post. On the topic of vagueness, Salome also failed to elaborate on the problem she was having in replacing "var" variable declarations with "const" or "let". Other users like Mitya and Stuart pointed this out, prompting Salome to state the error she was having in greater detail. Also, only one user, justDan, took the time to write a full-on response to Salome answering her question. These responses (or lack thereof) from StackOverFlow users clearly illustrate that Salome's question was not phrased in the best way. Not to mention, Salome's actual post itself had spelling mistakes and grammatical errors, such as "*wery well*" instead of "very well," errors that could have easily been fixed but weren't. Therefore, it's evident that Salome's question is not a smart question.

## The Benefits of Writing Smart Questions
It goes without saying that writing smart questions is an important practice all software engineers should follow. As I've learned from reading StackOverFlow posts, smart questions are more likely to yield smart answers and will allow you to gain the respect of others in a community. In addition, if you ask a smart question and get a response, you are going to be able to help many others who have the same question! Without a shadow of a doubt, it's clear that GManNickG's question had this impact; his post received 1.6 million views, 25812 upvotes, and 27 answers at the time of my writing this essay. Overall, I am glad that I learned about smart questions and how to use them on forums like StackOverFlow. Smart questions are sure to come in handy someday, be it in software engineering, or any other field.

Image Source: [Pixabay](https://pixabay.com/vectors/paperwork-stack-office-papers-1296324/)