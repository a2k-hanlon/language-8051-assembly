# language-8051-assembly-crosside package

Syntax highlighting and snippets for 8051 assembly, adapted for use alongside CrossIDE by Jesus Calvino-Fraga.
This is a package for GitHub's Atom editor.

This package is unlikely to be updated.
Feel free to fork and modify according to your needs, or contribute directly to this repo if you have something useful to add!

Code is **MIT licensed**.

## Installation
If you previously installed the language-8051-assembly package from which this repo was forked (which is the one listed in the Atom package index), ensure it is uninstalled before installing this package.

Clone this git repository into Atom's packages folder: ```<your user directory>/.atom/packages/```. If you don't have git set up, you can place the folder from the .zip download there instead. Restart Atom.

The .asm extension is not exclusive to 8051 microcontroller assembly files. As such, Atom's language autodetect may not correctly identify these files if other assembly language packages are installed; for example, language-arm. Check that "8051 Assembly" is listed as the file language at the bottom of the Atom window.

The syntax highlighting should kick in automatically for .asm and .inc files. If it doesn't kick in, or the wrong language has been detected, click on the language setting at the bottom of the Atom window and select "8051 Assembly".

## Notes on changes from the forked repository
This fork of language-8051-assembly is set up so as to function similarly to the syntax highlighting in CrossIDE.
It also adds lowercase versions of all snippets. The original uppercase ones remain as well, with a few modifications.

This package is not listed on https://atom.io/packages. Unfortunately, that means it cannot be installed through the package installer within atom.

Original Package website
https://atom.io/packages/language-8051-assembly
