[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Unix/CLI Diagnostic

Carry out all of the following tasks using _only the command line_! As is
usually the case, you're welcome to use any resource you can find (except
another developer, of course) to reach your answer.

## Navigating the Filesystem

Complete each of following steps, **in order** :

1. Create a new directory called `cli-diagnostic/` inside the root directory of
  this repository (`unix-cli-diagnostic/`).

1. Create a new file inside `cli-diagnostic/` called `rhyme.txt`.

1. Open `rhyme.txt` using Atom (via the terminal) and add the following text:

     "The rain in Spain falls mainly in the plain."

    - Once you've done this, save the file and quit Atom.

1. Make a directory inside `cli-diagnostic/` called `temp/`. Inside it, create a
   new blank file called `temp.md`.

    - Navigate back up to `unix-cli-diagnostic/` directory.
    Using Atom, open up `diagnostic.md` and write your answers below
    (where indicated).

1. Great Work! Back in the terminal, do `git status` to view your changes. What
   color is the directory name?

    ```md
    <!-- your answer here -->
    ```

1. Do `git add <file_name>` to stage your changes. Do `git status` again to see
   the newly staged file. What color is the file name now?

    ```md
    <!-- your answer here -->
    ```

1. Let's commit these changes with `git commit`. The commit can consist of
   both a header, `Add files and directories`, and a body,
   `Add rhyme.txt, temp.md, and associated directories`.

1. Navigate back down to `cli-diagnostic/` and delete the `temp/` directory
   (with `temp.md` inside of it). Use `ls` to show the contents of
   `cli-diagnostic/` - was `temp/` deleted?

    ```md
    <!-- your answer here -->
    ```

1. Let's commit our changes. Do `git status` to view your changes. Do
   `git add <file_name>` to stage your changes. Commit these changes with
   `git commit`. This commit can consist of both a header,
   `Remove temp directory`, and a body,
   `Remove directory and all files located within`.

## Absolute and Relative Paths

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you
   know?

    ```md
    <!-- your answer here -->
    ```

1. Given:

    ```sh
    ~/project
    ├── css
    ├── data
    ├── img
    ├── js
    └── planning
    ```

    If we are in the `project` directory and use `cd planning`, is a relative or
    absolute path being referenced? How do you know?

    ```md
    <!-- your answer here -->
    ```

1. Now suppose that we have an image file living inside our project. Would we
   refer to it with an absolute or relative path? Why?

    ```md
    <!-- your answer here -->
    ```

You're done! Refer back to README.md.
