# dotminttyrc
This repo stores my config for mintty (Git Bash's terminal app).

## Usage
Clone this repo, then symlink `%USERPROFILE%\\.minttyrc` to your clone of
`.minttyrc`:
1.  On Windows, clone this repo somewhere on your local storage.  For
    example, `%USERPROFILE%\\dotfiles\\dotminttyrc\\`.
2.  Edit `%PROGRAMFILES%\\Git\\etc\\gitconfig`:
    1.  Find the `[core]` section and set `symlinks = true`.
3.  Run `git-bash` **as administrator**.
4.  In the `git-bash` administrator prompt:
    1.  Run `export MSYS=winsymlinks:nativestrict`.
    2.  Run `ln -si /c/Users/<YOUR-USERNAME>/dotfiles/dotminttyrc/.minttyrc /c/Users/<YOUR-USERNAME>/.minttyrc`
