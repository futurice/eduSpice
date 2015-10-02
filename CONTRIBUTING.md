# First contribution

-- You need a GitHub account, git set up locally, a fork of the eduSpice project clones locally

1. Get a GitHub account or log in: https://github.com
2. If you are working at Futurice, ask IT to add you to futurice organization
3. Set up Git: https://help.github.com/articles/set-up-git/
4. Fork the eduSpice repository by going to “https://github.com/futurice/eduSpice” and clicking Fork
5. In your own version (fork) of the project in GitHub, copy the SSH clone URL
6. In your terminal, in suitable directory: git clone git@github.com:[your username]/eduSpice.git

-- You now have the project locally and you can do the changes or additions

7. When done, add the new or changed files for commit: git add template.md
8. Commit your changes with a brief description: git commit -m “brief description here”
9. Push your committed changes to your fork in GitHub: git push
10. Access your fork in GitHub (through browser) and click on Pull Request 
11. Review your pull request, are all the relevant changes there?
12. If something is wrong or missing, go back to step 6.
13. If everything is in order, send the pull request to futurice/eduSpice project.

# Further contributions

-- You need to make sure your local copy (and GitHub fork) are up to date

1. Set your current working directory in terminal to be your local copy of the eduSpice project
2. Fetch the potential changes from the original futurice eduSpice project: git fetch upstream
3. Check out your fork’s master branch: git checkout master
4. Merge the potential changes into your local: git merge upstream/master

-- Project is locally up to date, you can continue to make changes from step 7 in first time instructions

