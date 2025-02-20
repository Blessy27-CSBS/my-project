

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colorful Web Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Web Page</h1>
    </header>
    <main>
        <section class="colorful-section">
            <h2>Section 1</h2>
            <p>This is a sample text for section 1.</p>
        </section>
        <section class="colorful-section">
            <h2>Section 2</h2>
            <p>This is a sample text for section 2.</p>
        </section>
        <section class="colorful-section">
            <h2>Section 3</h2>
            <p>This is a sample text for section 3.</p>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>


# CSS (styles.css)

body {
    background-color: #000; /* Black background */
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333; /* Dark gray background */
    color: #fff; /* White text color */
    padding: 20px;
    text-align: center;
}

main {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
}

.colorful-section {
    background-color: #fff; /* White background */
    border: 1px solid #ddd; /* Light gray border */
    margin-bottom: 20px;
    padding: 20px;
    width: 80%;
}

.colorful-section:nth-child(1) {
    background-color: #f44336; /* Red background */
    color: #fff; /* White text color */
}

.colorful-section:nth-child(2) {
    background-color: #2196f3; /* Blue background */
    color: #fff; /* White text color */
}

.colorful-section:nth-child(3) {
    background-color: #8bc34a; /* Green background */
    color: #fff; /* White text color */
}


# JavaScript (script.js)

// You can add JavaScript code here to enhance the functionality of your web page.


This code creates a basic web page with a black background, a dark gray header, and three colorful sections with white text. You can customize the styles and add more content as needed.

Save the HTML, CSS, and JavaScript code in separate files (index.html, styles.css, and script.js) and open the index.html file in a web browser to view the web page.
