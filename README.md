# Course Assessment Analytics

## Table of Contents
1. [Project Overview](#project-overview)
2. [Business Rules](#business-rules)
3. [Key Objectives](#key-objectives)
4. [Data Structure](#data-structure)
5. [Queries and Insights](#queries-and-insights)
6. [Exploration](#exploration)

## Project Overview

In the realm of academia, we are embarking on an innovative endeavor - the creation of a database that will serve as a comprehensive repository for questions utilized in university courses. The primary aim of this database is to facilitate the analysis of whether the learning objectives of these courses have been effectively achieved.

### Business Rules

Our project operates under the following set of business rules:

- Within the university, an assortment of courses is offered, each instructed by a dedicated professor. The uniqueness of each course stems from the diverse array of assessment types chosen by the professors. These assessment types encompass a wide spectrum, including exams, projects, assignments, quizzes, presentations, and more.

- Professors have the autonomy to select a distinct combination of assessments for each course they teach. For example, a course such as "Introduction to Database Systems" may employ in-class activities, written exams, projects, and presentations for assessment, while avoiding the use of popup quizzes.

- Assessments are attributed specific weights by professors, and they may consist of multiple questions, each assigned individual point values. Certain assessments even provide sample solutions.

- Each question within an assessment is linked to a specific learning objective, which is categorized into six distinct levels: Knowledge, Comprehension, Application, Analysis, Synthesis, and Evaluation. Each level further contains subcategories known as Graduate Attribute Indicators (GAI).

- Professors strive to ensure comprehensive assessment coverage, ensuring that all GAIs are assessed with at least one question/assessment, and that all learning outcomes are tested with two questions throughout the term.

### Key Objectives

Through the utilization of queries within this repository, we aim to answer a variety of critical questions:

- What percentage of students successfully completed a specific course?
- To what extent do the assessments in course X align with the first learning outcome?
- What assortment of assessments were utilized for course X during a particular academic year and term?

### Data Structure

We have meticulously designed the database structure to effectively capture all the nuances of course assessments, including their types, weights, and alignment with learning objectives.

### Queries and Insights

The heart of our project lies in the myriad of queries that enable us to extract valuable insights into course assessments and learning outcomes. These queries have the potential to provide answers to pressing academic questions and drive improvements in course design and instruction.

### Exploration

We invite you to explore our project and delve into the intricacies of our database. By doing so, you'll gain invaluable insights into the world of course assessments and the achievement of learning objectives.
![ER Diagram](ERD-1.png)
