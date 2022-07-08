# Menu-with-HTML-CSS
//I have design a logo by THML and CSS. 

<!---      HTML    ---------------------->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="CSS/style.css" type="text/css">
  <title>Navbar</title>
</head>
<body>
  <header>
  <div class="container">
   <img src="MSU.jpg" alt="logo" width="150px" height="30px" title="MSU" class="logo">
   <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Pricing</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
   </nav>
  </div>
</header>
</body>
</html>


<!*************************************************************>
//CSS

@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");

/***************************Reset Viewport Global style****************************/
* {
  margin: 0;
  /* padding: 0; */
  /* box-sizing: border-box; */
}

/***********************Body style***************************/

body {
  font-weight: 300;
}

/**************** Styling Main container (parent) by using class *****************/
header {
  background: #55d6aa;
  color: #5bc8f7;
}
header::after {
  content: "";
  display: table;
  clear: both;
}
.container {
  width: 80%;
  margin: auto;
}
.logo {
  float: left;
  padding: 10px 0;
}
nav {
  float: right;
}
nav ul {
  margin: 0;
  padding: 0;
  list-style: none;
}
nav li {
  display: inline-block;
  margin-left: 70px;
  padding-top: 23px;

  position: relative;
}

nav a {
  color: #444;
  text-decoration: none;
  text-transform: uppercase;
  font-size: 14px;
}

nav a:hover {
  color: #000;
}

