<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>Capitão America</title>
		<style type="text/css">
.Circle{

	border-radius: 50%;
	display: flex;
	align-items: center;
	justify-content: center;
	border: 1px solid #3c404f;

}

#Circle1{
	margin:auto;
	width:256px;
	height:256px;
	background-color: red;

}

#Circle2{
	width:206px;
	height:206px;
	background-color: white;
}

#Circle3{
	width:156px;
	height:156px;
	background-color: red;
}

#Circle4{
	width:106px;
	height:106px;
	background-color: blue;
}


#star{
	border-left: 50px solid transparent; 
	border-right: 50px solid transparent;
	border-bottom: 35px solid white;
	transform: rotate(180DEG);

}

#star:before{
	position: absolute;
	border-left: 50px solid transparent; 
	border-right: 50px solid transparent;
	border-bottom: 35px solid white;
	transform: rotate(70deg);
	content: "";
	left:-50px; 
}

#star:after{
	position: absolute;
	border-left: 50px solid transparent; 
	border-right: 50px solid transparent;
	border-bottom: 35px solid white;
	transform: rotate(-70deg);
	content: "";
	left:-48.8px; 
}
		
		</style>
	</head>

	<body>
		<div id="Circle1" class="Circle">
			<div id="Circle2" class="Circle">
				<div id="Circle3" class="Circle">
					<div id="Circle4" class="Circle">
						<div id="star">
							
						</div>
					</div>
				</div>
			</div>
		</div>

	</body>
</html>
