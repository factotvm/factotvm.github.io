---
layout: post
title: Hello, world
---

Whenever I create a new git repository, I do the following series of steps to allow me to rebase effectively early on.

{% highlight sh %}
git init
touch .gitignore
git add .
git commit -m"Initial commit"
{% endhighlight %}

The reason for this is that in the past, if I wanted to reorder or squash commits, I needed an innocuous commit at the root to serve as a bookend. However, since [git 1.7.12](https://github.com/git/git/blob/master/Documentation/RelNotes/1.7.12.txt#L59), you can now rewrite history down to the root commit.  But I still follow this practice.

And whenever I create a new blog (and there have been a few), I always write a first post entitled, *Hello, world*.

