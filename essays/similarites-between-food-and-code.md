---
layout: essay
type: essay
title: Similarities Between Food and Code
# All dates must be YYYY-MM-DD format!
date: 2022-04-28
labels:
  - Programming
  - Baking
  - Design Patterns
  - Observer
---

## I Love Food
Due to the sudden free time I (and the entire world) suddenly had at the start of 2020, my friends and I took up baking and cooking as hobbies. We started with simple foods - like cookies - and then worked our way up to making macarons. The process of making macarons is very difficult and requires a lot of precision; therefore, we not only followed one recipe, but cross compared it with other recipes in order to formulate the ideal way we could create our macarons. There were some recipes that required a stand mixer - which are expensive - and because we did not have one, we would have to seek out how to substitute it with a part of another recipe. Without any guide on how to make macarons, we would have ended up with a gunk of sugar and food coloring sandwiched between two brittle pieces of starch.
The methodologies and precision required in baking and programming run parallel to each other. Both require precise deliberation about the end product before even starting the conception of a pastry or project. Instead of recipes, programmers utilize design patterns in order to conceptualize the process to solve the intended problem. Design patterns are general solutions to common problems that are seen in programming. The programmer would change the design pattern depending on what they want achieved. Some popular design patterns include (but are not limited to) the Factory Method, Singleton, and Observer.

## I Love Programming

After learning about design patterns and some of the more common ones, I realize that I have been utilizing some of them without even knowing their categorization. 

Previously, I had dived into a side project regarding OpenCV and image recognition in the hopes of creating a bot that could perform automated tasks in a simple video game. I have not been able to find the code for it yet; however, I remember that I had created an “event handler” in the form of checking the status of the screen as the subject. Once certain buttons were visible on the screen, the bot would click them in a predetermined order. The subject kept changing but the bot was able to perform the necessary actions. 

The Observer design pattern allowed me to have as many dependencies as I needed based on the status of the screen. This simplified the process of handling each status of the screen as its own event. I was also able to easily debug any problems because each dependency was contained. For example, if a button was not being pressed, I would be able to easily identify if it was the image recognition for that certain button or if it was the event handler failing.

Design patterns have allowed me to create a structured solution to any program that I may have to create. Without it, there would be lots of “dead code”, in the form of unused variables and obsolete classes.
