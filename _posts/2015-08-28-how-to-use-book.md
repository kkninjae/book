---
title: How to Use Book
date: 2015-08-28
comment: false
---

Simple is better, but many themes are over designed.
So, [Book](https://github.com/kkninjae/book) is born.


## Get started

You should be able to use Book without significant change.
But make sure you have modified `baseurl` properly before using it.

After that, you can follow the steps below to run it locally.

1.  Download this repository
    *   Use Git to clone it, or
    *   Download it via [Github](https://github.com/kkninjae/book/archive/master.zip)
1.  Read `_config.yml` and change the default settings as your need
1.  Install `jekyll` and run `jekyll serve -w`


## Tips

Use absolute path when you change values of `favicon` or `avatar`.

When you write posts, there is no need to specify a layout for each post.
`post` layout is the default value for any posts.
Otherwise, specify a different layout value if you do not want to use `post` layout.

If you are using [Disqus](https://disqus.com/) commenting system, commenting is turned on for every post by default. You can set `disqus: false` in `_config.yml` file to disable comment for all posts. Or, you can add `comment: false` in the front matter of the page you want to disable comment. As you can see, this post disables comment.


## End.

If you like it, why not give it a [star](https://github.com/kkninjae/book) :).
