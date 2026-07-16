There is an automatic rendering of the website when changes are pushed to the gitrepos. Alternatively, once can locally run the command `quarto publish gh-pages` .


Once rendered, the website is at [berkeley-stat.github.io/purdom-site](berkeley-stat.github.io/purdom-site). This website should be aliased at:
* [purdom.stat.berkeley.edu](purdom.stat.berkeley.edu)
* [stat.berkeley.edu/~epurdom](stat.berkeley.edu/~epurdom)

The `gh-pages` branch needs to have a file CNAME with contents purdom.stat.berkeley.edu . It sometimes gets deleted in which case it won't show on the aliased website.