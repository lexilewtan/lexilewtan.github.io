#lexilewtan.com
Documentation - April 7th, 2014

###Technology

We built it on [Jekyll](http://jekyllrb.com). Each section is in its own include file so it's easy to update.

If you want to update the site and use the templates and includes, you should [install Jekyll](http://jekyllrb.com/docs/quickstart/). 

Jekyll outputs static HTML, so you can also edit HTML directly.

##The actual output is in _site. On Github, it's in the "Production" branch.

###_includes

**_includes/** are where all the sections live.

**_announcements.md** is where you will change the text for the top bar.

**about.md** is the top copy. Both announcements and about are in Markdown.

###Main folder

**index.html** is the main page with all the includes. You can edit your SEO keywords and description here.

**_layouts/main.html** is the page scaffolding. If you need analytics or other resources (like CSS or JS), you can add here.