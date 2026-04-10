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

- [Gitstar](https://dev.gitstar.ai?utm_medium=github_readme&utm_source=awesome_list&utm_campaign=webpro_awesome-dotfiles) - Follow designers and frontend devs on GitHub, see what UI repos and tools they are into.
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
| [sobolevn's dotfiles][41]  | Dotfiles for the developer happiness                                                                                | macOS, zsh, brew, vscode, codespaces, python, node, elixir                                                                                       |
| [yutkat's dotfiles][42]    | Well-maintained dotfiles that use CI to test and measure startup speeds.                                            | Zsh, Neovim, Wezterm, swaywm working on Arch/Ubuntu/Fedora Linux.                                                                                |
| [Luke's voidrice][43]      | My dotfiles (deployed by LARBS)                                                                                     | Zsh, vim/nvim, zsf                                                                                                                               |
| [2KAbhishek's dots2k][44]  | Passionately crafted, extensible dotfiles with multi platform support                                               | CLI tools at core, with extensions for different platforms (windows/mac/android), editors and window managers                                    |
| [Zim][45]                  | Modular, customizable, and blazing fast Zsh framework                                                               | Zim is a Zsh configuration framework that bundles a plugin manager, useful modules, and a wide variety of themes, without compromising on speed. |

### Fish

| Title                 | Description                                           | Focus                                                                            |
| :-------------------- | :---------------------------------------------------- | :------------------------------------------------------------------------------- |
| [oh-my-fish][46]      | The Fish Shell Framework                              | Core infrastructure to allow you to install packages to extend/modify your shell |
| [Paul's dotfiles][47] | paul's fish, bash, git, etc config files. good stuff. | Fish, macOS, Homebrew, Custom Shell functions                                    |

### Ansible

| Title                   | Description                                  | Focus                                                                           |
| :---------------------- | :------------------------------------------- | :------------------------------------------------------------------------------ |
| [.dots][48]             | New and upgraded dotfiles, now with Ansible! | Completely automated desktop setup, configuration and maintenance using Ansible |
| [Mac Dev Playbook][49]  | Mac setup and configuration via Ansible      | Full macOS dev machine setup including Homebrew, dotfiles, apps, and OS config  |
| [sloria's dotfiles][50] | sloria's dotfiles as Ansible roles           | Sets up a full local development environment with a single command              |

## Tools

- [Ansible][51] - Radically simple configuration-management, application deployment, task-execution, and multinode
  orchestration engine.
- [chezmoi][52] - Manage your dotfiles securely across multiple machines.
- [comtrya][53] - Configuration management for localhost, written in Rust, for Linux, BSD, macOS, and Windows.
- [dotbot][54] - Tool that bootstraps your dotfiles.
- [dotdrop][55] - Save your dotfiles once, deploy them everywhere.
- [dotter][56] - A dotfile manager and templater written in Rust.
- [dots][57] - Opinionated dotfiles generator that allows quick configuration of different window managers in multiple
  OSs!
- [Fisher][58] - A package manager for Fish.
- [fresh][59] - Keep your dotfiles fresh. Fresh is a tool to source shell configuration (aliases, functions, etc) from
  others into your own configuration files.
- [GNU Stow][60] - Symlink farm manager which takes distinct packages of software and/or data located in separate
  directories on the filesystem, and makes them appear to be installed in the same place.
- [home-manager][61] - Manage a user environment using Nix.
- [homeshick][62] - Git dotfile synchronizer written in Bash.
- [lnk][63] - Git-native dotfiles management without extra config.
- [mackup][64] - Keep your application settings in sync (macOS/Linux).
- [OpenBoot][65] - Mac dev environment manager that captures and restores Homebrew packages, dotfiles, shell
  configuration, and macOS preferences via interactive TUI.
- [rcm][37] - rc file (dotfile) management.
- [rotz][66] - Fully cross-platform dotfile manager and dev environment bootstrapper written in Rust.
- [themer][67] - Manage and generate themes across your development tools from within your dotfiles.
- [toml-bombadil][68] - Templatize and manage your dotfiles.
- [xdg-ninja][69] - A shell script which checks your $HOME for unwanted files and directories.
- [yadm][70] - Tool for managing a collection of files across multiple computers, using a shared Git repository and some
  additional features.
- [yolk][71] - Dotfile manager with inline templating via comments, so files stay valid even un-deployed.

### macOS

- [dockutil][72] - Command line tool for managing dock items.
- [mas][73] - Mac App Store command line interface.

## Miscellaneous

- [dotfiles.github.io][74] - Your unofficial guide to dotfiles on GitHub.
- [Filesystem Hierarchy Standard][75] - Directory structure and directory contents in Linux distributions.
- [XDG Base Directory Specification][76] - [Summary][77]
- [A lesson in shortcuts][78] - How the idea of "hidden" or "dot" files was born, by Rob Pike (originally posted on
  Google+).

## Related Lists

- [Awesome Dev Env][79] - Curated list of awesome tools, resources and workflow tips making an awesome development
  environment.
- [Awesome Fish][80] - Curated list of packages, prompts, and resources for the fish shell.
- [Awesome Shell][81] - Curated list of awesome command-line frameworks, toolkits, guides and gizmos.
- [Awesome Sysadmin][82] - A curated list of amazingly awesome open source sysadmin resources.
- [Awesome Zsh Plugins][83] - List of Zsh plugins suitable for use with oh-my-zsh, antigen & Prezto.
- [Terminals Are Sexy][84] - A curated list of Terminal frameworks, plugins & resources for CLI lovers.

## Archive/abandoned projects

- [antigen][85]
- [bashdot][86]
- [Bashstrap][87]
- [battleschool][88]
- [Bork][89]
- [Cider][90]
- [dev-setup][91]
- [dotbare][92]
- [dotfiles][93]
- [dotstow][94]
- [Eduardo's dotfiles][95]
- [ellipsis][96]
- [emplace][97]
- [holman does dotfiles][98]
- [homesick][99]
- [Kevin's dotfiles][100]
- [kody][101]
- [macOS Defaults][102]
- [osxc][103]
- [Pearl][104]
- [rkalis's dotfiles][105]
- [vcsh][106] ([article][107], [article][108])
- [YADR][109]
- [Zero.sh][110]

## License

[![CC0][112]][111]

To the extent possible under law, [Lars Kappert][113] has waived all copyright and related or neighboring rights to this
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
[17]: http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/
[18]: https://chr4.org/blog/2014/09/10/conf-dot-d-like-directories-for-zsh-slash-bash-dotfiles/
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
[41]: https://github.com/sobolevn/dotfiles
[42]: https://github.com/yutkat/dotfiles
[43]: https://github.com/LukeSmithxyz/voidrice
[44]: https://github.com/2KAbhishek/dots2k
[45]: https://github.com/zimfw/zimfw
[46]: https://github.com/oh-my-fish/oh-my-fish
[47]: https://github.com/paulirish/dotfiles
[48]: https://github.com/Addvilz/dots
[49]: https://github.com/geerlingguy/mac-dev-playbook
[50]: https://github.com/sloria/dotfiles
[51]: https://www.ansible.com
[52]: https://github.com/twpayne/chezmoi
[53]: https://github.com/comtrya/comtrya
[54]: https://github.com/anishathalye/dotbot
[55]: https://github.com/deadc0de6/dotdrop
[56]: https://github.com/SuperCuber/dotter
[57]: https://github.com/ulises-jeremias/dotfiles
[58]: https://github.com/jorgebucaran/fisher
[59]: https://freshshell.com
[60]: http://www.gnu.org/software/stow/
[61]: https://github.com/nix-community/home-manager
[62]: https://github.com/andsens/homeshick
[63]: https://github.com/yarlson/lnk
[64]: https://github.com/lra/mackup
[65]: https://github.com/openbootdotdev/openboot
[66]: https://github.com/volllly/rotz
[67]: https://github.com/themerdev/themer
[68]: https://github.com/oknozor/toml-bombadil
[69]: https://github.com/b3nj5m1n/xdg-ninja
[70]: https://github.com/TheLocehiliosan/yadm
[71]: https://github.com/elkowar/yolk
[72]: https://github.com/kcrawford/dockutil
[73]: https://github.com/mas-cli/mas
[74]: https://dotfiles.github.io/
[75]: https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard
[76]: https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html
[77]: https://wiki.archlinux.org/title/XDG_Base_Directory
[78]: https://web.archive.org/web/20180827160401/https://plus.google.com/+RobPikeTheHuman/posts/R58WgWwN9jp
[79]: https://github.com/jondot/awesome-devenv
[80]: https://github.com/jorgebucaran/awsm.fish
[81]: https://github.com/alebcay/awesome-shell
[82]: https://github.com/awesome-foss/awesome-sysadmin
[83]: https://github.com/unixorn/awesome-zsh-plugins
[84]: https://github.com/k4m4/terminals-are-sexy
[85]: http://antigen.sharats.me
[86]: https://github.com/bashdot/bashdot
[87]: https://github.com/barryclark/bashstrap
[88]: https://github.com/spencergibb/battleschool
[89]: https://github.com/mattly/bork
[90]: https://github.com/msanders/cider
[91]: https://github.com/donnemartin/dev-setup
[92]: https://github.com/kazhala/dotbare
[93]: https://github.com/jbernard/dotfiles
[94]: https://github.com/clayrisser/dotstow
[95]: https://github.com/eduardolundgren/dotfiles
[96]: https://github.com/ellipsis/ellipsis
[97]: https://github.com/tversteeg/emplace
[98]: https://github.com/holman/dotfiles
[99]: https://github.com/technicalpickles/homesick
[100]: https://github.com/kdeldycke/dotfiles
[101]: https://github.com/jh3y/kody
[102]: https://github.com/kevinSuttle/macOS-Defaults
[103]: http://osxc.github.io
[104]: https://github.com/pearl-core/pearl
[105]: https://github.com/rkalis/dotfiles
[106]: https://github.com/RichiH/vcsh
[107]: https://blog.tfnico.com/2014/03/managing-dot-files-with-vcsh-and-myrepos.html
[108]: https://www.kunxi.org/blog/2014/02/manage-dotfiles-using-vcsh-and-mr/
[109]: http://skwp.github.io/dotfiles/
[110]: https://github.com/zero-sh/zero.sh
[111]: https://creativecommons.org/publicdomain/zero/1.0/
[112]: https://licensebuttons.net/p/zero/1.0/88x31.png
[113]: https://www.webpro.nl
