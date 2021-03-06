 # Git Diff Margin [![VS Marketplace](https://vsmarketplacebadge.apphb.com/version/LaurentKempe.GitDiffMargin.svg)](https://marketplace.visualstudio.com/items?itemName=LaurentKempe.GitDiffMargin) [![Rating(Short)](https://vsmarketplacebadge.apphb.com/rating-short/LaurentKempe.GitDiffMargin.svg)](https://marketplace.visualstudio.com/items?itemName=LaurentKempe.GitDiffMargin) [![Installs(Short))](https://vsmarketplacebadge.apphb.com/installs-short/LaurentKempe.GitDiffMargin.svg)](https://marketplace.visualstudio.com/items?itemName=LaurentKempe.GitDiffMargin) [![Downloads(Short)))](https://vsmarketplacebadge.apphb.com/downloads-short/LaurentKempe.GitDiffMargin.svg)](https://marketplace.visualstudio.com/items?itemName=LaurentKempe.GitDiffMargin)

Git Diff Margin displays live Git changes of the currently edited file on Visual Studio margin and scroll bar.

[![Build Status](https://dev.azure.com/techheadbrothers/GitDiffMargin/_apis/build/status/laurentkempe.GitDiffMargin)](https://dev.azure.com/techheadbrothers/GitDiffMargin/_build/latest?definitionId=7) [![Build status](https://ci.appveyor.com/api/projects/status/n2j1hcqpdel0xj0c/branch/master?svg=true)](https://ci.appveyor.com/project/laurentkempe/gitdiffmargin/branch/master) [![Gitter](https://img.shields.io/gitter/room/inferred/freebuilder.svg?style=flat-square)](https://gitter.im/GitDiffMargin/Lobby)

* Supports Visual Studio 2012 through Visual Studio 2019 Preview
* Quickly view all current file changes on
    * Left margin
    * Scroll Bars in map and bar mode with and without source overview
        * blue rectangle for modifications
        * green rectangles for new lines
        * red triangles for deletions
        * all colors configurable through Visual Studio Fonts and Colors options
* Undo the change
* Copy the old code into the clipboard
* Copy a part of the old code by selecting it in the popup
* Show the diff in Visual Studio Diff window
* Navigate to previous/next change on the file using user defined keyboard shortcuts or the popup icons
* Open popup with user defined keyboard shortcuts, close with esc key 
* Support Visual Studio 2013 Dark, Light and Blue Theme
* Support zoom

![Screenshot](https://farm4.staticflickr.com/3893/15335334635_a88dc1f271.jpg)

Git Diff Margin version 3.2.2 is the latest release supporting Visual Studio 2010 it uses LibGit2Sharp v0.23.1 and is not being maintained. You can [download it here](https://github.com/laurentkempe/GitDiffMargin/releases/tag/v3.2.2).

## Installation

Grab it from inside of Visual Studio's Extension Manager searching for Git Diff Margin, or via the [Extension Gallery link](https://marketplace.visualstudio.com/items?itemName=LaurentKempe.GitDiffMargin)

You can use [Chocolatey Git Diff Margin](https://www.chocolatey.org/packages/GitDiffMargin/)

## Video

You might see a little video on the [following page](https://www.flickr.com/photos/laurentkempe/14879945429/).

## Feedback

* To report a bug, please use the [**Issue Tracker**](https://github.com/laurentkempe/GitDiffMargin/issues/new?assignees=&labels=bug&template=bug_report.md&title=)
* To suggest an idea, please use the [**Issue Tracker**](https://github.com/laurentkempe/GitDiffMargin/issues/new?assignees=&labels=&template=feature_request.md&title=)
* Write a [**review**](https://marketplace.visualstudio.com/items?itemName=LaurentKempe.GitDiffMargin#review-details)
* Tweet me [![Follow on Twitter](https://img.shields.io/twitter/url/http/realvizu.svg?style=social&label=@laurentkempe)](https://twitter.com/laurentkempe)

## Credits

Thanks to

* Sam Harwell [@sharwell](https://github.com/sharwell) for all the improvements
* Rick Sladkey [@ricksladkey](https://github.com/ricksladkey) for the fixes
* Ethan J. Brown [@Iristyle](https://github.com/Iristyle) for the first chocolatey package
* [@heinzbeinz](https://github.com/heinzbeinz) for the support of Visual Studio 15 preview
* Jamie Cansdale [@jcansdale](https://github.com/jcansdale) for bugfix
* Charles Milette [sylveon](https://github.com/sylveon) for bugfix
* Gary Ewan Park [@gep13](https://github.com/gep13) for the new chocolatey package
