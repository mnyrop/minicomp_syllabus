# Command Line Cheat Sheet

## Basic
- `pwd`       – __Print working directory__ command. It's like asking "Where am i?"
- `cd [PATH]` - __Change directory__ command. Lets you navigate your filesystem and move around.
- `ls [PATH]` - __List directory contents__. Tells you what's in a directory.
- `clear`     - __Clear the terminal screen__. On Windows it's `cls`.
- `rm [PATH]` - __Remove (items)__. Be careful with this one!
- `~`         - Shortcut to your user directory (Mac/Unix)

## Jekyll
- `(bundle exec) jekyll serve` – Build your site to the `_site` folder and serve your site locally.
- `(bundle exec) jekyll build` – Build your site to the `_site` folder.

## Wax
- `(bundle exec) rake wax --tasks` – List available tasks.
- __Others:__ see https://minicomp.github.io/wiki/wax/running-the-tasks/

## Git
- `git init`– Initializes your current directory as a Git repository
- `git add [FILES]` – Add files/changes
- `git commit -m [MESSAGE]` - Describe and commit the files/changes that were added
- `git push` – Upload the files/changes that were committed to your remote/online repository (on GitHub)
- `git fetch` – Look for changes in the remote/online repository
- `git pull`  – Download + merge the changes from your remote/online repository into your local repository
