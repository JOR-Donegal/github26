# Undoing

## Undo before Staging

My starting point is to check the current status, both locally and in VSCode.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig39.jpg">
<figcaption>Fig 39. GIT status .</figcaption>
</figure>

Now I’m making a small change in jor.txt and saving but I have not staged or committed.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig40.jpg">
<figcaption>Fig 40. GIT status .</figcaption>
</figure>

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig41.jpg">
<figcaption>Fig 41. Diff .</figcaption>
</figure>

Imagine I have broken something, and I want to revert to the last committed version. If I use the command __git checkout filename__ I can revert to the previous version. I could also use __git restore filename__.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig42.jpg">
<figcaption>Fig 42. Checkout .</figcaption>
</figure>

## Undo after Staging

I have changed the same file again and this time, I have staged the change.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig43.jpg">
<figcaption>Fig 43. Status.</figcaption>
</figure>

You may notice, each time git tells me my options! In this case, I will restore the staged file.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig44.jpg">
<figcaption>Fig 44. Status.</figcaption>
</figure>

Now I can either remodify or restore from the last commit.

## Undo after Commit

This time I will stage and commit all using VSCode. I am using the message “Update at 14:46”.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig45.jpg">
<figcaption>Fig 45. Status.</figcaption>
</figure>

First, I need to identify the version I want. As you can see, my messages are very unhelpful, that is a lesson! I want to revert to a previous saved version.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig46.jpg">
<figcaption>Fig 46. Log.</figcaption>
</figure>

To go back to that version, I can also use git checkout hash with the hash of the version I want to restore.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig47.jpg">
<figcaption>Fig 47. Roll back.</figcaption>
</figure>

I can then commit this and push it to GitHub.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig48.jpg">
<figcaption>Fig 48. Commit.</figcaption>
</figure>

And finally, to check it really has updated....

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig49.jpg">
<figcaption>Fig 49. Verify.</figcaption>
</figure>
