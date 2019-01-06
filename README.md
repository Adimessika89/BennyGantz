	<!doctype html> 
	<html>
	<head>
	<link rel="stylesheet" href="css/style.css">
	<title>new Tab</title>
	</head>
	<body>
	<div id="fb-root"></div>
	<script>(function(d, s, id) {
	var js, fjs = d.getElementsByTagName(s)[0];
	if (d.getElementById(id)) return;
	js = d.createElement(s); js.id = id;
	js.src = 'https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v2.12';
	fjs.parentNode.insertBefore(js, fjs);
	}(document, 'script', 'facebook-jssdk'));</script>
	<div id="app">
	<div class="date-wrpaer">
	<p class="date">{{date}}</p>
	<p class="time">{{time}}</p>
	</div>
	<main class="main">
	<h1>BennyGantz-Bot</h1>
	<section class="quote">
	<blockquote>{{quote.main}}</blockquote>
	<p class="tag">@{{quote.famous}}</p>
	<p class="hastag">{{quote.hashtag}}#</p>
	<div class="media">
	<div class="titles">
	<p>benny</p>
	<h6>{{title}}</h6>
	</div>
	</div>
	<img :src="img" alt="benny">
	</section>
	<div class="share">
	<div> <button @click="restart">↺</button></div> 
	<div class="fb-share-button" data-href="https://Adimessika89/BennyGantz/" 
	data-layout="button" data-size="large" data-mobile-iframe="true">
	<a target="_blank" href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fnemo369.github.io%2Fmessika%2F&amp;src=sdkpreparse" class="fb-xfbml-parse-ignore">Share</a></div>
	</div>
	</main>
	<footer>
	<a href="https://Adimessika89/BennyGantz/"><img src="tab-icon.png" /></a>

	</footer>
	</div>
	
	<script src="lib/vue.js"></script>

	<script src="js/main.js"></script>

	</body>
	</html>

