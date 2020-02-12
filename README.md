# Blind-Arduino Blog
The site for the Blind-Arduino Blog

## Quick Links

[View the site live]( https://blind-arduino.github.io/Blind-Arduino-Blog/)


# Contributing
## No Write Access

1.	Click "Fork" and fork the repository to your account.
2.	Follow the steps below to create a new file.
3.	Go back to the homepage of this blog, and click new pull request. Select your forked repository master branch to go into this repository, and open a pull request.
4.	We will review your pull request.

## If you are a member of the org

1.	Click the "Create new file" button on the [repository page](https://github.com/Blind-Arduino/Blind-Arduino-Blog) or a sub directory from the top table.
2.	If you want to create a single page with no assets, just make a new top-level markdown file.
3.	If you want to add a new path, or add some assets, you put the path in the name of the file when you click on "create new file". For example: "about/index.md" would be put in the name field if you wanted the user to type "/about" at the end of the URL when they visit the site. Type "about/technology/index.md" if you want the users to type "about/technology" at the end of the URL.
4.	Write your document in markdown and hit commit
5.	Once the file has been committed, wait about 20 minutes and the blog will show the file on the live site.

### Things that are complicated

1. To do a link to a page, you can't just do
`<a href="/about">About</a>`,
you need to put relative_url after the link like:
`<a href="{{ "/about" | relative_url }}">About</a>`

# Things to Consider

1.	We should decide if we want our site URL to be a custom domain, "blind-arduino.github.io", or " blind-arduino.github.io/Blind-Arduino-Blog/"
2.	We need to come up with a nice layout for the site

# References

[Intro documentation on Github Pages and Jekyll](https://jekyllrb.com/docs/github-pages/)
[Guide on building a blog with Github Pages](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/)
[Introduction to Liquid Templating Language](https://shopify.github.io/liquid/basics/introduction/)
[Github Liquid Filters and variables](https://jekyllrb.com/docs/liquid/)
[Posts using Jekyll](https://jekyllrb.com/docs/posts/) 
