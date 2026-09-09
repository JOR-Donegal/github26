# New projects

Where we have complex projects with multiple developers, we need some way to allow users to work independently. And once we have a usable project, we will need to add features from time to time. We alo have to maintain the project, with bug and security fixes.

In GIT, we can work on multiple branches of a project simultaneously without breaking the main project.

I created a new repo called __BranchTest__ on GitHub. I created a directory OneDrive - Atlantic TU\GitHub\BranchTest and created a single batch file in the directory, __setup.cmd__.

````linux
echo "# BranchTest" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/GreatlyImprovedTechnology/BranchTest.git
git push -u origin main
````

My file setup.cmd is not in the GitHub repo, in this case, I’ll add it and I check online to confirm.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig50.jpg">
<figcaption>Fig 50. Create new repo.</figcaption>
</figure>

The question arises, should I have included this file in the repo, or should I have excluded any such local build files in a .gitignore file? And as for my __readme.md__, GitHub kept the quote marks and didn’t render the line as markdown. I edited the line in GitHub and did a pull to resync.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig51.jpg">
<figcaption>Fig 51. Pull.</figcaption>
</figure>

That renders properly now!

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig52.jpg">
<figcaption>Fig 52. Verify.</figcaption>
</figure>