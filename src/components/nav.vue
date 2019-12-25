<template>
<div class="static" style="border:1px solid black;">
	<nav  class="navbar navbar-expand-lg pt-4">
  <a  style="margin-left:110px; font-family:sans-serrif; color:#fff; font-weight:70px;font-size:32px;"   class="navbar-brand" href="#">Coinbase</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse " id="navbarText" style="color:#ffff;">
    <ul style="margin-left:427px; color#fff;"  class="navbar-nav mr-auto ">
      <li class="nav-item active">
      	<div class="dropdown">
      	<a  class=" list dropbtn center nav-link" href="#">Product<i class="fa fa-angle-down ml-2"></i></a>
  		<!-- <button class="dropbtn">Dropdown</button> -->
 		 <div class="dropdown-content">
   		 <a href="#">Link a</a>
    	<a href="#">Link 2</a>
    	<a href="#">Link 3</a>
  	</div>
		</div>
        <!-- <a class=" center nav-link" href="#">   Products<i class="fa fa-angle-down"> <span class="sr-only">(current)</span></i></a> -->
      </li>
      <li class="nav-item ml-3">
        <a  class=" list center nav-link" href="#">Price </a>
      </li>
      <li class="nav-item ml-3">
      	<div class="dropdown">
      	<a  class=" list dropbtn center nav-link" href="#">Company<i class="fa fa-angle-down ml-2"></i></a>
  		<!-- <button class="dropbtn">Dropdown</button> -->
 		 <div class="dropdown-content">
   		 <a href="#" style="text-align:left;">About Us</a>
    	<a href="#" style="text-align:left;">Blog</a>
    	<a href="#" style="text-align:left;">Support</a>
    	<a href="#" style="text-align:left;">Careers</a>
  	</div>
		</div>
        <!-- <a class="dropbtn center nav-link" href="#">Company<i class="fa fa-angle-down"></i></a> -->
      </li>
    </ul>
    <span class="right navbar-text">
      <div>
      	<router-link :to="{name:'signin'}">
      	<h5 style="color:#ffff;">Sign in<span><button class="btn" style="margin-left:30px;">Get started</button></span></h5>
      </router-link>
      </div>
    </span>
  </div>
</nav>
</div>
	




</template>


<style>
body{
		font-family: Graphik, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;	
	}

	.static{
	background-color: rgb(22, 82, 240);
    width: 100%;
    height: 100px;
    padding-top: 5px;
    padding-left: 15px;
    padding-right: 15px;
    position: fixed;
    top: 0px;
    font-weight: 500;
    text-align: center;
    transition: .5s;
   
	}

	.top{
		height:80vh;
		background-color: rgb(22, 82, 240);
		font-family: Graphik, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif;	

	}

	.center{
		justify-content: center;
	}


	.dropdown {
  position: relative;
  display: inline-block;
}
/*drop down content hidden by default*/
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #ffff;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

/* Links inside the dropdown */
.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

a:hover{
	color: #000;
}

/* Change color of dropdown links on hover */
.dropdown-content a:hover {background-color: #ffff; opacity: 0.9;}

/* Show the dropdown menu on hover */
.dropdown:hover .dropdown-content {display: block;}

.right{
	margin-right: 100px;
}

.btn{
	background-color: #1652f0;
	border-color: #ffff;
	color: #fff;
	height: 45px;
	width: 120px;
}

.btn:hover{
	background-color: #ffff;
	color: #000;
}

.list{
	color: rgb(255, 255, 255);
    position: relative;
    cursor: pointer;
    font-size: 16px;
    font-weight: 900px;
    text-decoration: none;
    /*transition: all 150ms*/
    font-family:Arial, Helvetica, sans-serif; 
        padding-left: 35px;
}

	


</style>