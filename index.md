<!doctype html>
<html><head>
		<meta charset="utf-8">
		<title>HTML Practice</title>
		<link rel="stylesheet" type="text/css" href="basicstructurestyle.css">
	</head>
	<body>
		<header>
		<h1>Daniel Thompson</h1>
		<h2>Web programming is FUN</h2>
		<nav>
			<ul>
				<li><a href="home.html">Home</a></li>
				<li><a href="education.html">Education</a></li>
				<li><a href="work.html">Work</a></li>
			</ul>
		</nav>
	</header>
	<div>
		<section id="aboutMe">
		<h3>About Me</h3>
		<img alt="Dan" src="dan.jpg">


		<p>Hello, my name is Daniel. I am a college student assigned with making this page.
    I think its pretty safe to say that I am rather confused about how to do this, but it will be ok
  because this is just like learning a brand new language. I think this will be an interesting class though
because it will teach me something that I am not too familiar with and a skill that can be useful in the future!</p>
		<p>I am from a military family so I have been all over the place. I think it is very cool
    to have been able to travel around the United States and the world at a young age. I was able to see
    different cultures and different world attractions like the Eiffel Tower in Paris and the Colesseum in Rome!
    <p>

      <p>Coming from a military family, I have decided to follow in family footsteps and join the Army as well.
        I am part of the MO Army National Guard where my role is to set up and maintain communication systems
        for my unit. I chose that job because I think i works well with what I am doing in college and I feel that
        both are useful for today's world.<p>

		<p></p>
    Thank you for stopping by, and I hope you enjoy reading about me!
     <p></p>
		</section>

		<section id="contactme">
		<h3>Contact Me</h3>
		<form action="#">
		<p>Enter your name: <input type="text"></p>
		<p>Select a topic:
			<select>
				<option>Learn more about me</option>
				<option>Just saying hi</option>
			</select>
		</p>
		<label>Type your message: </label><br>
		<textarea></textarea><br>
		<input type="submit" value="Send">
		<input type="reset" value="Clear">
		</form>
		</section>
	</div>


<input type = "text" pattern = "[A-Z][a-zA-Z'\s.-]+$">
<textarea id = "message"></textarea>
<input type = "submit" id = "submit" value="Send">

<script>
document.getElementById("submit").onclick = function(){
	var message = document.getElementById("message").value;
	if(message.split(' ').length < 5){
		alert("At least Five words please.");
	}
}
</script>


	</body>
	</html>
