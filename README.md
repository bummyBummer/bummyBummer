my-website/
├── index.html
├── style.css
└── script.js  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>My Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    
    <main>
        <p>This is a simple website created for demonstration purposes.</p>
        <button id="alert-button">Click me!</button>
    </main>
    
    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* Basic styling for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* Header styles */
header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

/* Main content styles */
main {
    padding: 2em;
    text-align: center;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
    position: absolute;
    width: 100%;
    bottom: 0;
}

/* Button styling */
button {
    padding: 0.5em 1em;
    background-color: #008cba;
    color: white;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #005f5f;
}
// When the button is clicked, show an alert
document.getElementById('alert-button').addEventListener('click', function() {
    alert('Button clicked!');
});
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/your-username/your-repo-name.git
git branch -M main
git push -u origin main
