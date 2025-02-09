## Full Stack Developer - Technical Written Exam

Duration: 90 minutes
Total Marks: 100

#### Section 1: Backend Development with Laravel API (20 Marks)

1. (10 marks) Write a Laravel API endpoint to create a new user with validation rules:

```
name: required, string, max 255
email: required, email, unique in users table
password: required, min 8 characters
```

Return a response with the newly created user or validation errors.

2. (10 marks) Explain the difference between Laravel API Resource and JSON response in a controller. When should you use each?

**Section 2:** Laravel Blade Template (10 Marks)

3. (5 marks) How do you pass data from a Laravel controller to a Blade template? Provide a code example.

4. (5 marks) What is the purpose of Blade directives like @yield, @section, and @extends? Provide an example of how they are used in a layout file.

_Section 3:_ Frontend Development with React & React Native (20 Marks)

5. (10 marks) Given the API response from `https://jsonplaceholder.typicode.com/users` with Get method, Write a React functional component that fetches this data from the API and displays the users in a table format.

6. (10 marks) In a React Native project, how would you handle user authentication using JWT tokens stored securely? Explain your approach with code snippets where necessary.

_Section 4:_ Node.js with Express and Socket.io (20 Marks) 7. (10 marks) Write a Node.js Express API endpoint that allows users to send a chat message (message field) to a MongoDB database.

8. (10 marks) Implement a basic WebSocket connection using Socket.io in Node.js. The server should broadcast a message to all connected clients when a new message is received.

_Section 5:_ Relational Database & Laravel Migration (20 Marks)

9. (10 marks) Given the products table, write a Laravel migration to create a product_variants table that supports:

```
id (primary key)
product_id (foreign key referencing products.id)
color (string)
size (string)
additional_price (decimal)
```

10. (10 marks) Explain the differences between hasOne, hasMany, belongsTo, and belongsToMany relationships in Laravel Eloquent. Provide examples of when to use each.

_Section 6:_ Algorithm & Problem-Solving (10 Marks)

11. (10 marks) Write a function in JavaScript or PHP that takes an array of integers and returns the second largest number.
