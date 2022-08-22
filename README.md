<!DOCTYPE html>
<html>
    <!--Head-->
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width" />
        <title>Rammoy Lawrence</title>
        <link rel="stylesheet" type="text/css" href="./css/portfolio.css">
    </head>

    <!--Body-->
    <body class="Background">
        
        <!--Navbar-->
        <div class="Navbar">
            <a class="active" href="#Home">Home</a>
            <a href="#About_Me">About Me</a>
            <a href="#GitHub">GitHub</a>
            <a href="#Contact">Contact</a>
        </div>

        <!--Breaks inserted to add space between navbar and the first heading-->
        <br>
        <br>

        <!--Background video-->
        <div id="Home">
            <video width="640" height="480" autoplay muted loop id="Waves_Video">
                <source src="./Images/wave.mp4" type="video/mp4">
                <!--Display message if video fails to run-->
                Your browser does not support HTML5 video.
            </video>
        </div>

        <!--Video text-->
        <div class="Video_Text">
            <h1 class="white-text">Rammoy Lawrence's Portfolio</h1>
            <strong>
                <p class="center">
                    <q>We mimic our creators intentions when we develop. Thats why we're called Programmers.
                        <br>Absolute authroity sometimes it is mistaken for the divine, an unforseen property that curates this realm we are in.
                        <br>The authroity itself isn't divine, its the arrangment of it all. How it all works. Developers get the chance to peek into this divinity.
                    </q>
                </strong>
                <br>
                    <br>Hey, My name is Rammoy, welcome to my portfolio website. Here you'll learn a little about me,
                    <br>and my background as a software developer.
                    <br> Thanks for stopping by ~
                </p>
        </div>

        <!--About section-->
        <div class="Row" id="About_Me">
            <!--Left column-->
            <div class="Column_2">
                <img src="./Images/pexels.png" alt="About Me as a Software Developer">
            </div>
            <!--Right column-->
            <div class="Column_1">
                <h1>About Me</h1>
                <p>
                    Born on the small island of Jamaica, at the age of 4 with a small family of 3 (My mother, her sister and I) we migrated to America while the process to gain citizenship was nearly completed. 
                    Growing up in America exposed me to a lot of modern media early. The number one powerhouse being the internet and experiencing it during its boom in the 21st century.
                <br>  
                <br>I am currently of student enrollled in <a href="https://www.learncodinganywhere.com" target="_blank">The Tech Academy</a>’s Software
                Developer Boot Camp developing my skills in the following web & programming languages: HTML, CSS, JavaScript, SQL, C# & more.
                <br>The jounrey to becoming a full stack developer has been an interesting & humbling one. I'm always ready to learn somethhing new & new ways of solving new/old problems. <a href="#Contact">Contact</a> me below!
                </p>
            </div>
        </div>

        <!--GitHub section-->
        <div class="Row" id="GitHub">
            <!--Left column-->
            <div class="Column_1">
                <h1>GitHub</h1>
                <p>
                    I keep my porjects on GitHub.
                    <br>You can see my work and look at my profile in the link below:
                    <br>
                    <p class="center"><a href="https://github.com/RammoyL" target="_blank">Rammoy's GITHUB</a></p>
                </p>
            </div>
            <!--Right column-->
            <div class="Column_2">
                <a href="https://github.com/RammoyL" target="_blank"><img src="./Images/github.png" alt="GitHub Logo"></a>
            </div>
        </div>

        <!--Contact section-->
        <div class="Row" id="Contact">
            <!--Contact image, left column-->
            <div class="Column_2 Column_tall">
                <img src="./Images/email.png" alt="Contact Me">
            </div>
            <!--Contact form, right column-->
            <div class="Column_1 Column_tall">
                <h1>Contact</h1>
                <!--This specifies where and how to send the form data; we are leaving it blank-->
                <form action="" method="POST"> <!-- Here we are utilizing a 3rd party service to submit the contact form data, insert your formspree endpoint in the action attribute -->
                    <label>Name:</label>
                        <input type="text" placeholder="Please enter your name here">
                    <label>Email:</label>
                        <input type="text" id="Email" name="Email" placeholder="Please enter your email here">
                    <label>Message:</label>
                        <input type="text" id="Message" name="Message" placeholder="Please write your message here">
                        <input type="submit" value="SUBMIT">
                </form>
            </div>
        </div>

        <!--Footer section-->
        <footer>
            <p>
                <p class="center">&copy Prosper Consulting Inc., <a href="https://www.learncodinganywhere.com/" target="_blank">The Tech Academy</a></p>
                <br>
            </p>
        </footer>
    </body>
</html>
