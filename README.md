# Go Notes

## Version
Go v1.18+

## Go Modules and Packages

- A single directory can only have one package
- The package name can be different from the directory name. When they are different, you should use the directory name with the `import` keywoard and reference the package name in your code. 
- When importing a package, you either specify its full path (even for a sub directory of the current project), or put the package in `$GOROOT/src` (searched first) or `$GOPATH/src` (searched second).
