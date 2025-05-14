# job-portal
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Home - Job Portal</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #f5f5f5;
    }

    /* Navbar */
    header {
      background-color: #333;
      padding: 15px 0;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
    }

    nav ul li {
      margin: 0 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 18px;
    }

    nav ul li a:hover {
      color: #00bcd4;
    }

    /* Welcome Section */
    .welcome {
      text-align: center;
      padding: 100px 20px;
      background-color: #007BFF;
      color: white;
    }

    .welcome h1 {
      font-size: 50px;
      margin-bottom: 20px;
    }

    .welcome p {
      font-size: 22px;
      max-width: 600px;
      margin: 0 auto;
    }

    /* About Section */
    .about {
      max-width: 1000px;
      margin: 50px auto;
      padding: 20px;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .about h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #333;
    }

    .about p {
      font-size: 18px;
      color: #555;
      line-height: 1.6;
      text-align: center;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background-color: #333;
      color: white;
      margin-top: 50px;
    }
  </style>
</head>

<body>

  <!-- Header & Navigation -->
  <header>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
            <li><a href="job.html">Jobs</a></li>
            <li><a href="company.html">Companies</a></li>
            <li><a href="about.html">About us</a></li>
            <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Welcome Section -->
  <section class="welcome">
    <h1>Welcome to Job Portal</h1>
    <p>Your dream job is just a click away. Discover exciting career opportunities today!</p>
  </section>

  <!-- About Section -->
  <section class="about">
    <h2>Why Choose Us?</h2>
    <p>We connect job seekers with top companies worldwide. Our platform is designed to make job hunting easier, faster, and more reliable. Start your journey with us today and take your career to the next level!</p>
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 Job Portal | All Rights Reserved
  </footer>

</body>
</html>

#jobs

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Jobs - Job Portal</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #f9f9f9;
    }

    /* Navbar */
    header {
      background-color: #333;
      padding: 15px 0;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
    }

    nav ul li {
      margin: 0 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 18px;
    }

    nav ul li a:hover {
      color: #00bcd4;
    }

    /* Job List Section */
    .jobs-container {
      max-width: 1000px;
      margin: 40px auto;
      padding: 20px;
    }

    .job-card {
      background: white;
      padding: 25px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .job-card:hover {
      transform: scale(1.02);
    }

    .job-card h3 {
      color: #333;
      margin-bottom: 10px;
    }

    .job-card p {
      color: #555;
      margin-bottom: 10px;
    }

    .job-card .apply-btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #007BFF;
      color: white;
      border-radius: 5px;
      text-decoration: none;
      font-size: 16px;
    }

    .job-card .apply-btn:hover {
      background-color: #0056b3;
    }

    /* Footer */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
  </style>
</head>

<body>

  <!-- Header & Navigation -->
  <header>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="#">Jobs</a></li>
        <li><a href="company.html">Companies</a></li>
        <li><a href="about.html">About us</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Jobs List -->
  <section class="jobs-container">
    <h1 style="text-align:center; margin-bottom: 30px;">Available Jobs</h1>

    <div class="job-card">
      <h3>Software Developer</h3>
      <p><strong>Company:</strong> Tech Solutions</p>
      <p><strong>Location:</strong> New York, USA</p>
      <p><strong>Experience:</strong> 2+ years</p>
      <a href="#" class="apply-btn">Apply Now</a>
    </div>

    <div class="job-card">
      <h3>Graphic Designer</h3>
      <p><strong>Company:</strong> Creative Minds</p>
      <p><strong>Location:</strong> London, UK</p>
      <p><strong>Experience:</strong> 1+ year</p>
      <a href="#" class="apply-btn">Apply Now</a>
    </div>

    <div class="job-card">
      <h3>Marketing Manager</h3>
      <p><strong>Company:</strong> Global Marketing Ltd.</p>
      <p><strong>Location:</strong> Sydney, Australia</p>
      <p><strong>Experience:</strong> 5+ years</p>
      <a href="#" class="apply-btn">Apply Now</a>
    </div>

  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 Job Portal | All Rights Reserved
  </footer>

