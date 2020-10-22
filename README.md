# online-ticket-booking-webpage
in this webpage we can book tickets 

............................HOME PAGE.......................................................

<!DOCTYPE html>
<html>
<head>
 <title>ONLINE TICKET BOOKING</title>
<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
<header>
<div class="main">
<ul>
<li><a href="#">Login</a></li>
<li><a href="#">Train tickets</a></li>
<li><a href="#">Bus tickets</a></li>
<li><a href="#">Flight tickets</a></li>
<li><a href="#">Booking history</a></li>
<li><a href="#">PNR status</a></li>
<li><a href="#">About us</a></li>
<li><a href="#">Contact us</a></li>


</ul>
</div>
<div class="title">
<h1>ONLINE TICKET BOOKING</h1>

</header>
</body>
</html>

...................................................................CSS CODE..........................................

{
margin: 0;
padding: 0;
font family: century gothic;
}

header{
background-image: url(kl.png);
height: 103vh;
background-size: cover;
background-position: center;
}

ul{
float: right;
list-style-type: none;

}

ul li{
display: inline-block;
}

ul li a{
text-decoration: none;
color: white;
padding: 5px 20px;
border: 1px solid white;
transition: 0.6s ease;
}

ul li a:hover{
background-color: white;
color: #000;
}

ul li.active a{
background-color:white;
color: #000;
}

.title{
position: absolute;
top: 40%;
left: 40%;
transform: translate(-40%,-40%);
}

.title h1{
color: white;
font-size: 60px;
}
