# Feature Branch

As discussed in the theory notes, we should be doing commits on code changes on dedicated feature branches. When they are looking good, we can merge them to dev or test. I am going to add initial pages to my repo. This time, I’m going to use an option -b to create and change branches in a single command.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig57.jpg">
<figcaption>Fig 57. Checkout.</figcaption>
</figure>

And I verify I am on the right branch.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig58.jpg">
<figcaption>Fig 58. Verify branch.</figcaption>
</figure>

Next, I add in some files, and test them to ensure they basically work. After, I check where I am with git status.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig59.jpg">
<figcaption>Fig 59. Verify status.</figcaption>
</figure>

I stage and commit these files to the initial_pages branch. 

If I have done something stupid and broken the application, it doesn’t matter! The permanent branches, main, test and dev do not utilize this new code, it is only on the specific feature branch.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig60.jpg">
<figcaption>Fig 60. Commit.</figcaption>
</figure>