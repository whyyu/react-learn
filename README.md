<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>react学习</title>
	<style>
	#app{
		background: #ccc;
	}
	</style>
</head>
<body>



	<div id="app"></div>

	<script src="react.js"></script>
	<script src="react-dom.js"></script>
	<script src="browser.js"></script>
	<script type="text/babel">


		ReactDOM.render(
		<h1>hello <span>world</span></h1>,
		document.getElementById('app')
		);


	</script>
</body>
</html>
