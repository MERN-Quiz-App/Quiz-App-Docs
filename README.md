# T3A2 - Full Stack App - Quiz App

[Netlify Link]()
    
[github repo]()

[Youtube link]()


## PURPOSE
There are three main purposes of this application: 
1. The application's first purpose is an education tool to help people learn a fun way. Therefore, the application is an effort to encourage learning for all ages.  
   
2. To be used as a resource for teaching and assessment. This application is suitable to use in a classroom to make lessons interactive and interesting. Features such as creating new quizzes under different categories can make the learning experience more customisable.
   
3. At the end of the day, the application is a game, so it aims to entertain. The user/player can use it as a light-hearted way to wind down, or as a challenge to their friends.


## FUNCTIONALITY/FEATURES
MVP features and functionalities
* Take a quiz:  
  - Choose a category  
  - Choose a quiz  
  - Quit any time
  - See the quiz progress (i.e. question 5/15)
  - Skip to the next question before timer runs out
  - See total score at the end of the quiz 
  - See the correct and incorrect answers
  - Pop-up alert for high achievements
  
* Make a quiz:
  - Choose an exisiting category 
  - Create a new category
  - Specify the number of questions in a quiz
  - Add questions and answers
  - Save and exit when finished
  - Quit any time

* Edit a quiz:
  - Delete an entire quiz with all its questions and answers
  - Add, edit, delete questions
  - Add, edit, delete answers
  - Save and exit when finished

Nice-to-haves:
* Change timer duration for individual question
* User portal
  - Sign in
  - Edit user's information
  - Delete account
* Authorization 
  - Only registered users can create a new quiz 
  - Only admins and the quiz creator can edit or delete the quiz
* Sign up  
 - Sign up with a valid email address and password
* Leaderboard  
 - View users with high total points

## TARGET AUDIENCE
* Quiz enthusiasts who enjoy playing informational games and learning new things
* Students who want to practise knowledge learned in class or to prepare for a test
* Teachers who want a fun way to teach or to assess students' knowledge (i.e. homework and tests)

## USER STORIES
## STAGE 1
<details>

<summary><strong>1. General Users of Quiz App</strong></summary>

* As a general user of the quiz app, I want to be able to play fascinating quizzes on multiple topics.
</details>

<details>

<summary><strong>2. Quiz enthusiasts</strong></summary>

* As a quiz enthusiast, I want to be able to play quizzes to enhance my knowlege on various subjects to prepare for quiz competitions and track my performance.
</details>

<details>
<summary><strong>3. Students</strong></summary> 

* As a student, I want to be able to play quizzes to practice knowledge learned in class or to prepare for a test in a fun way.
</details>

<details>
<summary><strong>4. Teachers</strong></summary>

* As a teacher, I want to be able to create new quiz questions for my class students to study and revise their lessons in an entertaining and less stressful way.
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
- I wanted to have an app which is free and simple to use. 

Challenges :
- It has been very difficult to get a proper application where I can do my practice quiz and check my level of knowledge.
- Most applications which are currently available are complicated and paid ones. 
- There are very less options currently available where I can create my own quizzes.  

#### Students 
  
Goals :
- As a student, I am always keen to gain my knowledge on various school subject and also revise as part exam prep.
- It is great to have a place where I can compete with the schoolmates and be the best.
- It would be great to have an application where my teacher can set quizzes for me and this gives an opportunity for me to evaluate myself.
- I always wanted to learn things in a fun way.

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
- It is always stressful to track and evaluate my students learning, It would be great to have an app that make this easier. 
  

## Stage 3

<details>

<summary><strong>1. General Users of Quiz App</strong></summary>

* As a general user of the quiz app, I want to be able to play fascinating quizzes.
* As a general user of the quiz app, I want to be able to explore quizzes from various quiz categories.
* As a general user of the quiz app, I want to be able to create new quiz questions for existing categories.
* As a general user of the quiz app, I want to be able to create new quiz categories and questions for the new category of the quiz.
* As a general user of the quiz app, I want to be able to have the option for editing and deleting the quiz questions.
* As a general user of the quiz app, I want to be able to create new user profiles. 

</details>

<details>

<summary><strong>2. Quiz enthusiasts</strong></summary>

* As a quiz enthusiast, I want to be able to play quizzes to enhance my knowlege on various subjects to prepare for quiz competitions.
* As a quiz enthusiast, I want to be able to share my quiz knowledge with other collegues who are interested in quizzes by creating new quiz questions.
* As a quiz enthusiast, I want to be able to view and track my quiz performances as a leaderboard feature.

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
![Dataflow diagram](docs/Dataflow%20diagram.jpg)

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
* Netlify
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
