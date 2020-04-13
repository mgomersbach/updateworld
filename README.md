# updateworld

[![Build Status](https://travis-ci.com/mgomersbach/updateworld.svg?branch=master)](https://travis-ci.com/mgomersbach/updateworld) [![Join the chat at https://gitter.im/chinstrap-overlay/Lobby](https://badges.gitter.im/chinstrap-overlay/Lobby.png)](https://gitter.im/chinstrap-overlay/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Chat on freenode](https://img.shields.io/badge/chat-on%20freenode-red.png)](irc://freenode/chinstrap)

This is a small utility program to update @world profile

## Installation

Gentoo:

```sh
eselect repository add chinstrap git https://github.com/mgomersbach/chinstrap-overlay.git
emaint sync -r chinstrap
emerge updateworld
```

## Contribute

Submitting a pull request is more than just code\! To achieve a quality product, the *documentation* needs to be updated as well. An excellent pull request will include these in the changes, wherever relevant.

### Commit message formatting

Since every type of change requires making Git commits, we will start by covering the importance of ensuring that all of your commit messages are in the correct format.

### CI

This repo uses [semantic-release](https://github.com/semantic-release/semantic-release) for automating numerous processes such as bumping the version number appropriately, creating new tags/releases and updating the changelog.
The entire process relies on the structure of commit messages to determine the version bump, which is then used for the rest of the automation.

Full details are available in the upstream docs regarding the [Angular
Commit Message Conventions](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines).
The key factor is that the first line of the commit message must follow
this format:

`type(scope): subject`

e.g. `docs(contributing): add commit message formatting instructions`.

Besides the version bump, the changelog and release notes are formatted accordingly. So based on the example above:

- The `type` translates into a `Documentation` sub-heading.
- The `(scope):` will be shown in bold text without the brackets.
- The `subject` follows the `scope` as standard text.

## Meta

[![](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/images/0)](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/links/0)[![](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/images/1)](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/links/1)[![](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/images/2)](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/links/2)[![](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/images/3)](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/links/3)[![](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/images/4)](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/links/4)[![](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/images/5)](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/links/5)[![](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/images/6)](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/links/6)[![](https://sourcerer.io/fame/mgomersbach/mgomersbach/chinstrap-overlay/images/7)](https://sourcerer.io/fame/mgomersbach/mgomersbach/updateworld/links/7)

Mark Gomersbach – markgomersbach@gmail.com

Distributed under the GPLv2 license. See ``LICENSE`` for more information.
