# Sublime Text 3

[Keyboard shorcuts](#keyboard-shorcuts) | [Install packages](#packages) | [Snippets](#snippets) | [Color-scheme & Theme](#color-scheme-theme)

Local Folders:

- [dev/Sublime Text/](file:///C:/Users/Jordi/dev/Sublime Text/)
- [AppData/Roaming/Sublime Text 3/](file:///C:/Users/Jordi/AppData/Roaming/Sublime Text 3/)
- [AppData/Roaming/Sublime Text 3/Packages/](file:///C:/Users/Jordi/AppData/Roaming/Sublime Text 3/Packages/)
- [AppData/Roaming/Sublime Text 3/Packages/User/snippets](file:///C:/Users/Jordi/AppData/Roaming/Sublime Text 3/Packages/User/snippets)

Tutorials:

- [scotch.io - Best plugins and settings](https://scotch.io/bar-talk/best-of-sublime-text-3-features-plugins-and-settings)
- [scotch.io - Themes, color schemes](https://scotch.io/bar-talk/the-complete-visual-guide-to-sublime-text-3-themes-color-schemes-and-cool-features)

<br />

## Keyboard shortcuts

Menu `Preferences` > `Key Bindings - Default`

[Default (Windows).sublime-keymap](AppData/Roaming/Sublime Text 3/Packages/User/Default (Windows).sublime-keymap)


Scope | Keyboard | Action
:-- | :-- | :--
Show Console | <kbd>ctrl</kbd> + <kbd>8</kbd> | show_panel
Toggle Side Bar | <kbd>ctrl</kbd> + <kbd>k</kbd>, <kbd>ctrl</kbd> + <kbd>b</kbd> | toggle_side_bar
Full-screen | <kbd>f11</kbd> | toggle_full_screen
<i></i> | <kbd>shift</kbd> + <kbd>f11</kbd> | toggle_distraction_free
Layouts | <kbd>alt</kbd> + <kbd>shift</kbd> + <kbd>1</kbd> | set_layout
<i></i> | <kbd>alt</kbd> + <kbd>shift</kbd> + <kbd>2</kbd> | set_layout
<i></i> | <kbd>alt</kbd> + <kbd>shift</kbd> + <kbd>3</kbd> | set_layout
Groups | <kbd>ctrl</kbd> + <kbd>1</kbd> | focus_group
<i></i>| <kbd>ctrl</kbd> + <kbd>2</kbd> | focus_group
<i></i> | <kbd>ctrl</kbd> + <kbd>3</kbd> | focus_group
<i></i> | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>1</kbd> | move_to_group
<i></i> | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>2</kbd> | move_to_group
<i></i> | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>3</kbd> | move_to_group
Panes | <kbd>ctrl</kbd> + <kbd>k</kbd>, <kbd>ctrl</kbd> + <kbd>up</kbd> | new_pane
<i></i> | <kbd>ctrl</kbd> + <kbd>k</kbd>, <kbd>ctrl</kbd> + <kbd>down</kbd> | close_pane
Reveal current file in side-bar | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>r</kbd> | reveal_in_side_bar<kbd>}
Expand selection to line | <kbd>ctrl</kbd> + <kbd>l</kbd> | expand_selection
Expand selection to scope | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>space</kbd> | expand_selection
Expand selection to brackets | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>m</kbd> | expand_selection
Upper-case| <kbd>ctrl</kbd> + <kbd>k</kbd>, <kbd>ctrl</kbd> + <kbd>u</kbd> | upper_case
Lower-case| <kbd>ctrl</kbd> + <kbd>k</kbd>, <kbd>ctrl</kbd> + <kbd>l</kbd> | lower_case
Permutar líneas seleccionadas | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>up</kbd> | swap_line_up
<i></i> | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>down</kbd> | swap_line_down
Juntar líneas | <kbd>ctrl</kbd> + <kbd>j</kbd> | join_lines
Duplicar línea | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>d</kbd> | duplicate_line
Escribir en columna, en varias líneas a la vez | <kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>up</kbd> | select_lines
<i></i> | <kbd>ctrl</kbd> + <kbd>alt</kbd> + <kbd>down</kbd> | select_lines
Ordenar filas | <kbd>ctrl</kbd> + <kbd>f9</kbd> | sort_lines
Wrap lines | <kbd>alt</kbd> + <kbd>q</kbd> | wrap_lines
Toggle Comment| <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>q</kbd> | toggle_comment
<i></i> | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>alt</kbd> + <kbd>q</kbd> | toggle_comment
GoTo show files | <kbd>ctrl</kbd> + <kbd>p</kbd> | show_overlay
GoTo cursor back / foward | <kbd>alt</kbd> + <kbd>-</kbd> | jump_back
<i></i> | <kbd>alt</kbd> + <kbd>shift</kbd> + <kbd>-</kbd> | jump_forward
Find & Repalce| <kbd>ctrl</kbd> + <kbd>f</kbd> | show_panel
<i></i> | <kbd>ctrl</kbd> + <kbd>h</kbd> | show_panel
<i></i> | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>h</kbd> | replace_next
<i></i> | <kbd>f3</kbd> | find_next
<i></i> | <kbd>shift</kbd> + <kbd>f3</kbd> | find_prev
Buscar ocurrencias, siguiente ocurrencia | <kbd>ctrl</kbd> + <kbd>d</kbd> | find_under_expand
<i></i> | <kbd>ctrl</kbd> + <kbd>k</kbd>, <kbd>ctrl</kbd> + <kbd>d</kbd> | find_under_expand_skip
<i></i> | <kbd>ctrl</kbd> + <kbd>u</kbd> | soft_undo
Bookmarks| <kbd>f2</kbd> | next_bookmark
<i></i> | <kbd>shift</kbd> + <kbd>f2</kbd> | prev_bookmark
<i></i> | <kbd>ctrl</kbd> + <kbd>f2</kbd> | toggle_bookmark
<i></i> | <kbd>ctrl</kbd> + <kbd>shift</kbd> + <kbd>f2</kbd> | clear_bookmarks
<i></i> | <kbd>alt</kbd> + <kbd>f2</kbd> | select_all_bookmarks
Collapse by level | <kbd>ctrl</kbd> + <kbd>k</kbd>, <kbd>ctrl</kbd> + <kbd>1</kbd> | fold_by_level
<i></i> | <kbd>ctrl</kbd> + <kbd>k</kbd>, <kbd>ctrl</kbd> + <kbd>2</kbd> | fold_by_level
<i></i> | <kbd>ctrl</kbd> + <kbd>k</kbd>, <kbd>ctrl</kbd> + <kbd>3</kbd> | fold_by_level
Expand all | <kbd>ctrl</kbd> + <kbd>k</kbd>, <kbd>ctrl</kbd> + <kbd>0</kbd> | unfold_all


<br />

## Packages

##### Install package via Package Control:

1. Type <kbd>Ctrl</kbd> + <kbd>Sfhit</kbd> + <kbd>P</kbd>.
1. Type `Package Control: Install Package`.
1. Type name of package you want to install.


##### [SideBarEnhancements](https://packagecontrol.io/packages/SideBarEnhancements)

Provides enhancements to the operations on Sidebar of Files and Folders for Sublime Text.


##### [CodeFormatter](https://packagecontrol.io/packages/CodeFormatter)

Plugin that supports format (beautify) source code.


##### [PackageResourceViewer](https://github.com/skuroda/PackageResourceViewer)

Plugin to assist viewing and editing package resources.


##### [Babel](https://github.com/babel/babel-sublime)

Language definitions for ES6+ JavaScript with React JSX syntax extensions.

1. Open a file with `.js` or `.jsx` extensions,
1. Select `View` from the menu,
1. Then `Syntax` > `Open all with current extension as...` > `Babel` > `JavaScript (Babel)`


##### [Babel Snippets](https://github.com/babel/babel-sublime-snippets)

1. Type snippet trigger, e.g. `rcc` (see [avaible snippets](https://github.com/babel/babel-sublime-snippets#available-snippets).)
1. Type <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>,</kbd> in order to expand snippet.


To set a key binding, go to `Preferences` > `Key Bindings - User` and add an entry like this:

```json
{
    "keys": ["ctrl+shift+,"],
    "command": "insert_snippet",
    "args": {
        "name": "Packages/Babel Snippets/react_wrap.sublime-snippet"
    }
}
```



##### [ESLint](https://github.com/SublimeLinter/SublimeLinter-eslint)

This linter plugin for SublimeLinter provides an interface to ESLint. It will be used with files that have the "javascript" syntax.


##### [Predawn Theme](https://github.com/jamiewilson/predawn)

Predawn is a dark interface and syntax theme for Sublime Text and Atom

To activate the theme replace your current theme settings, go to `Preferences` > `Settings - User` and add this:

```json
{
    "theme": "predawn-DEV.sublime-theme",
    "color_scheme": "Packages/Predawn/predawn.tmTheme",
    "predawn_findreplace_small": true,
    "predawn_quick_panel_small": true,
    "predawn_sidebar_arrows": true,
    "predawn_sidebar_large": false,
    "predawn_sidebar_medium": false,
    "predawn_sidebar_narrow": false,
    "predawn_sidebar_small": true,
    "predawn_sidebar_xlarge": false,
    "predawn_sidebar_xsmall": false,
    "predawn_tabs_active_underline": true,
    "predawn_tabs_large": false,
    "predawn_tabs_medium": false,
    "predawn_tabs_small": true,
}
```




##### [Oceanic Next Color Scheme](https://github.com/voronianski/oceanic-next-color-scheme)

1. Menú `Preferences` > `Color Scheme...`
1. Select `Oceanic Next`
1. Change colors: (view [Edit a theme: .tmTheme](#edit-a-theme-tmtheme))
	- `entity.name.tag` change color ~~#EB606B~~ to #**FF7A85**
	- `background` change color ~~#1B2B34~~ to #**282828**
	- `selectionBackground`, `selection`, `stackGuide` change color ~~#4f5b66~~ to #**4f4f4f**


##### [SFTP](https://wbond.net/sublime_packages/sftp)

Spend less time managing file transfers and more time coding.

Upload current file: <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>U</kbd> + <kbd>F</kbd>

`sftp-config.json`

```json
{
    "type": "ftp",

    "save_before_upload": true,
    "upload_on_save": false,
    "sync_down_on_open": false,
    "sync_skip_deletes": false,
    "sync_same_age": true,
    "confirm_downloads": false,
    "confirm_sync": true,
    "confirm_overwrite_newer": false,
    
    "host": "ftp.host.com",
    "user": "username",
    "password": "password",
    
    "remote_path": "/www/",
    "ignore_regexes": [
        "\\.sublime-(project|workspace)", "sftp-config(-alt\\d?)?\\.json",
        "sftp-settings\\.json", "/venv/", "\\.svn/", "\\.hg/", "\\.git/",
        "\\.bzr", "_darcs", "CVS", "\\.DS_Store", "Thumbs\\.db", "desktop\\.ini",
        "_model.doc\\.xml", "_nose_model.doc\\.html", "entities-content\\.html", "/sessions/",
        "_api.json", "queries.txt", "rest - abans de mainEntity.php"

    ],

    "connect_timeout": 30
}
```


##### [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter)

Provides a framework for linting code.


##### [Terminal](https://packagecontrol.io/packages/Terminal)

Shortcuts and menu entries for opening a terminal at the current file, or the current root project folder.


##### [Emmet](https://emmet.io/blog/sublime-text-3/)

Emmet is a plugin for many popular text editors which greatly improves HTML & CSS. (See [abbreviations](https://docs.emmet.io))

Usage: expand abreviation typing <kbd>Ctrl</kbd> + <kbd>E</kbd>

Example: `#page>div.logo+ul#navigation>li*5>a{Item $}`

```html
<div id="page">
    <div class="logo"></div>
    <ul id="navigation">
        <li><a href="">Item 1</a></li>
        <li><a href="">Item 2</a></li>
        <li><a href="">Item 3</a></li>
        <li><a href="">Item 4</a></li>
        <li><a href="">Item 5</a></li>
    </ul>
</div>
```


##### [Colorpicker](https://packagecontrol.io/packages/ColorPicker)

A multi-platform color picker plugin. Usage: <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd>


##### [Markdown Editing](https://github.com/SublimeText-Markdown/MarkdownEditing)

Syntax for `Readme.md` files. See this [tutorial](https://github.com/jordhor/markdown).


##### [Markdown Preview ](https://github.com/facelessuser/MarkdownPreview)

Preview and build your markdown files quickly in your web browser using Sublime Text 3.

1. From the `.md` document
1. Type <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>
1. Type `Markdown Preview: Preview in Browser`



<br />

## Snippets

Menu : `Tools` > `Develop` > `New snippet...`



<br />

##	Color-scheme & Theme

##### Edit a theme: `.tmTheme`

1. Type <kbd>Ctrl</kbd> + <kbd>Sfhit</kbd> + <kbd>P</kbd>.
1. Type `Package Resource Viewer: Open Resource`
1. Select `Color Scheme - Default` o `Oceanic Next Color Scheme`
1. Select theme to edit: `Oceanic Next.tmTheme`

##### Establecer un color-scheme para un lenguaje específico:

1. Nos situamos en un archivo del tipo que deseamos establecer, por ejemplo _my_scripts.js_
1. Menu : `Preferences` > `Settings - More` > `Syntax Specific - User`
1. Write the color-scheme for syntax highlight, exemple:
```json
{
    "color_scheme": "Packages/Color Scheme - Default/JavaScript.tmTheme"
}
```
1. Se guarda en [/AppData/Roaming/Sublime Text 3/Packages/Color Scheme - Default/](file:///C:/Users/Jordi/AppData/Roaming/Sublime Text 3/Packages/Color Scheme - Default/)





