---
layout: page
title:  "3. Getting Started with Jekyll"
permalink: getting-started
number: 3
---
Before you get started don't forget that you'll need to have Ruby installed first!

Open up Terminal or the Command Line and type in:
{% highlight ruby %} gem install jekyll bundler {% endhighlight %}

This will install the Jekyll gem in your Ruby directory. If you get an error here, you may need to go back and make sure you have Ruby properly installed.

To create a new Jekyll site, you'll want to move to the directory you want to create the directory for your site in before you create your site. Once you've done this, you can type in the command {% highlight ruby %}jekyll new sitename{% endhighlight %} to create your new site.

This creates a folder with your new jekyll site. Let's navigate into it and see what it looks like.:
{% highlight ruby %}
_posts (folder) --> 2017-03-30-welcome-to-jekyll.md
.gitignore
_config.yml
about.md
Gemfile
Gemfile.lock
index.md
{% endhighlight %}

The two pieces of information to take note of here are the "_posts" folder, which contains the individual pages of your site.

The other file to take note of is the _config.yml file. This is the Configuration file for your site. You can do a lot with this file, including:
* Set a base URL for your site
* Set a theme for your site
* Set variables that can be used elsewhere in your site (Social media user names, etc)
* Use to configure plugins (if used)

Let's take a look at what the site looks like. Type the following into the Terminal or Command Line:
{% highlight ruby %}
bundle exec jekyll serve
{% endhighlight %}

Next, open up a browser and naviate to [localhost:4000](localhost:4000). You'll see the site you've just created!

If you navigate back to your site folder, you'll notice that two more folders got added. They are:
* .sass-cache (contains site CSS)
* _site 

The first folder contains the cache for the CSS used for your site. The second folder contains the built version of your site. <strong> Do not modify these folders!</strong> They are automatically generated and changing them could cause your site to break.

[4. Creating Posts](/posts)