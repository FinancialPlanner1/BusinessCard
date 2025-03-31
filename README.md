<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Preggie Govender - Digital Business Card</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .container {
            width: 90%;
            margin: 65px auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0px 0px 10px #aaa;
            border-radius: 8px;
            text-align: center;
        }
        h1, h2 {
            color: #005B9F;
        }
        .contact-info, .services {
            background: #005B9F;
            color: white;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        .contact-info a, .linkedin a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .section {
            text-align: left;
            margin-bottom: 20px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #005B9F;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 20px;
        }
        .button:hover {
            background-color: #00407a;
        }
        footer {
            text-align: center;
            background-color: #f4f4f9;
            padding: 10px;
            margin-top: 40px;
            font-size: 0.9em;
        }
        .meeting-form {
            background: #e6f2ff;
            padding: 15px;
            border-radius: 5px;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background: #005B9F;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
        }
        button:hover {
            background: #00407a;
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
            <h2>Property</h2>
            <p>Sales Manager | Sales & Rental</p>
        </div>

        <div class="section">
            <h2>Loans</h2>
            <p>Short-term funding and bridging finance</p>
        </div>

        <div class="section">
            <h2>StepChain</h2>
            <p>Monetize your steps. Get paid for walking and playing brain games.</p>
            <p>Improve your mental and physical health.</p>
        </div>

        <div class="linkedin">
            <h2>Connect with Me</h2>
            <p><a href="https://www.linkedin.com/in/preggie-govender-mr-g-30a97040/" target="_blank" class="button">Connect on LinkedIn</a></p>
        </div>

        <div class="section meeting-form">
            <h2>Book a Meeting</h2>
            <form action="mailto:preggie@preggiegovender.com" method="post" enctype="text/plain">
                <label for="name">Name:</label>
                <input type="text" id="name" name="Name" required>

                <label for="surname">Surname:</label>
                <input type="text" id="surname" name="Surname" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="Email" required>

                <label for="contact">Contact Number:</label>
                <input type="tel" id="contact" name="Contact" required>

                <label for="message">Additional Details (Optional):</label>
                <textarea id="message" name="Message" rows="4"></textarea>

                <button type="submit">Send Meeting Request</button>
            </form>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Preggie Govender. All rights reserved.</p>
        <p>Disclaimer: This website is for informational purposes only and does not constitute professional financial or real estate advice.</p>
    </footer>
</body>
</html>
