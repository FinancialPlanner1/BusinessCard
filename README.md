<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Preggie Govender - Digital Business Card</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000000;
            color: #ffffff;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 90%;
            max-width: 950px;
            margin: 50px auto;
            background: #102030;
            padding: 50px;
            box-shadow: 0px 0px 10px #dedede;
            border-radius: 7px;
            text-align: center;
        }
        h1, h2 {
            color: #dedede;
        }
        .contact-info {
            background: #0a0a0a;
            color: white;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        .contact-info a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .section {
            text-align: left;
            margin-bottom: 20px;
            padding: 15px;
            background: #1a1a1a;
            border-radius: 5px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #dedede;
            color: #000000;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 10px;
        }
        .button:hover {
            background-color: #ffffff;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Preggie Govender</h1>
        <h2>Chief Inspiration Officer</h2>
        <hr>

        <div class="contact-info">
            <p><strong>Contact Me</strong></p>
            <p>Email: <a href="mailto:preggie@preggiegovender.com">preggie@preggiegovender.com</a></p>
            <p>Cell: <a href="tel:+27825511433">082 551 1433</a></p>
        </div>

        <div class="section">
            <h2>What We Do</h2>
            <p>We provide business coaching, motivational speaking, and financial planning services.</p>
        </div>

        <div class="section">
            <h2>Services Offered</h2>
            <ul>
                <li>Sales & Skills Coaching</li>
                <li>Mentorship</li>
                <li>Motivational Speaking</li>
                <li>Business Coaching</li>
                <li>Life Coaching</li>
                <li>Business Restructuring & Planning</li>
                <li>Financial Planning</li>
                <li>Investment & Estate Planning</li>
            </ul>
        </div>

        <div class="section">
            <h2>Book a Meeting</h2>
            <form action="mailto:preggie@preggiegovender.com" method="post" enctype="text/plain">
                <label for="name">Name:</label>
                <input type="text" id="name" name="Name" required>
                <br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="Email" required>
                <br>
                <label for="message">Message:</label>
                <textarea id="message" name="Message" rows="4"></textarea>
                <br>
                <button type="submit">Send Request</button>
            </form>
        </div>

        <div class="section">
            <h2>Connect with Me</h2>
            <p><a href="https://www.linkedin.com/in/preggie-govender-mr-g-30a97040/" target="_blank" class="button">LinkedIn Profile</a></p>
        </div>
    </div>
</body>
</html>
