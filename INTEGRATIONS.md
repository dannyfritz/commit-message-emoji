# Integrations

There are various ways to make inserting emojis easier.

## OSX

You can pull up the emoji keyboard by hitting <kbd>ctrl</kbd>+<kbd>⌘</kbd>+<kbd>space</kbd>

## Windows 10

You can pull up the emoji keyboard by hitting <kbd>Win</kbd>+<kbd>.</kbd>

## Ubuntu 20

You can press <kbd>Super</kbd> to search for the emoji name, but only the first 5 matches are displayed. This works for "book", but not for "bug".

![Ubuntu Focal Fossa emoji search](https://user-images.githubusercontent.com/33569/82133882-d0ff1f00-97a5-11ea-9d8e-97fdf7dd41da.png)


## Ubuntu (all versions)

Launch the "Characters" application.

![Characters](https://user-images.githubusercontent.com/33569/82133860-7bc30d80-97a5-11ea-9d91-33ad8caab611.png)

## Gnome Shell

You can show a list of emoji to copy to your system clipboard using the [Emoji Selector](https://extensions.gnome.org/extension/1162/emoji-selector/) Gnome extension. This extension [recognises commit message emoji labels](https://github.com/maoschanz/emoji-selector-for-gnome/pull/80) like 'refactor', 'version', 'wip'.

## Atom Editor

Install package for [autocomplete-emojis](https://atom.io/packages/autocomplete-emojis).
In the package settings, check the box for "Enable Unicode Emojis".

Atom can also help with using emoji in commit message by installing [git-plus](https://atom.io/packages/git-plus)

## Sublime Text

Install package for [GithubEmoji](https://github.com/akatopo/GithubEmoji).

## Vim 

Install package for [Vim-emoji](https://github.com/junegunn/vim-emoji#installation).

Add `set completefunc=emoji#complete` to `.vimrc` and then run emoji completion with `CTRL-X CTRL-U`

## npm

Create an `.npmrc` [file](https://docs.npmjs.com/files/npmrc) and set the `message` value.
```ini
message = "🔖 %s"
```

## Emacs

Install [emoji-cheat-sheet-plus](https://github.com/syl20bnr/emacs-emoji-cheat-sheet-plus).

Bring up the emoji buffer with:

```
M-x emoji-cheat-sheet-plus-insert
```

