<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jamar Brown - Resume</title>
    <style>
        /* Basic reset and general styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        h1, h2 {
            margin-bottom: 20px;
        }
        
        /* Header styles */
        header {
            background: #35424a;
            color: white;
            padding: 30px 0;
            text-align: center;
        }
        header h1 {
            font-size: 2.5em;
        }
        
        /* Section styles */
        .section {
            background: white;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        /* Skills list style */
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            list-style-type: none;
        }
        .skills-list li {
            background: #e8491d;
            color: white;
            padding: 5px 10px;
            margin: 5px;
            border-radius: 5px;
        }
        
        /* Footer styles */
        footer {
            background: #35424a;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
        footer a {
            color: #e8491d;
        }
    </style>
</head>
<body>
    <!-- Header section -->
    <header>
        <div class="container">
            <h1>Jamar Brown</h1>
            <p>Student interested in AI and Business Technology</p>
        </div>
    </header>

    <!-- Main content -->
    <div class="container">
        <!-- About Me section -->
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod nunc in quam ultricies, a aliquam nunc tincidunt.</p>
        </section>

        <!-- Education section -->
        <section id="education" class="section">
            <h2>Education</h2>
            <p>High School Graduate</p>
            <p>Currently attending BMCC studying CIS (Computer Information Systems)</p>
        </section>

        <!-- Experience section -->
        <section id="experience" class="section">
            <h2>Experience</h2>
            <ul>
                <li>
                    <h3>Work ED AI Discovery Program at Amazon HQ (2024)</h3>
                    <p>July 1, 2024 - August 9, 2024</p>
                </li>
                <li>
                    <h3>TTMES (TakeTripsMeps)</h3>
                    <p>March 2021 - 2022</p>
                    <p>Worked on social media for the company on Instagram and created news flyers for outreach and news articles.</p>
                </li>
                <li>
                    <h3>Fedex - Keasbey, NJ</h3>
                    <p>2022 - November 2023</p>
                    <p>Package Handler/Facer: Ensured packages flow through the conveyor belt without disruption</p>
                    <p>Switcher: Driving trailers (long rails and short rails)</p>
                </li>
                <li>
                    <h3>Amazon - New York, NY</h3>
                    <p>2020 - 2021</p>
                    <p>Door to door package delivery</p>
                </li>
                <li>
                    <h3>ASG (Associated Supermarket Group) - Long Island, NY</h3>
                    <p>July 2018 - August 2018</p>
                    <p>Intern/Office Assistant: Sorted paperwork for clients, managed phone calls, learned time management and responsibility</p>
                </li>
            </ul>
        </section>

        <!-- Skills section -->
        <section id="skills" class="section">
            <h2>Skills</h2>
            <ul class="skills-list">
                <li>Time Management</li>
                <li>Punctuality</li>
                <li>Organization</li>
                <li>Multitasking</li>
                <li>Budgeting</li>
                <li>Active Listening</li>
                <li>Teamwork</li>
                <li>Flexibility</li>
                <li>Reliability</li>
                <li>Positive Attitude</li>
            </ul>
        </section>

        <!-- Certifications section -->
        <section id="certifications" class="section">
            <h2>Certifications</h2>
            <p>3 badges from the Work ED AI Discovery program</p>
        </section>

        <!-- Contact section -->
        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Phone: 929-280-9367</p>
            <p>Email: Jamarbrown854@gmail.com</p>
        </section>
    </div>

    <!-- Footer section -->
    <footer>
        <p>Connect with me on <a href="https://JamarBrownlinkedin.com" target="_blank">LinkedIn</a></p>
    </footer>

    <script>
        // JavaScript to add interactivity (e.g., smooth scrolling)
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
