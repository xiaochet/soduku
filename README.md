

<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width,user-scalable=no" />
	<title>SUDUKO</title>
	<link rel="Stylesheet" type="text/css" href="soduku.css" />
</head>
<body>
	<div class = "btn-group">
		<button onclick = "sd.checkRes();">Finish</button>
		<button onclick = "sd.reset();">Reset</button>
		<button onclick = "sd.again();">Again</button>
	</div>
	<script src="http://apps.bdimg.com/libs/jquery/1.8.1/jquery.min.js"></script>
	<script src="soduku.js"></script>
	<script>
		var sd = new SD;
		sd.init(30);
	</script>
</body>
</html>
