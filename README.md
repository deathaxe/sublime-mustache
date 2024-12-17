# Sublime Mustache

[Mustache](https://mustache.github.io/) Syntax definitions and Snippets for for [Sublime Text](https://www.sublimetext.com) 
based on its CSS, HTML, JavaScript and JSON syntaxes.

## Installation

### Package Control

The easiest way to install is using [Package Control](https://packagecontrol.io). It's listed as `Mustache`.

1. Open `Command Palette` using <kbd>ctrl+shift+P</kbd> or menu item `Tools → Command Palette...`
2. Choose `Package Control: Install Package`
3. Find `Mustache` and hit <kbd>Enter</kbd>

### Manual Install

1. Download appropriate [Mustache.sublime-package](https://github.com/SublimeText/Mustrache/releases) for your Sublime Text build.
2. Copy it into _Installed Packages_ directory

> [!NOTE]
>
> To find _Installed Packages_...
>
> 1. call _Menu > Preferences > Browse Packages.._
> 2. Navigate to parent folder

### Git Clone

You can clone this repository into your _Sublime Text x/Packages_

##### Mac OS

```shell
cd ~/Library/Application\ Support/Sublime\ Text/Packages/
git clone https://github.com/SublimeText/Mustache.git
```

##### Linux

```shell
cd ~/.config/sublime-text/Packages
git clone https://github.com/SublimeText/Mustache.git
```

##### Windows

```shell
cd "%APPDATA%\Sublime Text\Packages"
git clone https://github.com/SublimeText/Mustache.git
```

## Snippets

| Name               | Trigger  | Result                                 |
|:-------------------|:---------|:---------------------------------------|
| Escaped Variable   | `var`    | `{{ variable }}`                       |
| Unescaped Variable | `let`    | `{{{ variable }}}`                     |
| Comment            | `!`      | `{{! comment }}`                       |
| Section            | `if`     | `{{# variable }} [..] {{/ variable }}` |
| Inverted Section   | `else`   | `{{^ variable }} [..] {{/ variable }}` |
| Partial            | `inc`    | `{{> partial }}`                       |

## Screenshots

### Monokai
![Monokai](docs/monokai.png)

### Mariana
![Mariana](docs/mariana.png)

### Breakers
![Breakers](docs/breakers.png)

### Sixteen
![Sixteen](docs/sixteen.png)
