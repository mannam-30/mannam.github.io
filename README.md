webpage background template create in html code 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background Template</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <h1>Welcome to My Website</h1>
        </header>
        <main>
            <p>This is a sample template with a background image or color.</p>
        </main>
        <footer>
            <p>&copy; 2024 Your Name. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>


webpage create background template link creating code in css
/* styles.css */

body, html {
    margin: 0;
    padding: 0;
    height: 100%;
}

body {
    font-family: Arial, sans-serif;
    background: url('background.jpg') no-repeat center center fixed; /* Background image */
    background-size: cover; /* Ensure the background covers the entire page */
    /* For a solid color background, use this instead:
    background-color: #f0f0f0; 
    */
}

.container {
    display: flex;
    flex-direction: column;
    height: 100%;
}

header, footer {
    background-color: rgba(0, 0, 0, 0.7); /* Semi-transparent background */
    color: white;
    text-align: center;
    padding: 20px;
}

main {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #333;
    padding: 20px;
}

h1 {
    margin: 0;
    font-size: 2.5em;
}

p {
    font-size: 1.2em;
}

/* styles.css */

body, html {
    margin: 0;
    padding: 0;
    height: 100%;
}

body {
    font-family: Arial, sans-serif;
    background: url('background.jpg') no-repeat center center fixed; /* Background image */
    background-size: cover; /* Ensure the background covers the entire page */
    /* For a solid color background, use this instead:
    background-color: #f0f0f0; 
    */
}

.container {
    display: flex;
    flex-direction: column;
    height: 100%;
}

header, footer {
    background-color: rgba(0, 0, 0, 0.7); /* Semi-transparent background */
    color: white;
    text-align: center;
    padding: 20px;
}

main {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: #333;
    padding: 20px;
}

h1 {
    margin: 0;
    font-size: 2.5em;
}

p {
    font-size: 1.2em;
}




