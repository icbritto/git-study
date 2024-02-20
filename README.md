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
```
