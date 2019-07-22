# Microsoft VS Code Extensions 

Microsoft vs code Extension API...

# What Extensions do?

1. Change the look of VS Code with a color or icon theme - Theming
2. Add custom components & views in the UI - Extending the Workbench
3. Create a Webview to display a custom webpage built with HTML/CSS/JS - Webview Guide
4. Support a new programming language - Language Extensions Overview
5. Support debugging a specific runtime - Debugger Extension Guide

# 01. Material Theme

The most epic theme meets Visual Studio Code

<h2>Installation</h2>

You can override the Material Theme UI and schemes colors by adding these theme-specific settings to your configuration. For advanced customisation please check the relative section on the VS Code documentation.

<p>Windows - Ctrl + Shift + x</p>
<p>macOS - ⌘ + Shift + x</p>
<p>Linux - Ctrl + Shift + x</p>

after search <a href="https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme">matherial theme</a> install...

# 02. Material Icon Theme

The Material Icon Theme provides lots of icons based on Material Design for Visual Studio Code.

<h2>Installation</h2>

You can change the color of the default folder icon using the command palette:
- Using user settings:

<p>Windows - Ctrl + Shift + x</p>
<p>macOS - ⌘ + Shift + x</p>
<p>Linux - Ctrl + Shift + x</p>

after search <a href="https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme">Material Icon Theme</a> install....

<h2>Futures</h2>

1. File icons
2. Folder icons
3. Customize folder color
4. Folder themes
5. Custom icon opacity
6. Custom icon saturation
7. Custom icon associations
6. One-click activation

Press Ctrl-Shift-P to open the command palette and type Material Icons....

# 03. Auto Rename Tag

Auto rename paired HTML/XML tag

- This will be for the lazy people this one is called auto renaming tags

<h2>Installation</h2>

Automatically rename paired HTML/XML tag, same as Visual Studio IDE does.
- Using user settings:

<p>Windows - Ctrl + Shift + x</p>
<p>macOS - ⌘ + Shift + x</p>
<p>Linux - Ctrl + Shift + x</p>

after search <a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag">Auto Rename Tag</a> install....

<h2>Futures</h2>

- When you rename one HTML/XML tag, automatically rename the paired HTML/XML tag

<h3>Configuration</h3>

Add entry into auto-rename-tag.activationOnLanguage to set the languages that the extension will be activated. By default, it is ["*"] and will be activated for all languages.

<span>Note:</span>The setting should be set with language id defined in VS Code. Taking javascript definition as an example, we need to use javascript for .js and .es6, use javascriptreact for .jsx. So, if you want to enable this extension on .js file, you need to add javascript in settings.json.

# 04. Live Server

Launch a development local Server with live reload feature for static & dynamic pages

- This will be my favorite it's called live server i thnik every text editor have this ..
- This basically allows us to generate server and whenever we save our file our html,css,python,javascript.. whatever you want progranmming language it's automatically reload our page...so you can see the live changes..

. let's take a look of how we can install that..

<h2>Installation</h2>

<p>Windows - Ctrl + Shift + x</p>
<p>macOS - ⌘ + Shift + x</p>
<p>Linux - Ctrl + Shift + x</p>

after search <a href="https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer">Live Server</a> install...

<h2>Futures</h2>

01. A Quick Development Live Server with live browser reload.
02. Start or Stop server by a single click from status bar.
03. Open a HTML file to browser from Explorer menu <a href="https://raw.githubusercontent.com/ritwickdey/vscode-live-server/master/images/Screenshot/vscode-live-server-explorer-menu-demo-1.gif">.[Quick Gif Demo].</a>
04. Support for excluding files for change detection.
05. Hot Key control.
06. Customizable Port Number, Server Root, default browser.
07. Support for any browser (Eg: Firefox Nightly) using advance Command Line.
08. SVG Support
09. https Support.
10. Multi-root workspace supported.

<h3>Version</h3>

