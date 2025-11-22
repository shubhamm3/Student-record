# Student-record
Student Record API

This is a small project made using *Node.js, **Express, and **MongoDB*.  
It is used to store and manage student records.



 How to Run

1. Install all packages  
   
   npm install
   

2. Create a .env file and add  
   
   MONGO_URI=your_mongodb_link
   PORT=5000
   

3. Start the server  
   
   npm start
   



 API Routes

| Method  |   Route      | Work |

| GET     |/             | Check if server is running |
| GET     |/students     | Show all students |
| POST    |/students     | Add new student |
| PUT  `  |/students/:id | Update student |
| DELETE  |/students/:id | Delete student |



 Files

- server.js → main file  
- config/db.js → database connection  
- routes/students.js → routes for students  


 Note
Run MongoDB before starting the project.  
You can test all APIs using *Postman*.
