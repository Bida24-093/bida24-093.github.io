<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Juniors Football Academy Application</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to Juniors Football Academy</h1>
        <p>Apply now to join our football training program!</p>
    </header>

    <section id="application-form">
        <h2>Application Form</h2>
        <p>Fill in your details to apply for the football academy:</p>
        
        <form action="https://formspree.io/f/your-form-id" method="POST">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" required><br><br>

            <label for="age">Age:</label>
            <input type="number" id="age" name="age" required><br><br>

            <label for="address">Address:</label>
            <input type="text" id="address" name="address" required><br><br>

            <label for="contact">Contact Number:</label>
            <input type="tel" id="contact" name="contact" required><br><br>

            <button type="submit">Submit Application</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Juniors Football Academy. All rights reserved.</p>
    </footer>
</body>
</html>
