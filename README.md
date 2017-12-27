![](https://raw.githubusercontent.com/kkninjae/book/master/github/hero.png)


# Book

Book, a simple and ready-to-use Jekyll theme. [Live](http://kkninjae.github.io/book/).


## How-to

*   [Setup](#setup)
*   [Customization](#customization)
*   [Writing Posts](#writing-posts)
*   [Deploy to Github Page](#deploy-to-gh-pages)


### <a name="setup" id>Setup</a>

```sh
# get a copy of book source code
$ git clone https://github.com/kkninjae/book.git

# running site locally
$ jekyll serve -w

# from now, you should be able to start development or customization
```


### <a name="customization">Customization</a>

Book is designed as simple as possible, but few changes can make your site uniq.
You only need to change the values of keys in `_config.yml` file.

*   Change site path: `baseurl`
*   Give your site a name: `title`
*   Make a site favicon: `favicon`
*   Make a special home button image: `avatar`


Last but not least

*   If you are using Google analytics: `ga`
*   If you are using Disqus commenting system: `disqus`


### <a name="writing-posts">Writing Posts</a>

Make a markdown file in `_posts` directory,
follow [Jekyll post naming convention](https://jekyllrb.com/docs/posts/) to name your post,
and put following front matter to the top of your post.
You should be able to start to write your awesome post.
Read this [POST](https://kkninjae.github.io/book/2015/08/28/how-to-use-book.html) to know more tips.

```markdown
---
title: Your awesome post title
date: YYYY-MM-DD
---
```


### <a name="deploy-to-gh-pages">Deploy to Github Page</a>

There is a deploying script built out of box.
You need to install one more tool before using it which is [npm](https://www.npmjs.com/get-npm).
This script will push your current static site to `gh-pages` branch.
If there is no `gh-pages` branch yet, the script will create it for you.

```sh
# start to deploy your site to Github pages
$ npm run deploy
```


## End.

If you like this theme, why not give it a star. :)
