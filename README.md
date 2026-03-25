# Awesome Dotfiles [![Awesome][2]][1]

A curated list of dotfiles resources. Inspired by the [awesome][3] list thing. Note that some articles or tools may look
old or old-fashioned, but this usually means they're battle-tested and mature (like dotfiles themselves). Feel free to
propose new articles, projects or tools!

## Articles

### Introductions

- [Getting started with dotfiles][4] ([L. Kappert][5])
- [Getting started with dotfiles][6] ([D. Vints][7])
- [Managing your dotfiles][8]
- [Dotfiles Are Meant to Be Forked][9]
- [Dotfile discovery][10]
- [I do Dotfiles!][11]

### Tutorials

- [Setting up a new (OS X) development machine: Part 3 - Dotfiles and custom SSH config][12]
- [Setting Up a Mac Dev Machine From Zero to Hero With Dotfiles][13]
- [Using Git and GitHub to manage your dotfiles][14]
- [conf.d like directories for zsh/bash dotfiles][15]
- [Managing your dotfiles][16]
- [The best way to store your dotfiles: A bare Git repository][17]
- [Dotfiles Management][18]

### Shell startup

- [Shell startup scripts][19]
- [Zsh/Bash startup files loading order][20]

### Using specific tools

- [Using GNU Stow to manage your dotfiles][21]
- [Managing Dotfile Symlinks with GNU Stow][22]
- [Dotfiles and dev tools provisioned by Ansible][23]

## Find dotfiles repos

There are many great dotfiles repos out there, each containing their own inspiration and gems. One way to go through
them is to [search GitHub for "dotfiles"][24].

Also see:

- [Google for "dotfiles"][25]
- [Archlinux collection][26]
- Tip: search for a filename on GitHub, e.g. [path:\*\*/.gitconfig][27].

## Example dotfiles repos

A collection of the most popular, well-maintained, and collaborative dotfiles repositories & frameworks. Some projects
contain just the dotfiles. Others go further by allowing you to easily add your own custom dotfiles, and some include
scripts to manage dotfiles and plugins.

### Bash

