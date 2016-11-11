# letterfy.js
This is a plugin that displays a string one letter at a time

## The Markup
First of all, include the "letterfy.min.js" to your project.

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>letterfy</title>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script> <!-- You need jquery -->
	<script src="letterfy.min.js"></script> <!-- This is the script that does the magic -->
</head>
<body>
	<h1 id="writeText">Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</h1> <!-- the selector -->
	<script>
		$("#writeText").letterfy({
			speed: 10 // the speed of the animation
		});
	</script>
</body>
</html>
```
