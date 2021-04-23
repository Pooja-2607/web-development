<!DOCTYPE html>
<html>
<head>
	<title>E COMMERCE WEBSITE</title>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
	<link rel="stylesheet" type="text/css" href="first.css">

</head>

<body>
	<!-- navbar -->
		<nav class="navbar navbar-expand-lg navbar-dark bg-dark" id="nav" >
			<div class="container-fluid" style="border-bottom: 2px solid white; ">
	   			 <a class="navbar-brand" href="#" style="margin-left: 10px; padding-top: 10px;">
			      <img src="logo.png" alt="" width="40" height="40" class="d-inline-block align-text-top" style="margin-right:15px">
			      ABC
			    </a>
			    <div class="collapse navbar-collapse" id="navbarNav">
		      <ul class="navbar-nav" style="display: flex;">
		        <li class="nav-item">
		          <a class="nav-link active" aria-current="page" href="#">Home</a>
		        </li>
		        <li class="nav-item">
		          <a class="nav-link" href="#">About</a>
		        </li>
		        <li class="nav-item">
		          <a class="nav-link" href="#">Contact Us</a>
		        </li>
		      </ul>
		      <button class="navbtn">Log In</button>
		    </div>
		    <div id="mySidenav" class="sidenav ">
	  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
	  <a href="#">Home</a>
	  <a href="#">About Us</a>
	  <a href="#">Contact</a>
	</div>
	<button onclick="openNav()" class="side">&#9776;</button>
	  		</div>	  

	</nav>
<!-- side navbar -->

	

	<!-- CAROUSEL -->
	
<div id="box">

  <input type="radio" name="position"   />
  <input type="radio" name="position" />
  <input type="radio" name="position"  checked/>
  <input type="radio" name="position" />
  <input type="radio" name="position" />	

  <main id="carousel">
    <div class="item"></div>
    <div class="item"></div>
    <div class="item"></div>
    <div class="item"></div>
    <div class="item"></div>
    </main>
</div>
		<!-- services -->
	  <div class="container ">
		  <div class="row">
		  	
		    <div class="col-sm" >
		    	<div>
		  		<img src="truck.png" class="services_img">
		  		
		  		
		  	</div><p class="services">
		      Fast Delivery<br><br>
		      Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		      consequat. </p>
		    </div>
		    
			
		    <div class="col-sm ">
		    <div>
		    <img src="return.png"class="services_img">	
		    </div><p class="services">
		  	  Easy Returns<br><br>
		      O Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		      consequat. </p>
		    </div>
		    
		    <div class="col-sm">
		    	<div>
		  		<img src="quality.png"class="services_img" >
		  	</div> <p class="services">Quality<br><br>
		  	
		       Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		      quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		      consequat. </p>
		    </div>
		  </div>
	</div>

	<!-- trusted by -->
	<div class="trusted">
		<p>TRUSTED BY </p>
        <div class="flex-container">
		<img src="c3.png" >	
		<img src="c1.png">
		<img src="c2.png" >
	</div></div>

	<!-- Footer -->
<footer class="bg-dark text-center text-white" style="padding-top: 40px;">
  <!-- Grid container -->
  <div class="container p-4">
    <!-- Section: Social media -->
    <section class="mb-4">
      <!-- Facebook -->
      <a class="btn btn-outline-light btn-floating m-1" href="#!" role="button"
        > <img src="facebook.png"><i class="fab fa-facebook-f"></i
      ></a>

      <!-- Twitter -->
      <a class="btn btn-outline-light btn-floating m-1" href="#!" role="button"
        ><img src="twitter.png"><i class="fab fa-twitter"></i
      ></a>

      <!-- Google -->
      <a class="btn btn-outline-light btn-floating m-1" href="#!" role="button"
        ><img src="gmail.png"><i class="fab fa-google"></i
      ></a>

      <!-- Instagram -->
      <a class="btn btn-outline-light btn-floating m-1" href="#!" role="button"
        ><img src="instagram.png"><i class="fab fa-instagram"></i
      ></a>
    </section> 
    <!-- Section: Form -->
    <section class="">
      <form action="">
        <!--Grid row-->
        <div class="row d-flex justify-content-center">
          <!--Grid column-->
          <div class="col-auto">
            <p class="pt-2">
              <strong>Sign up for FREE!</strong>
            </p>
          </div>
          <!--Grid column-->

          <!--Grid column-->
          <div class="col-md-5 col-12">
            <!-- Email input -->
            <div class="form-outline form-white mb-4">
              <input type="email" id="form5Example2" class="form-control" / placeholder="Email address">
              
            </div>
          </div>
          <!--Grid column-->

          <!--Grid column-->
          <div class="col-auto">
            <!-- Submit button -->
            <button type="submit" class="btn btn-outline-light mb-4">
              Sign Up
            </button>
          </div>
          <!--Grid column-->
        </div>
        <!--Grid row-->
      </form>
    </section>

    <!-- Section: Text -->
    <section class="mb-4">
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt distinctio earum
        repellat quaerat voluptatibus placeat nam..
      </p>
    </section>
   <!-- Section: Links -->
    <section class="">
      <div class="row">
        <div class="col-md-6">
          <h5 class="text-uppercase">Links</h5>

          <ul class="list-unstyled mb-0">
            <li>
              <a href="#!" class="text-white">Link 1</a>
            </li>
            <li>
              <a href="#!" class="text-white">Link 2</a>
            </li>
            <li>
              <a href="#!" class="text-white">Link 3</a>
            </li>
            <li>
              <a href="#!" class="text-white">Link 4</a>
            </li>
          </ul>
        </div>
        <div class="col-lg-3 col-md-6 mb-4 mb-md-0">
          <h5 class="text-uppercase">Links</h5>

          <ul class="list-unstyled mb-0">
            <li>
              <a href="#!" class="text-white">Link 1</a>
            </li>
            <li>
              <a href="#!" class="text-white">Link 2</a>
            </li>
            <li>
              <a href="#!" class="text-white">Link 3</a>
            </li>
            <li>
              <a href="#!" class="text-white">Link 4</a>
            </li>
          </ul>
        </div>
      </div>
    </section>
  </div>
  <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
    © 2021 Copyright Reserved.<br>
    Made with &hearts; in India.
    
  </div>
</footer>
	<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.1/dist/umd/popper.min.js" integrity="sha384-SR1sx49pcuLnqZUnnPwx6FCym0wLsk5JZuNx2bPPENzswTNFaQU1RDvt3wT4gWFG" crossorigin="anonymous"></script>
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.min.js" integrity="sha384-j0CNLUeiqtyaRmlzUHCPZ+Gy5fQu0dQ6eZ/xAww941Ai1SxSY+0EQqNXNE6DZiVc" crossorigin="anonymous"></script>
</body>
</html>


<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "250px";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0";
}
</script>
