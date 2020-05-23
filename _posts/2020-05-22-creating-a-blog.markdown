---
layout: post
title: "Hosting a blog"
date: 2020-05-22
categories: blog github
---
During the COVID19 pandemic-induced increased amounts of free time, I decided it
would be a good idea to create a blog to keep a record of things I experiment
with over time so they I can remember them in the future.

## Research

First thing I did was do some research into which blogging platforms are out 
there and what makes more sense for me. Some of the most populars in the 
software developer world are:

* [Medium](https://medium.com/): is a widely popular blogging platform where
authors are paid based on how many readers they get. It is one of the easier
platforms to get started with.
* [Wordpres](https://wordpress.com/): is one of the most popular blogging
platforms. It has been around for a while and you don't need much programming
knowledge to be proficient on it.
* [Ghost](https://ghost.org/): is similar to Wordpress but sleeker. It is newer
than Wordpress and based in node.js.
* [Github Pages](https://pages.github.com/): provides a way to expose a static
website through a git repository hosted in Github. It integrates with 
[Jekyll](https://jekyllrb.com/) to provide markdown-based static websites.

While all the options are excellent I ended up deciding between Medium and 
Github pages due to their simplicity (and both being free). I ended up choosing
Github Pages because it is a bit more customizable and because there is 
something very satisfying about having your website being a git repo.

## Starting the Github Pages Blog

The [documentation](https://pages.github.com/) for Github Pages has good 
instructions for creating a site. The steps are basically:

* Create a repo in github named `$YOUR_USERNAME.github.io`, this is because 
github will host your site at that address since your github username is unique.

* Add a markdown file called `index.md` to the repository with the content
you want to show on your site:

{% highlight markdown %}
# Hello World!

Welcome to my github pages site!
{% endhighlight %}

* Push it into master and then go to `$YOUR_USERNAME.github.io` and you have a
site setup!

