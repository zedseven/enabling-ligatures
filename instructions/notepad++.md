# Notepad++

To enable ligatures in Notepad++, go to `Plugins > Plugins Admin...` and find `Luascript` in the list of available plugins.

![Go to Plugins > Plugins Admin...](/media/notepad++/pluginsAdmin.gif "Go to Plugins > Plugins Admin...")

![Install Luascript](/media/notepad++/installLuascript.png "Install Luascript")

Enable and install it, then go to `Plugins > Luascript > Edit Startup Script`.

Notepad++ should open it up and the script will likely be empty or just about.

Add the following two lines to the end of the script:

```lua
editor1.Technology = SC_TECHNOLOGY_DIRECTWRITE
editor2.Technology = SC_TECHNOLOGY_DIRECTWRITE
```

Once done, simply restart Notepad++ and your changes should take effect. Remember, in order for this to work, you have to set the editor to use [a font that supports ligatures](/liga-fonts.md).


Thank you to [dail8859 for this solution](https://github.com/notepad-plus-plus/notepad-plus-plus/issues/2287#issuecomment-256638098).
