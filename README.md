# TiddlyWiki
A tiddly wiki that is hosted on, and saves edits to github

To create your own github tiddlywiki first open this URL in your browser:

http://38911bytesfree.github.io/TiddlyWiki/blank.html

Fill in the advanced options with

* your github username,
* your github personal access token (this is stored locally as a cookie on your browser and not uploaded to github),
* the repository where you would like to store your tiddlywiki and
* the tiddlywiki filename.

Note that the github repository must already have a **gh-pages** branch setup (see [Github Account Setup](#github-account-setup))

![TiddlyWiki Advanced Options setup](https://cloud.githubusercontent.com/assets/12428654/8635892/9d014ab0-287a-11e5-92a8-4d8f6de51ec4.png)

Then click "save changes" on the blank tiddlywiki. This will save a copy of it into the gh-pages branch of your github repository.

Afterwards the new tiddlywiki can be loaded directly using its own github.io URL:

[http://{github username}.github.io/{repository name}/{tiddlywiki filename}.html](http://xyz)

## Github Account Setup

If you don't already have a github account you can create one for your tiddlywiki file in just a couple of clicks.

Sign up to github and create a repository to store the tiddlywiki file

* Enter the repository name and
* Tick the checkbox "Initialize this repository with a README"

![Github create repository](https://cloud.githubusercontent.com/assets/12428654/8635890/96dd6452-287a-11e5-8227-88c06a51f3c1.png)

### Create a gh-pages branch

If it does not already exist, create a gh-pages branch in your repository. The files on this branch can be accessed from the web.

![Github create gh-pages branch](https://cloud.githubusercontent.com/assets/12428654/8635891/998c7ecc-287a-11e5-9b08-5c6a1f08cddb.png)

The github account is now setup and is ready to host your tiddlywiki page.

### Personal access Token

Finally, to create a personal access token see: [Managing your personal access tokens](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-fine-grained-personal-access-token)
