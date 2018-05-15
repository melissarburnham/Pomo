Click [here](https://still-sea-86679.herokuapp.com/) for a live version of this site. 

## Description
Pomo is a teacher tool application with a dual purpose. It teaches students time management by using a pmodoro timer. Also, it is a behavior management tool that awards students coins for completing tasks and following directions. 

## Technologies Used
**Front End:** <br>
hbs, bootstrap(local copy), jquery(local copy), popper.js(local copy) <br>
**Back End:** <br>
express-generator, https-errors, morgan, bcryptjs, passport, passport-local, express-session, redis, connect-redis, express-limiter, csurf  <br>
**Development:**  <br>
ESLint (enforcement of specific code style), node-sass-middleware, mocha, chai, chai-http, Sketch app (low/high fidelity mock-ups and prototyping)

## Demo
Teachers can sign up or log in to create a class. Each class has a password for all students, but teachers can customize login names for students. 
![signup](https://github.com/melissarburnham/Pomo/blob/master/Demo/signupandaddclass.gif "Sign Up")

In each class, teachers can add/delete classes and students. 
![edit class](https://github.com/melissarburnham/Pomo/blob/master/Demo/deleteclassaddstudent.gif "edit class")

Teachers can differentiate by adding different tasks and timer amounts to each student. 
![add task](https://github.com/melissarburnham/Pomo/blob/master/Demo/assigntaskandlogout.gif "add task")

Students can log in to see their timer, task, and coin value.
![student dashboard](https://github.com/melissarburnham/Pomo/blob/master/Demo/studentdashboard.gif "student dashboard")

When the timer runs out, a 5 minute break timer (set to 10 seconds for this purpose) will appear. Then, the original timer will return until a student hits done. 
![break timer](https://github.com/melissarburnham/Pomo/blob/master/Demo/endoftimer.gif "break timer")

When students hit done, they are rewarded the coins. They can also view the store at anytime. 
![store](https://github.com/melissarburnham/Pomo/blob/master/Demo/doneandstore.gif "store")


