# Awesome dotfiles

A curated list of dotfiles resources. Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.
Note that some articles or tools may look old or old-fashioned, but this usually means they're battle-tested and mature
(like dotfiles themselves). Feel free to propose new articles, projects or tools!

## Articles

### Introductions

- [Getting started with dotfiles](https://medium.com/@webprolific/getting-started-with-dotfiles-43c3602fd789)
  ([L. Kappert](https://github.com/webpro))
- [Getting started with dotfiles](https://driesvints.com/blog/getting-started-with-dotfiles/)
  ([D. Vints](https://github.com/driesvints))
- [Managing your dotfiles](https://medium.com/@webprolific/managing-your-dotfiles-7d2725297304)
- [Dotfiles Are Meant to Be Forked](https://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/)
- [Dotfile discovery](https://wynnnetherland.com/journal/dotfiles-discovery/)
- [I do Dotfiles!](https://jogendra.dev/i-do-dotfiles)

### Tutorials

- [Setting up a new (OS X) development machine: Part 3 - Dotfiles and custom SSH config](https://mattstauffer.com/blog/setting-up-a-new-os-x-development-machine-part-3-dotfiles-rc-files-and-ssh-config/)
- [Setting Up a Mac Dev Machine From Zero to Hero With Dotfiles](https://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449);
  [Part 2](https://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles-part-2--cms-23145)
- [Using Git and GitHub to manage your dotfiles](http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/)
- [conf.d like directories for zsh/bash dotfiles](https://chr4.org/blog/2014/09/10/conf-dot-d-like-directories-for-zsh-slash-bash-dotfiles/)
- [Managing your dotfiles](https://www.anishathalye.com/2014/08/03/managing-your-dotfiles/)
- [The best way to store your dotfiles: A bare Git repository](https://www.atlassian.com/git/tutorials/dotfiles)

### Shell startup

- [Shell startup scripts](https://blog.flowblok.id.au/2013-02/shell-startup-scripts.html)
- [Zsh/Bash startup files loading order](https://shreevatsa.wordpress.com/2008/03/30/zshbash-startup-files-loading-order-bashrc-zshrc-etc/)

### Using specific tools

- [Using GNU Stow to manage your dotfiles](http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html)
- [Managing Dotfile Symlinks with GNU Stow](https://spin.atomicobject.com/2014/12/26/manage-dotfiles-gnu-stow/)
- [Dotfiles and dev tools provisioned by Ansible](http://palcu.blogspot.com/2014/06/dotfiles-and-dev-tools-provisioned-by.html)
- [Manage a development machine with Ansible](http://kreusch.com.br/blog/2013/12/03/manage-a-development-machine-with-ansible)

## Find dotfiles repos

There are many great dotfiles repos out there, each containing their own inspiration and gems. One way to go through
them is to [search GitHub for "dotfiles"](https://github.com/search?q=dotfiles&type=Repositories).

Also see:

- [Google for "dotfiles"](https://www.google.nl/search?q=dotfiles)
- [Archlinux collection](https://wiki.archlinux.org/index.php/Dotfiles)
- Tip: search for a filename on GitHub, e.g.
  [in:path .gitconfig](https://github.com/search?utf8=%E2%9C%93&type=Code&q=in%3Apath+.gitconfig).

## Example dotfiles repos

A collection of the most popular, well-maintained, and collaborative dotfiles repositories & frameworks. Some projects
contain just the dotfiles. Others go further by allowing you to easily add your own custom dotfiles, and some include
scripts to manage dotfiles and plugins.

### Bash

| Title                                                               | Description                                  | Focus                                                                                                                        |
| :------------------------------------------------------------------ | :------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------- |
| [Bash it](https://github.com/Bash-it/bash-it)                       | Community bash framework.                    | Autocompletion, themes, aliases, custom functions. Well-structured framework.                                                |
| [Mathias’s dotfiles](https://github.com/mathiasbynens/dotfiles)     | Sensible hacker defaults for macOS           | Lots of goodness here, great collaborative community effort.                                                                 |
| [Maximum Awesome](https://github.com/square/maximum-awesome)        | Config files for vim and tmux                | Vim, tmux. Built for Mac OS X.                                                                                               |
| [webpro's dotfiles](https://github.com/webpro/dotfiles)             | macOS dotfiles                               | Bash, Homebrew, Brew Cask, Git, Node.js, Hammerspoon.                                                                        |
| [rootbeersoup's dotfiles](https://github.com/rootbeersoup/dotfiles) | Effortless Bash, Vim and macOS configuration | A `curl \| sh` installer and a Makefile offer portable and effortless setup for either permanent or temporary configuration. |
| [Luke's voidrice](https://github.com/LukeSmithxyz/voidrice)         | Arch linux dotfile bootstrap                 | Bloatless, often suckless software. Vim config for editing documents in markdown or latex                                    |

### Zsh

| Title                                                         | Description                                                            | Focus                                                                                                                                                              |
| :------------------------------------------------------------ | :--------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles) | Set of vim, zsh, git, and tmux configuration files                     | Zsh, vim, tmux, git, homebrew. Uses [rcm](https://github.com/thoughtbot/rcm).                                                                                      |
| [oh-my-zsh](https://ohmyz.sh)                                 | Community-driven framework for managing your zsh configuration.        | Includes 200+ optional plugins (rails, git, OSX, hub, capistrano, brew, ant, php, python, etc), over 140 themes to spice up your morning, and an auto-update tool. |
| [Prezto](https://github.com/sorin-ionescu/prezto)             | The configuration framework for Zsh.                                   | Enriches the command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes.                                        |
| [YADR](http://skwp.github.io/dotfiles/)                       | The best vim, git, zsh plugins and the cleanest vimrc you've ever seen | Homebrew, zsh, git, vim, and more. Active repository.                                                                                                              |
| [antigen](http://antigen.sharats.me)                          | Plugin manager for zsh, inspired by oh-my-zsh and vundle.              | Antigen is a small set of functions that help you easily manage your shell (zsh) plugins. Antigen is to zsh, what Vundle is to vim.                                |
| [Dries's dotfiles](https://github.com/driesvints/dotfiles)    | Simplified approach to dotfiles for macOS                              | Zsh, Oh My Zsh, macOS, Homebrew, Mackup                                                                                                                            |
| [sobolevn's dotfiles](https://github.com/sobolevn/dotfiles)   | Dotfiles for the developer happiness                                   | Zsh, Brew, Sublime, Python, Node, Elixir                                                                                                                           |

### Fish

| Title                                                    | Description                                                                    | Focus                                                                                    |
| :------------------------------------------------------- | :----------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------- |
| [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish)   | Community Fish framework.                                                      | Includes many plugins and themes, with installation, auto-update, and scaffolding tools. |
| [Paul's dotfiles](https://github.com/paulirish/dotfiles) | Abundant dotfiles with a plethora of cool custom functions                     | Fish, macOS, Homebrew, Custom Shell functions                                            |
| [rkalis's dotfiles](https://github.com/rkalis/dotfiles)  | Well-maintained dotfiles featuring Fish, repository management and Hammerspoon | Fish, macOS, Homebrew, Repository management, Hammerspoon                                |

### Ansible

| Title                                                   | Description                                  | Focus                                                                           |
| :------------------------------------------------------ | :------------------------------------------- | :------------------------------------------------------------------------------ |
| [.dots](https://github.com/Addvilz/dots)                | New and upgraded dotfiles, now with Ansible! | Completely automated desktop setup, configuration and maintenance using Ansible |
| [sloria's dotfiles](https://github.com/sloria/dotfiles) | sloria's dotfiles as Ansible roles           | Sets up a full local development environment with a single command              |

## Tools

- [Ansible](https://www.ansible.com) - Radically simple configuration-management, application deployment,
  task-execution, and multinode orchestration engine.
- [bashdot](https://github.com/bashdot/bashdot) - Minimalist dotfile management framework written entirely in bash.
- [chezmoi](https://github.com/twpayne/chezmoi) - Manage your dotfiles securely across multiple machines.
- [dotbare](https://github.com/kazhala/dotbare) - Manage dotfiles interactively with fzf.
- [dotbot](https://github.com/anishathalye/dotbot) - Tool that bootstraps your dotfiles.
- [dotdrop](https://github.com/deadc0de6/dotdrop) - Save your dotfiles once, deploy them everywhere.
- [dotstow](https://github.com/codejamninja/dotstow) - Manage dotfiles with stow.
- [emplace](https://github.com/tversteeg/emplace) - Synchronize installed packages on multiple machines using a dotfiles
  repository.
- [Fisher](https://github.com/jorgebucaran/fisher) - A package manager for Fish
- [fresh](https://freshshell.com) - Keep your dotfiles fresh. Fresh is a tool to source shell configuration (aliases,
  functions, etc) from others into your own configuration files.
- [GNU Stow](http://www.gnu.org/software/stow/) - Symlink farm manager which takes distinct packages of software and/or
  data located in separate directories on the filesystem, and makes them appear to be installed in the same place.
- [homeshick](https://github.com/andsens/homeshick) - Git dotfile synchronizer written in Bash.
- [homesick](https://github.com/technicalpickles/homesick) - Your home directory is your castle. Don't leave your
  dotfiles behind ([article](https://technicalpickles.com/posts/never-leave-your-dotfiles-behind-again-with-homesick)).
- [mackup](https://github.com/lra/mackup) - Keep your application settings in sync (OS X/Linux).
- [Pearl](https://github.com/pearl-core/pearl) - Package manager that allows to control, sync, share dotfiles as
  packages automatically activated during shells or editors startup. There is a wide range of packages already available
  in the [Official Pearl Hub](https://github.com/pearl-hub) (for Linux and OSX).
- [rcm](https://github.com/thoughtbot/rcm) - rc file (dotfile) management.
- [themer](https://github.com/mjswensen/themer) - Manage and generate themes across your development tools from within
  your dotfiles.
- [toml-bombadil](https://github.com/oknozor/toml-bombadil) - Templatize and manage your dotfiles.
- [yadm](https://github.com/TheLocehiliosan/yadm) - Tool for managing a collection of files across multiple computers,
  using a shared Git repository and some additional features.

### macOS

- [dockutil](https://github.com/kcrawford/dockutil) - Command line tool for managing dock items
- [mas](https://github.com/mas-cli/mas) - Mac App Store command line interface
- [zero](https://github.com/zero-sh/zero.sh) - Radically simple personal bootstrapping tool for macOS.

## Miscellaneous

- [dotfiles.github.io](http://dotfiles.github.io) - Your unofficial guide to dotfiles on GitHub.
- [OS X Defaults](https://github.com/kevinSuttle/macOS-Defaults) - Centralized place for the awesome work started by
  [@mathiasbynens on .macos](https://github.com/mathiasbynens/dotfiles#sensible-macos-defaults).
- [Filesystem Hierarchy Standard](https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard) - Directory structure and
  directory contents in Linux distributions.
- [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) -
  [Summary](https://wiki.archlinux.org/index.php/XDG_Base_Directory)
- [A lesson in shortcuts](https://www.reddit.com/r/linux/comments/at05xh/why_do_hidden_files_in_unix_begin_with_a_dot/egyj6lr/) -
  How the idea of "hidden" or "dot" files was born, by Rob Pike (originally posted on Google+)

## Related Lists

- [Awesome Dev Env](https://github.com/jondot/awesome-devenv) - Curated list of awesome tools, resources and workflow
  tips making an awesome development environment.
- [Awesome Fish](https://github.com/jorgebucaran/awesome-fish) - Curated list of packages, prompts, and resources for
  the fish shell.
- [Awesome Shell](https://github.com/alebcay/awesome-shell) - Curated list of awesome command-line frameworks, toolkits,
  guides and gizmos.
- [Awesome Sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of amazingly awesome open source
  sysadmin resources.
- [Awesome Zsh Plugins](https://github.com/unixorn/awesome-zsh-plugins) - List of Zsh plugins suitable for use with
  oh-my-zsh, antigen & Prezto.
- [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - A curated list of Terminal frameworks, plugins &
  resources for CLI lovers.

## Archive/abandoned projects

- [Bashstrap](https://github.com/barryclark/bashstrap)
- [battleschool](https://github.com/spencergibb/battleschool)
- [Bork](https://github.com/mattly/bork)
- [Cider](https://github.com/msanders/cider)
- [dev-setup](https://github.com/donnemartin/dev-setup)
- [dotfiles](https://github.com/jbernard/dotfiles)
- [Eduardo's dotfiles](https://github.com/eduardolundgren/dotfiles)
- [ellipsis](https://github.com/ellipsis/ellipsis)
- [holman does dotfiles](https://github.com/holman/dotfiles)
- [Kevin's dotfiles](https://github.com/kdeldycke/dotfiles)
- [kody](https://github.com/jh3y/kody)
- [osxc](http://osxc.github.io)
- [vcsh](https://github.com/RichiH/vcsh)
  ([article](https://blog.tfnico.com/2014/03/managing-dot-files-with-vcsh-and-myrepos.html),
  [article](https://www.kunxi.org/2014/02/manage-dotfiles-using-vcsh-and-mr/))

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Lars Kappert](https://www.webpro.nl) has waived all copyright and related or
neighboring rights to this work.
