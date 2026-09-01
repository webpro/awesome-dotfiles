# Awesome Dotfiles [![Awesome][2]][1]

A curated list of dotfiles resources. Inspired by the [awesome][3] list thing. Note that some articles or tools may look
old or old-fashioned, but this usually means they're battle-tested and mature (like dotfiles themselves). Feel free to
propose new articles, projects or tools!

## Articles

### Introductions

- [Getting started with dotfiles][4], [Lars Kappert][5]
- [Getting started with dotfiles][6], [Dries Vints][7]
- [Managing your dotfiles][8], [Lars Kappert][5]
- [Dotfiles Are Meant to Be Forked][9], [Zach Holman][10]
- [Dotfile discovery][11], [Wynn Netherland][12]
- [I do Dotfiles!][13], [Jogendra][14]

### Tutorials

- [Setting up a new (OS X) development machine: Part 3 - Dotfiles and custom SSH config][15]
- [Setting Up a Mac Dev Machine From Zero to Hero With Dotfiles][16]
- [Using Git and GitHub to manage your dotfiles][17]
- [conf.d like directories for zsh/bash dotfiles][18]
- [Managing your dotfiles][19]
- [The best way to store your dotfiles: A bare Git repository][20]
- [Dotfiles Management][21]

### Shell startup

- [Shell startup scripts][22]
- [Zsh/Bash startup files loading order][23]

### Using specific tools

- [Using GNU Stow to manage your dotfiles][24]
- [Managing Dotfile Symlinks with GNU Stow][25]
- [Dotfiles and dev tools provisioned by Ansible][26]

## Find dotfiles repos

There are many great dotfiles repos out there, each containing their own inspiration and gems. One way to go through
them is to [search GitHub for "dotfiles"][27].

Also see:

- [Google for "dotfiles"][28]
- [Archlinux collection][29]
- Tip: search for a filename on GitHub, e.g. [path:\*\*/.gitconfig][30].

## Example dotfiles repos

A collection of the most popular, well-maintained, and collaborative dotfiles repositories & frameworks. Some projects
contain just the dotfiles. Others go further by allowing you to easily add your own custom dotfiles, and some include
scripts to manage dotfiles and plugins.

### Bash

