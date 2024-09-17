# Solution-repo
<!DOCTYPE html>
<html>
<head>
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
  padding: 0;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 20px;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
  width: 100%;

}

.header-left {
  display: flex;
  align-items: center;
}

.header-left img {
  width: 30px;
  height: 30px;
  margin-right: 10px;
}

.header-right {
  display: flex;
  align-items: center;
}

.header-right a {
  margin-right: 20px;
  text-decoration: none;
  color: #333;
}

h1 {
  margin-top: 0;
  margin-bottom: 10px;
  font-size: 3em;
}

.subheading {
  margin-top: 0;
  margin-bottom: 20px;
  font-size: 1.2em;
  color: #666;
   padding-bottom:150px ;
}

.content {
  display: flex;
  justify-content: space-between;
  width: 100%;
  margin-bottom: 20px;
}

.section {
  width: 30%;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 5px;
}

.section h2 {
  margin-top: 0;
  margin-bottom: 10px;
  font-size: 1.5em;
}

.section ul {
  list-style: none;
  padding: 0;
}

.section li {
  margin-bottom: 5px;
}

.section a {
  text-decoration: none;
  color: #007bff;
}

.reviews {
  display: flex;
  justify-content: space-between;
  width: 100%;
  margin-bottom: 20px;
}

.review {
  width: 30%;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 5px;
}

.footer {
  text-align: center;
  padding: 10px;
}
</style>
</head>
<body>
<div class="container">
  <div class="header">
    <div class="header-left">
      <img src="https://via.placeholder.com/30" alt="logo">
      <h2>your name</h2>
    </div>
    <div class="header-right">
      <a href="#">Home</a>
      <a href="#">Projects</a>
      <a href="#">Articles</a>
      <a href="#">Contact</a>
    </div>
  </div>
  <h1>Frontend Developer</h1>
  <div class="subheading">html only with proper layout, no styling</div>
  <div class="content">
    <div class="section">
      <h2>Projects</h2>
      <ul>
        <li>HTML Only Portfolio</li>
        <li>Calculator</li>
        <li>Quiz App</li>
        <li>Countdown Timer</li>
        <li>Product Upcoming Page</li>
      </ul>
    </div>
    <div class="section">
      <h2>Work Experience</h2>
      <p>roadmap.sh</p>
      <p>Solved all the frontend projects</p>
      <a href="#">Visit my Profile</a>
      <p>OpenSource Work</p>
      <p>Contributed to 50 opensource projects. Made my own projects with 200 GitHub Stars.</p>
      <a href="#">Visit my GitHub Profile</a>
    </div>
    <div class="section">
      <h2>Education</h2>
      <p>Graduated with 3.76 out of 4 CGPA. Won Acme Hackathon. Organized 30 sessions.</p>
      <h3>Courses I took:</h3>
      <ul>
        <li>Object Oriented Programming</li>
        <li>Data Structures and Algorithms</li>
        <li>Web Engineering</li>
        <li>Artificial Intelligence</li>
        <li>Human Computer Interaction</li>
        <li>Computer Graphics</li>
        <li>Database Management Systems</li>
        <li>Distributed Database Systems</li>
        <li>Discreet Mathematics</li>
      </ul>
    </div>
  </div>
  <div class="reviews">
    <div class="review">
      <h2>John doe was a brilliant student; always stood out with his assignments.</h2>
      <p>Jane Doe<br>Assistant Professor</p>
    </div>
    <div class="review">
      <h2>John doe was a brilliant student; always stood out with his assignments.</h2>
      <p>Jane Doe<br>Assistant Professor</p>
    </div>
    <div class="review">
      <h2>John doe was a brilliant student; always stood out with his assignments.</h2>
      <p>Jane Doe<br>Assistant Professor</p>
    </div>
  </div>
  <div class="footer">
    <p>&copy; all rights reserved 2025</p>
  </div>
</div>
</body>
</html>
