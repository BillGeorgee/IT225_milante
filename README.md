<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

.header {
  padding: 80px;
  text-align: center;
  background: #11b8ce;
  color: white;
}

.header h1 {
  font-size: 40px;
}

.navbar {
  overflow: hidden;
  background-color: #333;
}

.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

.navbar a.right {
  float: right;
}

.navbar a:hover {
  background-color: #ddd;
  color: black;
}

.row {  
  display: flex;
  flex-wrap: wrap;
}

.side {
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

.main {   
  flex: 70%;
  background-color: white;
  padding: 20px;
}

.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}


@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width:100%;
  }
}
</style>
</head>
<body>


<div class="header">
  <h1>Personal Website</h1>
  <p>Hi this is my Personal Website, My Name is Bill George Milante</p>
</div>

<div class="navbar">
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Resume/CV</a>
  <a href="#" class="right">Link</a>
</div>

<div class="row">
  <div class="side">
    <h2>About Me</h2>
    <h5>Photo of me:</h5>
    <img src="bill.png" width="300" height="300">    
    <h3>Contact Information</h3>
    <p>&#9990; 09184165155</p>
    <p>&#x1F4E7; bgmilante27@gmail.com</p>
    <p></p>
  </div>
  <div class="main">
    <h2>Blog/Articles</h2>
    <h5>My Experience With Playing Basketball</h5>
    <p>Basketball is just a game to most people, but it's so much more to me. I've learned a lot about life and myself over the more than 13 years that I've played basketball. When I enter the court, my thoughts is unrestricted by the number of people observing me. I feel completely at home when I have the ball in my hands, the court is vacant, and my headphones are in my ears.  It was on the basketball court that I made some of my closest friends. My best life lessons have come from playing basketball.</p>    
    <img src="basketball court.jpg" width="400" height="300">
    <br>
    <h2>My Hobbies</h2>
    <h5>- Playing Games</h5>
    <h5>- Playing basketball</h5>
    <img src="pc setup.jpg" width="400" height="300"> <img src="basketball.jpg" width="400" height="300">
    <p> My hobbies is playing games, playing basketball, and other stuff. Before I used to play in tournaments in playing video games and sometimes sometimes I play basketball league it depends if there is a team</p>
  </div>
</div>

</body>
</html>
