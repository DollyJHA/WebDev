<html>
<head>
<title>OnlineTeaOrder</title>
<link href="https://fonts.googleapis.com/css?family=Marck+Script|Rock+Salt" rel="stylesheet">
<link rel="stylesheet" type="text/css" href="Style\w3.css" />

</head>
<body>


<header  class=" w3-container w3-orange">
 <img src="img/c2.png" alt="Lights" class="w3-image w3-left" width="100" height="100">
<h1 class="w3-center w3-myfont">
<b>AB Order Chai Online</b>
</h1>

<a class="w3-btn w3-brown w3-right w3-round w3-margin-bottom" href="Login.html" >Login/Register</a>
		
</header>
<nav class="w3-sidenav w3-orange w3-text-cyan " style="display:block" id="mySidenav">
	<h2 class="w3-text-black">Menu</h2>
	<a class="w3-border-bottom" href="#">TEA</a>
	<div class="w3-dropdown-hover">
	<a class="w3-border-bottom" href="#">Coffee <i class="fa fa-caret-down"></i></a>
	<div class="w3-dropdown-content w3-blue w3-card-4">
	<a class="w3-border-bottom" href="ChangePassword.html">latte Coffee</a>
    </div>
	</div> 
</nav>

<div class="w3-content w3-section" style="width:400px">
  

  <img class="mySlides w3-animate-fading" src="img/s1.jpg" style="width:100%">
  <img class="mySlides w3-animate-fading" src="img/s2.jpg" style="width:100%">
  <img class="mySlides w3-animate-fading" src="img/s3.jpg" style="width:100%">
  <img class="mySlides w3-animate-fading" src="img/s4.jpg" style="width:100%">
  <img class="mySlides w3-animate-fading" src="img/s5.jpg" style="width:100%">
  <img class="mySlides w3-animate-fading" src="img/s6.jpg" style="width:100%">
</div>

<script>
var myIndex = 0;
carousel();

function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 9000);    
}
</script>
<footer class=" w3-container w3-orange w3-bottom">
<h6 class="w3-center">CopyRight@Xerox&CTS</h6></footer>
</body>
</html>
