<!doctype html>
<html>

<head>
<title>My Project</title>
</head>

<body>
<h1 style="color:red;"><B>Gandhi Monil Mrugesh</B></h1>
<h2 style="color:red;"><B><I>Registeration No.: 20BCE10128</B></I></h2>
<form>
<h3 style="color:blue;"><center>FORM</center></h3>
first name:<input type="text" placeholder="Enter first Name"><br>
last name:<input type="text" placeholder="Enter last Name"><br>
Email id:<input type="text" placeholder="Enter Official Mail id"><br>
Password:<input type="password" placeholder="Enter your password"><br>
Branch:<input type="text" placeholder="Enter your current branch"><br>
Select Year of Graduation:<input type="radio" name="grad">2022
		<input type="radio" name="grad">2023
		<input type="radio" name="grad">2024
		<input type="radio" name="grad">2025
<br>
<br>
<button type="submit" value="submit">Submit!!</button>
<button type="reset" value="reset">Reset all!!</button>
</form>

<hr>
<p style="color:lime;">"Lets play a game!!</p>

<script>
var userNumber =10;
var counter = 0;
var maxTries = 8;
var randomNumber = Math.floor(Math.random() * userNumber + 1);
while (attempts != randomNumber){
    var attempts = prompt("Lets play a guess game.We'll generate a no. between 1 to 10,Please pick a number between 1 and " + userNumber);
    counter += 1;
    if (counter > maxTries){
        document.write("You have no more tries left. Refresh site to play again");
        break
    }
    if (attempts == randomNumber){
        document.write("Congrats you guess the correct number");
        document.write(" the random number was " + randomNumber);
        document.write(" It took you " + counter + " attempts to guess the correct number")
    }
}
</script>
</body>
</html>
