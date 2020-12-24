+++
title = "my computer science experiences"
slug = "experience"
+++

### Fairness in Foods Research
In 2016 the City of Chicago introduced the [Food Inspection Forecasting project](https://chicago.github.io/food-inspections-evaluation/), a machine learning model to order food inspections to decrease the spread of food borne illnesses. The model attempts to reorder inspections so that critical violations will be found earlier. The [original code base](https://github.com/Chicago/food-inspections-evaluation) consists of a machine learning model which is written in R.

Since June of 2020, I have been working with [Professor Ian Kash](https://www.cs.uic.edu/~iankash/) and PhD candidate Shubham Singh on analyzing the **fairness of the current machine learning model and refactoring it**. We hope to provide some insight into how models can be structured in operations that heavily rely on human inspectors and opinions.

I have mainly worked in the geographical analysis using **statistical functions in R and pivot tables**. I used [CARTO](https://carto.com) to visually represent the geographical disparities we observed in the data. As we were analyzing the model, we realized that most influential features were the inspector groupings. After chatting with the original creators of the model, we found that the grouping were based on violation rates of each inspector. This was one of the features that was skewing the fairness of the model as well. So, I wrote a model that did not use the food inspectors as a feature.

Here is a [one-pager](https://docs.google.com/document/d/1Mhki-Hj8xgeoZ3l12L8nMmxaCng7g8AnVbTZS04p9fw/edit?usp=sharing) of our report to the city in November 2020! There is more coming soon!

### LifeWeb 360 Technology Intern
In the summer of 2020, I had to opportunity to intern at [LifeWeb 360](https://www.lifeweb360.com), a Chicago-based 1871 start-up. LifeWeb 360 is a web memorial platform who celebrates the life of those who are not with us and keeps their memories alive. I am inspired every day by depth of the impact LifeWeb360 make on the lives of its users every day. This summer the company was in the process of migrating from their MVP to their first built-out product.

My main project was to automate the creation of virtual memorial presentations and printed memory books. Most of the MVP was created using **GoogleApp scripts** (which is similar to **JavaScript**), so I had the opportunity build on the code base. Additionally, I was introduced to **front-end development** customizing a tumblr blog to create a group memorial with GIPCC. Being introduced to **product development** through weekly brainstorm and user interview transcript analysis allowed me to contribute to the creation of the audio memory feature.

One of my future goals, is to a found a start-up and this opportunity to work at an early age company, truly helped me understand what that experience entails. In the weekly meetings I learned a lot positioning and marketing research strategies. Having coffee chats with the 8 other incredibly talented LifeWeb-ers, introduced me to many new topics and career pathways. One of the key takeaways was a reminder to take advantage of my current stage in life and ask as many questions as I can to as many different people as I can. Thank you to the founders for giving me the opportunity to learn and grow at LifeWeb 360.

### Teaching Assistant
For the Spring and Fall semesters of 2020, I have been teaching assistant for the Computer Science department of my university. I have TA-ed for [CS 211: Programming Practicum](https://cs211.class.uic.edu), which is an introduction to pointers and other C/C++ concepts and [CS 251: Data Structures](https://catalog.uic.edu/ucat/course-descriptions/cs/), which is taught in C++. My duties included instructing labs, holding office hours, and preflighting labs and projects.

Education is an industry I am very interested in. I hope to work in education or an edutech company or start-up in the future. Being a teaching assistant, especially during covid, has allowed me to understand how different teaching styles create different classroom environments. In many of my classes, I am more fascinated by how certain concepts are taught rather than the actually concepts, so being a TA has allowed to experiment with methods of teaching concepts that I have already learned.
