---
layout: page
title: Catalogue
---
<script type="text/javascript" src="http://code.jquery.com/jquery-1.7.1.min.js">
	</script>
<script type="text/javascript" src="js/hey.js/turn.min.js">
	</script>
<script>
$("#magazine").turn({
    width: 1125,
    height: 750,
    autoCenter: true
});
</script>

<p> Catalogue of class designs. </p>

  <div id="magazine">
			{% for post in site.tags.magazine %}
 				<li>
					{{post.content}}
      			</li>
			{% endfor %}
		</div>


		



<script src = "../myTurn.js">

</script>