

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COC GradeHub</title>
    <link rel="stylesheet" href="css/style.css">
</head>

<body>
    <header>
        <nav class="navbar">
            <a href="index.html" class="logo">COC GradeHub.</a>
                <ul class="menu-links">
                    <li><a href="index.html">Home</a></li>
                    <li><a href="Login.html">Log in</a></li>
                    <li><a href="Aboutus.html">About Us</a></li>
                    <li><a href="Contactus.html">Contact Us</a></li>
                </ul>
        </nav>
    </header>
    <section class="hero-section">
        <div class="content">
            <h1>Welcome to COC GradeHub</h1>
            <p>A system for Grade Consultation and Management.</p>
            <a href="Login.html" class="btn">Log In Now</a>
            <h6> If you have no account contact the developer</h6>
        </div>
    </section>
</body>
</html>





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - COC GradeHub</title>
    <link rel="stylesheet" href="css/login.css">
</head>
<body>
    <header>
        <nav class="navbar">
            <a href="index.html" class="logo">COC GradeHub.</a>
                <ul class="menu-links">
                    <li><a href="index.html">Home</a></li>
                    <li><a href="Login.html">Log in</a></li>
                    <li><a href="Aboutus.html">About Us</a></li>
                    <li><a href="Contactus.html">Contact Us</a></li>
                </ul>
        </nav>
    </header>
    <section class="login-section">
        <div class="login-box">
            <h1>Log In</h1>
            <form>
                <label for="username">Username</label>
                <input type="text" id="username" placeholder="Enter username" required>

                <label for="password">Password</label>
                <input type="password" id="password" placeholder="Enter password" required>

                <div class="login-buttons">
                    <a href="Student.html" class="btn">Student</a>
                    <a href="Teacher.html" class="btn">Teacher</a>
                </div>
            </form>
            <p class="note">If you have no account, contact the developer.</p>
        </div>
    </section>
</body>
</html>





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COC GradeHub - Teacher</title>
    <link rel="stylesheet" href="css/Teacher.css"> 
</head>
<body>
    <header>
        <nav class="navbar">
            <a href="Teacher.html" class="logo">COC GradeHub.</a>
            <ul class="menu-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="Login.html">Log out</a></li>
                <li><a href="Aboutus.html">About Us</a></li>
                <li><a href="Contactus.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="dashboard-section">

        <h1>Teacher Dashboard</h1>
        <input type="radio" name="teacher-tab" id="viewGrades" checked>
        <input type="radio" name="teacher-tab" id="editGrades">
        <input type="radio" name="teacher-tab" id="viewRequests">
        <input type="radio" name="teacher-tab" id="comments">

        <div class="dashboard-buttons">
            <label for="viewGrades">View Grades</label>
            <label for="editGrades">Edit Grades</label>
            <label for="viewRequests">View Requests</label>
            <label for="comments">Comments & Feedback</label>
        </div>

        <div class="dashboard-content">
            <div class="section section1" id="gradesSection">
                <h2>All Student Grades</h2>
                <p><br> Regodon: <br> Project: <br> Quiz: <br> Assignment: <br> Exam: <br> Class Standing: <br> Final Grade: <br></p><br><hr>
                <p><br> Sumahon: <br> Project: <br> Quiz: <br> Assignment: <br> Exam: <br> Class Standing: <br> Final Grade: <br></p>
            </div>

            <div class="section section2" id="editSection">
                <h2>Edit Student Grades</h2>
                <p>Select a student and type grades: </p>
                <label>Project: <input type="number" placeholder="0-100"></label><br><br>
                <label>Quiz: <input type="number" placeholder="0-100"></label><br><br>
                <label>Assignment: <input type="number" placeholder="0-100"></label><br><br>
                <label>Exam: <input type="number" placeholder="0-100"></label><br><br>
                <button class="btn-action">Submit Grades</button>
            </div>

            <div class="section section3" id="requestsSection">
                <h2>Grade Requests</h2>
                <p>Regodon requested grade review.</p>
                <p>Sumahon requested grade review.</p>
                <button class="btn-action">Clear All Requests</button>
            </div>

            <div class="section section4" id="commentsSection">
                <h2>Comments & Feedback</h2>
                <p>Regodon: Thanks</p>
                <textarea placeholder="Add comment"></textarea>
                <button class="btn-action">Submit Comment</button>
            </div>
        </div>
    </section>
</body>
</html>



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COC GradeHub</title>
    <link rel="stylesheet" href="css/Contactus.css">
</head>

<body>
    <header>
        <nav class="navbar">
            <a href="index.html" class="logo">COC GradeHub.</a>
                <ul class="menu-links">
                    <li><a href="index.html">Home</a></li>
                    <li><a href="Login.html">Log in</a></li>
                    <li><a href="Aboutus.html">About Us</a></li>
                    <li><a href="Contactus.html">Contact Us</a></li>
                </ul>
        </nav>
    </header>
    <section class="contact-section">
    <div class="contact-container">
        <h1>Contact Us</h1>
        <p>Please fill out the form below and we will get back to you as soon as possible.</p>

        <form class="contact-form">
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text" id="name" placeholder="Your full name" required>
            </div>

            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" placeholder="you@example.com" required>
            </div>

            <div class="form-group">
                <label for="phone">Phone</label>
                <input type="tel" id="phone" placeholder="+63 912 345 6789">
            </div>

            <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" placeholder="Type your message here" rows="5" required></textarea>
            </div>

            <button type="submit">Submit</button>
        </form>
    </div>
</section>
</body>
</html>





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COC GradeHub - Teacher</title>
    <link rel="stylesheet" href="css/Aboutus.css"> 
</head>
<body onload="window.scrollTo(0,0)">
    <header>
        <nav class="navbar">
            <a href="Teacher.html" class="logo">COC GradeHub.</a>
            <ul class="menu-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="index.html">Log in</a></li>
                <li><a href="Aboutus.html">About Us</a></li>
                <li><a href="Contactus.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section class="about-section">
        <h1>About Us</h1>
        <p>COC GradeHub is a student–teacher consultation system designed to streamline grade management and communication. It provides students and teachers with a centralized platform to view, request, and manage academic grades efficiently.</p>
        
        <h2>Our Mission</h2>
        <p>To enhance the academic experience by providing a simple, intuitive platform that fosters transparency, communication, and timely grade consultations between students and teachers.</p>
        
        <h2>Key Features</h2>
        <ul>
            <li>View and request grades</li>
            <li>Submit and clear grade requests</li>
            <li>Teacher feedback and comments</li>
            <li>Centralized dashboard for easy access</li>
        </ul>

        <h2>Developer <br></h2>
        <ul>
            <li>BAHIAN, ARTHJUN</li>
            <li>CAYETUNA, JUSTINE</li>
            <li>EDERANGO JR., ELIZER</li>
            <li>SUMAHON, ALDAVE</li>
            <li>TEVES, JEFF</li>
            <li>REGODON, JOHN RANIEL</li>
        </ul>
        
        <h2>Future Goals</h2>
        <p>Expansion with real-time notifications, multi-device support, and advanced analytics to better support both teachers and students.</p>
    </section>
</body>
</html>
