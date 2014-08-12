I'm a Heading
==========

I'm a sub heading
----------

*I'm Italic*

**I'm Bold**

	There's an intent before me

REAL README
==========
To use pages and Jekyll : 
- https://help.github.com/categories/20/articles
- https://help.github.com/articles/using-jekyll-with-pages
- Ruby 2.0.0 doesn't work yet
- To switch ruby version, use rvm https://rvm.io/
- http://www.ruanyifeng.com/blog/2012/08/blogging\_with\_jekyll.html
- Branch gh-pages is important

Once jekyll installed,
- bundle exec jekyll serve
- Install nodejs first if it says sth like "javascript runtime missing"

If 404 error,
- Delete the gh-pages branch on github
	git push origin --delete gh-pages

- Delete the gh-pages branch on local
	git branch -D gh-pages

- Reinitialize git repo
	git init

- Recreate the branch on local
	git branch gh-pages

- Repush the gh-pages branch to github
	git push origin gh-pages



