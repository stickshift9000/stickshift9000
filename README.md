<!doctype html>
<html>
<head>
<link rel="stylesheet" type="text/css" href="device.css">

<meta chorset="utf-8">
<title>page test</title>
</head>
<body>
<button id="clicker">push me</button>
<h1 id = "color">Hi</h1>


<script>

var clickerButton = document.getElementById("clicker");

var onButtonClick = function() {
    clickerButton.textContent = "oh";

};
clickerButton.addEventListener("click",onButtonClick);

</script>
</body>
</html>
