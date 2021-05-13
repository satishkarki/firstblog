---
layout: default
title: Satish Karki
---
<div class="blurb">
	<h1>Hi there!, I'm Satish Karki</h1>
	<p>Here, I write about the things I stumbled across the boulevard of Information Technology. <a href="/about">Read more about my life...</a></p>
</div><!-- /.blurb -->
<hr style="height:2px;border-width:0;color:blue;background-color:blue">
**Did you know?** Google receives over 63,000 searches per second on any given day. That's the average figure of how many people use Google a day, which translates into at least 2 trillion searches per year, 3.8 million searches per minute, 228 million searches per hour, and 5.6 billion searches per day. Pretty impressive, right? [Check it out.](https://www.internetlivestats.com/)

It takes about 50 milliseconds (that's 0.05 seconds) for anyone to form an opinion about a website. It determines whether you like my site or not, whether you will stay or leave. If you are still reading this, Hurray!!! I choose to believe, you haven't made an extreme level of snap judgment about my homepage. 

However, if I were you, I would have swiftly closed this tab (`CTRL+W` is the keyboard shortcut, don't do it, Plz!). I know my Github page sucks. I am still learning how [Jekyll](https://jekyllrb.com/) works, and with the mystical power of HTML and CSS, I will embellish this page (*fingers crossed*). Appearance matters, a front-end girl would certainly say, but I am more of a terminal guy. Teehee. 
 
<hr style="height:2px;border-width:0;color:blue;background-color:blue">
<h2>Here is the list of my blog post (more of a personal note)</h2>
<ul>
	{% for post in site.posts %}
	  <li>
		<a href="{{ post.url }}">{{ post.title }}</a>
	  </li>
	{% endfor %}
  </ul>
