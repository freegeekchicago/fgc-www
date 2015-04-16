# Install Ruby
sudo apt-get install ruby ruby-dev

# Install Jekyll Gem
sudo gem install jekyll

# Optional - Grab Bootstrap for CSS
wget https://github.com/twbs/bootstrap/releases/download/v3.2.0/bootstrap-3.2.0-dist.zip

# Questions
- What dynamic content do we need?
	- Calendar (Google Calendar Embed)
	- Pickup Form (Google Form Embed)
	- Contact Form (Google Form Embed)
	- Comments for Blog Posts (Disqus or Livefyre Embed)
	- Directions / Map (OpenStreets Embed? or Google Maps Embed)
	- Site Search (Google custom search, but there are other options we should look at if needed.


- Host on FGC Webfaction server or on github pages?
	- Webfaction would require either pushing static content to server or installing ruby, bundler, and jekyll on to server
	- Github Pages are more limiting in additional plugins that are supported.
		- More info on this available at: https://help.github.com/articles/using-jekyll-with-pages/


# Maybe useful links for working with Jekyll
- http://thinkshout.com/blog/2014/12/creating-dynamic-menus-in-jekyll/
