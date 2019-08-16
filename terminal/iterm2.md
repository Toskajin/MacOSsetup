# iterm2

[iTerm2](http://www.iterm2.com/) is an open source replacement for Apple's Terminal. It's highly customizable and comes with a lot of useful features.

### Installation <a id="installation"></a>

Use [Homebrew](http://sourabhbajaj.com/mac-setup/Homebrew/) to download and install:

```text
brew cask install iterm2
```

### Customization <a id="customization"></a>

#### Colors and Font Settings <a id="colors-and-font-settings"></a>

Here are some suggested settings you can change or set, **they are all optional**.

* Set hot-key to open and close the terminal to `command + option + i`
* Go to profiles -&gt; Default -&gt; Terminal -&gt; Check silence bell to disable the terminal session from making any sound
* Download [one of iTerm2 color schemes](https://github.com/mbadolato/iTerm2-Color-Schemes/tree/master/schemes) and then set these to your default profile colors
* Change the cursor text and cursor color to yellow make it more visible
* Change the font to 14pt Source Code Pro Lite. Source Code Pro can be downloaded using [Homebrew](https://sourabhbajaj.com/mac-setup/Homebrew/) `brew tap caskroom/fonts && brew cask install font-source-code-pro`
* If you're using BASH instead of ZSH you can add `export CLICOLOR=1` line to your `~/.bash_profile`file for nice coloring of listings

