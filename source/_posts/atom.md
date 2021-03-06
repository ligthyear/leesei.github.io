---
title: "Atom"
date: 2015-07-09 00:16:00
categories:
- app
tags:
- atom
- settings
- package-manager
toc: true
---

[Atom](https://atom.io/)
[Issues · atom/atom](https://github.com/atom/atom/issues)

[Atom Editor Tips and Tricks](http://www.atomtips.com/)  
[Atom editor or Sublime Text which one to pick](http://www.atomtips.com/atom-editor-vs-sublime-text/)

<!-- more -->

## Must Read Docs

[Atom](https://atom.io/docs/latest/)  
[Documentation](https://atom.io/docs)  

Terminology:

| SublimeText | Atom        |
| ----------- | ----------- |
| Syntax      | Grammar     |

## Package Management

Atom has a built in package manager `apm` to install packages form official repo. It is actually a wrapper for `npm` for the Atom repo so you should find it familiar.  
You can do install, search, list with it. `apm search -p` for packages, `apm search -t` for themes.
You can also directly install to config folder.

[Packages](https://atom.io/packages)  
[Themes](https://atom.io/themes)  

[How to synchronize packages and settings](http://www.atomtips.com/how-to-synchronize-atom-between-computers/)  
[sync-settings](https://atom.io/packages/sync-settings)  
[parcel](https://atom.io/packages/parcel)  
[package-list](https://atom.io/packages/package-list)  
[package-list-downloader](https://atom.io/packages/package-list-downloader)  
[package-sync](https://atom.io/packages/package-sync)  

### Adding to Context Menu

In `init.coffee`:

```coffee
atom.contextMenu.add {
    'atom-text-editor': [{
        label: 'Bookmark',
        command: 'my-package:toggle'
    }]
}
```

## Extension Development

[package-generator](https://atom.io/packages/package-generator)  
[run-in-atom](https://atom.io/packages/run-in-atom)  

### Theme Development

### Grammar Development

### Snippets Development

[Get productive with Atom Snippets - Atom Editor Tips and Tricks](http://www.atomtips.com/get-productive-atom-snippets/)

### Publishing to Package Control

## My Installed Packages

[Atom Setup | Front End Engineering, May 2015](http://jacobthemyth.gitbooks.io/front-end-engineering-may-2015/content/notes/misc/atom-setup.html)

### Synchronize settings


[Syncing settings & packages between machines - features - Atom Discussion](https://discuss.atom.io/t/syncing-settings-packages-between-machines/1385/23)

symlink ~/.atom would be overkill
[sync-settings](https://atom.io/packages/sync-settings)  
[package-sync](https://atom.io/packages/package-sync)  

### Color scheme/Themes

[atom-material-ui](https://atom.io/themes/atom-material-ui)  
[seti-ui](https://atom.io/themes/seti-ui)  
[unity-ui](https://atom.io/themes/unity-ui)  

[material-design-syntax](https://atom.io/themes/material-design-syntax)

### Grammar/Snippets

[angularjs](https://atom.io/packages/angularjs)  
[atom-bootstrap3](https://atom.io/packages/atom-bootstrap3)  
[jquery-snippets](https://atom.io/packages/jquery-snippets)  
[react](https://atom.io/packages/react)  

[javascript-snippets](https://atom.io/packages/javascript-snippets)  
[turbo-javascript](https://atom.io/packages/turbo-javascript)  

### Plugins

[atom-alignment](https://atom.io/packages/atom-alignment)  
[atom-beautify](https://atom.io/packages/atom-beautify)  
[autocomplete-paths](https://atom.io/packages/autocomplete-paths)  
[autocomplete-plus](https://atom.io/packages/autocomplete-plus)  
[autocomplete-snippets](https://atom.io/packages/autocomplete-snippets)  
[git-plus](https://atom.io/packages/git-plus)  
[highlight-selected](https://atom.io/packages/highlight-selected)  
[keybinding-cheatsheet](https://atom.io/packages/keybinding-cheatsheet)  
[minimap-find-and-replace](https://atom.io/packages/minimap-find-and-replace)  
[minimap-highlight-selected](https://atom.io/packages/minimap-highlight-selected)  
[minimap](https://atom.io/packages/minimap)  
[pain-split](https://atom.io/packages/pain-split)
[pigments](https://atom.io/packages/pigments)  
[project-manager](https://atom.io/packages/project-manager)  
[script](https://atom.io/packages/script)  

### Plugins development

[Floobits News: Developing Atom Plugins, Part 1: On the Bleeding Edge](https://news.floobits.com/2015/10/12/developing-atom-plugins-on-the-bleeding-edge/)
[Floobits News: Developing Atom Packages, Part 2: So Much Potential, So Many Bugs](https://news.floobits.com/2015/10/14/developing-atom-plugins-so-much-potential-so-many-bugs/)

### Linter

[linter](https://atom.io/packages/linter)  ([Linters list](http://atomlinter.github.io/))

[Wallaby.js for Atom text editor · Artem Govorov](http://dm.gl/2015/08/31/wallaby-for-atom/)
