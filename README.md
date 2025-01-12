# dmenu-scripts
Scripts to open Video, Music, Documents, Config's, etc.



| script                                                                                            | about                                                  |
|---------------------------------------------------------------------------------------------------|--------------------------------------------------------|
| [dmenu_manpage](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_manpage)             | _xmonad like manpage prompt_
| [dmenu_video](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_video)                 | _prompt to launch videos in specified video dirs_
| [dmenu_music](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_music)                 | _prompt to launch music in specified music dirs_
| [dmenu_document](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_document)           | _prompt to launch document in specified document dirs_
| [dmenu_picture](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_picture)             | _prompt to launch images in specified picture dirs_
| [dmenu_wallpaper](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_wallpaper)         | _set wallpaper available in specified wallpaper dirs_
| [dmenu_web-bookmarks](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_web-bookmarks) | _simple prompt to open web bookmarks_
| [dmenu_web-search](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_web-search)       | _you can search on duckduckgo, youtube or others using this script_
| [dmenu_build](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_build)                 | _build project's on fly_
| [dmenu_config](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_config)               | _prompt to open specified config file in specified editor_
| [dmenu_termrun](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_termrun)             | _run in terminal_
| [dmenu_termrunp](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_termrunp)           | _run in terminal and pause at the end_
| [dmenu_package](https://github.com/DarkSamus669/dmenu-scripts/raw/main/dmenu_package)             | _view info or run command on installed packages (currently supports apt but you can customize script according to your package manager)_


Customization can be done by editing scripts, like adding or changing directories used in find command.



## Installation
* Run ```make install``` to install and ```make uninstall``` to uninstall.
* Configs are installed in ```~/.local/share/dmenu```
* To install in different path rather than default ```~/.local/bin``` do ```make install INSTALL_DIR=some_directory```



## Usage
* Best way to use these scripts is to include it as keybindings.
* You can use sxhkd config, run ```sxhkd -c your_sxhkdrc -c ~/.local/dmenu/sxhkd/sxhkdrc```



## Todo
- [ ] Config files.
- [ ] Optional command line arguments.
- [x] Makefile or script for installation.



## Recommended

**applications:**
```dmenu``` ```st``` ```urxvt```


**manpages:**
```find(1)``` ```dmenu(1)``` ```st(1)``` ```dash(1)```


**dmenu_patches:**
```separator``` ```printinputtext```
