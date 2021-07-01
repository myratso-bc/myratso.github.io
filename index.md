<!DOCTYPE html>
<html>
  <head>
      <style>

* {
  box-sizing: border-box;
}

/* Style inputs */
input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #2F2D2B;
  color: white;
  padding: 12px 20px;
  border: none;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #A9CCE3;
}

/* Style the container/contact section */
.contact {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 10px;
}

/* Create two columns that float next to eachother */
.column {
  float: left;
  width: 50%;
  margin-top: 6px;
  padding: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}


.parallax {
  /* The image used */
  background-image: url("/Users/myrat/Desktop/Stuff/2560/Scan916.jpg");

  /* Set a specific height */
  min-height: 500px;

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

	.text {
 	width: 550px;
  	padding: 10px;
  	border: 5px ;
  	margin: 0;
	}
	
	.contactText {
 	width: 420px;
  	padding: 10px;
  	border: 5px solid #EBF5FB;
  	margin: 0;
	}


	.center {
  	display: block;
 	margin-left: auto;
  	margin-right: auto;
  	width: 90%;
	}

	.center 2 {
  	display: block;
 	margin-left: 250px;
  	margin-right: 0px;
  	width: 100%;
	}

	.container {
  	position: relative;
	width:100%;
	}

	.top-left {
  	position: absolute;
  	top: 250px;
  	left: 375px;
	}

	/* Google Font CDN Link */
	@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700&display=swap');
	*{
  	margin: 0;
  	padding: 0;
  	box-sizing: border-box;
  	font-family: "Poppins" , Courier New; //Avenir Light
	}

	body{
  	position: relative;
  	min-height: 100vh;
  	width: 100%;
	}
	::selection{
  	color: #fff;
  	background:#242426;
	}

	.sidenav {
  	height: 100%; /* Full-height: remove this if you want "auto" height */
  	width: 250px; /* Set the width of the sidebar */
  	position: fixed; /* Fixed Sidebar (stay in place on scroll) */
  	z-index: 1; /* Stay on top */
  	top: 0; /* Stay at the top */
  	left: 0;
  	background-color: #A7BB98; /* Black */
  	overflow-x: hidden; /* Disable horizontal scroll */
  	padding-top: 10px;
	}

	/* The navigation menu links */
	.sidenav a {
  	padding: 2px 8px 6px 35px;
  	text-decoration: none;
  	font-size: 19px;
  	color: #232621;
  	display: block;
	}

	/* When you mouse over the navigation links, change their color */
	.sidenav a:hover {
  	color: #f1f1f1;
	}

	.image{
  	width: 175px;
  	height: 175px;
  	border: 11px solid #F1EEE2;
  	margin: 1.5em auto 0;
  	border-radius: 50%; /*don't forget prefixes*/
  	background-image: url("/Users/myrat/Desktop/Stuff/Screen Shot 2020-12-09 at 9.08.28 PM.png");

  	background-position: center;
  	/* as mentioned by Vad: */
  	background-size: cover;
	}

	/* Style page content */
	.main {
  	margin-left: 250px; /* Same as the width of the sidebar */
  	padding: 30px 10px;
	}
     </style>

    <meta charset="UTF-8">
    <!--<title>Myra Tso</title>-->
    <link rel="stylesheet" href="style.css">
    <link href='https://unpkg.com/boxicons@2.0.7/css/boxicons.min.css' rel='stylesheet'>
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <body>


<div class="parallax">
	<div class="container">
		<img src="/Users/myrat/Desktop/Stuff/2560/Scan911.jpg"  align="right" class="center 2"/>

		<div class="top-left">
			<h1 style="color:#F1F3EB;font-family:Bebas Neue; text-align:center;font-size:400%">Myra Tso</h1>
			<p style="color:#A7BB98;font-family:Courier New;font-size:120%">she/her/hers</p>
		</div>
	</div>

<section id="block">
	<div class="main">
	<p>&nbsp;</p>
      </div>
    </section>


<section id="about">
	<div class="main">
        <h2 style="color:#282A23; font-family:Royal Acidbath;align=right;font-size:250%">About</h2>

	<div class="text">
        <p>Hello and thank you for wanting to learn more about me!</p>
	<p>My name is Myra. I am a first-generation Chinese/Vietnamese-American. Currently, at Bellevue College in my 4th year studying Computer Science.</p>
	</div>
      </div>
    </section>


<section id="resume">
	<div class="main">
        <h2 style="color:#FFBB6A; font-family:Royal Acidbath;align=right;font-size:250%">Resume</h2>
	<img src="/Users/myrat/Desktop/Resumé.png" class="center">
	
      </div>
    </section>

<!--
<section id="project">
	<div class="main">
        <h2 style="color:#FFBB6A; font-family:Royal Acidbath;align=right;font-size:250%">Projects</h2>
      </div>
    </section>

-->
<section id="contact">
<div class="main">
<div style="text-align:center">
        <h2 style="color:#282A23; font-family:Royal Acidbath; text-align=center;font-size:250%">Contact</h2>
    <p>Let's connect or send me a message!</p>
  </div>
  <div class="row">
    <div class="column">
	<div class="contactText">
<p><strong>Email: </strong>myra.lilly.tso@gmail.com</p>
<p><strong>Linkedln: </strong><a href="https://www.linkedin.com/in/myratso/" style="color: #2F2D2B">www.linkedin.com/in/myratso/</a></p>
<p><strong>Location: </strong>Seattle, WA</p>
</div>
    </div>
    <div class="column">
      <form action="/action_page.php">
        <label for="name">Name</label>
        <input type="text" id="name" name="name" placeholder="Your name..">
        <label for="email">Email</label>
        <input type="text" id="email" name="email" placeholder="Your email..">
        <label for="subject">Subject</label>
        <input type="text" id="sub" name="subject" placeholder="Subject..">
        </select>
        <label for="message">Message</label>
        <textarea id="mes" name="message" placeholder="Write something.." style="height:170px"></textarea>
        <input type="submit" value="Send">
      </form>
    </div>
  </div>
</div>
</section>


     <div class="sidenav">
   	<div class="image"></div>
	<pre> </pre>
	<h2 style="color:#F1EEE2;font-family:Royal Acidbath;text-align:center;font-size:200%;">Myra Tso</h2>
	  <pre>     
          </pre>

        <a href="#">
          <i class='bx bx-grid-alt' ></i>
          <span class="links_name">Home</span>
	  <pre> </pre>
        </a>

	<a href="#">
          <i class='bx bx-user' ></i>
          <span class="links_name">About</span> 
	  <pre> </pre>
        </a>

	<a href="#">
          <i class='bx bx-folder' ></i>
          <span class="links_name">Resume</span>
          <pre> </pre>
        </a>
<!--
	<a href="#">
          <i class='bx bx-pie-chart-alt-2' ></i>
          <span class="links_name">Projects</span>
          <pre> </pre>
        </a>
-->
	<a href="#">
          <i class='bx bx-chat' ></i>
          <span class="links_name">Contact</span>
          <pre> </pre>
        </a>
     </div>
  </div>
</body>
</html>