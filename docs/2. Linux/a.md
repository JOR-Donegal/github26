# Linux

I am not going to do a detailed walkthrough here. GIT commands are the same and when I cover using Linux, it should all make sense. You may come back to these notes in a few weeks.

## SSH

Usernames and passwords are old fashioned and low security. It's much better to use SSH keys and logging on and off from Linux servers.

On a Linux server called __Sonar1__ or any Linux IoT device, I create a unique SSH key.

''''linux
ssh-keygen -t ed25519 -C "john.oraw@hotmail.com"
''''

I check the ~/.ssh directory

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig27.jpg">
<figcaption>Fig 27. SSH Directory.</figcaption>
</figure>

Did I make a mistake...you can see my public key?

Do you notice, I didn't show you my private key?

Think about it!

## GITHUB

On GITHUB, I go to my personal profile and add the SSH key, with a meaningful name. I'm currently working on an IoT device called sonar1 running Raspbian OS. Eventually, this IoT device will control a [transducer](https://www.airmar.com/Product/SS510A) on a robotic vessel.

I check to see if everything is working.

<figure>
<img src = "https://jor-donegal.github.io/github26/images/fig28.jpg">
<figcaption>Fig 28. Verification.</figcaption>
</figure>
