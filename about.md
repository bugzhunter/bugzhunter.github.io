---
layout: page
title: About
permalink: /about/
---

# The largest heading (an <h1> tag)

## The second largest heading (an <h2> tag)

###### The 6th largest heading (an <h6> tag)


In the words of Abraham Lincoln:

> Pardon my french

*This text will be italic*
**This text will be bold**

Everyone _must_ attend the meeting at 5 o'clock today.

1. Item 1
	1. A corollary to the above item.
	2. Yet another point to consider.
2. Item 2
	* A corollary that does not need to be ordered.
		* This is indented four spaces, because it's two spaces further than the item above.
		* You might want to consider making a new list.
3. Item 3

Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.

Check out this neat program I wrote:

{% highlight ruby %}
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
{% endhighlight %}

~~Mistaken text.~~

| First Header | Second Header |
| - | - |
| Content from cell 1 | Content from cell 2 |
| Content in the first column | Content in the second column |


This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/)

You can find the source code for the Jekyll new theme at: [github.com/jglovier/jekyll-new](https://github.com/jglovier/jekyll-new)

You can find the source code for Jekyll at [github.com/jekyll/jekyll](https://github.com/jekyll/jekyll)
