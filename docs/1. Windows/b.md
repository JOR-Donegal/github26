# Cloning a repo

The computer I'm using for this exercise has the unwieldy path to my GITHUB files of C:\Users\John ORaw\OneDrive\GITHUB.johnoraw-education

````dos
cd C:\Users\John ORaw\OneDrive\GITHUB.johnoraw-education
````

I am going to clone the repo called __First__.

````dos
git clone https://github.com/JOR-Donegal/First.git
````

This creates a new directory called __First__ with the files I previously had in GitHub.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig1.jpg">
<figcaption>Fig 3. Cloning.</figcaption>
</figure>

## Adding a local file In Windows

I add a text file (jor.txt) with some random text. Can you figure out the old DOS command __copy con__?

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig4.jpg">
<figcaption>Fig 4. Create a test file.</figcaption>
</figure>

I add this for staging and then commit the new file. You should know what all this means from the previous notes.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig5.jpg">
<figcaption>Fig 5. Stage and Commit.</figcaption>
</figure>

But the message "Your branch is ahead of 'origin/main' by 1 commit."??

## Checking the remote origin

Because I originally cloned from a remote origin, Git knows where I can fetch or push things to. In Git, an origin is a pointer to the URL where you copied the repo from. Origin is the default remote name in Git. I should check all my configuration.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig6.jpg">
<figcaption>Fig 6. Config.</figcaption>
</figure>

The config includes details of where this repo was copied from, the origin.

## Pushing to the remote origin

I have a new file committed which is not in the remote location. I can now push this.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig7.jpg">
<figcaption>Fig 7. Pushing my changes back.</figcaption>
</figure>

And then check through the web browser to see if this worked.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig8.jpg">
<figcaption>Fig 8. Verify the changes.</figcaption>
</figure>