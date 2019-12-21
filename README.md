Nonna F&#0232; Art 
====================

A repository and website dedicated to the artwork of Fernanda Raspi.

----------

![nonnafe.art](https://raw.githubusercontent.com/rozsasarpi/photorama/gh-pages/nonnafe_small_thumb.gif)

> by [Laura Palumbo](https://dribbble.com/shots/2767492#shot-description)

----------

__[Live website](https://nonnafe.art)__

----------


Add content
============ 

## Paintings

### Add new galery

### Add new painting

## Writings

### Add new writing



Modify website features
==========================

----------

- The homepage welcomes the visitors with 3 animated photos of your choice. It is recommended that all three are landscape orientated for best view.

To change the welcome content at the far left of the Home page go here: `/index.html` and fill the responding lines of the YAML with your desired text.

----------

- To enable **disqus** comments in the posts, change their front matter for comments to 'true'.

You must have a registered account in disqus, where you will also register a forum for your website.

Find the line `s.src = '//yourproject.disqus.com/embed.js';  // ` in the disqus_comments.html and REPLACE 'yourproject' with your forum shortname.

----------

- In order to send **newsletters** about your posts to your subscribers, you should register an account in [tinyletter](http://www.tinyletter.com " tinyletter").

Find the line `'https://tinyletter.com/yourproject', ` in the *newsletter.html* and replace 'yourproject' with your registered website.

You can always ommit the newsletter rendering by deleting the line `{% include newsletter.html %}
` in the *default.html* layout.

----------

If you want to use the matching **NEWSLETTER** template, you must always create a new file  by copying its respective index.html and renaming it to e.g. 2016-March-newsletter.html and then save it inside the folder and the accompanying images inside the 'images folder', so it can be accessed to your viewers through their browser. In this case the root url for the above newsletter will be ***http://yourgithubusername.github.io/yourproject/2016-March-newsletter.html***. Copy this link and replace this part of the code `http://www.yoursite.com/newsletter/year-month-newsletter` with it.

----------

**TAGS** and **CATEGORIES** of the posts 

When you add a tag or a category name in the front matter of a post, don't forget to add the responding markdown files in /journal/tag/ folder and in /journal/category folder, so they can always render when browsing the journal or searching in the respective page.

----------


Read <a href="https://sunbliss.github.io/photorama/journal/images-size-for-better-performance/">**this**</a> post if you want to ensure your website always loads fast.


----------


Acknowledgement
==================

This repository and website are based on [sunbliss/photorama](https://github.com/sunbliss/photorama).