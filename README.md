UaNoaoAstroStats
================
Code for UA-NOAO Astrostatistics working group. Relevant links:

  * AstroML Home:  http://www.astroml.org/
  * Google Site:  https://sites.google.com/site/uaastrostats/home
  * Google Group:  https://groups.google.com/forum/?hl=en#!forum/ua-noao-astrostats
  * GitHub Page:  https://github.com/StewardObservatory/UaNoaoAstroStats
  * View IPython Notebooks: http://nbviewer.ipython.org/github/StewardObservatory/UaNoaoAstroStats/tree/master/


Getting started with git
------------------------
To get started, first download `git`. If you're using Linux, it should be available in distribution's package manager. If you're using Mac, you can download it from the `git` webpage: http://git-scm.com/download/mac. You can also download it through `homebrew`, although you may need the "developer tools" to compile things available through the Mac Store.

The documentation on `git`'s home page can be somewhat dense, but GitHub has a quite succinct "getting started" guide, that you should have seen when creating an account. But for an executive summary, the simplest way to make contributions is to:


  * Make a GitHub account
  * Navigate to this page and click the "Fork" button in the repository's upper right hand corner (you may also want to "Watch" and "Star" the repository as well for future reference).
  * Use `$ git clone https://github.com/YOUR_USERNAME/UaNoaoAstroStats` to make a local copy of your fork on your machine
  * Make your edits
  * *Commit* your changes `$ git commit -a -m 'My short explanation'`
  * Repeat for more changes
  * *Checkout* your commits `$ git checkout`
  * *Push* your changes to your fork `$ git push`
  * Go to your fork's GitHub page, and click that little green button with the arrows to make a *pull request*, with an explanation, and they can be integrated into the main repo.
  * The code in the pull request will be viewable as an "Issue" that others can comment on and review.
  * Congratulations, you have contributed code to a public GitHub repo!
  

We can cover more effecient workflows in our meetings, such as making changes to branches rather than directly editing `master`. If you find something written you consider an "anti-pattern" note you can make direct changes to this text to fix it! You can even use the "Edit" button on GitHub (after selecting the `README.md` file) to make changes within your browser.


Keeping your fork up to date
----------------------------
You'll need to incorporate other people's changes to the main "upstream" repository to sync to your local fork in order to keep it up to date.


  * Add the remote repository `$ git remote add upstream master https://github.com/StewardObservatory/UaNoaoAstroStats.git`, this is only necessary to do once
  * Sync your local repository on your computer by *pulling* changes from the *upstream* or "main" repository `$ git pull upstream master`
  * Sync your local repository to your forked GitHub repo `$ git push origin master`


