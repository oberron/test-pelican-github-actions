# test-pelican-github-actions
documents how to serve a pelican generated static site with github actions

## HOWTO

1. create the build-blog.yml under test-pelican-github-actions/.github/workflows/
   * change the project owner and email address in the .yml
3. add requirements.txt and pelicanconf.py under root folder
4. create a content folder and add a blog entry
5. change github projects settings to serve from gh-pages branch
6. QED


## Credits:

* https://biolitika.si/build-pelican-static-website-using-github-actions.html
* https://github.com/marketplace/actions/deploy-to-github-pages
