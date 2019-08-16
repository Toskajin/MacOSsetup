# Git

## Git and GitHub <a id="git-and-github"></a>

What's a developer without [Git](http://git-scm.com/)? To install, run:

```text
$ brew install git
```

When done, to test that it installed properly you can run:

```text
$ git --version
```

And `which git` should output `/usr/local/bin/git`.

Next, we'll define your Git user \(should be the same name and email you use for [GitHub](https://github.com/)\):

```text
$ git config --global user.name "Your Name Here"
$ git config --global user.email "your_email@youremail.com"
```

They will get added to your `.gitconfig` file.

To push code to your GitHub repositories, we're going to use the recommended HTTPS method \(versus SSH\). To prevent `git` from asking for your username and password every time you push a commit you can cache your credentials by running the following command, as described in the [instructions](https://help.github.com/articles/caching-your-github-password-in-git/).

```text
$ git config --global credential.helper osxkeychain
```

### SSH Config for GitHub <a id="ssh-config-for-github"></a>

The instructions below are referenced from [the official documentation](https://help.github.com/articles/generating-ssh-keys).

#### Check for existing SSH keys <a id="check-for-existing-ssh-keys"></a>

First, we need to check for existing SSH keys on your computer. We do this by running:

```text
$ ls -al ~/.ssh
# Lists the files in your .ssh directory, if they exist
```

Check the directory listing to see if you have files named either `id_rsa.pub` or `id_dsa.pub`. If you don't have either of those files then read on, otherwise skip the next section.

#### Generate a new SSH key <a id="generate-a-new-ssh-key"></a>

If you don't have an SSH key you need to generate one. To do that you need to run the commands below, and make sure to substitute the placeholder with your email. The default settings are preferred, so when you're asked to "enter a file in which to save the key,"" just press Enter to continue.

```text
$ ssh-keygen -t rsa -C "your_email@example.com"
# Creates a new ssh key, using the provided email as a label
```

