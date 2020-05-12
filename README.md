<p align="center">
  <img src="mac_os-config.png" alt="MacOS Config Icon"/>
</p>

# macOS Configuration

[![Circle CI Status](https://circleci.com/gh/bkuhlmann/mac_os-config.svg?style=svg)](https://circleci.com/gh/bkuhlmann/mac_os-config)

Shell scripts for customized macOS machine setup and configuration.

This project provides a highly opinionated default configuration built upon the
[macOS](https://github.com/bkuhlmann/mac_os) project. Should the configuration provided by this
project not be to your liking, feel free to fork and customize for your specific needs.

<!-- Tocer[start]: Auto-generated, don't remove. -->

## Table of Contents

  - [Features](#features)
  - [Requirements](#requirements)
  - [Setup](#setup)
  - [Usage](#usage)
    - [Pre-Install](#pre-install)
    - [Install](#install)
    - [Post-Install](#post-install)
    - [Global Hotkeys](#global-hotkeys)
    - [Newsyslog](#newsyslog)
    - [Customization](#customization)
  - [Versioning](#versioning)
  - [Code of Conduct](#code-of-conduct)
  - [Contributions](#contributions)
  - [License](#license)
  - [History](#history)
  - [Credits](#credits)

<!-- Tocer[finish]: Auto-generated, don't remove. -->

## Features

- Downloads, installs, and configures [Homebrew Formula](http://brew.sh) command line software:
    - [asciinema](https://asciinema.org)
    - [autoconf](https://www.gnu.org/software/autoconf)
    - [automake](https://www.gnu.org/software/automake/)
    - [Bash](https://www.gnu.org/software/bash)
    - [Bash Completion](http://bash-completion.alioth.debian.org)
    - [Bat](https://github.com/sharkdp/bat)
    - [blueutil](https://github.com/toy/blueutil)
    - [Byobu](http://byobu.co/index.html)
    - [chruby](https://github.com/postmodern/chruby)
    - [cloc](http://cloc.sourceforge.net)
    - [coreutils](https://www.gnu.org/software/coreutils)
    - [CTags](http://ctags.sourceforge.net)
    - [curl](https://curl.haxx.se/)
    - [diff-so-fancy](https://github.com/so-fancy/diff-so-fancy)
    - [Entr](http://eradman.com/entrproject)
    - [ExifTool](http://www.sno.phy.queensu.ca/~phil/exiftool/index.html)
    - [fasd](https://github.com/clvv/fasd)
    - [fd](https://github.com/sharkdp/fd)
    - [FLAC](https://www.xiph.org/flac)
    - [FZF](https://github.com/junegunn/fzf)
    - [Git](http://git-scm.com)
    - [Git Sizer](https://github.com/github/git-sizer)
    - [GPG](https://www.gnupg.org)
    - [Graphics Magick](http://www.graphicsmagick.org)
    - [Graphviz](http://www.graphviz.org)
    - [hexyl](https://github.com/sharkdp/hexyl)
    - [hr](https://github.com/LuRsT/hr)
    - [htop](http://hisham.hm/htop)
    - [Hyperfine](https://github.com/sharkdp/hyperfine)
    - [jq](http://stedolan.github.com/jq)
    - [lame](http://lame.sourceforge.net)
    - [Lynis](https://github.com/CISOfy/lynis)
    - [Magic Wormhole](https://magic-wormhole.readthedocs.io)
    - [Mac App Store](https://github.com/mas-cli/mas)
    - [Minisign](https://jedisct1.github.io/minisign)
    - [Mosh](http://mosh.mit.edu)
    - [Namebench](https://code.google.com/p/namebench)
    - [NCurses Disk Usage](https://dev.yorhel.nl/ncdu)
    - [Nginx](http://wiki.nginx.org)
    - [Noti](https://github.com/variadico/noti)
    - [Nushell](https://github.com/nushell/nushell)
    - [OpenSSL](https://openssl.org)
    - [Pandoc](https://pandoc.org)
    - [Parallel](https://savannah.gnu.org/projects/parallel)
    - [Pigz](http://www.zlib.net/pigz)
    - [Pretty Ping](http://denilson.sa.nom.br/prettyping)
    - [Pipe Viewer](http://www.ivarch.com/programs/pv.shtml)
    - [Ranger](https://ranger.github.io)
    - [Readline](http://tiswww.case.edu/php/chet/readline/rltop.html)
    - [Reattach to User Namespace](https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard)
    - [Redis](http://redis.io)
    - [ripgrep](https://github.com/BurntSushi/ripgrep)
    - [Ruby Install](https://github.com/postmodern/ruby-install)
    - [Rust](https://www.rust-lang.org)
    - [ShellCheck](https://github.com/koalaman/shellcheck)
    - [Sleepwatcher](http://www.bernhard-baehr.de)
    - [Sox](http://sox.sourceforge.net/sox.html)
    - [Tag](https://github.com/jdberry/tag)
    - [Tarsnap](https://www.tarsnap.com)
    - [Terraform](https://www.terraform.io)
    - [The Silver Surfer](https://github.com/ggreer/the_silver_searcher)
    - [Tig](https://jonas.github.io/tig)
    - [tmux](http://tmux.sourceforge.net)
    - [Tree](http://mama.indstate.edu/users/ice/tree)
    - [Vim](http://www.vim.org)
    - [Watch](https://gitlab.com/procps-ng/procps)
    - [Wrk](https://github.com/wg/wrk)
    - [Yank](https://github.com/mptre/yank)
    - [Zsh](https://www.zsh.org/)
    - [Zsh Completion](https://github.com/zsh-users/zsh-completions)
- Downloads, installs, and configures [Homebrew Cask](https://caskroom.github.io) command line
  software:
    - [Alacritty](https://github.com/alacritty/alacritty)
    - [App Cleaner](http://www.freemacsoft.net/appcleaner)
    - [Atom](https://atom.io/)
    - [ClipGrab](https://clipgrab.org)
    - [CMake](https://cmake.org/)
    - [Dash](http://kapeli.com/dash)
    - [Docker](https://www.docker.com/community-edition)
    - [Dropbox](https://www.dropbox.com)
    - [Firefox](http://www.mozilla.com/en-US/firefox)
    - [Gimp](https://www.gimp.org/)
    - [Google Chrome](http://www.google.com/chrome)
    - [Google drive](https://www.google.com/drive/)
    - [HandBrake](http://handbrake.fr)
    - [iTerm2](http://www.iterm2.com)
    - [Mac Tex](https://www.tug.org/mactex/)
    - [Mac Vim](https://github.com/macvim-dev/macvim)
    - [Mendeley](https://www.mendeley.com/)
    - [Numi](http://numi.io)
    - [Onyx](https://www.titanium-software.fr/en/onyx.html)
    - [pgAdmin](http://www.pgadmin.org/index.php)
    - [Sublime Text 3](http://www.sublimetext.com)
    - [Tunnelblick](https://www.tunnelblick.net/)
    - [Virtual Box](https://www.virtualbox.org/)
    - [Virtual Box Extension Pack](https://www.virtualbox.org/)
    - [Visual Studio Code](https://code.visualstudio.com)
    - [VLC](http://www.videolan.org/vlc)
- Downloads, installs, and configures
    [App Store](http://www.apple.com/macosx/whats-new/app-store.html) applications.
    - [Leech](https://manytricks.com/leech)
    - [Slack](https://slack.com)
- Downloads, installs, and configures software applications not supported via Homebrew or the App
  Store:
    - ~~[Docker](https://www.docker.com)~~
    - ~~[HandBrake CLI](http://handbrake.fr)~~
    - ~~[Sublime Text URL Handler](https://github.com/asuth/subl-handler)~~
- Downloads, installs, and configures software extensions:
    - [Citation style language](https://github.com/citation-style-language/styles.git)
    - [Vim Airline](https://github.com/vim-airline/vim-airline)
    - [Vim Commentary](https://github.com/tpope/vim-commentary)
    - [Vim Fugitive](https://github.com/tpope/vim-fugitive)
    - [Vim Git Gutter](https://github.com/airblade/vim-gitgutter)
    - [Vim Snippets](https://github.com/honza/vim-snippets)
    - [Vim Splitjoin](https://github.com/AndrewRadev/splitjoin.vim)
    - [Vim Supertab](https://github.com/ervandew/supertab)
    - [Vim Ultisnips](https://github.com/SirVer/ultisnips)
    - [YouCompleteMe](https://github.com/Valloric/YouCompleteMe)

## Requirements

1. [macOS](https://github.com/bkuhlmann/mac_os)

## Setup

Open a terminal window and execute one of the following setup sequences depending on your version
preference:

Current Version (stable):

    git clone https://github.com/bkuhlmann/mac_os-config.git
    cd mac_os-config
    git checkout 12.2.0

Master Version (unstable):

    git clone https://github.com/bkuhlmann/mac_os-config.git
    cd mac_os-config

## Usage

The following will walk you through the steps of installing/re-installing your machine.

### Pre-Install

Double check you have the following in place:

1. A recent backup of your machine and a copy of your credentials to restore the backup.
1. A copy of your of your Apple, backup server, and backup volume credentials.
1. Xcode installed as per macOS requirements.

### Install

See the [macOS](https://github.com/bkuhlmann/mac_os#usage) project for usage as it provides the
command line interface for running the configuration defined by this project.

### Post-Install

The following are additional steps, not easily automated, that are worth completing after the
install scripts have been executed:

- System Preferences:
  - Security & Privacy:
    - General:
      - Require password immediately after sleep or screen saver begins.
      - Enable message when screen is locked. Example: `<url> | <email> | <phone>`.
      - Allow your Apple Watch to unlock your Mac.
    - FileVault:
      - Enable FileVault and save the recovery key in a secure location (i.e. 1Password).
    - Firewall:
      - Enabled it.
      - Automatically allow signed software.
      - Enable stealth mode.
    - Privacy:
      - Apps like Dash, Dropbox, etc. will need to be enabled for accessibility.
  - Notifications:
    - Enable *Do Not Disturb* from 9pm to 7am.
    - Enable *When display is sleeping.*
    - Enable *When mirroring.*
    - Enable allow repeated calls.
    - Disable *Show notifications on lock screen* for all apps.
    - Disable *Play sounds for notifications* for all apps.
    - Configure all calendar apps to show banners instead of alerts for notifications.
  - Printers & Scanners:
    - Add printer/scanner.
  - iCloud:
    - Enable Find My Mac.
  - Internet Accounts:
    - Add all accounts used by Mail.
  - Network:
    - Configure Wi-Fi.
  - Users & Groups:
    - Update avatar.
    - Remove unused login items.
    - Disable guest account.
- iStat Menus (double click, within the Applications folder, to install as a system preference).
- Hazel (double click, within the Applications folder, to install as a system preference).

### Global Hotkeys

Several applications provide global hotkey support. These are the associations I use (which are also
captured in the `restore.bom` as well):

- **COMMAND + SPACE (hold):** Siri (open)
- **COMMAND + SPACE:** Spotlight (open)
- **CONTROL + OPTION + COMMAND + 1:** CleanShot (capture area)
- **CONTROL + OPTION + COMMAND + 2:** CleanShot (capture fullscreen)
- **CONTROL + OPTION + COMMAND + 3:** CleanShot (record video)
- **CONTROL + OPTION + COMMAND + 4:** Gifox (capture area)
- **CONTROL + OPTION + COMMAND + 5:** Gifox (capture window)
- **CONTROL + OPTION + COMMAND + b:** Bartender (hidden menu toggle)
- **CONTROL + OPTION + COMMAND + c:** Sip (copy color)
- **CONTROL + OPTION + COMMAND + ENTER:** Keymo (move cursor by division)
- **CONTROL + OPTION + COMMAND + k:** Keymo (cursor highlight show/hide)
- **CONTROL + OPTION + COMMAND + m:** Moom (show/hide)
- **CONTROL + OPTION + COMMAND + n:** Notification Center (show/hide)
- **CONTROL + OPTION + COMMAND + p:** PixelSnap (show/hide)
- **CONTROL + OPTION + COMMAND + r:** Resolutionator (selector)
- **CONTROL + OPTION + COMMAND + s:** KeyCastr (show/hide)
- **CONTROL + OPTION + COMMAND + ←:** Keymo (move cursor left)
- **CONTROL + OPTION + COMMAND + ↑:** Keymo (move cursor up)
- **CONTROL + OPTION + COMMAND + →:** Keymo (move cursor right)
- **CONTROL + OPTION + COMMAND + ↓:** Keymo (move cursor down)
- **CONTROL + OPTION + SPACE:** OmniFocus (quick entry)
- **OPTION + SPACE:** Alfred (open)

### Newsyslog

Native to macOS, [newsyslog](https://www.freebsd.org/cgi/man.cgi?newsyslog.conf(5)) can be used to
configure system-wide log rotation across multiple projects. It's a good recommendation to set this
up so that disk space is carefully maintained. Here's how to configure it for your system, start by
creating a configuration for your projects in the `/etc/newsyslog.d` directory. In my case, I use
the following configurations:

- `/etc/newsyslog.d/alchemists.conf`

        # logfilename                                            [owner:group]    mode   count   size  when  flags
        /Users/bkuhlmann/Dropbox/Development/Work/**/log/*.log                    644    2       5120  *     GJN
- `/etc/newsyslog.d/homebrew.conf`

        # logfilename                   [owner:group]    mode   count   size    when  flags
        /usr/local/var/log/**/*.log                      644    2       5120    *     GJN

These configurations ensure that logs are rotated every 5MB (5120KB). In order to test that these
configurations are valid, run:

    sudo newsyslog -nvv

If you don't see any errors in the output, then your configuration settings are correct.

The last thing to do is to add a launch configuration to ensure the log rotations happen at
regularly scheduled intervals. To do this create the following file:
`$HOME/Library/LaunchAgents/com.apple.newsyslog.plist`. It should have the following content:

    <?xml version="1.0" encoding="UTF-8"?>
    <!DOCTYPE plist PUBLIC "-//Apple Computer//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
    <plist version="1.0">
    <dict>
      <key>Label</key>
      <string>com.apple.newsyslog</string>
      <key>ProgramArguments</key>
      <array>
        <string>/usr/sbin/newsyslog</string>
      </array>
      <key>LowPriorityIO</key>
      <true/>
      <key>Nice</key>
      <integer>1</integer>
      <key>StartCalendarInterval</key>
      <dict>
        <key>Minute</key>
        <integer>30</integer>
      </dict>
    </dict>
    </plist>

That's it. System-wide log rotation is setup for your projects.

### Customization

While this project's configuration is opinionated and tailored for my setup, you can easily fork
this project and customize it for your environment. Start by editing the files found in the `bin`
and `lib` directories. Here is a breakdown of each:

- `bin/apply_basic_settings`: Applies basic and initial settings for setting up a machine.
- `bin/apply_default_settings`: Applies useful system and application defaults.
- `bin/install_app_store`: Installs macOS, GUI-based, App Store applications.
- `bin/install_applications`: Installs macOS, GUI-based, non-App Store applications.
- `bin/install_extensions`: Installs macOS application extensions and add-ons.
- `bin/install_homebrew_casks`: Installs Homebrew Casks.
- `bin/install_homebrew_formulas`: Installs Homebrew Formulas.
- `bin/restore_backup`: Restores system/application settings from backup image.
- `bin/setup_software`: Configures and launches (if necessary) installed software.
- `lib/settings.sh`: Defines custom settings for software applications, extensions, etc.

*TIP*: The installer determines which applications/extensions to install as defined in the
`settings.sh` script. Applications defined with the "APP_NAME" suffix and extensions defined with
the "EXTENSION_PATH" suffix inform the installer what to care about. Removing/commenting out these
applications/extensions within the `settings.sh` file will cause the installer to skip these
applications/extensions.

## Versioning

Read [Semantic Versioning](https://semver.org) for details. Briefly, it means:

- Major (X.y.z) - Incremented for any backwards incompatible public API changes.
- Minor (x.Y.z) - Incremented for new, backwards compatible, public API enhancements/fixes.
- Patch (x.y.Z) - Incremented for small, backwards compatible, bug fixes.

## Code of Conduct

Please note that this project is released with a [CODE OF CONDUCT](CODE_OF_CONDUCT.md). By
participating in this project you agree to abide by its terms.

## Contributions

Read [CONTRIBUTING](CONTRIBUTING.md) for details.

## License

Copyright 2016 [Alchemists](https://www.alchemists.io).
Read [LICENSE](LICENSE.md) for details.

## History

Read [CHANGES](CHANGES.md) for details.
Built with [Bashsmith](https://github.com/bkuhlmann/bashsmith).

## Credits

Developed by [Brooke Kuhlmann](https://www.alchemists.io) at
[Alchemists](https://www.alchemists.io).
