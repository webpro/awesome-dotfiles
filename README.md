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

| Title                 | Description                                           | Focus                                                                            |
| :-------------------- | :---------------------------------------------------- | :------------------------------------------------------------------------------- |
| [oh-my-fish][43]      | The Fish Shell Framework                              | Core infrastructure to allow you to install packages to extend/modify your shell |
| [Paul's dotfiles][44] | paul's fish, bash, git, etc config files. good stuff. | Fish, macOS, Homebrew, Custom Shell functions                                    |

### Ansible

| Title                   | Description                                  | Focus                                                                           |
| :---------------------- | :------------------------------------------- | :------------------------------------------------------------------------------ |
| [.dots][45]             | New and upgraded dotfiles, now with Ansible! | Completely automated desktop setup, configuration and maintenance using Ansible |
| [sloria's dotfiles][46] | sloria's dotfiles as Ansible roles           | Sets up a full local development environment with a single command              |

## Tools

- [Ansible][47] - Radically simple configuration-management, application deployment, task-execution, and multinode
  orchestration engine.
- [chezmoi][48] - Manage your dotfiles securely across multiple machines.
- [comtrya][49] - Configuration management for localhost, written in Rust, for Linux, BSD, macOS, and Windows.
- [dotbot][50] - Tool that bootstraps your dotfiles.
- [dotdrop][51] - Save your dotfiles once, deploy them everywhere.
- [dots][52] - Opinionated dotfiles generator that allows quick configuration of different window managers in multiple
  OSs!
- [Fisher][53] - A package manager for Fish.
- [fresh][54] - Keep your dotfiles fresh. Fresh is a tool to source shell configuration (aliases, functions, etc) from
  others into your own configuration files.
- [GNU Stow][55] - Symlink farm manager which takes distinct packages of software and/or data located in separate
  directories on the filesystem, and makes them appear to be installed in the same place.
- [homeshick][56] - Git dotfile synchronizer written in Bash.
- [mackup][57] - Keep your application settings in sync (macOS/Linux).
- [OpenBoot][58] - Mac dev environment manager that captures and restores Homebrew packages, dotfiles, shell
  configuration, and macOS preferences via interactive TUI.
- [rcm][34] - rc file (dotfile) management.
- [rotz][59] - Fully cross-platform dotfile manager and dev environment bootstrapper written in Rust.
- [themer][60] - Manage and generate themes across your development tools from within your dotfiles.
- [toml-bombadil][61] - Templatize and manage your dotfiles.
- [xdg-ninja][62] - A shell script which checks your $HOME for unwanted files and directories.
- [yadm][63] - Tool for managing a collection of files across multiple computers, using a shared Git repository and some
  additional features.

### macOS

- [dockutil][64] - Command line tool for managing dock items.
- [mas][65] - Mac App Store command line interface.

## Miscellaneous

- [dotfiles.github.io][66] - Your unofficial guide to dotfiles on GitHub.
- [Filesystem Hierarchy Standard][67] - Directory structure and directory contents in Linux distributions.
- [XDG Base Directory Specification][68] - [Summary][69]
- [A lesson in shortcuts][70] - How the idea of "hidden" or "dot" files was born, by Rob Pike (originally posted on
  Google+).

## Related Lists

- [Awesome Dev Env][71] - Curated list of awesome tools, resources and workflow tips making an awesome development
  environment.
- [Awesome Fish][72] - Curated list of packages, prompts, and resources for the fish shell.
- [Awesome Shell][73] - Curated list of awesome command-line frameworks, toolkits, guides and gizmos.
- [Awesome Sysadmin][74] - A curated list of amazingly awesome open source sysadmin resources.
- [Awesome Zsh Plugins][75] - List of Zsh plugins suitable for use with oh-my-zsh, antigen & Prezto.
- [Terminals Are Sexy][76] - A curated list of Terminal frameworks, plugins & resources for CLI lovers.

## Archive/abandoned projects

- [antigen][77]
- [bashdot][78]
- [Bashstrap][79]
- [battleschool][80]
- [Bork][81]
- [Cider][82]
- [dev-setup][83]
- [dotbare][84]
- [dotfiles][85]
- [dotstow][86]
- [Eduardo's dotfiles][87]
- [ellipsis][88]
- [emplace][89]
- [holman does dotfiles][90]
- [homesick][91]
- [Kevin's dotfiles][92]
- [kody][93]
- [macOS Defaults][94]
- [osxc][95]
- [Pearl][96]
- [rkalis's dotfiles][97]
- [vcsh][98] ([article][99], [article][100])
- [YADR][101]
- [Zero.sh][102]

## License

[![CC0][104]][103]

To the extent possible under law, [Lars Kappert][105] has waived all copyright and related or neighboring rights to this
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
[45]: https://github.com/Addvilz/dots
[46]: https://github.com/sloria/dotfiles
[47]: https://www.ansible.com
[48]: https://github.com/twpayne/chezmoi
[49]: https://github.com/comtrya/comtrya
[50]: https://github.com/anishathalye/dotbot
[51]: https://github.com/deadc0de6/dotdrop
[52]: https://github.com/ulises-jeremias/dotfiles
[53]: https://github.com/jorgebucaran/fisher
[54]: https://freshshell.com
[55]: http://www.gnu.org/software/stow/
[56]: https://github.com/andsens/homeshick
[57]: https://github.com/lra/mackup
[58]: https://github.com/openbootdotdev/openboot
[59]: https://github.com/volllly/rotz
[60]: https://github.com/themerdev/themer
[61]: https://github.com/oknozor/toml-bombadil
[62]: https://github.com/b3nj5m1n/xdg-ninja
[63]: https://github.com/TheLocehiliosan/yadm
[64]: https://github.com/kcrawford/dockutil
[65]: https://github.com/mas-cli/mas
[66]: https://dotfiles.github.io/
[67]: https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard
[68]: https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html
[69]: https://wiki.archlinux.org/title/XDG_Base_Directory
[70]: https://web.archive.org/web/20180827160401/https://plus.google.com/+RobPikeTheHuman/posts/R58WgWwN9jp
[71]: https://github.com/jondot/awesome-devenv
[72]: https://github.com/jorgebucaran/awsm.fish
[73]: https://github.com/alebcay/awesome-shell
[74]: https://github.com/awesome-foss/awesome-sysadmin
[75]: https://github.com/unixorn/awesome-zsh-plugins
[76]: https://github.com/k4m4/terminals-are-sexy
[77]: http://antigen.sharats.me
[78]: https://github.com/bashdot/bashdot
[79]: https://github.com/barryclark/bashstrap
[80]: https://github.com/spencergibb/battleschool
[81]: https://github.com/mattly/bork
[82]: https://github.com/msanders/cider
[83]: https://github.com/donnemartin/dev-setup
[84]: https://github.com/kazhala/dotbare
[85]: https://github.com/jbernard/dotfiles
[86]: https://github.com/clayrisser/dotstow
[87]: https://github.com/eduardolundgren/dotfiles
[88]: https://github.com/ellipsis/ellipsis
[89]: https://github.com/tversteeg/emplace
[90]: https://github.com/holman/dotfiles
[91]: https://github.com/technicalpickles/homesick
[92]: https://github.com/kdeldycke/dotfiles
[93]: https://github.com/jh3y/kody
[94]: https://github.com/kevinSuttle/macOS-Defaults
[95]: http://osxc.github.io
[96]: https://github.com/pearl-core/pearl
[97]: https://github.com/rkalis/dotfiles
[98]: https://github.com/RichiH/vcsh
[99]: https://blog.tfnico.com/2014/03/managing-dot-files-with-vcsh-and-myrepos.html
[100]: https://www.kunxi.org/blog/2014/02/manage-dotfiles-using-vcsh-and-mr/
[101]: http://skwp.github.io/dotfiles/
[102]: https://github.com/zero-sh/zero.sh
[103]: https://creativecommons.org/publicdomain/zero/1.0/
[104]: https://licensebuttons.net/p/zero/1.0/88x31.png
[105]: https://www.webpro.nl
