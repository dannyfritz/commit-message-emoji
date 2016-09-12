# Integrations

There are various ways to make inserting emojis easier.

## OSX

You can pull up the emoji keyboard by hitting <kbd>^</kbd>+<kbd>⌘</kbd>+<kbd>space</kbd>

## Windows 10

Right click on your taskbar and enable "show touch keyboard button".
Click on the keyboard that is next to your taskbar clock.
Click on the smile face to find and insert emoji.

## Atom Editor

Install package for [autocomplete-emojis](https://atom.io/packages/autocomplete-emojis).

Atom can also help with using emoji in commit message by installing [git-plus](https://atom.io/packages/git-plus)

## Sublime Text

Install package for [GithubEmoji](https://github.com/akatopo/GithubEmoji).

## npm

Create an `.npmrc` [file](https://docs.npmjs.com/files/npmrc) and set the `message` value.
```ini
message = ":bookmark: %s"
```

## SourceTree

Not currently available. Vote for this [issue](https://jira.atlassian.com/browse/SRCTREEWIN-3072) to ask for it.

## Git cli included with g3l

Install a cli tool which name g3l, you can push your commits without think as well.
```
npm i -g g3l
```

```
g3l -m "Init"
```

![Demo](https://github.com/svtek/g3l/blob/master/images/init.png)
