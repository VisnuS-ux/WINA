
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Win Badminton Academy</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 0 20px;
        }

        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: 3px solid #e8491d;
        }

        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }

        header ul {
            padding: 0;
            margin: 0;
            list-style: none;
            overflow: hidden;
        }

        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }

        header #branding {
            float: left;
        }

        header #branding h1 {
            margin: 0;
        }

        header nav {
            float: right;
            margin-top: 10px;
        }

        header .highlight, header .current a {
            color: #e8491d;
            font-weight: bold;
        }

        header a:hover {
            color: #ccc;
            font-weight: bold;
        }

        #showcase {
            min-height: 400px;
            background: url('badminton-bg.jpg') no-repeat 0 -100px;
            text-align: center;
            color: #fff;
        }

        #showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }

        #showcase p {
            font-size: 20px;
        }

        #newsletter {
            padding: 15px;
            color: #fff;
            background: #333;
        }

        #newsletter h1 {
            float: left;
        }

        #newsletter form {
            float: right;
            margin-top: 15px;
        }

        #newsletter input[type="email"] {
            padding: 4px;
            height: 25px;
            width: 250px;
        }

        .button_1 {
            height: 38px;
            background: #e8491d;
            border: 0;
            padding-left: 20px;
            padding-right: 20px;
            color: #fff;
        }

        #boxes {
            margin-top: 20px;
        }

        #boxes .box {
            float: left;
            width: 30%;
            padding: 10px;
            text-align: center;
        }

        #boxes .box img {
            width: 90px;
        }

        footer {
            padding: 20px;
            margin-top: 20px;
            color: #fff;
            background-color: #e8491d;
            text-align: center;
        }

        article#main-col {
            float: left;
            width: 65%;
        }

        aside#sidebar {
            float: right;
            width: 30%;
            margin-top: 10px;
        }

        aside#sidebar .quote input, aside#sidebar .quote textarea {
            width: 90%;
            padding: 5px;
        }

        .dark {
            padding: 15px;
            background: #35424a;
            color: #fff;
            margin-top: 10px;
            margin-bottom: 10px;
        }

        /* Services Page */
        ul#services {
            padding: 0;
            list-style: none;
        }

        ul#services li {
            border: #ccc solid 1px;
            padding: 20px;
            margin-bottom: 5px;
            background: #e6e6e6;
        }

        /* Responsive Styling */
        @media(max-width: 768px) {
            header #branding,
            header nav,
            header nav li,
            #newsletter h1,
            #newsletter form,
            #boxes .box,
            article#main-col,
            aside#sidebar {
                float: none;
                text-align: center;
                width: 100%;
            }

            header {
                padding-bottom: 20px;
            }

            #showcase h1 {
                margin-top: 40px;
            }

            #newsletter form {
                margin-top: 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">WIN</span> Badminton Academy</h1>
            </div>
            <nav>
                <ul>
                    <li class="current"><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="services.html">Services</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="showcase">
        <div class="container">
            <h1>PROFESSIONAL COACHING | REAL PROGRESS | REAL VICTORY</h1>
            <p>Empowering athletes of all ages to achieve their badminton dreams.</p>
        </div>
    </section>

    <section id="newsletter">
        <div class="container">
            <h1>Subscribe To Our Newsletter</h1>
            <form>
                <input type="email" placeholder="Enter Email...">
                <button type="submit" class="button_1">Subscribe</button>
            </form>
        </div>
    </section>

    <section id="boxes">
        <div class="container">
            <div class="box">
                <img src="coach.png" alt="Coaching">
                <h3>Experienced Coaches</h3>
                <p>Learn from the best with our team of experienced and certified badminton coaches.</p>
            </div>
            <div class="box">
                <img src="training.png" alt="Training">
                <h3>Comprehensive Training</h3>
                <p>We offer a range of training programs for all skill levels, from beginners to advanced players.</p>
            </div>
            <div class="box">
                <img src="tournament.png" alt="Tournaments">
                <h3>Tournament Ready</h3>
                <p>Prepare for competitive play with our elite training program and tournament preparation.</p>
            </div>
        </div>
    </section>

    <section class="dark">
        <div class="container">
            <article id="main-col">
                <h1>About Us</h1>
                <p>WIN Badminton Academy was established in 2019 in Seremban by former national player Mr. Thanesh Veerappan and his father. WIN Badminton Academy is supported by a team of experienced coaches and is witnessing a steady increase in the number of trainees. Through its commitment to quality coaching, athlete development, and community engagement, WIN Badminton Academy is dedicated to shaping the future of badminton in Malaysia.</p>
                <p><strong>Our Vision:</strong> To be a leading badminton academy in Malaysia that empowers individuals to lead healthy lifestyles and achieve excellence in sport through structured training and continuous development.</p>
                <p><strong>Our Mission:</strong> To deliver professional badminton training in a safe, supportive, and inclusive environment. We aim to promote the physical, mental, and social benefits of sports while developing confident, disciplined, and high-performing athletes.</p>
            </article>

            <aside id="sidebar">
                <div class="dark">
                    <h3>Get a Quote</h3>
                    <form class="quote">
                        <div>
                            <label>Name</label><br>
                            <input type="text" placeholder="Name">
                        </div>
                        <div>
                            <label>Email</label><br>
                            <input type="email" placeholder="Email Address">
                        </div>
                        <div>
                            <label>Message</label><br>
                            <textarea placeholder="Message"></textarea>
                        </div>
                        <button class="button_1" type="submit">Send</button>
                    </form>
                </div>
            </aside>
        </div>
    </section>

    <footer>
        <p>Win Badminton Academy, Copyright &copy; 2024</p>
    </footer>
