Code4SA Static GitHub Pages Template
====================================

This is Code for South Africa's static template for GitHub pages apps.

About this template
-------------------

This template makes it easy to build GitHub pages static websites that fit the Code for South Africa best practices and guidelines.

* Jekyll-powered GitHub pages template
* Code for South Africa app templates and layouts
* Google Analytics
* Bower to install assets
* jQuery
* Bootstrap
* FontAwesome

Setting up the template
-----------------------

* Fork this repo on GitHub into your own repo and clone the repo locally.
* Install [RVM](http://rvm.io/)
* Install Jekyll ``bundle install``
* Edit ``_config.yml`` and set ``google_analytics_id`` correctly
* Run Jekyll: ``jekyll serve --watch``

Using the template
------------------

* For an app with Code4SA styling, use ``index.html`` or the ``app`` layout. 
* For an empty page, use ``naked.html`` or the ``default`` layout.

To add more javascript files, either add your code to ``js/app.js`` or add extra
files to the ``js/`` directory, and add their paths to your frontmatter:

```yaml
extra_stylesheets:
  - /css/foo.js
  - /css/bar.js
```

To add more CSS or SCSS, either add it to ``css/app.scss`` or copy the files
to the ``css`` directory and add their paths to your frontmatter:

```yaml
extra_js:
  - /js/foo.js
  - /js/bar.js
```

You can also install files with Bower: ``bower install -Sp package-to-install``

Production deployment
---------------------

Just deploy to your gh-pages branch with git push!

License
-------

MIT License
