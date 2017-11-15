---
layout: post
comments: true
title:  "Pre-compiling CSS"
date:   2017-11-14 10:00:42 +0100
categories: Blog post
---
### What do you think of pre-compiling your CSS?

I think that pre-compiling is very good compared to normal CSS. For example you dont have to repeat yourself like you have to do in normal CSS and I think it looks way more structured that normal CSS. Under here I will post two code examples, one with SASS (pre-compiling CSS) and one with normal CSS. 

{% highlight ruby %}
SASS:

$link-color: #999;
$link-hover: #229ed3;

ul {
    margin: 0;

    li {
        float: left;
    }

    a {
        color: $link-color;

        &:hover {
            color: $link-hover;
        }
    }
}
{% endhighlight %}

{% highlight ruby %}
CSS:

ul { margin: 0; }
ul li { float: left; }
ul a { color: #999; }
ul a:hover { color: #229ed3; }
{% endhighlight %}

You can see a huge difference here in both structure and how you write your code. For example here I have given $link-color: one color. So when I want to use that color again I just write $link-color: istead of writing the same color over and over again. By doing this I can also keep all my colors in the same place and really easily see which colors I use. So its much easier for later changes in the code when you normally needs to dig through your whole code.