</body>
</html>
```

```html project="WinBadmintonAcademy" file="about.html" version=1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - Win Badminton Academy</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 0 20px;
        }

        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: 3px solid #e8491d;
        }

        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }

        header ul {
            padding: 0;
            margin: 0;
            list-style: none;
            overflow: hidden;
        }

        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }

        header #branding {
            float: left;
        }

        header #branding h1 {
            margin: 0;
        }

        header nav {
            float: right;
            margin-top: 10px;
        }

        header .highlight, header .current a {
            color: #e8491d;
            font-weight: bold;
        }

        header a:hover {
            color: #ccc;
            font-weight: bold;
        }

        #newsletter {
            padding: 15px;
            color: #fff;
            background: #333;
        }

        #newsletter h1 {
            float: left;
        }

        #newsletter form {
            float: right;
            margin-top: 15px;
        }

        #newsletter input[type="email"] {
            padding: 4px;
            height: 25px;
            width: 250px;
        }

        .button_1 {
            height: 38px;
            background: #e8491d;
            border: 0;
            padding-left: 20px;
            padding-right: 20px;
            color: #fff;
        }

        footer {
            padding: 20px;
            margin-top: 20px;
            color: #fff;
            background-color: #e8491d;
            text-align: center;
        }

        article#main-col {
            float: left;
            width: 65%;
        }

        aside#sidebar {
            float: right;
            width: 30%;
            margin-top: 10px;
        }

        .dark {
            padding: 15px;
            background: #35424a;
            color: #fff;
            margin-top: 10px;
            margin-bottom: 10px;
        }

        /* Responsive Styling */
        @media(max-width: 768px) {
            header #branding,
            header nav,
            header nav li,
            #newsletter h1,
            #newsletter form,
            article#main-col,
            aside#sidebar {
                float: none;
                text-align: center;
                width: 100%;
            }

            header {
                padding-bottom: 20px;
            }

            #newsletter form {
                margin-top: 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">WIN</span> Badminton Academy</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li class="current"><a href="about.html">About</a></li>
                    <li><a href="services.html">Services</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="newsletter">
        <div class="container">
            <h1>Subscribe To Our Newsletter</h1>
            <form>
                <input type="email" placeholder="Enter Email...">
                <button type="submit" class="button_1">Subscribe</button>
            </form>
        </div>
    </section>

    <section class="dark">
        <div class="container">
            <article id="main-col">
                <h1>About Us</h1>
                <p>WIN Badminton Academy was established in 2019 in Seremban by former national player Mr. Thanesh Veerappan and his father. WIN Badminton Academy is supported by a team of experienced coaches and is witnessing a steady increase in the number of trainees. Through its commitment to quality coaching, athlete development, and community engagement, WIN Badminton Academy is dedicated to shaping the future of badminton in Malaysia.</p>
                <p><strong>Our Vision:</strong> To be a leading badminton academy in Malaysia that empowers individuals to lead healthy lifestyles and achieve excellence in sport through structured training and continuous development.</p>
                <p><strong>Our Mission:</strong> To deliver professional badminton training in a safe, supportive, and inclusive environment. We aim to promote the physical, mental, and social benefits of sports while developing confident, disciplined, and high-performing athletes.</p>
            </article>

            <aside id="sidebar">
                <div class="dark">
                    <h3>What We Offer</h3>
                    <p>Our academy provides top-notch badminton training for all ages and skill levels. Whether you're a beginner or an advanced player, we have a program to help you reach your goals.</p>
                </div>
            </aside>
        </div>
    </section>

    <footer>
        <p>Win Badminton Academy, Copyright &copy; 2024</p>
    </footer>
