# eclipse-solarized

Solarized themes for Eclipse, without red braces and such.
Adapted with minor changes from the themes shipped with Visual Studio Code.

Can be installed (as of 2020-04-19) using the DevStyle Eclipse Plugin.

* For Solarized Light, choose e. g.: Light Custom, H: 45, S: 50, L: 99, Theme Background
* For Solarized Dark, choose e. g.: Dark Custom, H: 193, S: 100, L: 99, Theme Background

## Disclaimer

You might find some parts of the UI don't match the colour scheme.
Feel free to tweak (almost all colours can be changed in Eclipse's preferences),
and feel free to add a GitHub issue or create a pull request if you think there is room for improvement

## Known differences

### Handling of keywords

Eclipse's Java highlighting appears to put control-flow keywords (`if`, `for`, `try`, ...)
in the same category as modifiers (`public`, `private`, and also `final`, `static`)
and meta-types (like `class`, `enum`, `interface`); VS Code colours control-flow keywords green and with regular weight
(probably to match the behaviour with other languages), but other Java keywords are displayed in bold,
but in the same colour as non-styled text. Here, I have chosen a compromise (literally a colour somewhere in the middle of the two).
