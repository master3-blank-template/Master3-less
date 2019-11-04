# Less pack for master3 template

_description in Russian [here](README.ru.md)_

A package of basic less-files for compiling custom styles for the [Master3](https://github.com/master3-blank-template/Master3) template.

**Does not contain a built-in compiler!**

Only used in conjunction with the [UIkit3 library for Joomla3](https://github.com/master3-blank-template/UIkit3-Joomla-library) library.

It consists of three files:

* `theme.less` – the main compiled file, contains the relative paths to the less and svg files from the UIkit package, the connection of the UIkit components, the connection of your less files and your custom style code.
* `uikit.less` – an uncompiled file with a list of plug-ins of UIkit. Comment out the connections of those components that you do not want to connect to your style set.
* `uikit-variables.less` – an uncompiled file with a list of all overridden less variables of all UIkit components. Set new values ​​for these variables to change the values ​​of the corresponding properties of the corresponding UIkit components. Do not delete variables to avoid unexpected consequences in your stylesheet. There is no need to delete the variables of those UIkit components that you disabled in the file above – they will not affect the final result.

After installation, the less folder with the above files will appear in the installed Master3 template.

**Please do not use this if you do not know how to configure the environment for compiling less files on your server, or contact the appropriate specialist for help.**
