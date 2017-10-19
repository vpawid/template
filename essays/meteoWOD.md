---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---

Working with the Meteor framework for about two weeks and it has not been overwhelming. My previous experience with the Django framework and the structure of MVCs have made most of Meteor familiar. One thing I have yet to wrap my head around is the client-side code. What I understand of now is that the code written for the client is basically the view section, but what is the main benefit of storing a mini mongo on the client's machine? 

This new concept has created a minor problem during development. Imports and routing in any framework are convention, but meteor takes this to a new level. What I mean is that besides the usual standard libraries that need to be imported other files have to connect to each other. When you add the new concept of date processing on the client-side I  feel that the amount of imports needed doubles. This increases complexity and thus the possibilities of error as well.

That being said Meteor is another powerful tool that makes web development easier. Luckily Meteors error Logs give the developer a sense of where the problem to be debug stems. The problems I've had only reflects my inexperience with other structures of Web development frameworks.   