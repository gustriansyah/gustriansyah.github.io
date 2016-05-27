---
layout: page
title: About the Theme
tags: [about, Jekyll, theme, moon]
date: 2016-03-21
---
    
<p><br><center><a href="sif.uin-suska.ac.id"> sistem informasi</a></center></br></p>
<p><center><a href="uin-suska.ac.id"> uin suska</a></center></p>



## Preview

{% capture images %}
<html>
	<head>
	       <title> Insert Gambar</title>
	</head>
	<body>
	      <img src="./UIN-Riau.png"></br>
	      <b> Penguins</b>
	</body>
</html>

<html>
	<head>
	       <title> Insert Gambar</title>
	</head>
	<body>
	      <img src="./fst.png"></br>
	      <b> Penguins</b>
	</body>
</html>
{% endcapture %}
{% include gallery images=images caption="Screenshots of Moon Theme" cols=2 %}
