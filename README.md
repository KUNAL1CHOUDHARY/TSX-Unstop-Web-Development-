# TSX-Unstop-Web-Development-
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>My First Webpage</title>
    <!-- Linking external CSS -->
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <h1>Hello, World!</h1>
    <p>This is a paragraph on my first webpage.</p>

    <!-- Button -->
    <button onclick="sayHello()">Click Me</button>

    <!-- Internal JavaScript -->
    <script>
        // Logs a message when the page loads
        console.log("Page has loaded successfully.");

        function sayHello() {
            alert("You clicked the button!");
        }
    </script>
</body>

</html>
