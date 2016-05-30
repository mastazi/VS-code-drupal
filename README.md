# Drupal Syntax Highlighting

This VS Code extension does one and only one thing: it provides syntax highlighting support for Drupal specific file types, such as .module, .inc, .theme etc.

### "This plugin is useless because you can specify the filetypes in settings.json" 

Well, specifying the filetypes in your settings.json is useless, because of this plugin :-p
Jokes apart, I developed it before the release of VS Code 1.0 and, at the time, using settings.json for that purpose wasn't an option.
Besides that, I think that the plugin is still useful as of today, as it is far easier to install a single plugin than having to manually add several file extensions to your settings.json (some of those extension are not common and might be easily missed).

### Standard Installation:

1. Open the Command Palette in VS Code (Ctrl-Shift-P, Mac: Cmd-Shift-P)
2. Type `ext install drupal`
3. Locate the package "Drupal Syntax Highlighting" from the results list and press enter.

### Supported file extensions:

* .engine 
* .theme 
* .install 
* .inc 
* .make 
* .module 
* .profile 
* .test
