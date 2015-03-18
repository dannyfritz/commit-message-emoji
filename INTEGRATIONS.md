# Integrations

There are various ways to make inserting emojis easier.

## Atom Editor

Install packages for [autocomplete-plus](https://atom.io/packages/autocomplete-plus) and [autocomplete-emojis](https://atom.io/packages/autocomplete-emojis).

Atom can also help with using emoji in commit message by installing [git-plus](https://atom.io/packages/git-plus)

## npm

Create an `.npmrc` [file](https://docs.npmjs.com/files/npmrc) and set the `message` value.
```ini
message = ":bookmark: %s"
```

## SourceTree

Not currently available. Vote for this [issue](https://jira.atlassian.com/browse/SRCTREEWIN-3072) to ask for it.
