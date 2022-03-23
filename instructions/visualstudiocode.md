# Visual Studio Code++

To enable ligatures in Visual Studio Code, go to `Settings > Text Editor > Font` and find `Font Ligatures` in the list of options

Continue to `Edit in settings.json`

Add the following line to the JSON
```json
    "editor.fontLigatures": true,
```

Once done, restart Visual Studio Code and your changes should take effect. Remember, in order for this to work, you have to set the editor to use [a font that supports ligatures](/liga-fonts.md).