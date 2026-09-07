# Repo from local files

Sometimes I populate a repo from local files.

Using the web interface, create a new empty public repo called __Second__

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig14.jpg">
<figcaption>Fig 14. New Repo.</figcaption>
</figure>

At setup I can see the URL as https://github.com/JOR-Donegal/Second.git

On the next page, I have several options, but I do nothing else here.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig15.jpg">
<figcaption>Fig 15. Landing page.</figcaption>
</figure>

On my local PC, I create a new folder called __Second__ and create some directories in it. Then I copy some random files to the directories. I called my directories rubbish 1-4, I left directory 4 empty, no files.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig16.jpg">
<figcaption>Fig 16. Dummy directories.</figcaption>
</figure>

Open a terminal at this path.

I use _git status_ to see if this is already a repo. I then ran commands to make it a repo.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig17.jpg">
<figcaption>Fig 17. Commands to create a repo.</figcaption>
</figure>

In Fig 15, some commands were recommended to push a repo from the command line, I will use these now.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig18.jpg">
<figcaption>Fig 18. Push a repo.</figcaption>
</figure>

If we review the repo, it looks almost correct. There is no folder called rubbish4. Can you figure out why?

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig19.jpg">
<figcaption>Fig 19. Push a repo.</figcaption>
</figure>

Note the command __git add *__ and identify what is does. Any directory which was empty did not copy up!
