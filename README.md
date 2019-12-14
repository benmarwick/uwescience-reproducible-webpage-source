UW eScience Reproducible and Open Research Special Interest Group
============

This is the repository for the source code for the page at http://uwescience.github.io/reproducible/ The files for that page are in the /public directory, and those files are hosted at and served from https://github.com/uwescience/reproducible

See information about the group at http://escience.washington.edu/about-us/working-groups/reproducibility-and-open-science/
 
Notes on maintaining the website:

- Source code for the page is at https://github.com/benmarwick/uwescience-reproducible-webpage-source
- The page is served from https://github.com/uwescience/reproducible 
- We're using blogdown with the [vex-hugo theme](https://github.com/themefisher/vex-hugo), and editing in RStudio. To see what the site looks like in RStudio: `blogdown::serve_site()`
- We edit text in data/homepage.yml
- We add images to static/images
- We edit menu anchors in the html files in themes/vex-hugo/layouts/partials
- The .git repo for the served materials is in /public, and this is what goes to this GitHub repo to serve the page, cf. [the blogdown book](https://bookdown.org/yihui/blogdown/github-pages.html)

