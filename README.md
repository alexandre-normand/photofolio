Hey, it's Alex's Photography!
=============================

This is the source to my [photography portfolio](http://photo.heyitsalex.net).

Uses the pretty cool [Hugo](http://hugo.spf13.com/).

Auto-generating portfolio from dropbox using [foglio](https://github.com/alexandre-normand/foglio)
--------------------------------------------------------------------------------------------------
foglio --template ~/projects/photo.heyitsalex.net/template.md --outputDirectory ~/projects/photo.heyitsalex.net/content/portfolio/ --dropboxPath /photo.heyitsalex.net

Regenerating after content addition
-----------------------------------

```hugo --baseUrl="http://photo.heyitsalex.net/" --config=./config.json```

To publish
----------
`git subtree push --prefix=public git@github.com:alexandre-normand/photofolio.git gh-pages`
