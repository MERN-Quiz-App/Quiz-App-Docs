# T3A2 - Full Stack App - Quiz App

[Netlify Link]()
    
[github repo]()

[Youtube link]()



## PURPOSE
The purpose of this application is to provide an alternative way to learn and revise knowledge on a wide range of topics.   




## FUNCTIONALITY/FEATURES
MVP features and functionalities
* Take a quiz:  
  - Choose a category  
  - Choose a quiz  
  - Quit any time
  - Skip to the next question before timer runs out
  - See total score at the end of the quiz 
  - See the correct and incorrect answers
  - Acquire badges/trophies for high achievements
  
* Make a quiz:
  - Choose an exisiting category 
  - Create a new category
  - Add questions and answers
  - Save and exit when finish
  - Quit any time

Nice-to-haves:
* Sign up and log in 
* Leaderboard

## TARGET AUDIENCE
* Quiz enthusiasts who enjoy playing informational games and learning new things
* Students who want to practise knowledge learned in class or to prepare for a test
* Teachers who want to have a fun way for their students to go through class's materials and test the students' knowledge

## USER STORIES
## STAGE 1
### TARGET AUDIENCE :
<details>

<summary><strong>1. General Users of Quiz App</strong></summary>

* As a general user of the quiz app, I want to be able to play fasinating quizzes.
* As a general user of the quiz app, I want to be able to explore quizzes from various quiz categories.
* As a general user of the quiz app, I want to be able to create new quiz questions for existing categories.
* As a general user of the quiz app, I want to be able to create new quiz categories and questions for the new category of the quiz.

</details>

<details>

<summary><strong>2. Quiz enthusiasts</strong></summary>

* As a quiz enthusiast, I want to be able to play quizzes to enhance my knowlege on various subjects to prepare for quiz competitions.
* As a quiz enthusiast, I want to be able to share my quiz knowledge with other collegues who are interested in quizzes by creating new quiz questions.

</details>

<details>
<summary><strong>3. Students</strong></summary> 

* As a student, I want to be able to play quizzes to practice knowledge learned in class or to prepare for a test.
* As a student, I want to be able to create new quiz questions for existing categories which can help other students.

</details>

<details>
<summary><strong>4. Teachers</strong></summary>

* As a teacher, I want to be able to create new quiz questions for my class students to study and revise their lessons. This will help the students to  achieve better scores in exams.

</details>
   
## STAGE 2
### USER PERSONAS :
To better understand our target audience User Personas were created so that we could learn more about the goals and needs of our users. The below details were consolidated upon consulting with the the target audience on their goal and experiences in achieving their goals. 

#### Quiz enthusiasts
  
Goals :
- Being a quiz enthusiast, I am always looking for every opportunity to learn new things and practice my knowledge.
- I always want to challenge myself and have constant checks on my knowledge level.
- I always wanted to exhibit my knowledge on various subjects by creating Quiz an challege others.
- It is always exhilarating to compete against other quiz enthusists.

Challenges :
- It has been very difficult to get a proper application where I can do my practice quiz and check my level of knowledge.
- There are very less options currently available where I can create my own quizzes.  

#### Students 
  
Goals :
- As a student, I am always keen to gain my knowledge on various school subject and also revise as part exam prep.
- It is great to have a place where I can compete with the schoolmates and be the best.
- It would be great to have an application where my teacher can set quizzes for me and this gives an opportunity for me to evaluate myself.

Challenges :
- The knowledge i get from books are usually tested during exams, the absense of a proper way to test my knowledge regularly, affects my learning and revision. 
- Showcasing my knowledge and what I have learned from the classes to my teachers are currently only through the periodic exams and assignements.
  
#### Teachers 
  
Goals :
- As a teacher, I am always curious about my students learning curve. 
- I am looking for a platform where I can set up regular challenges and quiz which can help my student in their learning.
- It is always great to have a place where I can have a constant check if my students are imrpving themselves. 

Challenges :
- Other that periodic exams and assignments, it is never possible to evaluate my students learning curve.
  

### USER STORY : Application Architecture Diagram (MVP)

Create a visual representation of the various components, modules, and interfaces that make up a software application and how they interact with each other. The AAD will include elements such as the user interface, business logic, data storage, and external systems and services.

### USER STORY : Create Wire frame (MVP)

Create a low-fidelity, visual representation of a user interface (UI) design, typically used during the early stages of the design process. The wireframe will be a simple, blueprint-like representation of the layout and functionality of a website or application, showing the placement of elements such as text, images, and buttons

### USER STORY : Environment setup (MVP)

Setting up the environment for project. Including the git repo, installing the dependecies etc.

### USER STORY : Log-in
<details>

* As a user, I want to have the ability to login to the Quiz application by passing my username and password.
* As a user, I want to have the ability to be denied access to the Quiz application when I try to login with incorrect credentials.

</details>

### USER STORY : Route:Quiz Data Preparation (MVP)

Prepare the initial data for the quiz application for testing purposes.

### USER STORY : Route:Take a Quiz (MVP)
<details>

* As a user, I want to be able to explore multiple categories of quizzes
* As a user, I want to have the ability to take quizzes from any chosen category.
* As a user, I want to have the ability to see the time countdown for completing each quiz question.
* As a user, I want to have the ability to submit each questions before the time countdown completes.
* As a user, I want to have the ability to have the quiz questions to be submited automatically when the time countdown becomes zero.
* As a user, I want to have the ability to see the result of the quiz attempt.

</details>

### USER STORY : Route:Create Quiz Category
<details>

* As a user, I want to have the the ability to create new quiz category.
* As a user, I want to have the ability to upload a category image to set against the new quiz category created.

</details>

### USER STORY : Route:Create Quiz Questions
<details>

* As a user, I want to have the ability to create new quiz questions for existing categories.
* As a user, I want to have the ability to create new quiz questions for new categories created.

</details>

### USER STORY : Route:Quiz Leaderboard & Stats
<details>

* As a user who has logged in, I want to have the ability to view the leaderboard and stats of my quiz performance.

</details>

### USER STORY : Pop up messages for Quiz wins
<details>

* As a user, I want to have the ability to get badges or pop messages as a way to celebrate the winning of quiz challenge.

</details>

## Dataflow diagram


## Application Architecture Diagram
![Application Architecture Diagram](./docs/Application%20Architecture%20Diagram.jpg)


## Wireframe screenshots

## Trello screenshots

## TECH STACK
### Front-end
* HTML
* CSS
* JavaScript
* React
### Back-end
* Express
* Node.js
### Object Data Modeling
* Mongoose
### Database
* MongoDB
### Deployment 
* Netlify (?!)
* Railway
### Project Management Tools
* Trello
* Google Docs
* Discord
### Testing
* Vitest
* Jest
### DevOps
* git
* GitHub
* Visual Studio Code
### Design Tools
* Figma