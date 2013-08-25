---
layout: post
title:  "Moving to Jeckyll for blogging"
date:   2013-08-23 16:04:10
categories: blog
tags: aws, ruby, jekyll
---

I have decided to change my blogging platform. I was using Blogger - since it was pretty easy to get up and running and could use a GUI for formatting the posts. But now I've learned more about using markdown and git and AWS - I decided to move my blog to using Jekyll (a ruby app) and use AWS for the hosting.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
