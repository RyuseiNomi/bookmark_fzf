# bookmark_fzf

![](./assets/bookmark_fzf.jpg)

## About it

You can explore your web browsing via bookmarks from your terminal by using this command!

This command load Google Chrome bookmarks from your local machine and show as a list by using [fzf](https://github.com/junegunn/fzf) and open the link.

## Requirements

You need to install **bash version 4.0** or later to exec the command.

If you get an error as below, please install bash with the latest version like `$brew install bash.

```
$ bookmark_fzf
/usr/local/bin/bookmark_fzf: line 7: declare: -A: invalid option
declare: usage: declare [-afFirtx] [-p] [name[=value] ...]
```

## Installation

You can get the command from homebrew

```
$ brew tap RyuseiNomi/tap
$ brew install RyuseiNomi/tap/bookmark_fzf
```


## Usage

The command has no parameter, no option. You can get explore just execute the command as below.

```
$ bookmark_fzf
```

## Demo

![](./assets/demo.gif)

## License

> The MIT License (MIT)
>
> Copyright (c) 2013-2020 Junegunn Choi

https://github.com/junegunn/fzf
