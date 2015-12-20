# The One Theme

> A dark theme for [iTerm](http://www.iterm2.com/), [Slack](http://slack.com/), [Terminal](https://en.wikipedia.org/wiki/Terminal_%28OS_X%29), and [ZSH](http://www.zsh.org/) based on [Atom's](http://atom.io/) One Dark syntax theme.

## Install

### iTerm 2

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```
$ git clone https://github.com/benniemosher/the-one-theme/
```

#### Install manually

Download using the [GitHub .zip download](https://github.com/benniemosher/the-one-theme/archive/master.zip) option and unzip them.

#### Activating theme

1. iTerm2 > Preferences > Profiles > Colors Tab
1. Click Load Presets...
1. Click Import...
1. Select the `iterm/TheOne.itermcolors` file
1. Select "The One" from Load Presets...

### Slack

#### Install manually

1. Go to User Menu > Preferences > Sidebar Theme
1. In the bottom of the window, look for a "customize your theme and share it with others" link
1. Copy and paste the values below

```
#272B33,#3e4451,#3e4451,#61AFEF,#5b626f,#FFFFFF,#97C279,#DF6B75
```

### Terminal

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```
$ git clone https://github.com/benniemosher/the-one-theme/
```

#### Install manually

Download using the [GitHub .zip download](https://github.com/benniemosher/the-one-theme/archive/master.zip) option and unzip them.

#### Activating theme

1. Terminal > Settings Tab
1. Click "Gear" icon
1. Click Import...
1. Select the `terminal/TheOne.terminal` file
1. Click Default

### ZSH

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```
$ git clone https://github.com/benniemosher/the-one-theme/
```

And creating a symbolic link to [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/)'s theme folder:

```
$ ln -s $THE_ONE_THEME/zsh/TheOne.zsh-theme $OH_MY_ZSH/themes/TheOne.zsh-theme
```

P.S.: Remember that you should replace $THE_ONE_THEME and $OH_MY_ZSH to the actual directories for this command to work.

#### Install manually

1. Download using the [GitHub .zip download](https://github.com/benniemosher/the-one-theme/archive/master.zip) option and unzip them.
1. Move zsh/TheOne.zsh-theme file to oh-my-zsh's theme folder: oh-my-zsh/themes/TheOne.zsh-theme.

#### Activating theme

Go to your ~/.zshrc file and set ZSH_THEME="TheOne".

## Roadmap

###### "Are you going to create a light color scheme?"

Yes. [Atom](http://atom.io/) has a One Light syntax theme, and eventually we will support that theme as well.

###### "Are you going to support editor X?"

I hope so, but I need your help to accomplish that. Since you're using editor X you're probably much more expert on it than me. So feel free to send a pull request based on the [Color Palette](#color-palette) below.

## Color Palette

Palette      | Hex       | RGB           | HSL
---          | ---       | ---           | ---
Background   | `#272B33` | `39 43 51`    | `220° 13% 18%`
Comment      | `#5b626f` | `91 98 111`   | `219° 10% 39%`
Current Line | `#2c323d` | `44 50 61`    | `219° 16% 21%`
Foreground   | `#abb2c0` | `171 178 192` | `220° 14% 71%`
Selection    | `#3e4451` | `62 68 81`    | `221° 13% 28%`
Blue 1       | `#61AFEF` | `97 175 239`  | `207° 82% 66%`
Blue 2       | `#65b6f8` | `101 182 248` | `207° 91% 68%`
Cyan 1       | `#56B5C2` | `86 181 194`  | `187° 47% 55%`
Cyan 2       | `#66d7e6` | `102 215 230` | `187° 72% 65%`
Green 1      | `#97C279` | `151 194 121` | `95° 38% 62%`
Green 2      | `#abdc89` | `171 220 137` | `95° 54% 70%`
Orange 1     | `#D19965` | `209 153 101` | `29° 54% 61%`
Orange 2     | `#E4BF7A` | `228 191 122` | `39° 67% 69%`
Purple 1     | `#C578DD` | `197 120 221` | `286° 60% 67%`
Purple 2     | `#d682f0` | `214 130 240` | `286° 79% 73%`
Red 1        | `#DF6B75` | `223 107 117` | `355° 65% 65%`
Red 2        | `#BE5046` | `190 80 70`   | `5° 48% 51%`
Yellow 1     | `#e2c08d` | `226 192 141` | `36° 59% 72%`
Yellow 2     | `#f2ce97` | `242 206 151` | `36° 78% 77%`

## Team

The One is a project created by [Bennie Mosher](https://github.com/benniemosher/) with the help of many awesome [contributors](https://github.com/benniemosher/the-one-theme/graphs/contributors). For each code editor theme there's a specific maintainer, that way we can achieve more and more code editors and still keep the quality high.

* [@benniemosher](https://github.com/bennieomsher/) - iTerm, Slack, Terminal, and ZSH

## Contributing

If you want to help, please read the [Contributing](https://github.com/benniemosher/the-one-theme/blob/master/CONTRIBUTING.md) guide.

## Credits

* Color palette inspired by [@atom's One Dark Syntax theme](https://github.com/atom/one-dark-syntax)

## History

For detailed changelog, see [Releases](https://github.com/benniemosher/the-one-theme/releases).

## License

[MIT License](http://benniemosher.mit-license.org) © Bennie Mosher
