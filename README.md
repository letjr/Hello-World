<!DOCTYPE html>
<html>
	<head>
		body {
	background-color: #b7d1c4
}

h2 {
	font-family: Verdana;
	font-weight: bold;
	text-align: center;
	padding-top: 25px;
	padding-bottom: 25px;
	color: #acd1b2;
}

img {
	height: 170px;
	width: 170px;
	box-shadow: rgba(0,0,0,0.2) 10px 10px;

}

#navbar {
	position: fixed;
	top:10px;
	left:50%;
	margin-left:-254px;
}

#header {
	position: relative;
	top: -10px;
	background-color: #3c4543;
	border-top-left-radius: 15px;
	border-top-right-radius: 15px;
}

ul{
	list-style-type: none;
	position: fixed;
	margin: -10px;
}

li {
	display: inline;
	border: 2px solid #000000;
	font-family: Futura, Tahoma, sans-serif;
	color: #ffffff;
	padding: 5px;
	border-radius: 5px 5px;
	background-color: #cc0323
}

#left{
	width: 45%;
	float: left;
}

p {
	font-family: Tahoma;
	font-size: 1em;
}

#right{
	width: 45%;
	float: right;
}

table {
	border: #000000 1px solid;
	background-color: #acd1b2;
	float: right;
	margin-right: 10px;
	border-bottom-right-radius: 15px;
	border-bottom-left-radius: 15px;
}

td {
	height: 75px;
	width: 75px;
}

td img {
	height: 75px;
	width: 75px;
	box-shadow: none;
}

th {
	font-family: Verdana;
	font-size: 1em;
	font-weight: normal;
	color: #3c4543
}

#bottom_left{
	border-bottom-left-radius: 15px;
}

#bottom_right{
	border-bottom-right-radius: 15px;
}

#footer{
	clear: both;
	position: relative;
	bottom: -20px;
	border-bottom-left-radius: 15px;
	border-bottom-right-radius: 15px;
	height: 75px;
	background-color: #3c4543;
}

#button{
	border: 2px solid #000000;
	float:left;
	position: relative;
	left: 229px;
	bottom: -20px;
	border-radius: 5px;
	background-color: #cc0323;
	height: 30px;
	width: 150px;
	
}

#button p{
	position: relative;
	bottom: 10px;
	font-size: 0.8em;
	color: #acd1b2;
	text-align: center;
}

.bold{
	font-family: tahoma;
	font-weight: bold;
	font-size: 1.2em;
	font-variant: small-caps;
	color: #ffffff;
}
	</head>
	<body>
		<div id="header">
			<div id="navbar">
				<ul>
					<li>Home</li>
					<li>About Me</li>
					<li>Plans for World Domination</li>
					<li>Contact</li>
				</ul>
			</div>
			<h2>About Me</h2>
		</div>
		<div id="left">
		<img src="https://s3.amazonaws.com/codecademy-blog/assets/puppy-main_zps26d178c5.jpg"/>
		<p>I am the angriest puppy in the world. This has been scientifically proven in several clinical trials.</p>
		</div>
		<div id="right">
		<table>
			<th colspan="3">My Bros</th>
			<tr>
				<td><img src="https://s3.amazonaws.com/codecademy-blog/assets/puppy-1_zps5666b8e7.jpg"/></td>
				<td><img src="https://s3.amazonaws.com/codecademy-blog/assets/puppy-2_zps1539e6b2.jpg"/></td>
				<td><img src="https://s3.amazonaws.com/codecademy-blog/assets/puppy-3_zps4692eafa.png"/></td>
			</tr>
			<tr>
				<td><img src="https://s3.amazonaws.com/codecademy-blog/assets/puppy-4_zps63ff5aa8.jpg"/></td>
				<td><img src="https://s3.amazonaws.com/codecademy-blog/assets/puppy-5_zps0ee0d2c8.jpg"/></td>
				<td><img src="https://s3.amazonaws.com/codecademy-blog/assets/puppy-6_zpsc4450a60.jpg"/></td>
			</tr>
			<tr>
				<td><img id="bottom_left" src="https://s3.amazonaws.com/codecademy-blog/assets/puppy-7_zps26e8a8d9.jpg"/></td>
				<td><img src="https://s3.amazonaws.com/codecademy-blog/assets/puppy-8_zps9a1469be.jpg"></td>
				<td><img id="bottom_right" src="https://s3.amazonaws.com/codecademy-blog/assets/puppy-9_zps3bab7732.jpg"/></td>
			</tr>
		</table>
		</div>
		<div id="footer">
			<div id="button">
				<p>Send me an <span class="bold">e-mail</span>!</p>
			</div>
		</div>
	</body>
</html>