</body>
</html>


#companies
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Companies - Job Portal</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #f9f9f9;
    }

    /* Navbar */
    header {
      background-color: #333;
      padding: 15px 0;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
    }

    nav ul li {
      margin: 0 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 18px;
    }

    nav ul li a:hover {
      color: #00bcd4;
    }

    /* Companies List Section */
    .companies-container {
      max-width: 1000px;
      margin: 40px auto;
      padding: 20px;
    }

    .company-card {
      background: white;
      padding: 25px;
      margin-bottom: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .company-card:hover {
      transform: scale(1.02);
    }

    .company-card h3 {
      color: #333;
      margin-bottom: 10px;
    }

    .company-card p {
      color: #555;
      margin-bottom: 10px;
    }

    .company-card .visit-btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 20px;
      background-color: #007BFF;
      color: white;
      border-radius: 5px;
      text-decoration: none;
      font-size: 16px;
    }

    .company-card .visit-btn:hover {
      background-color: #0056b3;
    }

    /* Footer */
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
  </style>
</head>

<body>

  <!-- Header & Navigation -->
  <header>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
            <li><a href="job.html">Jobs</a></li>
            <li><a href="#">Companies</a></li>
            <li><a href="about.html">About us</a></li>
            <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Companies List -->
  <section class="companies-container">
    <h1 style="text-align:center; margin-bottom: 30px;">Top Companies</h1>

    <div class="company-card">
      <h3>Tech Solutions</h3>
      <p><strong>Industry:</strong> Information Technology</p>
      <p><strong>Location:</strong> San Francisco, USA</p>
      <a href="https://www.techsolutions.com" class="visit-btn" target="_blank">Visit Website</a>
    </div>

    <div class="company-card">
      <h3>Creative Minds</h3>
      <p><strong>Industry:</strong> Design & Media</p>
      <p><strong>Location:</strong> London, UK</p>
      <a href="https://www.creativeminds.com" class="visit-btn" target="_blank">Visit Website</a>
    </div>

    <div class="company-card">
      <h3>Global Marketing Ltd.</h3>
      <p><strong>Industry:</strong> Marketing & Advertising</p>
      <p><strong>Location:</strong> Sydney, Australia</p>
      <a href="https://www.globalmarketing.com" class="visit-btn" target="_blank">Visit Website</a>
    </div>

  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 Job Portal | All Rights Reserved
  </footer>

</body>
</html>

#aboutus

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>About Us</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    body {
      background-color: #fbf7f7;
      padding: 20px;
    }

    .about-container {
      max-width: 900px;
      background-color: #f9f9f8;
      padding: 40px;
      margin: 50px auto;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
    }

    .about-container h1 {
      text-align: center;
      margin-bottom: 30px;
      color: #333;
    }

    .about-container p {
      font-size: 18px;
      color: #555;
      line-height: 1.7;
      margin-bottom: 20px;
      text-align: justify;
    }

    .about-container img {
      width: 100%;
      height: auto;
      border-radius: 10px;
      margin-top: 20px;
    }

    .footer {
      text-align: center;
      margin-top: 40px;
      color: #777;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <!-- About Us Section -->
  <div class="about-container">
    <h1>About Us</h1>
    <p>Welcome to Job Portal! We are passionate about
    <p>We have tie up companies</p>
    <p>We have excellent placement trainer</p>
    </p>
    </div>
    </body>
    </html>

    #contact

    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Contact Us</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      padding: 20px;
      margin: 0;
    }

    .contact-container {
      background: #fff;
      max-width: 600px;
      margin: 50px auto;
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }

    .contact-container h2 {
      text-align: center;
      margin-bottom: 30px;
      color: #333;
    }

    .contact-container form input,
    .contact-container form textarea {
      width: 100%;
      padding: 15px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 5px;
      resize: none;
      font-size: 16px;
    }

    .contact-container form button {
      width: 100%;
      padding: 15px;
      background-color: #007BFF;
      border: none;
      border-radius: 5px;
      color: white;
      font-size: 18px;
      cursor: pointer;
      transition: background 0.3s;
    }

    .contact-container form button:hover {
      background-color: #0056b3;
    }

    .footer {
      text-align: center;
      margin-top: 40px;
      color: #777;
      font-size: 14px;
    }
  </style>