01. Version 5.5.0 (12.02.19)
. [Fixes] Fixed ignoreFiles settings [#255]
. Attempt to fix high cpu load [#278]

02. Version 5.5.1 (12.02.19)
. [Fixes] Fixed Extension host terminated unexpectedly for MacOS. [#285]

03. Version 5.6.0 (17.04.19)
. [NEW] Intregation of Browser Preview with Live Server [#352 - Thanks to Kenneth Auchenberg]
. [NEW] Fallback to random port If given port is busy. [#330 - Thanks to Ali Almohaya ]
. [FIXES] Moved to vscode-chokidar lib for #285.
. Doc Fixes [#388 - Thanks to Ted Silbernagel]

04. Version 5.6.1 (17.04.19)
. [NEW] Fixing Extension host terminated unexpectedly *[#431]

# 05. Better Comments

Improve your code commenting by annotating with alert, informational, TODOs, and more!

- The Better Comments extension will help you create more human-friendly comments in your code.
With this extension, you will be able to categorise your annotations into:
. Alerts
. Queries
. TODOs
. Highlights
. Commented out code can also be styled to make it clear the code shouldn't be there
. Any other comment styles you'd like can be specified in the settings

. let's take a look of how we can install that..

<h2>Installation</h2>

<p>Windows - Ctrl + Shift + x</p>
<p>macOS - ⌘ + Shift + x</p>
<p>Linux - Ctrl + Shift + x</p>

after search <a href="https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments">Better Comments</a> install

<h3>Supported Languages</h3>
. C
. C++
. Ada
. AsciiDoc
. HTML
. CSS
. Javascript
. Python
<a href="https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments">View More</a>

# 06. CSS Peek

Allow peeking to css ID and class strings as definitions from html files to respective CSS. Allows peek and goto definition.

- This extension extends HTML and ejs code editing with Go To Definition and Go To Symbol in Workspace support for css/scss/less (classes and IDs) found in strings within the source code.

 -This was heavily inspired by a similar feature in Brackets called CSS Inline Editors.

 - The extension supports all the normal capabilities of symbol definition tracking, but does it for css selectors (classes, IDs and HTML tags). This includes:

 .Peek: load the css file inline and make quick edits right there. (Ctrl+Shift+F12)
. Go To: jump directly to the css file or open it in a new editor (F12)
. Hover: show the definition in a hover over the symbol (Ctrl+hover)

- In addition, it supports the Symbol Provider so you can quickly jump to the right CSS/SCSS/LESS code if you already know the class or ID name

. let's take a look of how we can install that..

<h2>Installation</h2>

<p>Windows - Ctrl + Shift + x</p>
<p>macOS - ⌘ + Shift + x</p>
<p>Linux - Ctrl + Shift + x</p>

after search <a href="https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek">CSS Peek</a> install...

#07. Live Sass Compiler

- Compile Sass or Scss to CSS at realtime with live browser reload.

-A VSCode Extension that help you to compile/transpile your SASS/SCSS files to CSS files at realtime with live browser reload.

. let's take a look of how we can install that..

<h2>Installation</h2>

<p>Windows - Ctrl + Shift + x</p>
<p>macOS - ⌘ + Shift + x</p>
<p>Linux - Ctrl + Shift + x</p>

after search <a href="https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass">Live Sass Compiler</a> install...

(or)

Open VSCode Editor and Press ctrl+P, type ext install live-sass.

<h2>Usage/Shortcuts</h2>

. Click to Watch Sass from Statusbar to turn on the live compilation and then click to Stop Watching Sass from Statusbar to turn on live compilation . 
. Press F1 or ctrl+shift+P and type Live Sass: Watch Sass to start live compilation or, type Live Sass: Stop Watching Sass to stop a live compilation.
. Press F1 or ctrl+shift+P and type Live Sass: Compile Sass - Without Watch Mode to compile Sass or Scss for one time.


<h2>Features</h2>

. Live SASS & SCSS Compile.
. Customizable file location of exported CSS.
. Customizable exported CSS Style (expanded, compact, compressed, nested).
. Customizable extension name (.css or .min.css).
. Quick Status bar control.
. Exclude Specific Folders by settings.
. Live Reload to browser (Dependency on Live Server extension).
. Autoprefix Supported (See setting section)

# 08. Prettier - Code formatter

VS Code plugin for prettier/prettier

- Prettier formatter for Visual Studio Code

VS Code package to format your JavaScript / TypeScript / CSS using<a href="https://github.com/prettier/prettier"> Prettier</a>.

. let's take a look of how we can install that..

<h2>Installation</h2>

<p>Windows - Ctrl + Shift + x</p>
<p>macOS - ⌘ + Shift + x</p>
<p>Linux - Ctrl + Shift + x</p>

after search <a href="https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode">Prettier - Code formatter</a> install...

-------------------------------------------

<h4>Visit Our Visual Studio Code More Extensions <a href="https://marketplace.visualstudio.com/search?term=prettier&target=VSCode&category=All%20categories&sortBy=Relevance">All Extensions</a> </h4>
