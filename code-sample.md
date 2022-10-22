# Code Sample  
## Below is a block of code that I wrote for a FizzBuzz assignment in an IT class.  

```
<!DOCTYPE html>  
<html>  
<head>  
<meta charset="UTF-8">  
<title>Fizz Buzz</title>  
<script>  
function fizzbuzz() {  
	var display = document.getElementById('display');  
	var displayHTML = "";  
	var divisible = '';  
	for (i = 1; i < 101; i++) {  
		if (i % 3 === 0 && i % 5 === 0) {  
			divisible = 'fizzbuzz';  
		} else if (i % 3 === 0) {  
			divisible = 'fizz';  
		} else if (i % 5 === 0) {  
			divisible = 'buzz';  
		} else {  
			divisible = i;  
		}  
	displayHTML += "<p>" + divisible + "</p>";  
	}  
	display.innerHTML = displayHTML  
}  
</script>  
</head>  
<body onload="fizzbuzz()">  
<div id="display">  
</div>  
</body>  
</html>  

```
[Return to home page](./README.md)
