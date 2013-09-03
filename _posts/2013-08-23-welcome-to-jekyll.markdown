---
layout: post
title:  "Moving to Jeckyll for blogging"
date:   2013-08-31 16:04:10
categories: blog
tags: aws, ruby, jekyll
---

I have decided to change my blogging platform. I was using Blogger - since it was pretty easy to get up and running and could use a GUI for formatting the posts. But now I've learned more about using markdown and git and AWS - I decided to move my blog to using Jekyll (a ruby app) and use AWS S3 and Route 53 for the hosting.

I am providing links to the tools that I used for my blog website - but won't provide detailed instructions - since the documentation is pretty good for each of the components:

* I followed these [instructions](http://docs.aws.amazon.com/AmazonS3/latest/dev/website-hosting-custom-domain-walkthrough.html) for setting up my AWS S3 bucket as a stand-alone website and to configure AWS Route 53 for my domain name server records.

* For writing my blog posts I use [Jekyll](https://github.com/mojombo/jekyll), a Ruby gem that allows you to write your blog posts in Markdown language and then it will convert your posts to html pages.

* I then use [s3_website](https://github.com/laurilehmijoki/s3_website), another Ruby gem, to publish my site pages to my Amazon S3 bucket.

* I am using [Disqus](http://disqus.com/) for the blog comments - you just add javascript to the post.html file in my _layouts folder and this javascript is added to each blog post html page.

Some key points to watch out for:

* Make sure you name your S3 bucket with your domain name (ex: my bucket is called "bethanyrentz.com")

* Take some time to play around with your blog layout locally before publishing live and to learn about how the html pages are created by Jekyll (the documentation on the Jekyll site is very well written).


My blog publishing workflow is as follows (I am using Linux Ubuntu 13.04):

1. On my computer create a new blog post in [markdown](http://en.wikipedia.org/wiki/Markdown) format.
2. run jekyll build from the terminal window- which creates the html pages.
3. run jekyll serve from the terminal window to check out my blog post on my local machine.
4. run s3_site push to push the website up to my S3 bucket.
5. push a copy of my website changes to my github repo.

I could probably spend some more time automating the push to AWS and git hub - but for now - I'm happy with the extra steps.
