# gitignore

Collection of gitignores for new projects. 

To install a gitignore in the current directory from terminal, add the following to your shell's `.rc` file:

```
function gi() {
    curl https://raw.githubusercontent.com/johntmcintosh/gitignore/master/$1.gitignore -o .gitignore
}
```