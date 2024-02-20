# Git

## Configuring Git

First, configure your Git user.

```bash
# substitute "your name" with your GitHub name
git config --global user.name "your name"

# substitute example@gmail.com with your e-mail
git config --global user.email example@gmail.com
```

Once your're done, the next step will be set our default branch to `main`.

```bash
git config --global init.default branch main
```

And if you want to know more about `git config` you can use the following command

```bash
git config -h
```

Or you can also take a look into the git docmentation (you don't have to be connected to the internet to open it).

```bash
git config -h

# and if you want more detailed information about an especific command,use this one and just add the command to end
git help config
```

## Initialize Git

Choose the directory you want to turn into a Git repository.

```bash
# example
cd C:\User\YOURUSER\Documents\git-study
```

And now that your're into the directory, you can initialize a respository using

```bash
git init
```

Now if look at your directory you will see that you have a `.git` directory. This means that everything has gone correctly.

But anyway, lets check if everything has really gone Ok by simply running

```bash
git status
```

If that returns something like that, then its all Ok.

```
On branch main

No commits yet

Untracked files:
    (use "git add <file>..." to include in what will be committed)
        index.html
        README.md

nothing added to commit but untracked files present (use "git add" to track)
```

