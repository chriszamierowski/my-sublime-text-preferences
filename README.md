# my-sublime-text-preferences

An easy way for me to transfer Sublime Text 3 preferences and packages between machines

### Setup
- Close Sublime Text 3
- Clone repo
- Navigate to `User` folder: `$ cd my-sublime-text-preferences/User`
- Copy current directory: `$ pwd|pbcopy`
- Navigate to Sublime's `Packages` folder. Mine is `/Users/chriszamierowski/Library/Application Support/Sublime Text 3/Packages`
- Remove the current `User` directory (or rename it for safe keeping): `$ rm -rf User`
- Setup a symlink to the `User` folder in the repo: `$ ln -s {paste clipboard} User`
- Open up Sublime Text 3. Should be all set

Based on [https://packagecontrol.io/docs/syncing](https://packagecontrol.io/docs/syncing)
