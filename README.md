# Organizing Your Work for this Course

## Learning Goals

- Configure a directory for storing lessons
- Understand the relationship between navigating directories in the terminal and
  navigating directories in a graphical user interface like Finder
- Practice common terminal commands such as `pwd`, `ls`, `mkdir`, and `cd`

## Introduction

From now on, you'll be executing code on your own computer. For each and every
lab, you'll be copying the code to your computer using
[Git](https://git-scm.com). You will then be able to run and test your code in
your terminal.

## Creating Folders to Organize Your Work

- Go to your terminal and navigate to your home directory by typing `cd ~`.
- Navigate into the `Development` folder with `cd Development` (if you don't
  have a `Development` folder yet, you can create it with `mkdir Development`,
  then `cd` into it).
- Create a directory for all your assignments by typing `mkdir code`.
- Navigate into this folder with `cd code`.
- In here, create a directory for the first module with
  `mkdir module-1`.

You'll be going through multiple modules in this course, so it may be helpful
to go one step further and also create folders for all 18 modules within
`code`. When making the module folders use a `-` between words, as we did above for `module-1`.

Having a specific place for your work will make it easier to find if you ever
need to look back at an earlier project. It'll also keep the rest of your
computer's folders clear of random code.

## Terminal Command Reference

Here's a quick reference of the terminal commands used in these videos. For
more, check out this awesome [cheatsheet].

| Command      | Description                                                |
| ------------ | ---------------------------------------------------------- |
| ls           | List all files and folders in the current directory        |
| ls -a        | List all files and folders, including hidden files         |
| mkdir [name] | Make a new directory with the given [name]                 |
| cd [folder]  | Change directories to the given [folder]                   |
| cd ..        | Change directories to the parent directory                 |
| cd ~         | Change directories to the home directory                   |
| pwd          | Print the full path of the current working directory       |
| explorer.exe | (Windows) Open the File Explorer to the current directory  |
| open .       | (Mac) Open the Finder application to the current directory |

## Resources

- [Terminal Commands Cheatsheet][cheatsheet]

[cheatsheet]: https://github.com/0nn0/terminal-mac-cheatsheet
