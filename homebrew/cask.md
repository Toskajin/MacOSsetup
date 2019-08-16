# cask



[Homebrew-Cask](https://caskroom.github.io/) extends Homebrew and allows you to install large binary files via a command-line tool. You can for example install applications like Google Chrome, Dropbox, VLC and Spectacle. No more downloading `.dmg` files and dragging them to your Applications folder!

### Installation <a id="installation"></a>

You need Homebrew on your system to use Cask, and you make Cask available by adding it as a tap:

```text
$ brew tap caskroom/cask
```

### Search <a id="search"></a>

To see if an app is available on Cask you can search on the [official Cask website](https://caskroom.github.io/). You can also search in your terminal:

```text
$ brew cask search <package>
```

### usage

"To install, drag this icon..." no more. `brew cask` installs macOS apps, fonts and plugins and other non-open source software.

```text
$ brew cask install firefox
```

