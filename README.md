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

after search <a href="https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme">Material Icon Theme</a> install

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

after search <a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag">Auto Rename Tag</a> install

<h2>Futures</h2>

- When you rename one HTML/XML tag, automatically rename the paired HTML/XML tag

<h3>Configuration</h3>

Add entry into auto-rename-tag.activationOnLanguage to set the languages that the extension will be activated. By default, it is ["*"] and will be activated for all languages.

<span>Note:</span>The setting should be set with language id defined in VS Code. Taking javascript definition as an example, we need to use javascript for .js and .es6, use javascriptreact for .jsx. So, if you want to enable this extension on .js file, you need to add javascript in settings.json.