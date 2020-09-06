<!DOCTYPE HTML>
<html>
<head>
<meta charset="utf-8">
<title>Responsive Layout</title>
<center style="color:red">TYPES OF CARS</center>

<style>
* {
	box-sizing: border-box;
}
 h1{
 	margin-bottom: 15px;
 	position text-align: center;
}
p {
	border: 1px solid black;
	background-color: grey;
	width:990px;
	height:100px;
	margin-right: auto;
	margin-left: auto;
	font-family: serif;
	color: black;
	font-size: 20px;
}

.row {
	width: 500px;
}

.box{
	height: 20px;
	width:20px;
}


@media (min-width: 1200px) and (max-width: 1199px) {
	.col-md-1, .col-md-2, .col-md-3, .col-md-4, {
		float: left;
		border: 1px solid green;
	}
	.col-md-1 {
		width: 8.33%;
	}
	.col-md-2{
		width: 16.66%;
	}
	.col-md-3{
		width: 25%;

	}
	.col-md-4{
		width: 33%
	}
</style>
</head>
<body>

	<div class="col-md-3 col-md-6"><p>CAR 1 At Mercedes-Benz of Cary Purchasing a new vehicle is a big decision. One that should not be taken lightly. Many factors go into choosing the right vehicle. What may be important to you may not be so important to someone else. And that is ok. Mercedes-Benz, the first car company in the world, offers a wide variety of vehicles with a wide variety of features. </p></div>

	<div class="col-md-3 col-md-6"><p>Item 2 Honda Cars India (HCIL) is a subsidiary of Japanese automobile manufacturer Honda. Founded in 1995, the company has its headquarters located in Greater Noida, Uttar Pradesh. ... Currently, the product portfolio of Honda Cars India includes Amaze, BR-V, Jazz, WR-V, City, Civic, CR-V, and Accord hybrid.</p></div>
	<div class="col-md-3 col-md-6"><p>Item 3 Maruti Suzuki India Limited, formerly known as Maruti Udyog Limited, is an automobile manufacturer in India. It is a 56.21% owned subsidiary of the Japanese automotive manufacturer Suzuki Motor Corporation. As of July 2018, it had a market share of 53% of the Indian passenger car market.</p></div>
	

</body>
	
}
</html>
