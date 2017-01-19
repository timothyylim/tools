# tools

## git 

- Squash commits together with rebase [[1]](http://gitready.com/advanced/2009/02/10/squashing-commits-with-rebase.html) [[2]](https://github.com/ginatrapani/todo.txt-android/wiki/Squash-All-Commits-Related-to-a-Single-Issue-into-a-Single-Commit)
- [Checkout a specific branch](http://stackoverflow.com/questions/67699/how-to-clone-all-remote-branches-in-git)
- [Create a branch from a branch](http://stackoverflow.com/questions/4470523/git-create-a-branch-from-another-branch)
- List all remote branches: ```git branch -a```
- Stash all changes in subdirectories ```find . -maxdepth 1 -type d -exec sh -c '(cd {} && git stash)' ';'```
- Stash all changes and set all to master branch:
```
find . -maxdepth 1 -type d -exec sh -c '(cd {} && git stash)' ';'
find . -maxdepth 1 -type d -exec sh -c '(cd {} && git checkout master)' ';'
```

## unix

- find a file [[1]](http://www.cyberciti.biz/faq/howto-find-a-file-under-unix/)
- create a symbolic link to a file: ``` ln -s source_file myfile```
- find a file then cd into it: ```find . -name "myfile.txt" | pbcopy``` then type ```cd``` and paste

## iterm2

- Skip words with cmd
- Delete iterm2 preferences ```defaults delete com.googlecode.iterm2```

## atom

- Focus on tree ctrl-0
* <kbd>alt-g up</kbd> to move the cursor to the previous diff in the editor
* <kbd>alt-g down</kbd> to move the cursor to the next diff in the editor

## drupal

- [Create keyboard shortcuts](https://www.drupal.org/project/keyboard_shortcut)
- clone is at the bottom of the page

## vim

- [Seven habits ...](http://www.moolenaar.net/habits.html)

