# BouncingButton
Bouncing Button Code in HTML
<!DOCTYPE html>
<html>
<head>
	<title>Bouncing Button</title>
	<link href="https://fonts.googleapis.com/css?family=Montserrat:400,700" rel="stylesheet">
	<style>
		/* Button styles */
		.button {
			display: inline-block;
			padding: 15px 24px;
			background-color: #eccbd6;
			color: #55003e;
			border-radius: 24px;
          	border: 2px solid #55003e;
			text-decoration: none;
			font-size: 24px;
			font-weight: bold;
			font-family: 'Montserrat', sans-serif;
			text-align: center;
			cursor: pointer;
			animation: bounce 2s infinite;
		}

		/* Bounce animation */
		@keyframes bounce {
			0% {
				transform: translateY(0);
			}
			50% {
				transform: translateY(-10px);
			}
			100% {
				transform: translateY(0);
			}
		}

		/* Hover styles */
		.button:hover {
			background-color: #55003e;
			color: #EBE5d6;
          	border-color: #55003e;
		}
	</style>
</head>
<body>
	<a href="https://www.brynncreates.com/resume" target="_blank" class="button">SHOW ME THE RESUME →</a>
</body>
</html>
