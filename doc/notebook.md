# Case Studies in Pandas (Finance focus) 

This is meant to be a practical application of the material learned in our pandas courses.  We'd love to showcase your real-world experience in Finance in this hands-on course.  Please include how to automate Business Reporting with Python.

Skills to practice:

- Import and export df
- EDA: statistical and graphic report
- Pivoting, melting, visualizing 
- Merge, join and combine data frames
- Organize, reshape and aggregate multiple datasets

## Step 1: Brainstorming



In order to have a clear idea of what you will teach in your course, we ask that you answer the following questions. 

### What problem(s) will students learn how to solve? 

Produce a Financial Report from multiple  data sources

### What techniques or concepts will students learn? 

In this course, the students will learn to applied all the skills they have learned from previous pandas courses (import, export, explanatory data analysis, manipulate multiple datasets, etc.)

### What technologies, packages, or functions will students use? 

pandas, matplotlib, seaborn, missingno, 



## Step 2: Choose the audience

*Unaware Umberto:* Umberto's degree gave him an excellent grounding in economic theory, but the only quantitative work he did was with very small data sets using Excel and a little bit of copy-and-paste SPSS. The managers he worked with so far in his projects used more complex spreadsheets and some software packages developed in house; he hasn't yet had much exposure to R, Python, SQL, or other stars in the data science constellation, and is only vaguely aware of how they could help him. However, Umberto is constantly looking for easier and more efficient ways of doing his job tasks-at-hand to move up in his demanding career.

*Starting Sindhu:* Sindhu came out of university with expert-level knowledge of immunology, but only knows basic statistical concepts and techniques. However, needing to visualise a lot of her findings, Sindhu quickly found that nor Excel and JMP - the tools used in her team - nor SPSS - the software used in university - were as customizable as she would have liked. Moreover, she lost a lot of time building her model from scratch each time. A quick survey among research scientist friends led her to R and DataCamp. After two free courses and the relief that it was actually doable, Sindhu subscribed.

*Coder Chen:* Chen is responsible for a group of 30 programmers developing software for next-generation farm machinery. Her team is now responsible for developing applications that will help customers analyze and understand the large volumes of data being collected by sensors placed in the field and on their equipment.

*Mathematical Marta:* Marta is very comfortable with mathematical abstractions, and is able to make sense of abstruse theory quickly and easily, but even the one stats course she did eight years ago was theoretically oriented. She is aware that real-world data is sometimes messy, but hasn't had to deal with that messiness herself.

*Advanced Alex:* Having touched the basics of data science in his education, Alex is currently using Python in his job. To get better and improve his business' competitive edge, he went looking for more Python skills. Google and forums led him to try edX and DataCamp. DataCamp's renowned instructors and the fact that respected institutions use it pulled Alex in. Today, he uses DataCamp as his first foundational resource and supplements it with specific, more in depth courses on Coursera. 



## Step 3: Course Outline

Each DataCamp course typically has about the same amount of content as a half-day conference workshop (about 4 hours), and contains 4 chapters, 15 lessons, and approximately 44-60 exercises (including videos).

A typical breakdown is:

Chapter 1 has 3 lessons. This chapter is shorter than the rest since it serves as an introduction to the topic.
Chapter 2 has 4 lessons.
Chapter 3 has 4 lessons.
Chapter 4 has 4 lessons.

Each lesson is comprised of:

\- a video lesson with slides and script presenting a topic, concept, or learning outcome
\- 2-4 exercises that allow learners to apply what you've presented in the preceding video

Please refer to the sample outline here for reference:  [https://github.com/datacamp/sample-outline](https://www.google.com/url?q=https://github.com/datacamp/sample-outline&sa=D&ust=1543198121706000&usg=AFQjCNE9xD48xAufulphnCfFggfG69rwKw)

Please  submit a complete course outline. Please provide the title of each  chapter, the title of each lesson, and a brief description of each  lesson's contents including a learning objective for each lesson. 

**Looking Back: A decade after the Great Recession?**

#### Chapter 1 - Where are all the data? A review of previous pandas courses.

- Lesson 1.1 - Getting all the data in the same places
  - A learning objective: Importing several data frames into one platform using function `pd.read_csv`, `pd.read_excel`
- Lesson 1.2 - Manipulating multiple data frames
  - A learning objective: Merging several data frames based on different conditions.
- Lesson 1.3 - EDA (statistical and graphical methods)
  - A learning objective: Getting some basic statistical information from the importing data (filtering, indexing, apply, grouping)

#### Chapter 2 - How bad was The Great Depression?

- Lesson 2.1 - Introduction to IPEDS Data 
  - A learning objective: Create a map step-by-step to gain a better understanding of how your data will dictate the map you create.
- Lesson 2.2 - Mapping California Colleges 
  - A learning objective: Pan and plot a point on a map using the IPEDS case study.
- Lesson 2.3 - Labels and Pop-ups 
  - A learning objective: Center, zoom in, and plot points on the IPEDS map.
- Lesson 2.4 - Color Coding Colleges 
  - A learning objective: Enhance the appearance of the IPEDS map by  changing the color palette of the markers and adding a map legend.

#### Chapter 3 - The laser focus - Creating your own version of this analysis

- Lesson 3.1 - The Leaflet Extras Package 
  - A learning objective: Add search capabilities to your map! Find a  location by typing it in a search bar, plus find the name of a location  by clicking on a point in your map.
- Lesson 3.2 - Overlay Groups 
  - A learning objective: Clarify how your data is distributed by adding toggles to group data on your map.
- Lesson 3.3 - Base Groups 
  - A learning objective: Give your user control over their view by adding toggles between base maps.
- Lesson 3.4 - Pieces of Flair 
  - A learning objective: Create an advanced and searchable map using special features like clustering.

#### Chapter 4 - The consequences and how it changes America's economy

- Lesson 4.1 - Spatial Data 
  - A learning objective: Define your map boundaries by performing a spatial join.
- Lesson 4.2 - Mapping Polygons 
  - A learning objective: Perform exploratory data analysis using polygons to examine data missingness.
- Lesson 4.3 - Putting it All Together 
  - A learning objective: Use interactive web maps to explore and understand the properties of data.



## Step 4: Final Chapter Exercise

The best way to make the goals in Step 1 firmer is to write a full description of an exercise that students will be able to do toward the end of the course. Writing exercises early is directly analogous to test-driven development: rather than working forward from a (probably ambiguous) set of learning objectives, curriculum designers work backward from concrete examples of where their students are going. Doing this also helps uncover technical requirements that might otherwise not be found until uncomfortably late in the lesson development process. 

Please include the course's capstone exercise with the corresponding code. You may want to refer to exercises in a live DataCamp course for reference or see the example below.

Sample Python Final Exercise

![img](https://lh6.googleusercontent.com/WUpfqIlc1khGZL2iTgxDh17RYG2GkuitFyYYVa7_RKuWdt8aHaUJ75zJpawovjd3GPr45pT8jg=w740)

Please  submit your course's final exercise below. You must include context  (the text above the instructions), 4 or fewer precise instructions, and  the solution code learners will need to execute your course's final  exercise to show how far learners are likely to get by the end of your  course. Check the screenshot above for an example. Note that no more  than 15 lines of code should be provided for the exercise.

#### Exercise

#### Instructions

#### Solution code

