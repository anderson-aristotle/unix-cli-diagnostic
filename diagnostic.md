[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Unix/CLI Diagnostic

Carry out all of the following tasks using _only the command line_! As is
usually the case, you're welcome to use any resource you can find (except
another developer, of course) to reach your answer.

## Navigating the Filesystem

Complete each of following steps, **in order** :

1. Create a new directory called `cli-diagnostic` inside the root directory of
this repository (`unix-cli-diagnostic`).

2. Create a new file inside `cli-diagnostic` called `rhyme.txt`.

3. Open `rhyme.txt` using Atom (via the terminal) and add the following text:

    ```md
     "The rain in Spain falls mainly in the plain."
    ```
    Once you've done this, save the file and quit Atom.

4. Make a directory inside `cli-diagnostic` called `temp`. Inside it, create a
   new blank file called `temp.md`.

Navigate back up to `unix-cli-diagnostic` directory.
Using Atom, open up `diagnostic.md` and write your answers below
(where indicated).

5. Great Work! Back in the terminal, do `git status` to view your changes. What
   color is the file name?

    ```md
    <!-- your answer here -->
    ```

6. Do `git add <file_name>` to stage your changes. Do `git status` again to see
   the newly staged file. What color is the file name now?

    ```md
    <!-- your answer here -->
    ```

7. Let's commit these changes with `git commit <file_name>` and the commit
   message of `add temp.md and associated folders`.

8. Navigate back up to `cli-diagnostic` and delete the `temp` directory (with
   `temp.md` inside of it). Use `ls` to show the contents of
   `cli-diagnostic` - was `temp` deleted?

    ```md
    <!-- your answer here -->
    ```

9. Let's commit our changes. Do `git status` to view your changes. Do
   `git add <file_name>` to stage your changes. Commit these changes with
   `git commit <file_name>` and the commit message of `remove temp folder`.

## Absolute and Relative Paths

1. Is `/Users/blah_blah/Desktop` a relative path or an absolute path? How do you
   know?

    ```md
    <!-- your answer here -->
    ```

 2. Given:
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

3. Now suppose that we have an image file living inside our project. Would we
   refer to it with an absolute or relative path? Why?

    ```md
    <!-- your answer here -->
    ```

<hr>

You're done! Refer back to README.md.
