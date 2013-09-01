# Code of Conduct 

Published: [Code of Conduct](http://railsbridge.github.io/code-of-conduct/)

# TO DO

* Add License file (proposal sent to list for review)
* Add links
* Add Contact Info


# Editing Instructions

We're using the [github-pages gem](https://github.com/github/pages-gem/blob/master/github-pages.gemspec#L16) to ensure we're using locally the same versions of gems that github uses when we publish. 

Fork this repo -- this makes a copy in your github account

Edit markdown files at the root directory or functional/visual design in _layouts, javascripts, stylesheets.  Do not directly edit anything in _sites

To make changes locally:

```
git clone git@github.com:yourname/code-of-conduct.git
cd code-of-conduct
bundle install
```

To view the site locally:
```
jekyll serve
```

View site at [http://localhost:4000](http://localhost:4000)

# For RailsBridge admin people 
to  publish to gh-pages, clone this repo, then...

```
git branch --track gh-pages origin/gh-pages

git checkout gh-pages
git merge master
git push
```


