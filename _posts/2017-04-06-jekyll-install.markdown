---
layout: page
title:  "Installing Jekyll"
permalink: jekyll-install
---
[Back](/jekyll-intro)

* [What's required for Jekyll](#required)
* [Useful to know about](#useful-know)
* [Resources](#resources)

<h3 id="required">What's required for Jekyll</h3>
* [Ruby 2.0+](https://www.ruby-lang.org/en/)
* Text editor ([Atom](https://atom.io/), [Notepad++](https://notepad-plus-plus.org/))

<h3 id="useful-know">Useful to know about </h3>
#### [Liquid](https://shopify.github.io/liquid/)

Liquid is a templating engine. You'll notice when it's in use from the curly braces it uses.

#### [Markdown](https://daringfireball.net/projects/markdown/basics)
Markdown is a text to HTML converter. Jekyll lets you write your pages in Markdown and/or classic HTML

Markdown allows you to encode a page in way that is a bit simpler than HTML (no need to close out brackets for example). For example of how this looks, take look at how this page is encoded:

{% highlight markdown %}
[Back](/jekyll-intro)

* [What's required for Jekyll](#required)
* [Useful to know about](#useful-know)
* [Resources](#resources)

<h3 id="required">What's required for Jekyll</h3>
* [Ruby 2.0+](https://www.ruby-lang.org/en/)
* Text editor ([Atom](https://atom.io/), [Notepad++](https://notepad-plus-plus.org/))

<h3 id="useful-know">Useful to know about </h3>
#### [Liquid](https://shopify.github.io/liquid/)

Liquid is a templating engine. You'll notice when it's in use from the curly braces it uses.

#### [Markdown](https://daringfireball.net/projects/markdown/basics)
Markdown is a text to HTML converter. Jekyll lets you write your pages in Markdown and/or classic HTML.

Markdown allows you to encode a page in way that is a bit simpler than HTML (no need to close out brackets for example). For example of how this looks, take look at how this page is encoded:
{% endhighlight %}

You'll notice the following differences between the encoding for this page and standard HTML:
* Instead of using ul and li tags for an unordered list, I can simply use asteriks in Markdown. 
* I can also use four pound symbols in succession to signal a fourth level heading rather than using the h4 tag. However, I used an h3 tag as well so I could take advantage of anchor tags
* Links don't require a tags + an href attribute. Instead, you're first putting your link text in square brackets followed by your link in partheneses
* Lastly, there's no need for p tags! Just type out your text. 

<h3 id="resources">Resources</h3>
Allan has done a great walkthrough of installing Jekyll on a Mac that can be found [here](https://allanberry.github.io/2017/04/04/install-ruby-jekyll-github-pages.html).

If you are using Windows, I highly recommend [this guide](https://labs.sverrirs.com/jekyll/) by Sverrir Sigmundarson.

[Getting Started](/getting-started)