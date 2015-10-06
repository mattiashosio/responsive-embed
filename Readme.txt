====================================
CSS
====================================
	.embed-wrap { 
		position: relative; 
		padding-bottom: 56.25%; 
		height: 0; 
		overflow: hidden; 
		max-width: 100%; 
	}
	.embed-wrap iframe, .embed-container object, .embed-container embed { 
		position: absolute; 
		top: 0; 
		left: 0; 
		width: 100%; 
		height: 100%; 
	}

====================================
HTML
====================================
<div class="embed-wrap">
<iframe src="https://www.youtube.com/embed/pM21uQR6G_Q" frameborder="0" allowfullscreen></iframe>
</div>