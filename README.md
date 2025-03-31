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
            max-width: 600px;
            margin: 70px auto;
            background: #fff;
            padding: 50px;
            box-shadow: 0px 0px 10px #aaa;
            border-radius: 8px;
            text-align: center;
        }
        h1, h2 {
            color: #005B9F;
        }
        .contact-info {
            background: #005B9F;
            color: white;
            padding: 90px;
            border-radius: 5px;
            margin-bottom: 60px;
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
            background: #e6f2ff;
            border-radius: 5px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #005B9F;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 10px;
        }
        .button:hover {
            background-color: #00407a;
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
        /* Slow motion animation for site map */
        @keyframes slowMotion {
            0% { transform: translateY(0); }
            50% { transform: translateY(5px); }
            100% { transform: translateY(0); }
        }
        .site-map {
            animation: slowMotion 4s ease-in-out infinite;
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
            <h2>Why Us</h2>
            <p>If your business is ready to grow, it’s time to forecast. Carefully map out your goals, growth engines, and targets. Access to affordable business funding empowers business owners to prioritize sustainable growth, scale without jeopardizing day-to-day operations, and achieve long-term success. Our fair and flexible business funding products are purpose-built to protect your cash flow and keep your growth agenda on track.</p>
        </div>

        <div class="section">
            <h2>What I Do</h2>
            <ul>
                <li>Sales/ Skills Coach</li>
                <li>Mentorship</li>
                <li>Motivational Speaker</li>
                <li>Business Coach</li>
                <li>Life Coach</li>
                <li>Business Restructuring & Planning</li>
            </ul>
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

        <div class="site-map">
            <footer>
                <p>&copy; 2025 Preggie Govender. All rights reserved.</p>
                <p>Disclaimer: This website is for informational purposes only and does not constitute professional financial or real estate advice.</p>
            </footer>
        </div>
    </div>
</body>
</html>
