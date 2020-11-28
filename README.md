# WEBSITETWO.github.io

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>WEBSITE</title>
	<link rel="stylesheet" type="text/css" href="home.css">
	<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Sansita+Swashed:wght@500&display=swap" rel="stylesheet">
<script src="https://kit.fontawesome.com/a076d05399.js"></script>
</head>
<body>


<nav>
	<input type="checkbox" id="check">
	<label for="check" id="checkbtn">
	<i class="fas fa-align-justify"></i>	
	</label>

	<label class="logo">TEST_WEBSITE</label>
	<ul>
		<li><a href="HOME.html" class="active">HOME</a></li>
		<li><a href="#">SERYAS</a></li>
		<li><a href="#">MOVIE</a></li>
		<li><a href="#">ABOUT US</a></li>
	</ul>
</nav>
<div>
	
  <video class="vd1"  autoplay="" muted=""><source src="vd.mp4" type="video/mp4"></video>
  <video class="vd2" controls=""><source src="vd2.mp4" type="video/mp4"></video>
<br><br>
<h4>CREATE : OMED A.M</h4>

</div>
</body>
</html>


*{
	padding: 0;
	margin: 0;
	text-decoration: none;
	list-style: none;
}

body{
	font-family: Work Sans;
}

nav{
	width: 100%;
	height: 80px;
	background-color: #09e058;
}

nav ul{
	float: right;
	margin-right: 50px;
}

nav ul li{
	line-height: 70px;
	display: inline-block;
	padding: 3px;
	margin: 4px auto;
}

nav ul li a{
	color: #027a2f;
	margin-right: 3px;
	text-transform: uppercase;
	font-size: 20px;
	border: 1px solid #323232;
	border-radius: 40%;
	padding: 7px;
	font-weight: 400;
}

a.active, a:hover{
	background-color: #4cf58b;
	color: #323232;
}


.logo{
	line-height: 70px;
	margin-left: 80px;
    font-weight: 600;
    font-size: 30px;
}

#checkbtn{
	float: right;
	font-size: 30px;
    color: #323232;
    line-height: 70px;
    margin-right: 40px;
    cursor: pointer;
    display: none;
}

#check{
	display: none;
}

@media (max-width: 800px){
	 ul {
	 	position: fixed;
	 	width: 100%;
	 	height: 100vh;
	 	background-color: #3232;
	 	top: 80px;
	 	left: -100%;
	 	text-align: center;
	 	transition: all .5s;
	}
	nav ul li{
		display: block;
		margin: 50px 0;
		line-height: 30px;
	}
	nav ul li a{
		font-size: 25px;
		color: #323232;
	}

	#checkbtn{
		display: block;
	}

	a.active,a:hover{
		background-color: #4cf58b;
		color: #000;
	}

	#check:checked ~ ul{
		left: 0;
	}


}

.vd1{
	float: left;
	margin-left: 10px;
	width: 400px;
	height: 400px;
}

.vd2{
	margin-left: 10px;
	width: 400px;
	height: 400px;
}

h4{
	background-color: lightblue;
	color: #000;
	display: inline-block;
	border: 2px double #3232;
	margin-left: 40px;
	padding: 10px;
	border-radius: 30%;
}
