# Commit Message Emoji

Every commit is important.
So let's celebrate each and every commit with a corresponding emoji! :smile:

Oh, and it can also help with glancing over commit messages to figure out
what kind of changes have been made. :smirk:

These are just guidelines, not rules, use your best judgment and feel free to propose changes to this document in a pull request.

## Usage

Prepend every commit message with an emoji with this form:
`:emoji: commit message`.

## Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally
* When only changing documentation, include `[ci skip]` in the commit description

## Which Emoji to Use? :confused:

Consider starting the commit message with an applicable emoji:

Commit Type | Emoji
----------  | -------------
Initial Commit | :tada: `:tada:`
Version Tag | :bookmark: `:bookmark:`
Deployment | :rocket: `:rocket:`
Release | :shipit: `:shipit:`
New Feature | :sparkles: `:sparkles:`
Metadata | :card_index: `:card_index:`
Refactoring | :package: `:package:`
Documentation | :books: `:books:`
Writing docs | :memo: `:memo:`
Cosmetic | :lipstick: `:lipstick:`
Tooling | :wrench: `:wrench:`
Deprecation | :poop: `:poop:`
Work In Progress (WIP) | :construction: `:construction:`
Bugfix | :bug: `:bug:`
Fixing something on Linux | :penguin: `:penguin:`
Fixing something on macOS | :apple: `:apple:`
Fixing something on Windows | :checkered_flag: `:checkered_flag:`
Improving the format/structure of the code | :art: `:art:` 
Improving performance | :racehorse: `:racehorse:`
Plugging memory leaks | :non-potable_water: `:non-potable_water:`
Removing code or files | :fire: `:fire:`
Tests | :rotating_light: `:rotating_light:`
Adding tests | :white_check_mark: `:white_check_mark:`
Fixing the CI build | :green_heart: `:green_heart:`
Dealing with security | :lock: `:lock:`
Upgrading dependencies | :arrow_up: `:arrow_up:`
Downgrading dependencies | :arrow_down: `:arrow_down:`
Removing linter warnings | :shirt: `:shirt:`
Translation | :globe_with_meridians: `:globe_with_meridians:`
Other | [Be creative](http://www.emoji-cheat-sheet.com/)

## Using Emoji is Hard! :rage:

Here are [some ways](INTEGRATIONS.md) to more easily integrate emoji into your workflow.

## Comparison

You can be the judge on which is easier to grok.

Example taken from [here](https://github.com/dannyfritz/funcdash/commits/master)
And from guidelines for contributing to [Atom](https://github.com/atom)

### Commits Without Emoji :anguished:

0.5.2

Fix exporting of the library to include _.ifElse

0.5.1

add _.ifElse to README.md

0.5.0

add _.ifElse

fix JSDoc comment for _.call

Fix _.not documentation example.

Update JSDoc comments.

0.4.1

Update links to documentation.

Fix documentation.

Link to documentation pages.

0.4.0

Added a curried version of the mixin for lodash-fp.

Switch from lodash to lodash-compat

Add shields to README.

Add missing methods to index.js.

### Commits with Emoji :smiley:

:bookmark: 0.5.2

:bug: Fix exporting of the library to include _.ifElse

:bookmark: 0.5.1

:books: add _.ifElse to README.md

:bookmark: 0.5.0

:sparkles: add _.ifElse

:books: fix JSDoc comment for _.call

:books: Fix _.not documentation example.

:books: Update JSDoc comments.

:bookmark: 0.4.1

:books: Update links to documentation.

:books: Fix documentation.

:books: Link to documentation pages.

:bookmark: 0.4.0

:sparkles: Added a curried version of the mixin for lodash-fp.

:card_index: Switch from lodash to lodash-compat

:card_index: Add shields to README.

:bug: Add missing methods to index.js.