| Title                         | Description                                  | Focus                                                                                                                        |
| :---------------------------- | :------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------- |
| [Bash it][31]                 | Community bash framework.                    | Autocompletion, themes, aliases, custom functions. Well-structured framework                                                 |
| [Mathias’s dotfiles][32]      | Sensible hacker defaults for macOS           | 🔧 .files, including \~/.macos — sensible hacker defaults for macOS                                                          |
| [webpro's dotfiles][33]       | macOS dotfiles                               | Bash, Homebrew, Brew Cask, Git, Node.js, Hammerspoon.                                                                        |
| [rootbeersoup's dotfiles][34] | Effortless Bash, Vim and macOS configuration | A `curl \| sh` installer and a Makefile offer portable and effortless setup for either permanent or temporary configuration. |

### Zsh

| Title                      | Description                                                                                                         | Focus                                                                                                                                            |
| :------------------------- | :------------------------------------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| [Nick Khan's dotfiles][35] | Personal dotfiles for configuring macOS environment with Zsh and Homebrew. No fluff, only the stuff I actually use. | Zsh, Git (w/ aliases), Visual Studio Code, Ghostty, shell aliases, sensible macOS defaults, custom CLI script, etc.                              |
| [thoughtbot dotfiles][36]  | Set of vim, zsh, git, and tmux configuration files                                                                  | Zsh, vim, tmux, git, homebrew. Uses [rcm][37].                                                                                                   |
| [oh-my-zsh][38]            | Community-driven framework for managing your zsh configuration.                                                     | Oh My Zsh is an open source, community-driven framework for managing your Zsh configuration                                                      |
| [Prezto][39]               | The configuration framework for Zsh.                                                                                | Enriches the command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes.                      |
| [Dries's dotfiles][40]     | Simplified approach to dotfiles for macOS                                                                           | Zsh, Oh My Zsh, macOS, Homebrew, Mackup                                                                                                          |
| [holman does dotfiles][41] | Topic-oriented, fork-friendly dotfiles                                                                              | Zsh, Git, Vim, Homebrew, macOS, modular topic directories and bootstrap scripts.                                                                 |
| [Kevin's dotfiles][42]     | macOS dotfiles for Python developers                                                                                | Zsh, Python, Neovim, VS Code, Homebrew, macOS defaults and security settings.                                                                    |
| [sobolevn's dotfiles][43]  | Dotfiles for the developer happiness                                                                                | macOS, zsh, brew, vscode, codespaces, python, node, elixir                                                                                       |
| [yutkat's dotfiles][44]    | Well-maintained dotfiles that use CI to test and measure startup speeds.                                            | Zsh, Neovim, Wezterm, swaywm working on Arch/Ubuntu/Fedora Linux.                                                                                |
| [Luke's voidrice][45]      | My dotfiles (deployed by LARBS)                                                                                     | Zsh, vim/nvim, zsf                                                                                                                               |
| [2KAbhishek's dots2k][46]  | Passionately crafted, extensible dotfiles with multi platform support                                               | CLI tools at core, with extensions for different platforms (windows/mac/android), editors and window managers                                    |
| [Zim][47]                  | Modular, customizable, and blazing fast Zsh framework                                                               | Zim is a Zsh configuration framework that bundles a plugin manager, useful modules, and a wide variety of themes, without compromising on speed. |

### Fish

| Title                 | Description                                           | Focus                                                                            |
| :-------------------- | :---------------------------------------------------- | :------------------------------------------------------------------------------- |
| [oh-my-fish][48]      | The Fish Shell Framework                              | Core infrastructure to allow you to install packages to extend/modify your shell |
| [Paul's dotfiles][49] | paul's fish, bash, git, etc config files. good stuff. | Fish, macOS, Homebrew, Custom Shell functions                                    |


### Cross-platform

| Title | Description | Focus |
| :--------------------------- | :------------------------------------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| [marcop135/dotfiles-core][116] | Cross-platform dotfiles for macOS, Windows, Git Bash, and WSL | One POSIX `sh` layer, four shells, manifest-driven symlinks, dry-run installers, bash 3.2 check gate, no extra runtime |

### Ansible

| Title                   | Description                                  | Focus                                                                           |
| :---------------------- | :------------------------------------------- | :------------------------------------------------------------------------------ |
| [.dots][50]             | New and upgraded dotfiles, now with Ansible! | Completely automated desktop setup, configuration and maintenance using Ansible |
| [Mac Dev Playbook][51]  | Mac setup and configuration via Ansible      | Full macOS dev machine setup including Homebrew, dotfiles, apps, and OS config  |
| [sloria's dotfiles][52] | sloria's dotfiles as Ansible roles           | Sets up a full local development environment with a single command              |

## Tools

- [Ansible][53] - Radically simple configuration-management, application deployment, task-execution, and multinode
  orchestration engine.
- [chezmoi][54] - Manage your dotfiles securely across multiple machines.
- [dotbot][55] - Tool that bootstraps your dotfiles.
- [dotdrop][56] - Save your dotfiles once, deploy them everywhere.
- [dotly][57] - Modular Zsh-based dotfiles framework for macOS, Linux, and WSL.
- [DotState][58] - Git-backed dotfile manager with profiles, automatic backups, and an interactive terminal interface.
- [dotter][59] - A dotfile manager and templater written in Rust.
- [dots][60] - Opinionated dotfiles generator that allows quick configuration of different window managers in multiple
  OSs!
- [Fisher][61] - A package manager for Fish.
- [fresh][62] - Keep your dotfiles fresh. Fresh is a tool to source shell configuration (aliases, functions, etc) from
  others into your own configuration files.
- [GNU Stow][63] - Symlink farm manager which takes distinct packages of software and/or data located in separate
  directories on the filesystem, and makes them appear to be installed in the same place.
- [home-manager][64] - Manage a user environment using Nix.
- [homeshick][65] - Git dotfile synchronizer written in Bash.
- [homesick][66] - Clone and manage Git-based dotfiles repositories with symlinks.
- [lnk][67] - Git-native dotfiles management without extra config.
- [mackup][68] - Keep your application settings in sync (macOS/Linux).
- [OpenBoot][69] - Mac dev environment manager that captures and restores Homebrew packages, dotfiles, shell
  configuration, and macOS preferences via interactive TUI.
- [rcm][37] - rc file (dotfile) management.
- [rotz][70] - Fully cross-platform dotfile manager and dev environment bootstrapper written in Rust.
- [themer][71] - Manage and generate themes across your development tools from within your dotfiles.
- [toml-bombadil][72] - Templatize and manage your dotfiles.
- [Tuckr][73] - Cross-platform, Stow-style dotfile manager with groups, hooks, and deployment validation.
- [xdg-ninja][74] - A shell script which checks your $HOME for unwanted files and directories.
- [yadm][75] - Tool for managing a collection of files across multiple computers, using a shared Git repository and some
  additional features.
- [yolk][76] - Dotfile manager with inline templating via comments, so files stay valid even un-deployed.

### macOS

- [dockutil][77] - Command line tool for managing dock items.
- [mas][78] - Mac App Store command line interface.

## Miscellaneous

- [dotfiles.github.io][79] - Your unofficial guide to dotfiles on GitHub.
- [Filesystem Hierarchy Standard][80] - Directory structure and directory contents in Linux distributions.
- [XDG Base Directory Specification][81] - [Summary][82]
- [A lesson in shortcuts][83] - How the idea of "hidden" or "dot" files was born, by Rob Pike (originally posted on
  Google+).

## Related Lists

- [Awesome Dev Env][84] - Curated list of awesome tools, resources and workflow tips making an awesome development
  environment.
- [Awesome Fish][85] - Curated list of packages, prompts, and resources for the fish shell.
- [Awesome Shell][86] - Curated list of awesome command-line frameworks, toolkits, guides and gizmos.
- [Awesome Sysadmin][87] - A curated list of amazingly awesome open source sysadmin resources.
- [Awesome Zsh Plugins][88] - List of Zsh plugins suitable for use with oh-my-zsh, antigen & Prezto.
- [Terminals Are Sexy][89] - A curated list of Terminal frameworks, plugins & resources for CLI lovers.

## Archive/abandoned projects

- [antigen][90]
- [bashdot][91]
- [Bashstrap][92]
- [battleschool][93]
- [Bork][94]
- [Cider][95]
- [dev-setup][96]
- [dotbare][97]
- [dotfiles][98]
- [dotstow][99]
- [Eduardo's dotfiles][100]
- [ellipsis][101]
- [emplace][102]
- [kody][103]
- [macOS Defaults][104]
- [osxc][105]
- [Pearl][106]
- [rkalis's dotfiles][107]
- [vcsh][108] ([article][109], [article][110])
- [YADR][111]
- [Zero.sh][112]

## License

[![CC0][114]][113]

To the extent possible under law, [Lars Kappert][115] has waived all copyright and related or neighboring rights to this
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
[10]: https://zachholman.com
[11]: https://wynnnetherland.com/journal/dotfiles-discovery/
[12]: https://wynnnetherland.com
[13]: https://jogendra.dev/i-do-dotfiles
[14]: https://jogendra.dev
[15]: https://mattstauffer.com/blog/setting-up-a-new-os-x-development-machine-part-3-dotfiles-rc-files-and-ssh-config/
[16]: https://code.tutsplus.com/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449t
[17]: https://blog.smalleycreative.com/using-git-and-github-to-manage-your-dotfiles/
[18]: https://chr4.org/posts/2014-09-10-conf-dot-d-like-directories-for-zsh-slash-bash-dotfiles/
[19]: https://www.anishathalye.com/2014/08/03/managing-your-dotfiles/
[20]: https://www.atlassian.com/git/tutorials/dotfiles
[21]: https://mitxela.com/projects/dotfiles_management
[22]: https://blog.flowblok.id.au/2013-02/shell-startup-scripts.html
[23]: https://shreevatsa.wordpress.com/2008/03/30/zshbash-startup-files-loading-order-bashrc-zshrc-etc/
[24]: http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html
[25]: https://spin.atomicobject.com/manage-dotfiles-gnu-stow/
[26]: http://palcu.blogspot.com/2014/06/dotfiles-and-dev-tools-provisioned-by.html
[27]: https://github.com/search?q=dotfiles&type=Repositories
[28]: https://www.google.nl/search?q=dotfiles
[29]: https://wiki.archlinux.org/index.php/Dotfiles
[30]: https://github.com/search?type=code&q=path%3A**%2F.gitconfig
[31]: https://github.com/Bash-it/bash-it
[32]: https://github.com/mathiasbynens/dotfiles
[33]: https://github.com/webpro/dotfiles
[34]: https://github.com/darrylabbate/dotfiles
[35]: https://github.com/nicksp/dotfiles/
[36]: https://github.com/thoughtbot/dotfiles
[37]: https://github.com/thoughtbot/rcm
[38]: https://ohmyz.sh
[39]: https://github.com/sorin-ionescu/prezto
[40]: https://github.com/driesvints/dotfiles
[41]: https://github.com/holman/dotfiles
[42]: https://github.com/kdeldycke/dotfiles
[43]: https://github.com/sobolevn/dotfiles
[44]: https://github.com/yutkat/dotfiles
[45]: https://github.com/LukeSmithxyz/voidrice
[46]: https://github.com/2KAbhishek/dots2k
[47]: https://github.com/zimfw/zimfw
[48]: https://github.com/oh-my-fish/oh-my-fish
[49]: https://github.com/paulirish/dotfiles
[50]: https://github.com/Addvilz/dots
[51]: https://github.com/geerlingguy/mac-dev-playbook
[52]: https://github.com/sloria/dotfiles
[53]: https://www.ansible.com
[54]: https://github.com/twpayne/chezmoi
[55]: https://github.com/anishathalye/dotbot
[56]: https://github.com/deadc0de6/dotdrop
[57]: https://github.com/CodelyTV/dotly
[58]: https://github.com/serkanyersen/dotstate
[59]: https://github.com/SuperCuber/dotter
[60]: https://github.com/ulises-jeremias/dotfiles
[61]: https://github.com/jorgebucaran/fisher
[62]: https://freshshell.com
[63]: http://www.gnu.org/software/stow/
[64]: https://github.com/nix-community/home-manager
[65]: https://github.com/andsens/homeshick
[66]: https://github.com/technicalpickles/homesick
[67]: https://github.com/yarlson/lnk
[68]: https://github.com/lra/mackup
[69]: https://github.com/openbootdotdev/openboot
[70]: https://github.com/volllly/rotz
[71]: https://github.com/mjswensen/themer
[72]: https://github.com/oknozor/toml-bombadil
[73]: https://github.com/RaphGL/Tuckr
[74]: https://github.com/b3nj5m1n/xdg-ninja
[75]: https://github.com/yadm-dev/yadm
[76]: https://github.com/elkowar/yolk
[77]: https://github.com/kcrawford/dockutil
[78]: https://github.com/mas-cli/mas
[79]: https://dotfiles.github.io/
[80]: https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard
[81]: https://specifications.freedesktop.org/basedir/basedir-spec-latest.html
[82]: https://wiki.archlinux.org/title/XDG_Base_Directory
[83]: https://web.archive.org/web/20180827160401/https://plus.google.com/+RobPikeTheHuman/posts/R58WgWwN9jp
[84]: https://github.com/jondot/awesome-devenv
[85]: https://github.com/jorgebucaran/awsm.fish
[86]: https://github.com/alebcay/awesome-shell
[87]: https://github.com/awesome-foss/awesome-sysadmin
[88]: https://github.com/unixorn/awesome-zsh-plugins
[89]: https://github.com/k4m4/terminals-are-sexy
[90]: http://antigen.sharats.me
[91]: https://github.com/bashdot/bashdot
[92]: https://github.com/barryclark/bashstrap
[93]: https://github.com/spencergibb/battleschool
[94]: https://github.com/mattly/bork
[95]: https://github.com/msanders/cider
[96]: https://github.com/donnemartin/dev-setup
[97]: https://github.com/kazhala/dotbare
[98]: https://github.com/jbernard/dotfiles
[99]: https://github.com/clayrisser/dotstow
[100]: https://github.com/eduardolundgren/dotfiles
[101]: https://github.com/ellipsis/ellipsis
[102]: https://web.archive.org/web/20260430004416/https://github.com/tversteeg/emplace
[103]: https://github.com/jh3y/kody
[104]: https://github.com/kevinSuttle/macOS-Defaults
[105]: http://osxc.github.io
[106]: https://github.com/pearl-core/pearl
[107]: https://github.com/rkalis/dotfiles
[108]: https://github.com/RichiH/vcsh
[109]: https://blog.tfnico.com/2014/03/managing-dot-files-with-vcsh-and-myrepos.html
[110]: https://www.kunxi.org/blog/2014/02/manage-dotfiles-using-vcsh-and-mr/
[111]: https://github.com/skwp/dotfiles
[112]: https://github.com/zero-sh/zero.sh
[113]: https://creativecommons.org/publicdomain/zero/1.0/
[114]: https://licensebuttons.net/p/zero/1.0/88x31.png
[115]: https://www.webpro.nl
[116]: https://github.com/marcop135/dotfiles-core
