---

layout: page
title: About

---

<p>Policy Club is the part-time after hours passion work of wannabe policy wonks...</p>
<div class="row">
	<div class="card-deck text-center">
		{% for member in site.data.team %}
		<div class="card">
		  <img class="card-img-top" src="/images/{{ member.pic }}" alt="Card image cap">
		  <div class="card-block">
		    <h3 class="card-title">{{ member.name }}</h3>
		    <p class="card-text"> {{ member.bio }}</p>
		  </div>
		  <div class="card-footer">
     		 <small class="text-muted"><a href="https://twitter.com/{{ member.twitter }}">@{{ member.twitter }}</a></small>
    	  </div>
		</div>
		{% endfor %}
	</div>
</div>
<div class="row">
	<div class="col-sm-6">
	<p>Special Thanks to our friends...</p>
	{% for friend in site.data.friends %}
	 <ul>
	 	<li>{{ friend.name }}</li>
	 </ul>
	{% endfor %}
	</div>
</div>