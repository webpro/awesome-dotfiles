# Awesome dotfiles

A curated list of dotfiles resources. Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.

## Articles

### Introduction

* [Getting started with dotfiles](https://medium.com/@webprolific/getting-started-with-dotfiles-43c3602fd789)
* [Managing your dotfiles](https://medium.com/@webprolific/managing-your-dotfiles-7d2725297304)
* [Dotfiles Are Meant to Be Forked](https://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/)
* [Dotfile discovery](http://wynnnetherland.com/journal/dotfiles-discovery/)

### Tutorials

* [Setting up a new (OS X) development machine: Part 3 - Dotfiles and custom SSH config](https://mattstauffer.co/blog/setting-up-a-new-os-x-development-machine-part-3-dotfiles-rc-files-and-ssh-config)
* [Setting Up a Mac Dev Machine From Zero to Hero With Dotfiles](http://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449) - [Part 2](http://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles-part-2--cms-23145)
* [Using Git and GitHub to manage your dotfiles](http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/)
* [conf.d like directories for zsh/bash dotfiles](http://chr4.org/blog/2014/09/10/conf-dot-d-like-directories-for-zsh-slash-bash-dotfiles/)

### Shell startup

* [Shell startup scripts](http://blog.flowblok.id.au/2013-02/shell-startup-scripts.html)
* [Zsh/Bash startup files loading order](https://shreevatsa.wordpress.com/2008/03/30/zshbash-startup-files-loading-order-bashrc-zshrc-etc/)

### Using GNU Stow

* [Using GNU Stow to manage your dotfiles](http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html)
* [Managing dotfiles with GNU Stow](https://taihen.org/managing-dotfiles-with-gnu-stow/)
* [Managing Dotfile Symlinks with GNU Stow](https://spin.atomicobject.com/2014/12/26/manage-dotfiles-gnu-stow/)

### Using vcsh & mr

* [Manage dotfiles Quickly and Effortlessly](http://www.martin-burger.net/blog/unix-shell/manage-dotfiles-quickly-and-effortlessly/)
* [Managing dot-files with vcsh and myrepos](http://blog.tfnico.com/2014/03/managing-dot-files-with-vcsh-and-myrepos.html)
* [Manage dotfiles using vcsh and mr](https://www.kunxi.org/blog/2014/02/manage-dotfiles-using-vcsh-and-mr/)

### Using Ansible

* [Dotfiles and dev tools provisioned by Ansible](http://palcu.blogspot.nl/2014/06/dotfiles-and-dev-tools-provisioned-by.html)
* [Manage a development machine with Ansible](http://kreusch.com.br/blog/2013/12/03/manage-a-development-machine-with-ansible/)

## Dotfiles repos

A collection of the most popular, well-maintained, and collaborative dotfiles repositories & frameworks. Some projects contain just the dotfiles. Others go further by allowing you to easily add your own custom dotfiles, and/or including scripts to manage dotfiles/plugins.

### Bash

Title | Description | Focus
:--|:--|:--
[Bashstrap](https://github.com/barryclark/bashstrap) | Bootstrap for your terminal. A quick way to spruce up OSX terminal. | OS X Terminal, prompt, iTerm.
[Bash it](https://github.com/Bash-it/bash-it) | Community bash framework. | Autocompletion, themes, aliases, custom functions. Well-structured framework.
[Mathias’s dotfiles](https://github.com/mathiasbynens/dotfiles) | .files, including ~/.osx — sensible hacker defaults for OS X | Lots of goodness here, great collaborative community effort.
[Maximum Awesome](https://github.com/square/maximum-awesome) | Config files for vim and tmux, by Square vimsters. | Vim, tmux. Built for Mac OS X.
[dev-setup](https://github.com/donnemartin/dev-setup) | Easy-to-understand instructions with automated setup scripts for developer tools and dev-based defaults for Mac OSX. | Developer tools on OS X.
[Kevin's dotfiles](https://github.com/kdeldycke/dotfiles) | An attempt to support both OSX and Kubuntu with the same set of dotfiles. | Python developers working in `vim`.

### Zsh

Title | Description | Focus
:--|:--|:--
[thoughtbot dotfiles](https://github.com/thoughtbot/dotfiles) | Set of vim, zsh, git, and tmux configuration files | Zsh, vim, tmux, git, homebrew. Uses [rcm](https://github.com/thoughtbot/rcm).
[oh-my-zsh](http://ohmyz.sh/) | Community-driven framework for managing your zsh configuration. | Includes 120+ optional plugins (rails, git, OSX, hub, capistrano, brew, ant, macports, etc), over 120 themes to spice up your morning, and an auto-update tool.
[Prezto](https://github.com/sorin-ionescu/prezto) | Prezto is the configuration framework for Zsh. | Enriches the command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes.
[YADR](http://skwp.github.io/dotfiles/) | The best vim, git, zsh plugins and the cleanest vimrc you've ever seen | Homebrew, zsh, git, vim, and more. Active repository.
[holman does dotfiles](https://github.com/holman/dotfiles) | holman does dotfiles | Organized well around topics. Author wants it to work for everyone.
[antigen](http://antigen.sharats.me/) | Plugin manager for zsh, inspired by oh-my-zsh and vundle. | Antigen is a small set of functions that help you easily manage your shell (zsh) plugins, called bundles.
[Eduardo's dotfiles](https://github.com/eduardolundgren/dotfiles) | The first JavaScript-based dotfiles powered by Grunt. | Zsh, Node.js, Ruby, OS X defaults. Installable from npm.

There are many more great dotfiles repos out there, each containing their own inspiration and gems.

* [Search GitHub for "dotfiles"](https://github.com/search?q=dotfiles&type=Repositories)
* [Google for "dotfiles"](https://www.google.com/#q=dotfiles)
* [Archlinux collection](https://wiki.archlinux.org/index.php/Dotfiles)

Tip: search for a filename on GitHub, e.g. [site:github.com .gitconfig](https://www.google.com/#q=site:github.com+.gitconfig).

## Tools

* [Ansible](https://www.ansible.com/) - Radically simple configuration-management, application deployment, task-execution, and multinode orchestration engine.
* [battleschool](https://github.com/spencergibb/battleschool) - Development environment provisioning using Ansible.
* [Bork](https://github.com/mattly/bork) - Bash DSL for config management.
* [dotbot](https://github.com/anishathalye/dotbot) - Tool that bootstraps your dotfiles.
* [dotfiles](https://pypi.python.org/pypi/dotfiles) - Tool to make managing your dotfile symlinks in $HOME easy.
* [Ellipsis](https://github.com/ellipsis/ellipsis) - A package manager for dotfiles.
* [fresh](http://freshshell.com/) - Keep your dotfiles fresh. Fresh is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files.
* [GNU Stow](http://www.gnu.org/software/stow/) - Symlink farm manager which takes distinct packages of software and/or data located in separate directories on the filesystem, and makes them appear to be installed in the same place.
* [homeshick](https://github.com/andsens/homeshick) - Git dotfile synchronizer written in Bash.
* [homesick](https://github.com/technicalpickles/homesick) - Your home directory is your castle. Don't leave your dotfiles behind ([post](http://technicalpickles.com/posts/never-leave-your-dotfiles-behind-again-with-homesick/)).
* [mackup](https://github.com/lra/mackup) - Keep your application settings in sync (OS X/Linux).
* [rcm](https://github.com/thoughtbot/rcm) - rc file (dotfile) management
* [remote-dotfiles](https://www.npmjs.com/package/remote-dotfiles) - Describe your dotfiles configuration, tuned for and deploy to all your servers.
* [Super User Spark](https://github.com/NorfairKing/super-user-spark) - Tool that allows you to manage your beautiful and precious system configuration accross multiple systems and failures ([post](http://cs-syd.eu/posts/2015-09-27-super-user-spark-getting-started)).
* [vcsh](https://github.com/RichiH/vcsh) - Version Control System for $HOME, multiple Git repositories in $HOME.
* [yadm](https://github.com/TheLocehiliosan/yadm) - Tool for managing a collection of files across multiple computers, using a shared Git repository and some additional features.

### OS X

* [Cider](https://github.com/msanders/cider) - Cider is a simple wrapper for Homebrew and Homebrew Cask that allows you to save your setup across different machines.
* [dockutil](https://github.com/kcrawford/dockutil) - Command line tool for managing dock items
* [kody](https://github.com/jh3y/kody) - Dotfiles runner/manager written in node
* [osxc](http://osxc.github.io/) - Set of playbook roles made for OS X configuration

## Miscellaneous

* [A lesson in shortcuts](https://plus.google.com/+RobPikeTheHuman/posts/R58WgWwN9jp) - How the idea of "hidden" or "dot" files was born, by Rob Pike.
* [dotfiles.github.io](http://dotfiles.github.io/) - Your unofficial guide to dotfiles on GitHub.
* [OS X Defaults](https://github.com/kevinSuttle/OSXDefaults) - Centralized place for the awesome work started by [@mathiasbynens on .osx](https://github.com/mathiasbynens/dotfiles#sensible-os-x-defaults).

## Related Lists

* [Awesome Shell](https://github.com/alebcay/awesome-shell) - Curated list of awesome command-line frameworks, toolkits, guides and gizmos.
* [Awesome Zsh Plugins](https://github.com/unixorn/awesome-zsh-plugins) - List of Zsh plugins suitable for use with oh-my-zsh, antigen & Prezto.
* [Awesome Dev Env](https://github.com/jondot/awesome-devenv) - Curated list of awesome tools, resources and workflow tips making an awesome development environment.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Lars Kappert](https://webpro.nl) has waived all copyright and related or neighboring rights to this work.