</body>
</html>
```

```html project="WinBadmintonAcademy" file="services.html" version=1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Services - Win Badminton Academy</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 0 20px;
        }

        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: 3px solid #e8491d;
        }

        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }

        header ul {
            padding: 0;
            margin: 0;
            list-style: none;
            overflow: hidden;
        }

        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }

        header #branding {
            float: left;
        }

        header #branding h1 {
            margin: 0;
        }

        header nav {
            float: right;
            margin-top: 10px;
        }

        header .highlight, header .current a {
            color: #e8491d;
            font-weight: bold;
        }

        header a:hover {
            color: #ccc;
            font-weight: bold;
        }

        #newsletter {
            padding: 15px;
            color: #fff;
            background: #333;
        }

        #newsletter h1 {
            float: left;
        }

        #newsletter form {
            float: right;
            margin-top: 15px;
        }

        #newsletter input[type="email"] {
            padding: 4px;
            height: 25px;
            width: 250px;
        }

        .button_1 {
            height: 38px;
            background: #e8491d;
            border: 0;
            padding-left: 20px;
            padding-right: 20px;
            color: #fff;
        }

        footer {
            padding: 20px;
            margin-top: 20px;
            color: #fff;
            background-color: #e8491d;
            text-align: center;
        }

        article#main-col {
            float: left;
            width: 65%;
        }

        aside#sidebar {
            float: right;
            width: 30%;
            margin-top: 10px;
        }

        .dark {
            padding: 15px;
            background: #35424a;
            color: #fff;
            margin-top: 10px;
            margin-bottom: 10px;
        }

        /* Services Page */
        ul#services {
            padding: 0;
            list-style: none;
        }

        ul#services li {
            border: #ccc solid 1px;
            padding: 20px;
            margin-bottom: 5px;
            background: #e6e6e6;
        }

        /* Responsive Styling */
        @media(max-width: 768px) {
            header #branding,
            header nav,
            header nav li,
            #newsletter h1,
            #newsletter form,
            article#main-col,
            aside#sidebar {
                float: none;
                text-align: center;
                width: 100%;
            }

            header {
                padding-bottom: 20px;
            }

            #newsletter form {
                margin-top: 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">WIN</span> Badminton Academy</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li class="current"><a href="services.html">Services</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="newsletter">
        <div class="container">
            <h1>Subscribe To Our Newsletter</h1>
            <form>
                <input type="email" placeholder="Enter Email...">
                <button type="submit" class="button_1">Subscribe</button>
            </form>
        </div>
    </section>

    <section class="dark">
        <div class="container">
            <article id="main-col">
                <h1>Our Services</h1>
                <ul id="services">
                    <li>
                        <h3>Group Training</h3>
                        <p><strong>Junior Level:</strong> Badminton training for young players.</p>
                        <p><strong>Senior Level:</strong> Advanced group training for experienced players.</p>
                        <p><strong>Adults:</strong> Group sessions for adult badminton enthusiasts.</p>
                    </li>
                    <li>
                        <h3>Personalised Private Training</h3>
                        <p>One-to-One, One-to-Two, One-to-Three, One-to-Four training sessions tailored to individual needs.</p>
                    </li>
                    <li>
                        <h3>Strength & Conditioning Training</h3>
                        <p>Guidance on physical conditioning, injury prevention, and nutrition to complement technical training and enhance overall athletic performance.</p>
                    </li>
                    <li>
                        <h3>Elite Training Program</h3>
                        <p>Advanced training for high-potential players who are preparing for competitive play. The program emphasizes technical refinement, mental toughness, and tournament preparation.</p>
                    </li>
                    <li>
                        <h3>Athlete Development Program</h3>
                        <p>A specific conditioning program will be developed according to athletes' sports needs. Athletes will be trained in a high-energy, result-driven environment while maintaining the individualized attention that proper athletic development requires.</p>
                    </li>
                    <li>
                        <h3>School & Corporate Team Training Program</h3>
                        <p>We offer customized badminton training programs tailored for corporate organizations and schools.</p>
                    </li>
                    <li>
                        <h3>Organizing Tournaments</h3>
                        <p>Hosting and managing tournaments to provide real match experience and exposure for players.</p>
                    </li>
                </ul>
            </article>

            <aside id="sidebar">
                <div class="dark">
                    <h3>Contact Us</h3>
                    <p>For more information about our services, please contact us today!</p>
                </div>
            </aside>
        </div>
    </section>

    <footer>
        <p>Win Badminton Academy, Copyright &copy; 2024</p>
    </footer>
</body>
</html>
```
Here's a basic website structure for the Win Badminton Academy. I've created three HTML files: `index.html` (Homepage), `about.html` (About Us), and `services.html` (Our Services).

Key features:

*   **Homepage (`index.html`):**
    *   Headline: "PROFESSIONAL COACHING | REAL PROGRESS | REAL VICTORY"
    *   Brief overview and call to action.
    *   Three boxes highlighting key aspects: Experienced Coaches, Comprehensive Training, Tournament Ready.
    *   About Us section with the academy's founding details, vision, and mission.
*   **About Us Page (`about.html`):**
    *   Detailed information about the academy's history, vision, and mission.
*   **Services Page (`services.html`):**
    *   Comprehensive list of services offered, including:
        *   Group Training (Junior, Senior, Adults)
        *   Personalized Private Training
        *   Strength & Conditioning Training
        *   Elite Training Program
        *   Athlete Development Program
        *   School & Corporate Team Training
        *   Organizing Tournaments

To make this website fully functional, you would need to:

*   Replace placeholder images (`coach.png`, `training.png`, `tournament.png`, and `badminton-bg.jpg`) with actual images.
*   Implement the form submission for the newsletter and "Get a Quote" sections.
*   Add more detailed content to each section.
*   Incorporate CSS for better styling and responsiveness.
*   Consider adding JavaScript for interactive elements.

I have used inline CSS for styling to keep the example simple and self-contained. For a real project, it's better to use an external CSS file.