| Title                         | Description                                  | Focus                                                                                                                        |
| :---------------------------- | :------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------- |
| [Bash it][28]                 | Community bash framework.                    | Autocompletion, themes, aliases, custom functions. Well-structured framework                                                 |
| [Mathias’s dotfiles][29]      | Sensible hacker defaults for macOS           | 🔧 .files, including \~/.macos — sensible hacker defaults for macOS                                                          |
| [webpro's dotfiles][30]       | macOS dotfiles                               | Bash, Homebrew, Brew Cask, Git, Node.js, Hammerspoon.                                                                        |
| [rootbeersoup's dotfiles][31] | Effortless Bash, Vim and macOS configuration | A `curl \| sh` installer and a Makefile offer portable and effortless setup for either permanent or temporary configuration. |

### Zsh

| Title                      | Description                                                                                                         | Focus                                                                                                                                            |
| :------------------------- | :------------------------------------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| [Nick Khan's dotfiles][32] | Personal dotfiles for configuring macOS environment with Zsh and Homebrew. No fluff, only the stuff I actually use. | Zsh, Git (w/ aliases), Visual Studio Code, Ghostty, shell aliases, sensible macOS defaults, custom CLI script, etc.                              |
| [thoughtbot dotfiles][33]  | Set of vim, zsh, git, and tmux configuration files                                                                  | Zsh, vim, tmux, git, homebrew. Uses [rcm][34].                                                                                                   |
| [oh-my-zsh][35]            | Community-driven framework for managing your zsh configuration.                                                     | Oh My Zsh is an open source, community-driven framework for managing your Zsh configuration                                                      |
| [Prezto][36]               | The configuration framework for Zsh.                                                                                | Enriches the command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes.                      |
| [Dries's dotfiles][37]     | Simplified approach to dotfiles for macOS                                                                           | Zsh, Oh My Zsh, macOS, Homebrew, Mackup                                                                                                          |
| [sobolevn's dotfiles][38]  | Dotfiles for the developer happiness                                                                                | macOS, zsh, brew, vscode, codespaces, python, node, elixir                                                                                       |
| [yutkat's dotfiles][39]    | Well-maintained dotfiles that use CI to test and measure startup speeds.                                            | Zsh, Neovim, Wezterm, swaywm working on Arch/Ubuntu/Fedora Linux.                                                                                |
| [Luke's voidrice][40]      | My dotfiles (deployed by LARBS)                                                                                     | Zsh, vim/nvim, zsf                                                                                                                               |
| [2KAbhishek's dots2k][41]  | Passionately crafted, extensible dotfiles with multi platform support                                               | CLI tools at core, with extensions for different platforms (windows/mac/android), editors and window managers                                    |
| [Zim][42]                  | Modular, customizable, and blazing fast Zsh framework                                                               | Zim is a Zsh configuration framework that bundles a plugin manager, useful modules, and a wide variety of themes, without compromising on speed. |

### Fish

| Title                   | Description                                                                    | Focus                                                                            |
| :---------------------- | :----------------------------------------------------------------------------- | :------------------------------------------------------------------------------- |
| [oh-my-fish][43]        | The Fish Shell Framework                                                       | Core infrastructure to allow you to install packages to extend/modify your shell |
| [Paul's dotfiles][44]   | paul's fish, bash, git, etc config files. good stuff.                          | Fish, macOS, Homebrew, Custom Shell functions                                    |
| [rkalis's dotfiles][45] | Well-maintained dotfiles featuring Fish, repository management and Hammerspoon | Fish, macOS, Homebrew, Repository management, Hammerspoon                        |

### Ansible

| Title                   | Description                                  | Focus                                                                           |
| :---------------------- | :------------------------------------------- | :------------------------------------------------------------------------------ |
| [.dots][46]             | New and upgraded dotfiles, now with Ansible! | Completely automated desktop setup, configuration and maintenance using Ansible |
| [sloria's dotfiles][47] | sloria's dotfiles as Ansible roles           | Sets up a full local development environment with a single command              |

## Tools

- [Ansible][48] - Radically simple configuration-management, application deployment, task-execution, and multinode
  orchestration engine.
- [bashdot][49] - Minimalist dotfile management framework written entirely in bash.
- [chezmoi][50] - Manage your dotfiles securely across multiple machines.
- [comtrya][51] - Configuration management for localhost, written in Rust, for Linux, BSD, macOS, and Windows.
- [dotbare][52] - Manage dotfiles interactively with fzf.
- [dotbot][53] - Tool that bootstraps your dotfiles.
- [dotdrop][54] - Save your dotfiles once, deploy them everywhere.
- [dots][55] - Opinionated dotfiles generator that allows quick configuration of different window managers in multiple
  OSs!
- [Fisher][56] - A package manager for Fish.
- [fresh][57] - Keep your dotfiles fresh. Fresh is a tool to source shell configuration (aliases, functions, etc) from
  others into your own configuration files.
- [GNU Stow][58] - Symlink farm manager which takes distinct packages of software and/or data located in separate
  directories on the filesystem, and makes them appear to be installed in the same place.
- [homeshick][59] - Git dotfile synchronizer written in Bash.
- [mackup][60] - Keep your application settings in sync (macOS/Linux).
- [OpenBoot][61] - Mac dev environment manager that captures and restores Homebrew packages, dotfiles, shell
  configuration, and macOS preferences via interactive TUI.
- [Pearl][62] - Package manager that allows to control, sync, share dotfiles as packages automatically activated during
  shells or editors startup. There is a wide range of packages already available. in the [Official Pearl Hub][63] (for
  Linux and OSX).
- [rcm][34] - rc file (dotfile) management.
- [rotz][64] - Fully cross-platform dotfile manager and dev environment bootstrapper written in Rust.
- [themer][65] - Manage and generate themes across your development tools from within your dotfiles.
- [toml-bombadil][66] - Templatize and manage your dotfiles.
- [xdg-ninja][67] - A shell script which checks your $HOME for unwanted files and directories.
- [yadm][68] - Tool for managing a collection of files across multiple computers, using a shared Git repository and some
  additional features.

### macOS

- [dockutil][69] - Command line tool for managing dock items.
- [mas][70] - Mac App Store command line interface.
- [zero][71] - Radically simple personal bootstrapping tool for macOS.

## Miscellaneous

- [dotfiles.github.io][72] - Your unofficial guide to dotfiles on GitHub.
- [Filesystem Hierarchy Standard][73] - Directory structure and directory contents in Linux distributions.
- [XDG Base Directory Specification][74] - [Summary][75]
- [A lesson in shortcuts][76] - How the idea of "hidden" or "dot" files was born, by Rob Pike (originally posted on
  Google+).

## Related Lists

- [Awesome Dev Env][77] - Curated list of awesome tools, resources and workflow tips making an awesome development
  environment.
- [Awesome Fish][78] - Curated list of packages, prompts, and resources for the fish shell.
- [Awesome Shell][79] - Curated list of awesome command-line frameworks, toolkits, guides and gizmos.
- [Awesome Sysadmin][80] - A curated list of amazingly awesome open source sysadmin resources.
- [Awesome Zsh Plugins][81] - List of Zsh plugins suitable for use with oh-my-zsh, antigen & Prezto.
- [Terminals Are Sexy][82] - A curated list of Terminal frameworks, plugins & resources for CLI lovers.

## Archive/abandoned projects

- [antigen][83]
- [Bashstrap][84]
- [battleschool][85]
- [Bork][86]
- [Cider][87]
- [dev-setup][88]
- [dotfiles][89]
- [dotstow][90]
- [Eduardo's dotfiles][91]
- [ellipsis][92]
- [emplace][93]
- [holman does dotfiles][94]
- [homesick][95]
- [Kevin's dotfiles][96]
- [kody][97]
- [macOS Defaults][98]
- [osxc][99]
- [vcsh][100] ([article][101], [article][102])
- [YADR][103]

## License

[![CC0][105]][104]

To the extent possible under law, [Lars Kappert][106] has waived all copyright and related or neighboring rights to this
work.

[1]: https://awesome.re
[2]: https://awesome.re/badge.svg
[3]: https://github.com/sindresorhus/awesome
[4]: https://www.webpro.nl/articles/getting-started-with-dotfiles
[5]: https://github.com/webpro
[6]: https://driesvints.com/blog/getting-started-with-dotfiles/
[7]: https://github.com/driesvints
[8]: https://www.webpro.nl/articles/managing-your-dotfiles
[9]: https://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/
[10]: https://wynnnetherland.com/journal/dotfiles-discovery/
[11]: https://jogendra.dev/i-do-dotfiles
[12]: https://mattstauffer.com/blog/setting-up-a-new-os-x-development-machine-part-3-dotfiles-rc-files-and-ssh-config/
[13]: https://code.tutsplus.com/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449t
[14]: http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/
[15]: https://chr4.org/blog/2014/09/10/conf-dot-d-like-directories-for-zsh-slash-bash-dotfiles/
[16]: https://www.anishathalye.com/2014/08/03/managing-your-dotfiles/
[17]: https://www.atlassian.com/git/tutorials/dotfiles
[18]: https://mitxela.com/projects/dotfiles_management
[19]: https://blog.flowblok.id.au/2013-02/shell-startup-scripts.html
[20]: https://shreevatsa.wordpress.com/2008/03/30/zshbash-startup-files-loading-order-bashrc-zshrc-etc/
[21]: http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html
[22]: https://spin.atomicobject.com/manage-dotfiles-gnu-stow/
[23]: http://palcu.blogspot.com/2014/06/dotfiles-and-dev-tools-provisioned-by.html
[24]: https://github.com/search?q=dotfiles&type=Repositories
[25]: https://www.google.nl/search?q=dotfiles
[26]: https://wiki.archlinux.org/index.php/Dotfiles
[27]: https://github.com/search?type=code&q=path%3A**%2F.gitconfig
[28]: https://github.com/Bash-it/bash-it
[29]: https://github.com/mathiasbynens/dotfiles
[30]: https://github.com/webpro/dotfiles
[31]: https://github.com/darrylabbate/dotfiles
[32]: https://github.com/nicksp/dotfiles/
[33]: https://github.com/thoughtbot/dotfiles
[34]: https://github.com/thoughtbot/rcm
[35]: https://ohmyz.sh
[36]: https://github.com/sorin-ionescu/prezto
[37]: https://github.com/driesvints/dotfiles
[38]: https://github.com/sobolevn/dotfiles
[39]: https://github.com/yutkat/dotfiles
[40]: https://github.com/LukeSmithxyz/voidrice
[41]: https://github.com/2KAbhishek/dots2k
[42]: https://github.com/zimfw/zimfw
[43]: https://github.com/oh-my-fish/oh-my-fish
[44]: https://github.com/paulirish/dotfiles
[45]: https://github.com/rkalis/dotfiles
[46]: https://github.com/Addvilz/dots
[47]: https://github.com/sloria/dotfiles
[48]: https://www.ansible.com
[49]: https://github.com/bashdot/bashdot
[50]: https://github.com/twpayne/chezmoi
[51]: https://github.com/comtrya/comtrya
[52]: https://github.com/kazhala/dotbare
[53]: https://github.com/anishathalye/dotbot
[54]: https://github.com/deadc0de6/dotdrop
[55]: https://github.com/ulises-jeremias/dotfiles
[56]: https://github.com/jorgebucaran/fisher
[57]: https://freshshell.com
[58]: http://www.gnu.org/software/stow/
[59]: https://github.com/andsens/homeshick
[60]: https://github.com/lra/mackup
[61]: https://github.com/openbootdotdev/openboot
[62]: https://github.com/pearl-core/pearl
[63]: https://github.com/pearl-hub
[64]: https://github.com/volllly/rotz
[65]: https://github.com/themerdev/themer
[66]: https://github.com/oknozor/toml-bombadil
[67]: https://github.com/b3nj5m1n/xdg-ninja
[68]: https://github.com/TheLocehiliosan/yadm
[69]: https://github.com/kcrawford/dockutil
[70]: https://github.com/mas-cli/mas
[71]: https://github.com/zero-sh/zero.sh
[72]: https://dotfiles.github.io/
[73]: https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard
[74]: https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html
[75]: https://wiki.archlinux.org/title/XDG_Base_Directory
[76]: https://web.archive.org/web/20180827160401/https://plus.google.com/+RobPikeTheHuman/posts/R58WgWwN9jp
[77]: https://github.com/jondot/awesome-devenv
[78]: https://github.com/jorgebucaran/awsm.fish
[79]: https://github.com/alebcay/awesome-shell
[80]: https://github.com/awesome-foss/awesome-sysadmin
[81]: https://github.com/unixorn/awesome-zsh-plugins
[82]: https://github.com/k4m4/terminals-are-sexy
[83]: http://antigen.sharats.me
[84]: https://github.com/barryclark/bashstrap
[85]: https://github.com/spencergibb/battleschool
[86]: https://github.com/mattly/bork
[87]: https://github.com/msanders/cider
[88]: https://github.com/donnemartin/dev-setup
[89]: https://github.com/jbernard/dotfiles
[90]: https://github.com/clayrisser/dotstow
[91]: https://github.com/eduardolundgren/dotfiles
[92]: https://github.com/ellipsis/ellipsis
[93]: https://github.com/tversteeg/emplace
[94]: https://github.com/holman/dotfiles
[95]: https://github.com/technicalpickles/homesick
[96]: https://github.com/kdeldycke/dotfiles
[97]: https://github.com/jh3y/kody
[98]: https://github.com/kevinSuttle/macOS-Defaults
[99]: http://osxc.github.io
[100]: https://github.com/RichiH/vcsh
[101]: https://blog.tfnico.com/2014/03/managing-dot-files-with-vcsh-and-myrepos.html
[102]: https://www.kunxi.org/blog/2014/02/manage-dotfiles-using-vcsh-and-mr/
[103]: http://skwp.github.io/dotfiles/
[104]: https://creativecommons.org/publicdomain/zero/1.0/
[105]: https://licensebuttons.net/p/zero/1.0/88x31.png
[106]: https://www.webpro.nl
