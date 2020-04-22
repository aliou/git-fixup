# `git-fixup`

`git-fixup` allows you to quickly fixup changes to a commit by selecting the commit from a list.
It uses `fzf` to allow quick selection and preview of the of commits.

<!-- insert description here -->
<!-- Insert gif here -->

## Usage

```sh
git fixup [BRANCH]
```

## Installation

With [Homebrew](brew.sh)
```sh
brew install aliou/tools/git-fixup
```

Manually
```sh
git clone https://github.com/aliou/git-fixup
cp git-fixup/git-fixup /usr/local/bin/ # Or somewhere else in your $PATH.
```

## Options

* `fixup.branch` Allows setting the default branch to 
By default `origin/master`

* `fixup.fzfOptions`
By default, `--height 40% --reverse`

<!--
## License
-->
