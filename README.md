# SIT737 - Task 2.1P - Simple Web Server with Node.js and Express

## Installation & Setup
1. Install [Node.js](https://nodejs.org/) if not already installed.
2. Clone this repository:

## Explanation of the process undertaken for this task
1. Installing Node.js
2. Creating the project folder with the name sit737-2025-prac2p
3. Run **npm init -y** on the command prompt to create the package.json file
4. Installing Express using **npm install express**
5. Creating the server.js and index.html files
6. Adding the following code to the server.js file

var express = require('express');
var app = express();

app.use(express.static(__dirname))
app.listen(3000, () => {
    console.log('Server is listening on port: 3000')
})

7. Adding the following code to the index.html file

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Node.js Website</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; }
        h1 { color: rgb(5, 5, 94); }
    </style>
</head>
<body>
    <h1>Welcome to Sample Node.js Website</h1>
    <p>This page is served using Express.js.</p>
</body>
</html>

8. Running the server using **node server.js**
9. initialize git repository

git init
git add .
git commit -m "Initial commit"

10. Push the code

git remote add origin https://github.com/Binara93Lokuliyanage/sit737-2025-prac2p.git
git branch -M main
git push -u origin main
