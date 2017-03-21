# Git Commit Hooks #

Various unopinionated---not, git commit hooks. Should all run on a stock POSIX
environment.

## Installation ##

```sh
cp * /path/to/your/.git/hooks
```

## Hooks ##

### `commit-msg` ###

Basic commit message style checker. Based on common community standards for Git
commit messages, such as the Linux kernel's.

Will prevent committing if there were unambiguous style errors (not warnings).
