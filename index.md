# Hi, I'm Miko
## Let's learn together!

### My Projects
Here are a list of projects that I am have been working on:
<ul>
<li><a href="https://github.com/miko202104/HelloWorld">Hello World Project</a></li>
</ul>

### My Interests
I'm interested in making it easier for everyone to write code to make their lives better.
### My Blog
<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

### Get in Touch
<ul>
<li><a href="https://twitter.com/{{ site.twitter_username }}">Twitter</a></li>
<li><a href="https://github.com/{{ site.github_username }}">GitHub</a></li>
</ul>
