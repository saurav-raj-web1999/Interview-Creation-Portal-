1. Create a Database/Schema name as "interviewportal" or run the following SQL queries.
```
CREATE DATABASE interviewportal;
```
```
USE interviewportal;
```
2. Add two tables "users", to hold data of the available users and "interviews", to hold the data of the upcoming interviews. Run the following SQL query.
  ```
  CREATE TABLE users (
    name VARCHAR(100) NOT NULL,
    email_id VARCHAR(100) NOT NULL,
    PRIMARY KEY (email_id));
  ```
Add some random names with email addresses to the users tables. Run the following SQL query.
```
INSERT INTO users VALUES ('Saurav', 'sauravraj@gmail.com'), ('Manish', 'manish@gmail.com'), ('vivek', 'vivekkumar@gmail.com'), ('Aman', 'aman123@gmail.com'), ('Abhimanu', 'Abhimanu61@live.com'), 
```
Create the table interviews with fields id, email1, email2, startTime, endTime. Run the following SQL query.
```
CREATE TABLE interviews (
  id INT NOT NULL AUTO_INCREMENT,
  email1 VARCHAR(100) NOT NULL,
  email2 VARCHAR(100) NOT NULL,
  startTime DATETIME NOT NULL,
  endTime DATETIME NOT NULL,
  PRIMARY KEY (id));
```

