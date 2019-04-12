wikitranslator
==============
Semi-automated translation of articles at the Team Fortress Wiki. Can be used with any kind of article and has extended functionality for item and set articles, possibly halfing translation time.

Simple GUI interface with real-time translation.

Additional information is [available on the TF Wiki](https://wiki.teamfortress.com/wiki/User:TidB/wikitranslator), also detailing the process of adding new languages.

Run `pyinstaller gui.py -n wikitranslator --onefile --add-data="lang;lang"` and
`pyinstaller gui.py -n wikitranslator --onedir --add-data="lang;lang"` to build everything

To-Do
-----
- Cleaning up the code
- Fixing various problems with Mac OS X (copying/selecting text)
- {{w}} to [[w]] transformation
- Automatic {{update name}}
- Automatic translation of infobox classes
- Tests (ahem)
- Enable certain methods for unsupported languages
