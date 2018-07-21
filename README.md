# activetimer

> Track how long you've been working

activetimer is a shell script.

## Install

Use [bin/activetimer](bin/activetimer) however you like. You can also install me via npm (`npm install -g rstacruz/activetimer` - it's a shell script, npm is only used as an installer).

## Usage

```sh
# Mark the current time as you started working
activetimer start
```

```sh
# After some time, show how long you've been working since
# you've typed the command above
activetimer duration  # => `2m 4s`
```

## Practical usage

**activetimer** is geared towards those who like to DIY their own desktop experience. It has no GUI, but you can integrate it into your desktop into whatever way you like.

1. **Show an indicator** &mdash; Show `activetimer duration` in your desktop somewhere. You can do this in many ways:

  > - [BitBar](https://bitbar.com/) (macOS)
  > - [GeekTool](https://www.tynsoe.org/v2/geektool/) (macOS)
  > - [Conky](https://github.com/brndnmtthws/conky) (Linux)
  > - [Polybar](https://github.com/jaagr/polybar) (Linux)
  > - your shell prompt
  > - your tmux status bar
  > - your vim status bar
  > - your emacs status bar
  > - _...and so on_

2. **Auto-reset on idle** _(Optional)_ &mdash; Run `activetimer start` after your computer gets out of screensaver mode. This will reset the work timer after you've been away from your computer. Here's a few ways to do it:

  > - [Sleepwatcher](http://brewformulas.org/Sleepwatcher) (macOS)
  > - [xautolock](https://linux.die.net/man/1/xautolock) (Linux)

3. **Manual reset** _(Optional)_ &mdash; you can also make a shortcut to `activetimer start`, preferrably when you click on the indicator that you've set up in step 1.

If you don't do either 2 or 3, simply run `activetimer start` manually to mark your time.

## Thanks

**activetimer** © 2018, Rico Sta. Cruz. Released under the [MIT] License.<br>
Authored and maintained by Rico Sta. Cruz with help from contributors ([list][contributors]).

> [ricostacruz.com](http://ricostacruz.com) &nbsp;&middot;&nbsp;
> GitHub [@rstacruz](https://github.com/rstacruz) &nbsp;&middot;&nbsp;
> Twitter [@rstacruz](https://twitter.com/rstacruz)

[![](https://img.shields.io/github/followers/rstacruz.svg?style=social&label=@rstacruz)](https://github.com/rstacruz) &nbsp;
[![](https://img.shields.io/twitter/follow/rstacruz.svg?style=social&label=@rstacruz)](https://twitter.com/rstacruz)

[MIT]: http://mit-license.org/
[contributors]: http://github.com/rstacruz/activetimer/contributors
