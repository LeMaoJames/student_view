# STUDENT_VIEW_WEB
This website help students at a english centre follow their schedule, lesson at class. Student can also view their status info at class and view entrance test result. Note that this website is still in progress.
## HOW TO INSTALL
- Make sure you have installed and set up NodeJS and posgreSQL on you PC.
- Clone the repository:
```sh
git clone https://github.com/LeMaoJames/student_view.git
cd student_view
```
- Create database:
```sh
psql -U postgres -c "CREATE DATABASE TTTA;"
```
then run the .sql file 
- Install dependencies:
```
npm install

```
- Create '.env' in root directory, add the necessary environment variables 
- Start the server
```
npm start
```
- Open your browser and go to http://localhost:3000
- Student id will be given by centre for log in, but you can log in with id "STXXXX", replace XXXX with a number not exceed 7350 for example. 
![example](ex1.png)
![example](ex2.png)