</head>
<body>

<div class="contact-container">
  <h2>Contact Us</h2>
  <form action="YOUR_BACKEND_ENDPOINT" method="POST">
    <input type="text" name="name" placeholder="Your Name" required>

    <input type="email" name="email" placeholder="Your Email" required>

    <input type="text" name="subject" placeholder="Subject" required>

    <textarea name="message" rows="6" placeholder="Your Message" required></textarea>

    <button type="submit">Send Message</button>
  </form>
</div>

<div class="footer">
  &copy; 2025 Job Portal. All Rights Reserved.
</div>

</body>
</html>

#reg

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Simple Coding Page</title>
  <link rel="icon" href="data:image/png;base64,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">

  <!-- Font Awesome CDN -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      line-height: 1.6;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
    }

    header {
      background: #3b5ae6;
      color: #fff;
      padding: 20px 0;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    header h1 {
      font-size: 2.5rem; /* Increased font size */
    }

    nav a {
      color: #fff;
      margin-left: 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background: #f4f4f4;
      padding: 60px 20px;
      text-align: center;
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    .btn {
      display: inline-block;
      background: #282828;
      color: #fff;
      padding: 10px 25px;
      text-decoration: none;
      border-radius: 5px;
    }

    .features {
      display: flex;
      justify-content: space-between;
      padding: 40px 0;
      gap: 20px;
      flex-wrap: wrap;
    }

    .feature-box {
      background: #eaeaea;
      padding: 20px;
      flex: 1;
      min-width: 250px;
      text-align: center;
      border-radius: 10px;
    }

    footer {
      background: #3f67ec;
      color: #fff;
      text-align: center;
      padding: 20px 0;
      margin-top: 40px;
      font-size: 1.5rem; /* Increased font size */
    }

    footer a {
      color: #fff;
      text-decoration: none;
      margin: 0 10px;
    }

    footer .social-icons {
      margin: 20px 0;
    }

    footer .social-icons a {
      font-size: 2rem; /* Icon size */
      margin: 0 15px;
    }

    @media (max-width: 768px) {
      header {
        flex-direction: column;
        text-align: center;
      }

      nav {
        margin-top: 10px;
      }

      .features {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <center>
        <h1>My Coding Page</h1>
        <nav>
            <a href="home.html">Home</a>
            <a href="job.html">Jobs</a>
            <a href="company.html">Companies</a>
            <a href="about.html">About us</a>
            <a href="contact.html">Contact</a>
        </nav>
      </center>
    </div>
  </header>

  <center>
    <h1>Registration Form</h1>
    <form>
      <h2>
        <table>
          <tr>
            <td>Name:</td>
            <td><input type="text" placeholder="Enter Your Name"></td>
          </tr>
          <tr>
            <td>Age:</td>
            <td><input type="number" placeholder="Enter Your Age"></td>
          </tr>
          <tr>
            <td>Gender:</td>
            <td>
              <input type="radio" name="Gender">Male
              <input type="radio" name="Gender">Female
            </td>
          </tr>
          <tr>
            <td>Email:</td>
            <td><input type="email" placeholder="Enter Your Email"></td>
          </tr>
          <tr>
            <td>Upload Your Resume</td>
            <td>
                <input type="file">
            </td>
        </tr>
          <tr>
            <td><a href="#" class="btn">Sign up</a></td>
            <td><a href="#" class="btn">Login</a></td>
          </tr>
        </table>
      </form>
    </h2>
  </center>

  <footer>
    <div class="container">
      <p>&copy; 2025 My Coding Page. All rights reserved.</p>
      <div class="social-icons">
        <a href="#" class="fab fa-facebook-f"></a>
        <a href="#" class="fab fa-twitter"></a>
        <a href="#" class="fab fa-instagram"></a>
        <a href="#" class="fab fa-youtube"></a>
      </div>
    </div>
  </footer>
</body>
</html>

