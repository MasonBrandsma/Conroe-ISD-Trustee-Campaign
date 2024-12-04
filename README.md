
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2026 Campaign for Conroe ISD Trustee</title>
    <style>
        /* General styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #000;
        }
        header {
            background-color: #000;
            color: #ffd700;
            text-align: center;
            padding: 1.5em 0;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 0;
            font-size: 1.2em;
            font-style: italic;
        }
        section {
            padding: 2em;
            background-color: #fff;
            margin: 1em auto;
            max-width: 800px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        section h2 {
            color: #000;
            border-bottom: 2px solid #ffd700;
            padding-bottom: 0.5em;
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #000;
            color: #ffd700;
        }
        footer a {
            color: #ffd700;
            text-decoration: none;
        }
    </style>
    <script>
        function calculateAge() {
            const birthDate = new Date(2006, 3, 13); // April 13, 2006
            const today = new Date();
            let age = today.getFullYear() - birthDate.getFullYear();
            const monthDifference = today.getMonth() - birthDate.getMonth();
            if (monthDifference < 0 || (monthDifference === 0 && today.getDate() < birthDate.getDate())) {
                age--;
            }
            document.getElementById("age").textContent = age;
        }
        window.onload = calculateAge;
    </script>
</head>
<body>
    <header>
        <h1>Campaign for Conroe ISD Trustee 2026</h1>
        <p>Fresh Ideas, Bright Future for Conroe ISD</p>
    </header>
    <section id="about">
        <h2>About Me</h2>
        <p>Hello, I'm running for the Conroe ISD Trustee position in 2026 as an independent candidate. I bring a 
        fresh and young perspective, grounded in my personal connection to the district through my niece and nephew, 
        who are currently students in Conroe ISD.</p>
        <p>I was born on <strong>April 13, 2006</strong>, which makes me <span id="age"></span> years old. My commitment 
        is to bring energy, transparency, and inclusion to the board.</p>
    </section>
    <section id="priorities">
        <h2>My Priorities</h2>
        <ul>
            <li><strong>Empowering Parents:</strong> Advocating for transparency and a stronger partnership between families and schools.</li>
            <li><strong>Student Voice:</strong> Giving older students a greater say in their education to prepare them for success.</li>
            <li><strong>Inclusion:</strong> Ensuring every child, including those with disabilities, receives the respect and recognition they deserve.</li>
        </ul>
    </section>
    <section id="get-involved">
        <h2>Get Involved</h2>
        <p>Join me in shaping a brighter future for Conroe ISD! Whether you want to volunteer, share your ideas, or support the campaign, your involvement matters.</p>
        <p><strong>Contact me:</strong> Mason.Brandsma@icloud.com (281)624-6573</p>
    </section>
    <footer>
        <p>&copy; 2026 Campaign for Conroe ISD Trustee | Designed with care</p>
    </footer>
</body>
</html>
