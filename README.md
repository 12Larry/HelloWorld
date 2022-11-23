# HelloWorld

My first repository on GitHub

I love ☕ 🐶 and 💃
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: purple;
}

h1 {
  color: BlanchedAlmond;
  font-family: arial narrow;
  text-align: center;
}

h2 {
  color: BlanchedAlmond;
  font-family: arial narrow;
  text-align: left;
}

p {
  color: BlanchedAlmond;
  font-family: arial narrow;
  font-size: 20px;
}

input[type=text] {
  width: 100%;
  box-sizing: border-box;
  border: 2px solid #ccc;
  border-radius: 4px;
  font-size: 16px;
  background-color: white;
  background-image: url('searchicon.png');
  background-position: 10px 10px; 
  background-repeat: no-repeat;
  padding: 12px 20px 12px 40px;
  font-family: arial narrow;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;

  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: BlanchedAlmond;
  text-align: center;
  padding: 10px 16px;
  font-family: arial narrow;
  text-decoration: none;
}

li a:hover {
  background-color: #333;
}

div.gallery {
  margin: 15px;
  border: 1px solid #ccc;
  float: left;
  color: black;
  background-color: BlanchedAlmond;
  font-family: arial narrow;
  width: 200px;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: auto;
}

div.desc {
  padding: 15px;
  text-align: center;
}
</style>
</head>
<body>
<ul>
  <li><a class="active" href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li style="float:right"><a class="active" href="#about">About</a></li>
</ul>

<h1>AB 3 - Webtechnologien</h1>



<p>Aufgabe 1.2 CSS</p>

<h2>What are you looking for?</h2> 

<form>
  <input type="text" name="search" placeholder="Search.."> <br><br><br><br><br><br><br>
  <div class="gallery">
  <a target="_blank" href="img_5terre.jpg">
    <img src="img_5terre.jpg" alt="Cinque Terre" width="600" height="400">
  </a>
  <div class="desc">Cique Terre</div>
</div>

<div class="gallery">
  <a target="_blank" href="img_forest.jpg">
    <img src="img_forest.jpg" alt="Forest" width="600" height="400">
  </a>
  <div class="desc">Forest</div>
</div>

<div class="gallery">
  <a target="_blank" href="img_lights.jpg">
    <img src="img_lights.jpg" alt="Northern Lights" width="600" height="400">
  </a>
  <div class="desc">Northern Lights</div>
</div>

<div class="gallery">
  <a target="_blank" href="img_mountains.jpg">
    <img src="img_mountains.jpg" alt="Mountains" width="600" height="400">
  </a>
  <div class="desc">Mountains</div>
</div>
  
  
</form>

 

</body>
</html>


