﻿# FIXME/TODO Highlighter Visual Studio Extension

TodoHighlighter is an extension for Visual Studio 2010–2017 that places red boxes behind all the **FIXME**s in the editor window. It can also highlight other keywords, currently **TODO** with a yellow colour. Collapsed code regions also show the highlighting colour so that it is easily visible where such keywords exist.

![FIXME/TODO Highlighter Visual Studio Extension](TodoHighlighter_screen.png "FIXME/TODO Highlighter Visual Studio Extension")

Although not recommended, it is common practice to use comments with the “TODO” keyword throughout new code to indicate that something remains to be done in a certain place. And they serve as a good skeleton when writing down code for a work item, then adding the details for each part of it. These comments mostly look like other explanatory inline comments and are hard to find again unless you actually perform a text search for the keyword. This extension makes these keywords easily visible so that you quickly see where is work left to do before publishing the code.

The extension does not currently have any configuration. Keywords and colours are fixed. This may change in future releases.

Forked from original Yves Goergen's project [TODO Highlighter](https://github.com/ygoe/TodoHighlighter).

## Build extension

- install Visual Studio SDK (VS 2015 offers instalation automatically)
- adjust .Net frameword target version in solution properties
- build