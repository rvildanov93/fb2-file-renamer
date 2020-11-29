# [fb2 file renamer](https://rvildanov93.github.io/fb2-file-renamer/)

This python script unpacks `.zip` files that contains `.fb2` files inside and then renames `.fb2` files according to its `<book-title>` tags. If there are no `.zip` files in the directory, skips the unpacking part.

## Preview

[![fb2 file renamer](https://raw.githubusercontent.com/rvildanov93/fb2-file-renamer/master/file_renamer_cover_for_gh.jpg)](https://rvildanov93.github.io/fb2-file-renamer/)

## Download and Installation

To begin using this script, choose one of the following options to get started:

- Clone the repo: `git clone https://github.com/rvildanov93/fb2-file-renamer.git`
- [Fork, Clone, or Download on GitHub](https://github.com/rvildanov93/fb2-file-renamer.git)

Also you have to install [langdetect](https://pypi.org/project/langdetect/) python module via console command `pip install langdetect`.

## Usage


Clone the source files and navigate into the theme's root directory. Run `npm install` and then run `npm start` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `package.json` file to see which scripts are included.

## Bugs and Issues

Have a bug or an issue with this script? [Open a new issue](https://github.com/rvildanov93/fb2-file-renamer/issues) here on GitHub or write me a message on the [ramilvildanov.ru](https://ramilvildanov.ru).

## About
This version of fb2 file renamer can rename russian book-titles only. I will hopefully work on other functionality later. 
Firstly, script checks for the `.zip` files in the specified directory (`directory` variable) and upacks files to the same directory with deleting the original ones.
Then it checks for the `.fb2` files in the directory and finds its tag text, renames the file with this text and prints the list of renamed `.fb2` files in the console.
Script should work fine with Python v3.7 and later.

fb2 file renamer was created by and is maintained by **[Ramil Vildanov](https://ramilvildanov.ru/)**.

- <https://twitter.com/rvildanov93>
- <https://github.com/rvildanov93>

## Copyright and License
Copyright 2019-2020 by Ramil Vildanov
