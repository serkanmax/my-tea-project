<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello World</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="app">
        <h1>Hello World!</h1>
        <button onclick="changeMessage()">Change Message</button>
    </div>
    <script src="script.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello World</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div id="app">
        <h1>Hello World!</h1>
        <button onclick="changeMessage()">Change Message</button>
    </div>
    <script src="script.js"></script>
</body>
</html>


function changeMessage() {
    document.querySelector('h1').textContent = "Welcome!";
}
