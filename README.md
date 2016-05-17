# Drupal Syntax Highlighting

This VS Code extension does one and only one thing: it provides syntax highlighting support for Drupal specific file types, such as .module, .inc, .theme etc.

### "This extension is useless because you can specify the filetypes in settings.json" 

Specifying the filetypes in your settings.json is useless, because of this extension :-p
Jokes apart, I developed this plugin before the release of VS Code 1.0 and, at the time, using settings.json for that purpose wasn't an option.
Besides that I still think that it could be useful to install it: for example, did you remember to include in your settings.json those less common Drupal file extensions, such as .make and/or .profile? No? That's where you want to download Drupal Syntax Highlighting ;-)

### Standard Installation:

1. Open the Command Palette in VS Code (Ctrl-Shift-P, Mac: Cmd-Shift-P)
2. Type `ext install drupal`
3. Locate the package "Drupal Syntax Highlighting" from the results list and press enter.

### Manual Installation:

1. Install Visual Studio Code first.
2. Locate your home folder. In Windows, your home folder is probably C:\Users\\*YourName*, in Mac it's probably /Users/*yourname* and in Linux it's probably /home/*yourname*
3. Place the 'drupal' folder under *[your_home_folder]*/.vscode/extensions.
4. Restart Visual Studio Code

### Supported file extensions:

* .engine 
* .theme 
* .install 
* .inc 
* .make 
* .module 
* .profile 
* .test
