# latex-template-assign-sc
A LaTeX simple single column document. This is includes all the necessary components to work with Visual Studio Code, including but not limited to:  Visual Studio Code tasks, custom syntax highlighting for LaTeX, a custom dictionary (spell checker).

## Tools required
This template is built to work with Visual Studio Code plus the following extensions:

- Code Spell Checker
- Dracula At Night
- GitLens — Git supercharged
- LaTeX Snippets
- LaTeX Workshop
- latex-formatter

## Structure
The following describes the parts of the template.

.vscode directory contains:
- dictionary.txt - works in conjunction with Code Spell Checker extension, adds words to ignore.
- cSpell.json - works in conjunction with Code Spell Checker extension, adds words to ignore.
- settings.json - custom settings for working with LaTeX, custom theme colours better highlight syntax with dark themes.
- task.json - exection direction for compiling the document.

- citations.bib - place holder references in bib format.

The following style sheets and two custom packages are included:
- structure.tex

The main tex file is: latex-template-assign-sc.tex

## Usage
Simply install the abovementioned software and extensions then save.
