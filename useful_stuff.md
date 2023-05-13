---
layout: page
title: Useful stuff
description: Idk, I think it's useful...
background: '/img/escher2_half.jpg'
---

Here I post resources that I found useful when working on data science stuff. I'll keep updating it as I go.

## Git

- **Set up SSH keys to communicate with Gitlab/Github/whatever**
    I always have to consult this, and enough people has asked me to the point where I think it's useful to have it written here.
    
    The steps are taken from [this guide](https://docs.gitlab.com/ee/user/ssh.html). In particular these steps:
    1. Generate an SSH key pair](https://docs.gitlab.com/ee/user/ssh.html#generate-an-ssh-key-pair) (the ED25519 one)
    2. [Add an SSH key to your GitLab account](https://docs.gitlab.com/ee/user/ssh.html#add-an-ssh-key-to-your-gitlab-account) (if the way to copy the public key doesn't work, see this (basically run `cat ~/.ssh/id_ed25519.pub` and copy the output)). Then if you are in Github instead of Gitlab, go to your settings, to the "SSH and GPG keys" section, and click the button to add the ssh key.
    3. Finally, either try [this](https://docs.gitlab.com/ee/user/ssh.html#verify-that-you-can-connect), or just try to clone a repo.

- [Nice explanation on branching and merging](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging).

- ...

- You can also ask chatgpt for git-related stuff :)

## Python

- ...

- How to create a simple package (under construction)